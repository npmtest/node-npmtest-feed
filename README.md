# npmtest-feed

#### basic test coverage for  [feed (v1.0.2)](http://projets.jpmonette.net/en/feed)  [![npm package](https://img.shields.io/npm/v/npmtest-feed.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-feed) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-feed.svg)](https://travis-ci.org/npmtest/node-npmtest-feed)

#### Feed is a RSS and Atom feed generator for Node.js, making content syndication simple and intuitive!

[![NPM](https://nodei.co/npm/feed.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/feed)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-feed/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-feed/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-feed/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-feed/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-feed/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-feed/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-feed/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-feed/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-feed/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-feed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-feed/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-feed/build/test-report.html](https://npmtest.github.io/node-npmtest-feed/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-feed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-feed/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-feed/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-feed/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-feed/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-feed/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-feed/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-feed/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jean-Philippe Monette"
    },
    "bugs": {
        "url": "https://github.com/jpmonette/feed/issues"
    },
    "contributors": [
        {
            "name": "Pierre Galvez"
        }
    ],
    "dependencies": {
        "xml": ">= 0.0.5"
    },
    "description": "Feed is a RSS and Atom feed generator for Node.js, making content syndication simple and intuitive!",
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-preset-latest": "^6.24.0",
        "coveralls": "^2.13.0",
        "jest": "^19.0.2"
    },
    "directories": {},
    "dist": {
        "shasum": "730e28d5835b9a40b3e3eee21f65e37486b7eadc",
        "tarball": "https://registry.npmjs.org/feed/-/feed-1.0.2.tgz"
    },
    "engines": {
        "node": ">=0.4.0"
    },
    "gitHead": "28107323ba5b05f212a283a3fa29f29323552ec3",
    "homepage": "http://projets.jpmonette.net/en/feed",
    "jest": {
        "verbose": true,
        "collectCoverage": true,
        "collectCoverageFrom": [
            "**/src/*.{js}"
        ],
        "testMatch": [
            "**/*.spec.js"
        ]
    },
    "keywords": [
        "rss",
        "atom",
        "feed",
        "syndication",
        "xml",
        "wrapper",
        "blog"
    ],
    "license": "MIT",
    "main": "lib/feed.js",
    "maintainers": [
        {
            "name": "jpmonette"
        }
    ],
    "name": "feed",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jpmonette/feed.git"
    },
    "scripts": {
        "build": "rm -rf lib/ && mkdir lib && babel -d lib/ src/ --ignore **/*.spec.js -s",
        "prepublish": "npm run build",
        "test": "export NODE_ENV=test && jest",
        "test-travis": "export NODE_ENV=test && jest"
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
