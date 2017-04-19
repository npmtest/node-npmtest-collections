# npmtest-collections

#### test coverage for  [collections (v5.0.6)](http://www.collectionsjs.com)  [![npm package](https://img.shields.io/npm/v/npmtest-collections.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-collections) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-collections.svg)](https://travis-ci.org/npmtest/node-npmtest-collections)

#### data structures with idiomatic JavaScript collection interfaces

[![NPM](https://nodei.co/npm/collections.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/collections)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-collections/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-collections/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-collections/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-collections/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-collections/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-collections/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-collections/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-collections/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-collections/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-collections/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-collections/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-collections/build/test-report.html](https://npmtest.github.io/node-npmtest-collections/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-collections/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-collections/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-collections/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-collections/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-collections/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-collections/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-collections/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-collections/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kris Kowal",
        "url": "http://github.com/kriskowal"
    },
    "bugs": {
        "url": "http://github.com/montagejs/collections/issues"
    },
    "contributors": [
        {
            "name": "Benoit Marchant"
        }
    ],
    "dependencies": {
        "weak-map": "~1.0.x"
    },
    "description": "data structures with idiomatic JavaScript collection interfaces",
    "devDependencies": {
        "istanbul": "*",
        "jasmine-node": "github:montagestudio/jasmine-node#master",
        "opener": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "539c0ec6f300cec8f1da207cba8d165cbbbb6992",
        "tarball": "https://registry.npmjs.org/collections/-/collections-5.0.6.tgz"
    },
    "gitHead": "4690d1aaea3f7db3b5b4010e6326fcbf7ed7397b",
    "homepage": "http://www.collectionsjs.com",
    "keywords": [
        "collections",
        "data structures",
        "observable",
        "list",
        "set",
        "map",
        "splay"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/montagejs/collections/master/LICENSE.md"
        }
    ],
    "maintainers": [
        {
            "name": "kriskowal"
        },
        {
            "name": "aadsm"
        },
        {
            "name": "francoisfrisch"
        },
        {
            "name": "marchant"
        },
        {
            "name": "stuk"
        }
    ],
    "name": "collections",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/montagejs/collections.git"
    },
    "scripts": {
        "cover": "istanbul cover node_modules/jasmine-node/bin/jasmine-node spec && istanbul report html && opener coverage/index.html",
        "test": "jasmine-node spec"
    },
    "version": "5.0.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
