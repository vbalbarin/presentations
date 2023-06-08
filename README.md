# Wright Laboratory Presentations

## Introduction

This is a collection of slide presentations authored using the [Marpit](https://marpit.marp.app/) framework for Markdown.
This allows authors to create HTML based slide decks using the lightweight text markup language Markdown.

## Requirements

1. Visual Studio Code
2. VSCode Extensions
   1. [Marp for VSCode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) extensions
   2. [Markdown All In One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
   3. [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
3. The [Marpit CLI tools](https://github.com/marp-team/marp-cli) installed via [`npm`](https://www.npmjs.com/)

## How-To

* Install Visual Studio Code and the required extensions.
* Install `npm` for your operating system
* Install the Marp CLI tools.

```bash
npm init --yes
npm install --save-dev @marp-team/marp-cli
```

* Copy the `wright-laboratory-preso-template` directory to create a new presentation.

```bash
new_preso='{{ newPresentationName }}'

cp -R wright-laboratory-preso-template "${new_preso}"
```

* Modify `./source/slides.md`. ([This](https://www.hashbangcode.com/article/creating-presentations-markdown-marp#:~:text=Assuming%20you%20have%20npm%20installed%20you%20can%20initialise,npm%20init%20--yes%20%24%20npm%20install%20--save-dev%20%40marp-team%2Fmarp-cli) quick reference may be helpful.)
* Generate HTML slides.

```bash
npx marp --alllow-local-files \
  --output="${new_preso}/slides.html" \
  "${new_preso}/source/slides.md"
```
