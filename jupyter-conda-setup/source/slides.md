---
marp: true
theme: default
size: 16:9

backgroundColor: #fff
style: |
    .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    }

    section {
      font-size: 1.2em;
      justify-content: flex-start;
    }

    section::after {
      font-size: 0.6em;
      text-shadow: 1px 1px 0 #fff;
      left: 50%;
      transform: translateX(-50%);
      content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
    } 

    footer {
      bottom: 10px
    }


footer: '![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)'


---

# **Setting Up Jupyter Lab/Notebook Using `conda`**

Vincent Balbarin
June 2, 2023

---
<!-- paginate: true -->
<style>
blockquote {
    border-top: 0.1em dashed #555;
    font-size: 60%;
    margin-top: 50px;
}
sup {
  font-size: 65%;
}
</style>

## Primary Python Distributions

1. CPython: the default Python distribution shipping on many Linux distributions and MacOS
2. Anaconda: a Python distribution pre-loaded with ~250 packages used in data science
3. Miniconda: a bootstrap distribution of Anaconda with a much smaller footprint.

---

## Installing Miniconda

Download the appropriate installation script and SHA256 checksums:

```bash
installer_url="https://repo.anaconda.com/miniconda/Miniconda3-py310_23.3.1-0-Linux-x86_64.sh"
sha256_hashes_url="https://docs.conda.io/en/latest/miniconda_hashes.html"

curl -O "${installer_url}"
curl -O "${sha256_hashes_url}"
```

---

Verify installation script:

```bash
installer=$(basename ${installer_url})
sha256_hashes=$(basename ${sha256_hashes_url})

printf -v regex \
  '<td>%s<\/td>[\s\S]*?<td><code class="docutils literal notranslate"><span\s+class="pre">\K[a-z0-9]+' \
  "${installer//\./\\.}"

installer_sha256_checksum=$(grep -Pzo "${regex}" <"${sha256_hashes}" | tr -d '\0')

echo $installer_sha256_checksum $installer | sha256sum -c
```

If the script has not been altered or corrupted, the following output is expected:

```bash
Miniconda3-py310_23.3.1-0-Linux-x86_64.sh: OK
```

---

Execute script to install `conda`

```bash
sh ./Miniconda3-py310_23.3.1-0-Linux-x86_64.sh -b
```

Initialize `miniconda`:

```bash

# Activate base conda environment
eval "$(${HOME}/miniconda3/bin/conda shell.$(basename "${SHELL}") hook)"

# Initialize conda
conda init

# Disable auto-loading of base conda environment for subsequent user logins
conda config --set auto_activate_base false

# Deactivate base environment
conda deactivate

# Source .bashrc (if using bash) to set paths to conda in current shell
source ${HOME}/.bashrc
```

---

## Creating a Jupyter Lab/Notebook for Data Analysis

```bash
conda create -n jupyter_lab python=3.10.11 jupyter numpy pandas matplotlib
```

---

## Launching a Jupyter Lab/Notebook

It is highly recommended that you install `screen` or `tmux` and run your notebook from within a session.

```bash
screen -S jupyter
# or
tmux new-session -s jupyter
```

```bash
conda activate jupyter_lab

jupyter_port=$(python -c 'import socket; s=socket.socket(); s.bind(("", 0)); print(s.getsockname()[1]); s.close()')

jupyter lab --no-browser --port "${jupyter_port}"
# Alternatively: jupyter notebook --no-browser --port "${jupyter_port}"

```

---

## Connecting to the Jupyter Lab/Notebook

On the remote server running Jupyter, locate the web server url in the log trace:

```bash
....
[I 2023-06-02 15:31:07.517 ServerApp] nbclassic | extension was successfully loaded.
[I 2023-06-02 15:31:07.518 ServerApp] Serving notebooks from local directory: /home/veb3
[I 2023-06-02 15:31:07.518 ServerApp] Jupyter Server 1.23.4 is running at:
[I 2023-06-02 15:31:07.518 ServerApp] http://localhost:57321/lab?token=af77a96184f501ef59d45338a47796baac0eb81ab0085a02
[I 2023-06-02 15:31:07.518 ServerApp]  or http://127.0.0.1:57321/lab?token=af77a96184f501ef59d45338a47796baac0eb81ab0085a02
[I 2023-06-02 15:31:07.518 ServerApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
...
```

Here it is `http://localhost:57321/lab?token=af77a96184f501ef[truncated]`

Note the listening port `57321` and the login token `af77a96184f501ef[truncated]` and copy them to your clipboard.

These values will change for every launch of Jupyter.

---

On your workstation or laptop create an SSH tunnel to forward requests to the Jupyter web server

```bash
local_port=8888 # pick any appropriately high numbered port
remote_jupyter_port="{{ .pasteValueFromYourClipboard }}"
remote_jupyter_token="{{ .pasteValueFromYourClipboard }}"


ssh -L "${local_port}":localhost:"${remote_jupyter_port}" user@host
```

Browse to Jupyter Lab/Notebook site:

```bash
# OS X
open "http://localhost:${local_port}/lab?token=${remote_jupyter_token}"

# Linux
[firefox | google-chrome] "http://localhost:${local_port}/lab?token=${remote_jupyter_token}"
python3 -m webbrowser -t "http://localhost:${local_port}/lab?token=${remote_jupyter_token}"
```
