# stylelint-config-hd [![NPM Version](https://img.shields.io/npm/v/stylelint-config-hd.svg)](https://www.npmjs.com/package/stylelint-config-hd) [![NPM Downloads](https://img.shields.io/npm/dt/stylelint-config-hd.svg)](https://www.npmjs.com/package/stylelint-config-hd) [![NPM License](https://img.shields.io/npm/l/stylelint-config-hd.svg)](https://www.npmjs.com/package/stylelint-config-hd) [![Build Status](https://travis-ci.org/hugomrdias/stylelint-config-hd.svg?branch=master)](https://travis-ci.org/hugomrdias/stylelint-config-hd)

> Shareable stylelint config for me


## Install

```
$ yarn add stylelint-config-hd -D
```


## Usage

Add stylelint config to your `package.json`:

```js
"stylelint": {
        "extends": "stylelint-config-hd"
}
```


## vscode

Install [esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

```json
{
    "editor.formatOnType": true,
    "editor.formatOnSave": true,
    "prettier.stylelintIntegration": true,
    "prettier.printWidth": 80,
    "prettier.tabWidth": 4,
    "prettier.useTabs": false,
    "prettier.semi": true,
    "prettier.singleQuote": true,
    "prettier.trailingComma": "none",
    "prettier.bracketSpacing": true,
    "prettier.jsxBracketSameLine": false,
}

```


## License

MIT © [Hugo Dias](http://hugodias.me)
