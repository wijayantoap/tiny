# @wijayantoap/tiny

![npm (scoped)](https://img.shields.io/github/issues/wijayantoap/tiny.svg)
[![npm bundle size (minified)](https://img.shields.io/github/license/wijayantoap/tiny.svg)](https://www.npmjs.com/package/@wijayantoap/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @wijayantoap/tiny
```

## Usage

```js
const tiny = require("@wijayantoap/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
