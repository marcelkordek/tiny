# @marcelkordek/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@marcelkordek/tiny)](https://github.com/marcelkordek/tiny) [![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@marcelkordek/tins?label=minified%20size)](https://github.com/marcelkordek/tiny)

NPM Package - Removes all spaces from a string

## Install

```
$ npm install @marcelkordek/tiny
```

## Usage

```js
const tiny = require("@marcelkordek/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```