# test coverage for  [static-server (v2.0.4)](https://github.com/nbluis/static-server#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-static-server.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-static-server) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-static-server.svg)](https://travis-ci.org/npmtest/node-npmtest-static-server)
#### A simple http server to serve static resource files from a local directory.

[![NPM](https://nodei.co/npm/static-server.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/static-server)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-static-server/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-static-server/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-static-server/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-static-server/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-static-server/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-static-server/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-static-server/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-static-server/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-static-server/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-static-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-static-server/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-static-server/build/test-report.html](https://npmtest.github.io/node-npmtest-static-server/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-static-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-static-server/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-static-server/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-static-server/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-static-server/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-static-server/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-static-server/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-static-server/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Eduardo Bohrer"
    },
    "bin": {
        "static-server": "./bin/static-server.js"
    },
    "bugs": {
        "url": "https://github.com/nbluis/static-server/issues"
    },
    "dependencies": {
        "chalk": "^0.5.1",
        "commander": "^2.3.0",
        "file-size": "0.0.5",
        "mime": "^1.2.11"
    },
    "description": "A simple http server to serve static resource files from a local directory.",
    "devDependencies": {
        "istanbul": "^0.3.0",
        "mocha": "^1.21.4",
        "should": "^4.0.4",
        "supertest": "^0.15.0"
    },
    "directories": {},
    "dist": {
        "shasum": "f6cd4946f09fc95f264fec4fa1ff442ca176dfc3",
        "tarball": "https://registry.npmjs.org/static-server/-/static-server-2.0.4.tgz"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "gitHead": "0e80faa065b4696b6dc9ccb3307407cebd980d04",
    "homepage": "https://github.com/nbluis/static-server#readme",
    "keywords": [
        "static",
        "server",
        "local",
        "assets"
    ],
    "license": {
        "type": "MIT",
        "url": "http://creativecommons.org/licenses/MIT/"
    },
    "main": "./server.js",
    "maintainers": [
        {
            "name": "nbluis"
        }
    ],
    "name": "static-server",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/nbluis/static-server.git"
    },
    "scripts": {
        "start": "node server.js",
        "test": "mocha",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly"
    },
    "version": "2.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
