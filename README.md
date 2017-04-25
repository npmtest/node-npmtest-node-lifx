# npmtest-node-lifx

#### basic test coverage for  [node-lifx (v0.8.0)](https://github.com/MariusRumpf/node-lifx#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-node-lifx.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-lifx) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-lifx.svg)](https://travis-ci.org/npmtest/node-npmtest-node-lifx)

#### Node.js implementation of the LIFX protocol

[![NPM](https://nodei.co/npm/node-lifx.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-lifx)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-lifx/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-lifx/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-lifx/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-lifx/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-lifx/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-node-lifx/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-node-lifx/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-lifx/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-lifx/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-lifx/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-lifx/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-lifx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-lifx/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-lifx/build/test-report.html](https://npmtest.github.io/node-npmtest-node-lifx/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-lifx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-lifx/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-lifx/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-lifx/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-lifx/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-lifx/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-lifx/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-lifx/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Marius Rumpf"
    },
    "bugs": {
        "url": "https://github.com/MariusRumpf/node-lifx/issues"
    },
    "dependencies": {
        "eventemitter3": "^2.0.2",
        "lodash": "^4.5.0"
    },
    "description": "Node.js implementation of the LIFX protocol",
    "devDependencies": {
        "babel-core": "^6.0.15",
        "babel-preset-es2015": "^6.0.15",
        "chai": "^3.0.0",
        "codecov.io": "^0.1.6",
        "eslint": "^2.13.1",
        "istanbul": "^0.4.0",
        "lolex": "^1.4.0",
        "mocha": "^2.2.4"
    },
    "directories": {
        "test": "test",
        "lib": "lib",
        "example": "example"
    },
    "dist": {
        "shasum": "2f96993562100b9155e2ec49ddecbfc33c9a3dae",
        "tarball": "https://registry.npmjs.org/node-lifx/-/node-lifx-0.8.0.tgz"
    },
    "gitHead": "29a1263cc6afda9c354da02d36422109f0b32db9",
    "homepage": "https://github.com/MariusRumpf/node-lifx#readme",
    "keywords": [
        "bulb",
        "lifx",
        "light",
        "lightbulb"
    ],
    "license": "MIT",
    "main": "./lib/lifx",
    "maintainers": [
        {
            "name": "mariusrumpf"
        }
    ],
    "name": "node-lifx",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/MariusRumpf/node-lifx.git"
    },
    "scripts": {
        "lint": "eslint lib/ test/ example/ cli.js",
        "pretest": "npm run lint",
        "report-coverage": "cat ./coverage/coverage.json | node_modules/codecov.io/bin/codecov.io.js",
        "test": "istanbul cover -root lib/ node_modules/mocha/bin/_mocha -- -u tdd -r babelhook --recursive test/unit/"
    },
    "version": "0.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
