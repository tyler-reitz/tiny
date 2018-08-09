# @tdreitz/tiny

[![npm (scopeid)](https://img.shields.io/npm/v/@tdreitz/tiny.svg)](https://github.com/tyler-reitz/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @tdreitz/tiny
```

## Usage

```
const tiny = require('@tdreitz/tiny')

tiny('So much space!')
//=> 'Somuchspace!'

tiny(1337)
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
