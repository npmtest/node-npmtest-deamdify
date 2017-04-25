# npmtest-deamdify

#### basic test coverage for  [deamdify (v0.3.0)](https://github.com/jaredhanson/deamdify#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-deamdify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-deamdify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-deamdify.svg)](https://travis-ci.org/npmtest/node-npmtest-deamdify)

#### Browserify transform that converts AMD to CommonJS.

[![NPM](https://nodei.co/npm/deamdify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/deamdify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-deamdify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-deamdify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-deamdify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-deamdify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-deamdify/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-deamdify/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-deamdify/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-deamdify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-deamdify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-deamdify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-deamdify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-deamdify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-deamdify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-deamdify/build/test-report.html](https://npmtest.github.io/node-npmtest-deamdify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-deamdify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-deamdify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-deamdify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-deamdify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-deamdify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-deamdify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-deamdify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-deamdify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jared Hanson",
        "url": "http://www.jaredhanson.net/"
    },
    "bugs": {
        "url": "http://github.com/jaredhanson/deamdify/issues"
    },
    "dependencies": {
        "escodegen": "^1.8.1",
        "esprima": "^2.1.0",
        "estraverse": "^4.2.0",
        "through": "^2.3.8"
    },
    "description": "Browserify transform that converts AMD to CommonJS.",
    "devDependencies": {
        "chai": "^3.5.0",
        "mocha": "^3.2.0",
        "test-peer-range": "^1.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b91eb0b92ee7d6d0780546998db767234a8a2ac1",
        "tarball": "https://registry.npmjs.org/deamdify/-/deamdify-0.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "gitHead": "fbb3c7c95c8fdd771d2fbcb57508d34f14b155bc",
    "homepage": "https://github.com/jaredhanson/deamdify#readme",
    "keywords": [
        "browserify",
        "transform",
        "requirejs",
        "amd"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://www.opensource.org/licenses/MIT"
        }
    ],
    "main": "index.js",
    "maintainers": [
        {
            "name": "jaredhanson"
        },
        {
            "name": "tbranyen"
        }
    ],
    "name": "deamdify",
    "optionalDependencies": {},
    "peerDependencies": {
        "browserify": ">= 2.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/jaredhanson/deamdify.git"
    },
    "scripts": {
        "test": "test-peer-range browserify",
        "test-main": "mocha --reporter spec --require test/bootstrap/node test/*.test.js"
    },
    "version": "0.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
