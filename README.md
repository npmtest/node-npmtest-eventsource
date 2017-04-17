# test coverage for  [eventsource (v0.2.2)](http://github.com/aslakhellesoy/eventsource)  [![npm package](https://img.shields.io/npm/v/npmtest-eventsource.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eventsource) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eventsource.svg)](https://travis-ci.org/npmtest/node-npmtest-eventsource)
#### W3C compliant EventSource client for Node.js and browser (polyfill)

[![NPM](https://nodei.co/npm/eventsource.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eventsource)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eventsource/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventsource/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eventsource/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eventsource/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eventsource/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eventsource/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eventsource/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eventsource/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eventsource/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eventsource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eventsource/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eventsource/build/test-report.html](https://npmtest.github.io/node-npmtest-eventsource/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eventsource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eventsource/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eventsource/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eventsource/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eventsource/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eventsource/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Aslak Hellesøy"
    },
    "bugs": {
        "url": "http://github.com/aslakhellesoy/eventsource/issues"
    },
    "dependencies": {
        "original": "^1.0.0"
    },
    "description": "W3C compliant EventSource client for Node.js and browser (polyfill)",
    "devDependencies": {
        "express": "^4.13.4",
        "mocha": "^2.4.5",
        "serve-static": "^1.10.2",
        "sse": "^0.0.6",
        "webpack": "^1.12.14"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "8ac0576cbd16ee83478b3faaf27bdc7b7c8fcca9",
        "tarball": "https://registry.npmjs.org/eventsource/-/eventsource-0.2.2.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "b59da74de5916c45489f6362724f5225bae89e9a",
    "homepage": "http://github.com/aslakhellesoy/eventsource",
    "keywords": [
        "eventsource",
        "http",
        "streaming",
        "sse",
        "polyfill"
    ],
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/aslakhellesoy/eventsource/raw/master/LICENSE"
        }
    ],
    "main": "./lib/eventsource",
    "maintainers": [
        {
            "name": "aslakhellesoy"
        },
        {
            "name": "rexxars"
        }
    ],
    "name": "eventsource",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/aslakhellesoy/eventsource.git"
    },
    "scripts": {
        "polyfill": "webpack lib/eventsource-polyfill.js example/eventsource-polyfill.js",
        "postpublish": "git push && git push --tags",
        "test": "mocha --reporter spec"
    },
    "version": "0.2.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
