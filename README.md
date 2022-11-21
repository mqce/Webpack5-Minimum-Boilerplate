Webpack5 Minimum Boilerplate
===========
![npm](https://img.shields.io/npm/v/webpack?label=webpack&style=flat-square&logo=webpack)
![npm](https://img.shields.io/npm/v/webpack-cli?label=webpack-cli&style=flat-square&logo=webpack)

Simplest Webpack 5 Boilerplate.

No babel, SASS, and other features.

## Setup
```sh
$ npm install
```

## Build
Build the app in production mode
```sh
$ npm run build
```

## webpack.config.js

```js
const path = require('path');

module.exports = {
  entry: './src/index.js',
  output: {
    filename: 'main.js',
    path: path.resolve(__dirname, 'dist'),
  }
};
```