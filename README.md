# sass-lint-config-podpoint-base
[![npm](https://img.shields.io/npm/v/@pod-point/sass-lint-config-podpoint-base.svg)](https://www.npmjs.com/package/@pod-point/sass-lint-config-podpoint-base)

The base configuration for [Sass Lint](https://github.com/sasstools/sass-lint), to be included in every project using Sass.

## Installation

Install sass-lint globally:

```
npm install -g sass-lint
```

Install sass-lint as a dev dependency:

```
npm install --save-dev sass-lint
```

Install this package to use the config:

```
npm install --save-dev pod-point/sass-lint-config-podpoint-base
```

## Usage

Create a `.sass-lint.yml` file with the following contents:

```yml
options:
  config-file: "./node_modules/@pod-point/sass-lint-config-podpoint-base/.sass-lint.yml"
```

Note that rules can be added or overridden by creating in the following way:

```yml
options:
  config-file: "./node_modules/@pod-point/sass-lint-config-podpoint-base/.sass-lint.yml"
rules:
  indentation:
    - 4
```
