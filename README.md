# #devtunnel1/tiny

It's the tiniest!

[![npm (scoped)](https://img.shields.io/badge/npm-v1.0.0-blue)](https://github.com/devtunnel1/tiny)

Removes all spaces from a string.

## Install
```
$ npm install @devtunnel1/tiny
```

## Usage
```js
const tiny = require('@devtunnel1/tiny')

tiny('So much space!')
// => 'Somuchspace!'

tiny(1337)
// => Uncaught TypeError: Tiny wants a string!
```
