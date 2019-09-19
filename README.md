# demo-npm-version
A repository to test the semantic versioning on prerelease npm packages
![npm](https://img.shields.io/npm/v/@mikemalt/tiny?style=for-the-badge)

Removes all spaces from a string.

## Install
```
$ npm install @mikemalt/tiny
```

## Usage
const tiny = require("@mikemalt/tiny")

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
