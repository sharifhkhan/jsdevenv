# JavaScript Development Environment
My approach to using open source tools for a javascipt development environment. These are opinionated choices that I think are good. If you have suggestions I should consider, let me know.

## React Quick Start
If you're looking to get started as fast as possible, consider using [create-react-app](https://github.com/facebook/create-react-app/) after installing your dev tools.


## Setup
0. Install latest [git](https://git-scm.com/) better to use brew on macos. Make sure it's actually using the latest version you installed and not apple git. If it is, export PATH="/usr/local/bin:${PATH}" in your ~/.bash_profile and reopen terminal to verify the correct version.
1. Install editor [Visual Studio Code](https://code.visualstudio.com/) if you use sublime, evaluate it, then pay for it.
2. Add coding sytles [EditorConfig](https://editorconfig.org/) using facebook's [react](https://github.com/facebook/react/blob/master/.editorconfig) standards
3. Install latest [nodejs](https://nodejs.org/en/)
4. Set npm author and license [config](https://docs.npmjs.com/misc/config#init-author-name) values
5. Create `package.json` with `npm init`

## Dev web server

0. Use [express](https://expressjs.com/)
1. Use [localtunnel](https://localtunnel.github.io/www/) to expose yourself

