# eslint-config-simple-icons

[![Build status](https://img.shields.io/github/workflow/status/simple-icons/simple-icons-eslint/Verify/develop?logo=github&label=tests)](https://github.com/simple-icons/simple-icons-eslint/actions?query=workflow%3AVerify+branch%develop) [![NPM version](https://img.shields.io/npm/v/eslint-config-simple-icons.svg?logo=npm)](https://www.npmjs.com/package/eslint-config-simple-icons)

Simple Icons ESLint base configuration for all repositories.

Is a configuration based on [`eslint:recommended`](https://github.com/eslint/eslint/blob/e5e9e271da58361bda16f7abc8f367ccc6f91510/conf/eslint-recommended.js) and [`eslint-plugin-prettier`](https://github.com/prettier/eslint-plugin-prettier) with some custom rules.

## Usage

Install the package:

```sh
npm install -DE eslint-config-simple-icons
```

Set `simple-icons` in the `extends` property of the _.eslintrc.json_ file:

```json
{
  "extends": "simple-icons"
}
```
