# <img width=25 src="https://i.imgur.com/qCFeJOK.png"> Webpack Config

<p align=center>
  <a href="https://www.npmjs.com/package/@bamdadsabbagh/webpack-config"><img width=150 src="https://i.imgur.com/qCFeJOK.png"></a>
</p>

<p align=center>
  Bamdad Sabbagh's webpack config
</p>

<p align=center>
  <img src="https://img.shields.io/badge/role-lead-blueviolet">
</p>

<p align=center>
  <a href="https://github.com/bamdadsabbagh/webpack-config"><img src="https://img.shields.io/github/stars/bamdadsabbagh/webpack-config?label=git"></a>
  <img src="https://img.shields.io/github/license/bamdadsabbagh/webpack-config">
</p>

<p align=center>
  <img src="https://img.shields.io/github/languages/count/bamdadsabbagh/webpack-config">
  <img src="https://img.shields.io/github/languages/top/bamdadsabbagh/webpack-config">
</p>

<p align=center>
  <img src="https://img.shields.io/github/v/release/bamdadsabbagh/webpack-config">
  <img src="https://api.codeclimate.com/v1/badges/6891219ecb0b930cb5e7/maintainability">
</p>

<p align=center>
  <img src="https://img.shields.io/david/bamdadsabbagh/webpack-config">
  <img src="https://img.shields.io/david/dev/bamdadsabbagh/webpack-config">
  <img src="https://img.shields.io/snyk/vulnerabilities/github/bamdadsabbagh/webpack-config">
</p>

<p align=center>
  <img src="https://img.shields.io/npm/v/@bamdadsabbagh/webpack-config">
  <img src="https://img.shields.io/npm/dw/@bamdadsabbagh/webpack-config">
  <img src="https://img.shields.io/npm/dm/@bamdadsabbagh/webpack-config">
</p>

<p align=center>
  <img src="https://img.shields.io/badge/ci-github--actions-yellowgreen">
  <img src="https://img.shields.io/badge/cd-docker-yellowgreen">
</p>

## Vendor

> [webpack](https://webpack.js.org/) config.

## npm

> [npm](https://www.npmjs.com/package/@bamdadsabbagh/webpack-config) package.

## Installation

```shell
yarn add --dev @bamdadsabbagh/webpack-config
```

## Usage

```json
{
    "start": "cross-env NODE_ENV=development webpack-dev-server --config node_modules/@bamdadsabbagh/webpack-config/webpack.dev.js",
    "build": "yarn build:clean && yarn build:webpack && yarn build:serve",
    "build:clean": "rm -rf dist/",
    "build:webpack": "cross-env NODE_ENV=production webpack --config node_modules/@bamdadsabbagh/webpack-config/webpack.prod.js",
    "build:serve": "serve -s dist/"
}
```
