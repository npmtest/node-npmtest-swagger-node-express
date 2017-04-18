# npmtest-swagger-node-express

#### test coverage for  [swagger-node-express (v2.1.3)](https://github.com/swagger-api/swagger-node-express)  [![npm package](https://img.shields.io/npm/v/npmtest-swagger-node-express.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-swagger-node-express) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-swagger-node-express.svg)](https://travis-ci.org/npmtest/node-npmtest-swagger-node-express)

#### Wordnik swagger implementation for the express framework

[![NPM](https://nodei.co/npm/swagger-node-express.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/swagger-node-express)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-swagger-node-express/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-node-express/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-node-express/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-swagger-node-express/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-swagger-node-express/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-swagger-node-express/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-swagger-node-express/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-swagger-node-express/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-swagger-node-express/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-swagger-node-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-swagger-node-express/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-swagger-node-express/build/test-report.html](https://npmtest.github.io/node-npmtest-swagger-node-express/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-swagger-node-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-swagger-node-express/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-swagger-node-express/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-swagger-node-express/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-swagger-node-express/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-swagger-node-express/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-swagger-node-express/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-swagger-node-express/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tony Tam",
        "url": "http://swagger.io"
    },
    "bugs": {
        "url": "https://github.com/swagger-api/swagger-node-express/issues"
    },
    "contributors": [
        {
            "name": "Pauh Hill"
        }
    ],
    "dependencies": {
        "lodash": "1.3.1"
    },
    "description": "Wordnik swagger implementation for the express framework",
    "devDependencies": {
        "cors": "2.1.1",
        "docco": "0.4.x",
        "express": "3.x",
        "jshint": "~2.3.0",
        "mocha": "~1.20.0",
        "once": "~1.3.0",
        "request": "~2.36.0",
        "should": "~4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "4b1fee976e11284d276575911980b2258e379dab",
        "tarball": "https://registry.npmjs.org/swagger-node-express/-/swagger-node-express-2.1.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.x"
    },
    "gitHead": "ade33c39a4a41e02bc18553a554717337ff45c13",
    "homepage": "https://github.com/swagger-api/swagger-node-express",
    "keywords": [
        "http",
        "rest",
        "swagger",
        "server"
    ],
    "license": "apache 2.0",
    "main": "index.js",
    "maintainers": [
        {
            "name": "wordnik"
        }
    ],
    "name": "swagger-node-express",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/swagger-api/swagger-node-express.git"
    },
    "scripts": {
        "pretest": "jshint lib",
        "start": "node sample-application/app.js",
        "test": "mocha -r should './test/**/*.js'"
    },
    "version": "2.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
