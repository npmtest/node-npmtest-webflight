# npmtest-webflight

#### basic test coverage for  [webflight (v0.1.8)](https://github.com/Team-Webflight/WebFlight#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-webflight.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-webflight) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-webflight.svg)](https://travis-ci.org/npmtest/node-npmtest-webflight)

#### Turns a server into a seed for peer-to-peer content delivery

[![NPM](https://nodei.co/npm/webflight.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/webflight)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-webflight/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-webflight/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-webflight/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-webflight/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-webflight/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-webflight/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-webflight/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-webflight/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-webflight/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-webflight/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-webflight/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-webflight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-webflight/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-webflight/build/test-report.html](https://npmtest.github.io/node-npmtest-webflight/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-webflight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-webflight/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-webflight/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-webflight/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-webflight/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-webflight/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-webflight/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-webflight/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Team WebFlight"
    },
    "bugs": {
        "url": "https://github.com/Team-WebFlight/WebFlight/issues"
    },
    "dependencies": {
        "babel-eslint": "^5.0.0",
        "casperjs": "^1.1.0-beta5",
        "cheerio": "^0.20.0",
        "create-torrent": "^3.22.2",
        "electron-prebuilt": "^0.37.2",
        "electron-spawn": "^4.1.1",
        "expect": "^1.15.2",
        "express": "^4.13.4",
        "jquery": "^2.2.1",
        "lodash": "^4.6.1",
        "mocha": "^2.4.5",
        "nodemon": "^1.9.1",
        "parse-torrent": "^5.7.3",
        "sha1": "^1.1.1",
        "webtorrent": "^0.82.1",
        "xvfb": "^0.2.3"
    },
    "description": "Turns a server into a seed for peer-to-peer content delivery",
    "devDependencies": {
        "babel-preset-es2015": "^6.6.0",
        "babelify": "^7.2.0",
        "chai": "^3.5.0",
        "chai-as-promised": "^5.2.0",
        "chai-fs": "^0.1.0",
        "standard": "^6.0.8"
    },
    "directories": {},
    "dist": {
        "shasum": "8f52f79ec46e16d20dd4ea6712e1506c001f4014",
        "tarball": "https://registry.npmjs.org/webflight/-/webflight-0.1.8.tgz"
    },
    "homepage": "https://github.com/Team-Webflight/WebFlight#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "carolag"
        },
        {
            "name": "coryc"
        },
        {
            "name": "jfowler"
        },
        {
            "name": "tbywong"
        }
    ],
    "name": "webflight",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Team-Webflight/WebFlight.git"
    },
    "scripts": {
        "test": "standard && mocha test/tests",
        "test-mocha": "mocha test/tests/wfstart.js",
        "test-start": "node test/fixtures/test-website/server.js"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "/test/fixtures/*",
            "/test/tests/wfstart.js",
            "/test/tests/addStatusBar/*"
        ]
    },
    "version": "0.1.8",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
