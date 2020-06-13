# ESLint and Prettier setup

These are my personal settings I use across my projects, feel free to tweak to your liking.

## Installation

```shell
yarn install --dev eslint-config-jakeherp
```

or with npm:
```shell
npm install --save-dev eslint-config-jakeherp
```

in your `.eslintrc` file add:

```json
{
  "extends": [
    "jakeherp"
  ]
}
```

## What it does

 * Lints JavaScript and TypeScript according to latest web standards
 * Fixes formatting errors using Prettier
 * Based on `eslint-config-airbnb` for React