# #@devtunnel/tiny

It's the tiniest!

[![npm (scoped)](https://img.shields.io/badge/npm-v1.0.0-blue)](https://github.com/@devtunnel/tiny)

Removes all spaces from a string.

## Install
```
$ npm install @devtunnel/tiny
```

## Usage
```js
const tiny = require('@devtunnel/tiny')

tiny('So much space!')
// => 'Somuchspace!'

tiny(1337)
// => Uncaught TypeError: Tiny wants a string!
```
