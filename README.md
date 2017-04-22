# npmtest-usb-detection

#### basic test coverage for  [usb-detection (v1.4.0)](https://github.com/MadLittleMods/node-usb-detection)  [![npm package](https://img.shields.io/npm/v/npmtest-usb-detection.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-usb-detection) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-usb-detection.svg)](https://travis-ci.org/npmtest/node-npmtest-usb-detection)

#### Listen to USB devices and detect changes on them.

[![NPM](https://nodei.co/npm/usb-detection.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/usb-detection)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-usb-detection/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-usb-detection/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-usb-detection/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-usb-detection/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-usb-detection/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-usb-detection/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-usb-detection/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-usb-detection/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-usb-detection/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-usb-detection/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-usb-detection/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-usb-detection/build/test-report.html](https://npmtest.github.io/node-npmtest-usb-detection/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-usb-detection/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-usb-detection/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-usb-detection/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-usb-detection/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-usb-detection/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-usb-detection/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-usb-detection/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-usb-detection/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "usb-detection",
    "version": "1.4.0",
    "description": "Listen to USB devices and detect changes on them.",
    "main": "index.js",
    "gypfile": true,
    "scripts": {
        "test": "mocha --timeout 10000",
        "postinstall": "node-gyp rebuild"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/MadLittleMods/node-usb-detection.git"
    },
    "keywords": [
        "usb",
        "device",
        "hardware",
        "list",
        "insert",
        "add",
        "remove",
        "change",
        "plug",
        "unplug",
        "notification"
    ],
    "homepage": "https://github.com/MadLittleMods/node-usb-detection",
    "bugs": {
        "url": "https://github.com/MadLittleMods/node-usb-detection/issues"
    },
    "license": {
        "type": "MIT",
        "url": "https://raw.github.com/MadLittleMods/node-usb-detection/master/licence"
    },
    "dependencies": {
        "bindings": "1.1.0",
        "bluebird": "^2.9.27",
        "eventemitter2": ">=0.4.11",
        "nan": "^2.2.0"
    },
    "devDependencies": {
        "chai": "^3.0.0",
        "chai-as-promised": "^5.1.0",
        "chalk": "^1.0.0",
        "mocha": "^2.2.5"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
