# npmtest-paralleljs

#### basic test-coverage for  [paralleljs (v0.2.1)](https://github.com/adambom/parallel.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-paralleljs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-paralleljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-paralleljs.svg)](https://travis-ci.org/npmtest/node-npmtest-paralleljs)

#### parallel.js enables easy multi-thread processing in javascript

[![NPM](https://nodei.co/npm/paralleljs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/paralleljs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-paralleljs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-paralleljs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-paralleljs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-paralleljs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-paralleljs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-paralleljs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-paralleljs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-paralleljs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-paralleljs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-paralleljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-paralleljs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-paralleljs/build/test-report.html](https://npmtest.github.io/node-npmtest-paralleljs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-paralleljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-paralleljs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-paralleljs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-paralleljs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-paralleljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-paralleljs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-paralleljs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-paralleljs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Adam Savitzky"
    },
    "bugs": {
        "url": "https://github.com/adambom/parallel.js/issues"
    },
    "contributors": [
        {
            "name": "Sebastian Mayr",
            "url": "http://s3bmaster.blogspot.co.at/"
        }
    ],
    "dependencies": {},
    "description": "parallel.js enables easy multi-thread processing in javascript",
    "devDependencies": {
        "jasmine-node": "x",
        "q": "x"
    },
    "directories": {
        "lib": "lib",
        "test": "test"
    },
    "dist": {
        "shasum": "ebca745d3e09c01e2bebcc14858891ff4510e926",
        "tarball": "https://registry.npmjs.org/paralleljs/-/paralleljs-0.2.1.tgz"
    },
    "engines": {
        "node": ">=0.9.10"
    },
    "homepage": "https://github.com/adambom/parallel.js#readme",
    "keywords": [
        "parallel",
        "spawn",
        "map",
        "thread",
        "parallel.js",
        "workers",
        "webworkers"
    ],
    "license": "BSD",
    "main": "lib/parallel.js",
    "maintainers": [
        {
            "name": "asavitzky"
        }
    ],
    "name": "paralleljs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/adambom/parallel.js.git"
    },
    "scripts": {
        "test": "jasmine-node --verbose test/specs"
    },
    "testling": {
        "scripts": [
            "test/lib/jasmine/jasmine.js",
            "test/specs/*.js",
            "test/runner.js"
        ]
    },
    "version": "0.2.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
