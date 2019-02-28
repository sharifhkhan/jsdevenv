# JavaScript Development Environment

I use the following tools and settings for my dev workflow. If you have suggestions I should consider, please let me know.

## Setup macOS

0. Install [Homebrew](https://brew.sh/) package manager

1. Install [Visual Studio Code](https://code.visualstudio.com/) code editor

2. Install git using brew. Make sure you're actually using the latest version you installed and not apple git. If using apple git, `export PATH="/usr/local/bin:${PATH}"` in your `~/.bash_profile` and reopen terminal to verify the correct version.

3. Add coding sytles [EditorConfig](https://editorconfig.org/) extension ans use facebook's [react](https://github.com/facebook/react/blob/master/.editorconfig) standards

4. Install [nodejs](https://nodejs.org/en/) using brew

5. Set npm author and license [config](https://docs.npmjs.com/misc/config#init-author-name) values

6. Create `package.json` with `npm init` to get started

7. Install `eslint` using npm and save for dev using `--save-dev`

## Dev web server

1. Use [express](https://expressjs.com/)
2. Use [localtunnel](https://localtunnel.github.io/www/) to expose yourself


## React Quick Start
If you're looking to get started as fast as possible, and don't want to build your environment step by step, use [create-react-app](https://github.com/facebook/create-react-app/) after installing your dev tools.
