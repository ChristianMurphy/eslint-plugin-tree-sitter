# eslint-plugin-tree-sitter

[![NPM Version](https://img.shields.io/npm/v/eslint-plugin-tree-sitter.svg)](https://www.npmjs.com/package/eslint-plugin-tree-sitter)

Linting rules for tree sitter

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-tree-sitter`:

```
$ npm install eslint-plugin-tree-sitter --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-tree-sitter` globally.

## Usage

### Recommended Config

Add `plugin:tree-sitter/recommended` to the `extends` section of your `.eslintrc` configuration file:

```json
{
    "extends": [
        "plugin:tree-sitter/recommended"
    ]
}
```

### Manual Config

Add `tree-sitter` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "tree-sitter"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "tree-sitter/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here
