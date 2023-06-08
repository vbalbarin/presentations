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

# **Wright Laboratory Bootcamp**

## A Quick Introduction to Remote Access and the Unix Command Line

Vincent Balbarin
June 8, 2023

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
code {
  font-size: 75%;
}
</style>

## Remote Access

Some of your computation will be done on remote, multi-user Linux environments such as rubin.physics.yale.edu, meitner.wlab.yale.edu, or the `grace` HPC computing cluster.

---

## Secure Shell (SSH)

The Secure Shell client enables you to authenticate and open an encrypted connection to a remote host.
It allows for both username/password and key-based authentication.

The Wright Laboratory and YCRC HPC systems require the use of SSH keys for authentication.

---

## Create a New SSH Key Pair

Launching a command line terminal:

1. Mac OS
   1. Bring up Spotlight: [⌘] command + [space]
   2. Type **Terminal** and press [return] return to launch the Terminal app.
2. Windows
   1. Begin search by pressing [❖] Win
   2. Type **Powershell**
   3. Highlight **Powershell** in search results and press [⌤] enter to launch.

---

Generation of SSH keypair:

```shell
ssh-keygen --type ed25519
```

1. Answer the prompts with default values.
2. It is strongly recommended to use a password to protect your private key.
3. Once a key pair has been generated, the private and public key will be found at `${HOME}/.ssh` (Mac OS, Linux) or `${Env:USERPROFILE}\.ssh` (Windows)

---

Display the public key

```bash
cat ${HOME}/.ssh/id_ed25519.pub | pbcopy
```

```powershell
gc -Path "${env:USERPROFILE}\.ssh\id_ed25519.pub" | Set-Clipboard
```

1. Paste that value into an email to me with your NetID, preferred first and last name, and your PI.
2. This public key will be installed to your account home folder on the remote system.

---

To create a remote session, open a command line session and type:

```shell
ssh -i ./ssh/id_ed25519.pub {{ NetID }}@{{ HostFQDN }}
```

---

## The Shell

The shell is a text-based environment that lets you interact with the computer.
Windows has two native shells.

There are several different shells available on Linux and other variants of Unix such as Mac OS.

We will focus on Bash.
(Mac OS currently uses a related shell Zsh.)

---

## Navigating the File System

```bash
# Display (print) your current working directory
pwd

# Change directory
cd /path/to/directory

# Change directory, stash path of current working directory
pushd /path/to/directory
# Perform actions
# Return to original working directory
popd

# List the contents of your current directory
ls -la
total 32
drwx------. 3 netid netid    95 Jun  7 19:10 .
drwxr-xr-x. 5 root root      51 May 12 20:53 ..
-rw-------. 1 netid netid 18713 Jun  7 16:53 .bash_history
-rw-r--r--. 1 netid netid    18 Aug  3  2022 .bash_logout
-rw-r--r--. 1 netid netid   141 Aug  3  2022 .bash_profile
-rw-r--r--. 1 netid netid   853 Jun  2 14:21 .bashrc
drwx------. 2 netid netid    29 Jun  3 14:40 .ssh
```

---

## Working with Files and Folders

```bash
# Print text to the screen
echo "Hello, World!"

# Redirect to a file
echo "0 meow" > box.txt

# Append to existing file
echo "1 meow" >> box.txt

# Repeat 998 more times, starting from 2
for i in {2..1000}; do echo "${i} meow" >> box.txt; done

# Display contents, pausing output
cat box.txt | less

# Delete file
rm box.txt

# Copy a file
cp "/path/to/source/file" "/path/to/destination/file"

# Move a file
mv "/path/to/source/file" "/path/to/destination/file"
# Can also be used to rename a file
mv "file.txt" "file.bak"

# Edit a text file
nano "/path/to/file"
```

---

```bash
# Create a new folder
mkdir -p /path/to/new/folder

# Remove a folder and all its contents
rm -R /path/to/folder/*

# Copy a folder
cp -R /path/to/folder /path/to/folder_bak

# Remove the contents of a folder, leaving subfolders intact
# Note remove `echo` to actually delete files
find ./ -type f -name "*" -print0 | xargs -0 -I '%' bash -c 'echo rm "%"'
find ./ -type f -name "*"  -execdir bash -c 'echo rm "{}"' \;


```

---

## Information, Help, and Hints

```bash
# List all of your current shell's environment variables
# available to running applications/processes in your shell
env

# You may use the value of any variable in a command by using ${VARIABLE_NAME}
echo "${PATH}"

# Getting manual pages on a particular installed command
man "{{ command }}"

# Quick query for command, returns the name field of the manual pages
whatis "{{ command }}"

# Query for command or action in both name and description fields of all manual pages
# When you have an idea of what you want, but not a specific command
apropos "{{ commandOrAction }}"
```

---

```bash
# To view last set of commands in your history
history | less

# To search your history for a particular command invocation
history | grep -i "{{ string }}"

# To invoke a specific item in your history
# Note lack of space between exclamation point and number*
!{{ numberOfCommand }}
```

For even more fun with `history`: [How to Use Bash History to Improve Your Command-Line](https://www.howtogeek.com/44997/how-to-use-bash-history-to-improve-your-command-line-productivity/)
