# @ymanjuy/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@bamblehorse/tiny.svg)](https://www.npmjs.com/package/@ymanjuy/tiny)
[![npm bundle size (minified)](https://img.shields.io/npm/v/tiny.svg?style=popout)](https://www.npmjs.com/package/@ymanjuy/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @ymanjuy/tiny
```

## Usage

```js
const tiny = require("@ymanjuy/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
