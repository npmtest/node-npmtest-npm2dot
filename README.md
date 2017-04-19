# npmtest-npm2dot

#### basic test coverage for  [npm2dot (v1.0.2)](https://github.com/wyvernnot/npm2dot#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-npm2dot.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-npm2dot) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-npm2dot.svg)](https://travis-ci.org/npmtest/node-npmtest-npm2dot)

#### convert npm dependency list to graphviz format

[![NPM](https://nodei.co/npm/npm2dot.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm2dot)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-npm2dot/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm2dot/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-npm2dot/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-npm2dot/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-npm2dot/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-npm2dot/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-npm2dot/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-npm2dot/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-npm2dot/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-npm2dot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-npm2dot/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-npm2dot/build/test-report.html](https://npmtest.github.io/node-npmtest-npm2dot/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-npm2dot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-npm2dot/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-npm2dot/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm2dot/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm2dot/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm2dot/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-npm2dot/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-npm2dot/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "wyvernnot"
    },
    "bin": {
        "npm2dot": "./bin/npm2dot"
    },
    "bugs": {
        "url": "https://github.com/wyvernnot/npm2dot/issues"
    },
    "dependencies": {},
    "description": "convert npm dependency list to graphviz format",
    "devDependencies": {
        "mocha": "^2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "c5de49d8824599c6204505fb2e00ed1f8d050bfc",
        "tarball": "https://registry.npmjs.org/npm2dot/-/npm2dot-1.0.2.tgz"
    },
    "gitHead": "7c368e661d7befb67e161a5c2eaef3ed61215079",
    "homepage": "https://github.com/wyvernnot/npm2dot#readme",
    "keywords": [
        "graphviz"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wyvernnot"
        }
    ],
    "name": "npm2dot",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wyvernnot/npm2dot.git"
    },
    "scripts": {
        "publish-patch": "mocha && npm version patch && git push && git push --tags && npm publish",
        "test": "mocha ./test"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
