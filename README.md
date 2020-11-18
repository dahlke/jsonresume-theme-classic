# jsonresume-theme-classic

## Running

_NOTE: [2020-10-26] [v2.0.0 of resume-cli broke local theme development](https://github.com/jsonresume/resume-cli/issues/386)_

```bash
npm install -g resume-cli@2.1.4
git clone https://github.com/dahlke/jsonresume-theme-classic.git
cd jsonresume-theme-classic
resume serve --theme .
```

## Publishing to NPM

```bash
npm init
npm install /path/to/this/package

npm adduser

npm publish .
```
