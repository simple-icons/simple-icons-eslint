# simple-icons-eslint

Simple Icons ESLint base configuration for all repositories.

Is a configuration based on [`eslint:recommended`](https://github.com/eslint/eslint/blob/e5e9e271da58361bda16f7abc8f367ccc6f91510/conf/eslint-recommended.js) and [`eslint-plugin-prettier`](https://github.com/prettier/eslint-plugin-prettier) with some custom rules.

## Usage

Install the package:

```sh
npm install -D simple-icons-eslint
```

Add `simple-icons-eslint` to the `extends` array of the *.eslintrc.json* file:

```json
{
  "extends": ["simple-icons-eslint"]
}
```
