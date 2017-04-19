# npmtest-cacheman

#### basic test coverage for  [cacheman (v2.2.1)](https://github.com/cayasso/cacheman#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cacheman.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cacheman) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cacheman.svg)](https://travis-ci.org/npmtest/node-npmtest-cacheman)

#### Small and efficient cache provider for Node.JS with In-memory, Redis and MongoDB engines

[![NPM](https://nodei.co/npm/cacheman.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cacheman)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cacheman/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cacheman/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cacheman/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cacheman/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cacheman/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cacheman/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cacheman/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cacheman/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cacheman/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cacheman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cacheman/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cacheman/build/test-report.html](https://npmtest.github.io/node-npmtest-cacheman/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cacheman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cacheman/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cacheman/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cacheman/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cacheman/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cacheman/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cacheman/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cacheman/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Brumley"
    },
    "bugs": {
        "url": "https://github.com/cayasso/cacheman/issues"
    },
    "dependencies": {
        "cacheman-memory": "^1.0.2",
        "ms": "^0.7.1"
    },
    "description": "Small and efficient cache provider for Node.JS with In-memory, Redis and MongoDB engines",
    "devDependencies": {
        "babel-cli": "^6.4.5",
        "babel-core": "^6.4.5",
        "babel-plugin-add-module-exports": "^0.1.2",
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-stage-2": "^6.3.13",
        "bluebird": "^3.1.5",
        "mocha": "^2.4.4",
        "pre-commit": "^1.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "3510c0def12429d61b780128ff18f9d284bb02b8",
        "tarball": "https://registry.npmjs.org/cacheman/-/cacheman-2.2.1.tgz"
    },
    "gitHead": "19a3255c4e71fd1a17ec06140e5563ba60ab63d3",
    "homepage": "https://github.com/cayasso/cacheman#readme",
    "keywords": [
        "cache",
        "file",
        "redis",
        "memory",
        "mongodb",
        "caching",
        "mongo",
        "store",
        "ttl",
        "middleware",
        "bucket"
    ],
    "license": "MIT",
    "main": "./node/index",
    "maintainers": [
        {
            "name": "cayasso"
        }
    ],
    "name": "cacheman",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/cayasso/cacheman.git"
    },
    "scripts": {
        "prepublish": "make",
        "test": "make test"
    },
    "version": "2.2.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
