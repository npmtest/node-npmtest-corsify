# npmtest-corsify

#### basic test coverage for  [corsify (v2.1.0)](https://github.com/Raynos/corsify)  [![npm package](https://img.shields.io/npm/v/npmtest-corsify.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-corsify) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-corsify.svg)](https://travis-ci.org/npmtest/node-npmtest-corsify)

#### CORS up a route handler

[![NPM](https://nodei.co/npm/corsify.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/corsify)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-corsify/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-corsify/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-corsify/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-corsify/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-corsify/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-corsify/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-corsify/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-corsify/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-corsify/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-corsify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-corsify/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-corsify/build/test-report.html](https://npmtest.github.io/node-npmtest-corsify/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-corsify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-corsify/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-corsify/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-corsify/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-corsify/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-corsify/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-corsify/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-corsify/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "bugs": {
        "url": "https://github.com/Raynos/corsify/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "http-methods": "~0.1.0"
    },
    "description": "CORS up a route handler",
    "devDependencies": {
        "tape": "~1.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "11a45bc47ab30c54d00bb869ea1802fbcd9a09d0",
        "tarball": "https://registry.npmjs.org/corsify/-/corsify-2.1.0.tgz"
    },
    "gitHead": "9cb477b0d565d6a9ec331307efb45cf58585cfda",
    "homepage": "https://github.com/Raynos/corsify",
    "keywords": [],
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/Raynos/corsify/raw/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "raynos"
        }
    ],
    "name": "corsify",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/corsify.git"
    },
    "scripts": {
        "cover": "istanbul cover --report none --print detail ./test/index.js",
        "start": "node ./index.js",
        "test": "node ./test/index.js",
        "test-browser": "testem-browser ./test/browser/index.js",
        "testem": "testem-both -b=./test/browser/index.js",
        "travis-test": "istanbul cover ./test/index.js && ((cat coverage/lcov.info | coveralls) || exit 0)",
        "view-cover": "istanbul report html && google-chrome ./coverage/index.html",
        "watch": "nodemon -w ./index.js index.js"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": [
            "ie/8..latest",
            "firefox/16..latest",
            "firefox/nightly",
            "chrome/22..latest",
            "chrome/canary",
            "opera/12..latest",
            "opera/next",
            "safari/5.1..latest",
            "ipad/6.0..latest",
            "iphone/6.0..latest",
            "android-browser/4.2..latest"
        ]
    },
    "version": "2.1.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
