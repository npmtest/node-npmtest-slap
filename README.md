# npmtest-slap

#### basic test coverage for  [slap (v0.1.61)](https://github.com/slap-editor/slap#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-slap.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-slap) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-slap.svg)](https://travis-ci.org/npmtest/node-npmtest-slap)

#### Sublime-like terminal-based text editor

[![NPM](https://nodei.co/npm/slap.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/slap)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-slap/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-slap/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-slap/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-slap/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-slap/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-slap/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-slap/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-slap/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-slap/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-slap/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-slap/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-slap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-slap/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-slap/build/test-report.html](https://npmtest.github.io/node-npmtest-slap/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-slap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-slap/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-slap/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-slap/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-slap/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-slap/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-slap/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-slap/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": "",
    "bin": {
        "slap": "./slap.js"
    },
    "bugs": {
        "url": "https://github.com/slap-editor/slap/issues"
    },
    "dependencies": {
        "base-widget": "1.1.0",
        "blessed": "0.1.81",
        "bluebird": "3.4.1",
        "editor-widget": "1.1.1",
        "lodash": "4.14.1",
        "mkdirp": "0.5.1",
        "node-clap": "0.0.5",
        "rc": "1.1.6",
        "slap-util": "1.0.7",
        "ttys": "0.0.3",
        "update-notifier": "1.0.2"
    },
    "description": "Sublime-like terminal-based text editor",
    "devDependencies": {
        "get-random-port": "0.0.1",
        "istanbul": "0.4.4",
        "node-inspector": "0.12.8",
        "tape": "4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "179973ca85785d1b1c98f2a755a3ede866352a9a",
        "tarball": "https://registry.npmjs.org/slap/-/slap-0.1.61.tgz"
    },
    "gitHead": "0a55af6760fb12e6bf20f63d866608b960268d0e",
    "homepage": "https://github.com/slap-editor/slap#readme",
    "license": "MIT",
    "main": "lib/cli.js",
    "maintainers": [
        {
            "name": "dbkaplun"
        }
    ],
    "name": "slap",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/slap-editor/slap.git"
    },
    "scripts": {
        "cover": "istanbul cover spec/index.js",
        "debug": "node-debug ./slap.js",
        "start": "./slap.js",
        "test": "spec/index.js"
    },
    "version": "0.1.61"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
