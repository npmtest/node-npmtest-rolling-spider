# npmtest-rolling-spider

#### basic test coverage for  [rolling-spider (v1.7.0)](https://github.com/voodootikigod/node-rolling-spider#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-rolling-spider.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-rolling-spider) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-rolling-spider.svg)](https://travis-ci.org/npmtest/node-npmtest-rolling-spider)

#### A library for sending BLE commands to a Parrot Rolling Spider drone

[![NPM](https://nodei.co/npm/rolling-spider.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/rolling-spider)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-rolling-spider/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-rolling-spider/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-rolling-spider/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-rolling-spider/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-rolling-spider/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-rolling-spider/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-rolling-spider/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-rolling-spider/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-rolling-spider/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-rolling-spider/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-rolling-spider/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-rolling-spider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-rolling-spider/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-rolling-spider/build/test-report.html](https://npmtest.github.io/node-npmtest-rolling-spider/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-rolling-spider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-rolling-spider/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-rolling-spider/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-rolling-spider/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-rolling-spider/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-rolling-spider/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-rolling-spider/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-rolling-spider/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jack Watson-Hamblin",
        "url": "https://motioninmotion.tv/"
    },
    "bugs": {
        "url": "https://github.com/FluffyJack/node-rolling-spider/issues"
    },
    "dependencies": {
        "debug": "^2.1.1",
        "keypress": "^0.2.1",
        "lodash": "3.9.3",
        "logitech-dual-action-controller": "git+https://github.com/voodootikigod/node-logitech-dual-action-controller.git",
        "noble": "^1.8.0"
    },
    "description": "A library for sending BLE commands to a Parrot Rolling Spider drone",
    "devDependencies": {
        "eslint": "^3.19.0",
        "eslint-config-eta": "^0.0.9",
        "mocha": "2.2.5",
        "should": "6.0.3",
        "sinon": "1.14.1",
        "temporal": "^0.4.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f929f5e065c225242d539ba1a3a1c89d945945d9",
        "tarball": "https://registry.npmjs.org/rolling-spider/-/rolling-spider-1.7.0.tgz"
    },
    "gitHead": "db5f8a88d160d782c5fef6f1c52458818701c921",
    "homepage": "https://github.com/voodootikigod/node-rolling-spider#readme",
    "keywords": [
        "bluetooth",
        "ble",
        "parrot",
        "rolling-spider",
        "drone",
        "quadcopter",
        "multicopter",
        "flight"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fluffyjack"
        },
        {
            "name": "lynnaloo"
        },
        {
            "name": "voodootikigod"
        }
    ],
    "name": "rolling-spider",
    "optionalDependencies": {
        "logitech-dual-action-controller": "git+https://github.com/voodootikigod/node-logitech-dual-action-controller.git"
    },
    "os": [
        "darwin",
        "linux",
        "win32"
    ],
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/voodootikigod/node-rolling-spider.git"
    },
    "scripts": {
        "lint": "eslint . --ext .js",
        "test": "mocha"
    },
    "version": "1.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
