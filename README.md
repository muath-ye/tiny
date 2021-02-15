![npm](https://img.shields.io/npm/v/@muath-ye/tiny?label=tiny%20version&logo=npm&style=flat-square) 
[![npm developer name (Muathye)](https://img.shields.io/badge/Developer-Muathye-informational)](https://img.shields.io/badge/Developer-Muathye-informational)

Removes all spaces from a string.

## Install

```
$ npm install @muath-ye/tiny
```

## Usage

```js
const tiny = require("@muath-ye/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```