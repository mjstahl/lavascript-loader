# Webpack loader for Literate JavaScript

## Installation

```console
$ npm install --save-dev lavascript-loader
```

## Usage

### Configuration (recommended)

```js
// webpack.config.js
module.exports = {
  module: {
    rules: {
      { test: /\.js.md$/, use: 'lavascript-loader' }
    }
  }
}
```

### Inline

```js
import someModule from lavascript-loader!./some-module.js.md
```

### Command Line Interface

```console
$ webpack --module 'js.md=lavascript-loader'
```

