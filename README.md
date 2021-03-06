# npmdoc-qrcode

#### api documentation for  [qrcode (v0.8.1)](http://github.com/soldair/node-qrcode)  [![npm package](https://img.shields.io/npm/v/npmdoc-qrcode.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-qrcode) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-qrcode.svg)](https://travis-ci.org/npmdoc/node-npmdoc-qrcode)

#### QRCode / 2d Barcode api with both server side and client side support using canvas

[![NPM](https://nodei.co/npm/qrcode.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/qrcode)

- [https://npmdoc.github.io/node-npmdoc-qrcode/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-qrcode/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-qrcode/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-qrcode/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-qrcode/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-qrcode/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ryan Day"
    },
    "bin": {
        "qrcode": "./bin/qrcode"
    },
    "browser": {
        "./lib/index.js": "./lib/browser.js",
        "./lib/utils/buffer.js": "./lib/utils/typedarray-buffer.js"
    },
    "bugs": {
        "url": "https://github.com/soldair/node-qrcode/issues"
    },
    "contributors": [
        {
            "name": "Vincenzo Greco"
        }
    ],
    "dependencies": {
        "colors": "*",
        "dijkstrajs": "^1.0.1",
        "isarray": "^2.0.1",
        "pngjs": "^2.3.1"
    },
    "description": "QRCode / 2d Barcode api with both server side and client side support using canvas",
    "devDependencies": {
        "browserify": "^14.1.0",
        "canvas": "^1.6.4",
        "canvasutil": "*",
        "express": "2.5.x",
        "libxmljs": "^0.18.0",
        "os-tmpdir": "^1.0.2",
        "sinon": "^1.17.7",
        "standard": "*",
        "tap": "*",
        "uglify-js": "^2.7.5"
    },
    "directories": {},
    "dist": {
        "shasum": "5e802442cabdcacd4175b13b9546c063e1a99a92",
        "tarball": "https://registry.npmjs.org/qrcode/-/qrcode-0.8.1.tgz"
    },
    "engines": {
        "node": ">= 0.10"
    },
    "files": [
        "bin",
        "build",
        "lib",
        "helper"
    ],
    "gitHead": "61e24e7daec1b6eb48397cc4102dbd8d8c9f0b1c",
    "homepage": "http://github.com/soldair/node-qrcode",
    "keywords": [
        "canvas",
        "qrcode",
        "barcode"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "soldair"
        },
        {
            "name": "vigreco"
        }
    ],
    "name": "qrcode",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/soldair/node-qrcode.git"
    },
    "scripts": {
        "build": "node build.js",
        "lint": "standard",
        "prepublish": "npm run build",
        "pretest": "npm run lint",
        "test": "node test.js"
    },
    "standard": {
        "ignore": [
            "build/",
            "examples/vendors/"
        ]
    },
    "version": "0.8.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
