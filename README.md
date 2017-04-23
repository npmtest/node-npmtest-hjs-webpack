# npmtest-hjs-webpack

#### basic test coverage for  [hjs-webpack (v9.1.0)](https://github.com/henrikjoreteg/hjs-webpack)  [![npm package](https://img.shields.io/npm/v/npmtest-hjs-webpack.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hjs-webpack) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hjs-webpack.svg)](https://travis-ci.org/npmtest/node-npmtest-hjs-webpack)

#### Presets for setting up webpack with hotloading react and ES6(2015) using Babel.

[![NPM](https://nodei.co/npm/hjs-webpack.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hjs-webpack)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hjs-webpack/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hjs-webpack/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hjs-webpack/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hjs-webpack/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hjs-webpack/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hjs-webpack/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hjs-webpack/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hjs-webpack/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hjs-webpack/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hjs-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hjs-webpack/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hjs-webpack/build/test-report.html](https://npmtest.github.io/node-npmtest-hjs-webpack/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hjs-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hjs-webpack/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hjs-webpack/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hjs-webpack/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hjs-webpack/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hjs-webpack/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hjs-webpack/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hjs-webpack/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Henrik Joreteg"
    },
    "bin": {
        "hjs-dev-server": "bin/hjs-dev-server.js"
    },
    "bugs": {
        "url": "https://github.com/henrikjoreteg/hjs-webpack/issues"
    },
    "dependencies": {
        "compression": "^1.6.2",
        "connect-history-api-fallback": "^1.2.0",
        "contains-path": "^0.1.0",
        "express": "^4.14.0",
        "extract-text-webpack-plugin": "^2.1.0",
        "find-root": "^1.0.0",
        "http-proxy-middleware": "^0.17.0",
        "lodash.assign": "^4.0.6",
        "lodash.defaults": "^4.0.1",
        "lodash.pick": "^4.1.0",
        "rimraf": "^2.5.2",
        "webpack": "^2.2.1",
        "webpack-dev-middleware": "^1.10.0",
        "webpack-hot-middleware": "^2.16.1"
    },
    "description": "Presets for setting up webpack with hotloading react and ES6(2015) using Babel.",
    "devDependencies": {
        "git-validate": "^2.2.0",
        "standard": "^10.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5d314e61e39ca989f9192e1a847c435f2c2a4318",
        "tarball": "https://registry.npmjs.org/hjs-webpack/-/hjs-webpack-9.1.0.tgz"
    },
    "gitHead": "92c4ba5d0d6f7237d431128061837b16e62e7992",
    "homepage": "https://github.com/henrikjoreteg/hjs-webpack",
    "keywords": [
        "config",
        "human javascript",
        "webpack"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "dignifiedquire"
        },
        {
            "name": "henrikjoreteg"
        },
        {
            "name": "jasonrose"
        },
        {
            "name": "lukekarrys"
        },
        {
            "name": "selbekk"
        }
    ],
    "name": "hjs-webpack",
    "optionalDependencies": {},
    "pre-commit": [
        "lint",
        "validate"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/henrikjoreteg/hjs-webpack.git"
    },
    "scripts": {
        "lint": "standard",
        "validate": "npm ls"
    },
    "standard": {
        "ignore": [
            "examples/*/public/*",
            "examples/*/node_modules/*"
        ]
    },
    "version": "9.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
