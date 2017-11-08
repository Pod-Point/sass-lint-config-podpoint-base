# sass-lint-config-podpoint-base
[![npm](https://img.shields.io/npm/v/@pod-point/sass-lint-config-podpoint-base.svg)](https://www.npmjs.com/package/@pod-point/sass-lint-config-podpoint-base)

The base configuration for [Sass Lint](https://github.com/sasstools/sass-lint), to be included in every project using Sass.

## Installation

Install dependencies:

```
npm install --save-dev babel-eslint eslint eslint-config-airbnb-base eslint-plugin-import pod-point/eslint-config-podpoint-base
```

Create a `.sass-lint.yml` file with the following contents:

```yml
options:
  config-file: "./node_modules/@pod-point/sass-lint-config-podpoint-base/.sass-lint.yml"
```
