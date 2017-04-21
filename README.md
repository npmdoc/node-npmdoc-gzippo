# npmdoc-gzippo

#### api documentation for  [gzippo (v0.2.0)](http://www.tomg.co/gzippo)  [![npm package](https://img.shields.io/npm/v/npmdoc-gzippo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gzippo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gzippo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gzippo)

#### Gzip middleware for Connect using the native zlib library in node >= 0.6

[![NPM](https://nodei.co/npm/gzippo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gzippo)

- [https://npmdoc.github.io/node-npmdoc-gzippo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gzippo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gzippo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gzippo/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gzippo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gzippo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gzippo",
    "version": "0.2.0",
    "author": "Tom Gallacher",
    "description": "Gzip middleware for Connect using the native zlib library in node >= 0.6",
    "homepage": "http://www.tomg.co/gzippo",
    "repository": {
        "type": "git",
        "url": "git://github.com/tomgco/gzippo.git"
    },
    "keywords": [
        "compression",
        "gzip",
        "compress"
    ],
    "engines": {
        "node": ">= 0.5 < 0.9"
    },
    "scripts": {
        "test": "mocha"
    },
    "main": "./index.js",
    "dependencies": {
        "send": "*"
    },
    "devDependencies": {
        "should": "*",
        "connect": "~2",
        "express": "~3",
        "mocha": "*"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
