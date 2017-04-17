# test coverage for  [edge (v6.5.1)](https://github.com/tjanczuk/edge)  [![npm package](https://img.shields.io/npm/v/npmtest-edge.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-edge) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-edge.svg)](https://travis-ci.org/npmtest/node-npmtest-edge)
#### Edge.js: run .NET and Node.js in-process on Windows, Mac OS, and Linux

[![NPM](https://nodei.co/npm/edge.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/edge)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-edge/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-edge/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-edge/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-edge/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-edge/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-edge/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-edge/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-edge/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-edge/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-edge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-edge/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-edge/build/test-report.html](https://npmtest.github.io/node-npmtest-edge/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-edge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-edge/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-edge/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-edge/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-edge/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-edge/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-edge/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-edge/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tomasz Janczuk",
        "url": "http://tomasz.janczuk.org"
    },
    "bugs": {
        "url": "http://github.com/tjanczuk/edge/issues"
    },
    "dependencies": {
        "edge-cs": "1.2.1",
        "nan": "^2.0.9"
    },
    "description": "Edge.js: run .NET and Node.js in-process on Windows, Mac OS, and Linux",
    "devDependencies": {
        "jshint": "1.1.0",
        "mocha": "2.5.3"
    },
    "directories": {},
    "dist": {
        "shasum": "d3ebb02d0a7c044cb80bdfd4275ba64df9da57bb",
        "tarball": "https://registry.npmjs.org/edge/-/edge-6.5.1.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "gitHead": "636f6cf4f91eb7b1111e84d8927e116464a0a1c7",
    "homepage": "https://github.com/tjanczuk/edge",
    "licenses": [
        {
            "type": "Apache",
            "url": "http://www.apache.org/licenses/LICENSE-2.0"
        }
    ],
    "main": "./lib/edge.js",
    "maintainers": [
        {
            "name": "tjanczuk"
        }
    ],
    "name": "edge",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/tjanczuk/edge.git"
    },
    "scripts": {
        "install": "node tools/install.js",
        "jshint": "node ./tools/runJsHint.js",
        "test": "node tools/test.js"
    },
    "tags": [
        "owin",
        "edge",
        "net",
        "clr",
        "coreclr",
        "c#",
        "mono",
        "managed",
        ".net"
    ],
    "version": "6.5.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
