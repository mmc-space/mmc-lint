## Usage

### Install

```sh
$ pnpm add -D eslint @mmc-cloud/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": "@mmc-cloud/eslint-config"
}
```

> You don't need `.eslintignore` normally as it has been provided by the preset.

### Add script for package.json

For example:

```json
{
  "scripts": {
    "lint": "eslint .",
    "lint:fix": "eslint . --fix"
  }
}
```
