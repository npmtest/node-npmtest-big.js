# npmtest-big.js

#### basic test coverage for  [big.js (v3.1.3)](https://github.com/MikeMcl/big.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-big.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-big.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-big.js.svg)](https://travis-ci.org/npmtest/node-npmtest-big.js)

#### A small, fast, easy-to-use library for arbitrary-precision decimal arithmetic

[![NPM](https://nodei.co/npm/big.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/big.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-big.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-big.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-big.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-big.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-big.js/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-big.js/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-big.js/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-big.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-big.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-big.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-big.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-big.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-big.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-big.js/build/test-report.html](https://npmtest.github.io/node-npmtest-big.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-big.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-big.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-big.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-big.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-big.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-big.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-big.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-big.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Mclaughlin"
    },
    "bugs": {
        "url": "https://github.com/MikeMcl/big.js/issues"
    },
    "dependencies": {},
    "description": "A small, fast, easy-to-use library for arbitrary-precision decimal arithmetic",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "4cada2193652eb3ca9ec8e55c9015669c9806978",
        "tarball": "https://registry.npmjs.org/big.js/-/big.js-3.1.3.tgz"
    },
    "engines": {
        "node": "*"
    },
    "files": [
        "big.js",
        "big.min.js"
    ],
    "gitHead": "86268e96b3dbf6db8ce319489f410277d9d4ea1b",
    "homepage": "https://github.com/MikeMcl/big.js#readme",
    "keywords": [
        "arbitrary",
        "precision",
        "arithmetic",
        "big",
        "number",
        "decimal",
        "float",
        "biginteger",
        "bigdecimal",
        "bignumber",
        "bigint",
        "bignum"
    ],
    "license": "MIT",
    "main": "./big",
    "maintainers": [
        {
            "name": "mikemcl"
        }
    ],
    "name": "big.js",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MikeMcl/big.js.git"
    },
    "scripts": {
        "build": "uglifyjs -o ./big.min.js ./big.js",
        "test": "node ./test/every-test.js"
    },
    "version": "3.1.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
