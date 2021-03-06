# hterm-umdjs
Chromium's hterm, automatically packaged as a UMD module (CommonJS/AMD/globals)

## Installation

```sh
$ npm install hterm-umdjs
```

## Usage

```js
import {hterm, lib} from 'hterm-umdjs';
// or
var htermUMDjs = require('hterm-umdjs');
var hterm = htermUMDjs.hterm;
var lib = htermUMDjs.lib;

hterm.defaultStorage = new lib.Storage.Memory();
var term = new hterm.Terminal();
```

## See also

* Chromium's [hterm](https://chromium.googlesource.com/apps/libapps/+/HEAD/hterm)
* [hterm-umd](https://www.npmjs.com/package/hterm-umd), another wrapper
