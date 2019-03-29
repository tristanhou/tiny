# @johnhuu/tiny
[![npm](https://img.shields.io/npm/v/@johnhuu/tiny.svg)](https://www.npmjs.com/package/@johnhuu/tiny)

Removes all spaces from a string
###Install
```
$ npm install @bamblehorse/tiny
```
###Usage
```
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
// 
```
