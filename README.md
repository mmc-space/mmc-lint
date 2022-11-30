## Usage

### Install

```bash
pnpm add -D eslint @mmc-group/eslint-config
```

### Config `.eslintrc`

```json
{
  "extends": "@mmc-group/eslint-config"
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
