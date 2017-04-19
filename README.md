# npmtest-redux-api-middleware

#### test coverage for  [redux-api-middleware (v1.0.2)](https://github.com/agraboso/redux-api-middleware)  [![npm package](https://img.shields.io/npm/v/npmtest-redux-api-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-redux-api-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-redux-api-middleware.svg)](https://travis-ci.org/npmtest/node-npmtest-redux-api-middleware)

#### Redux middleware for calling an API.

[![NPM](https://nodei.co/npm/redux-api-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-api-middleware)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-redux-api-middleware/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-redux-api-middleware/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-redux-api-middleware/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-redux-api-middleware/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-redux-api-middleware/build/test-report.html](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-redux-api-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-api-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-api-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-api-middleware/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-redux-api-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alberto Garcia-Raboso"
    },
    "bugs": {
        "url": "https://github.com/agraboso/redux-api-middleware/issues"
    },
    "dependencies": {
        "babel-runtime": "^5.8.25",
        "isomorphic-fetch": "^2.1.1",
        "lodash.isplainobject": "^3.2.0"
    },
    "description": "Redux middleware for calling an API.",
    "devDependencies": {
        "babel": "^5.8.23",
        "babel-eslint": "^4.1.3",
        "babel-istanbul": "^0.3.20",
        "coveralls": "^2.11.4",
        "eslint": "^1.6.0",
        "eslint-plugin-babel": "^2.1.1",
        "nock": "^2.15.0",
        "normalizr": "^1.1.0",
        "rimraf": "^2.4.3",
        "tap-spec": "^4.1.0",
        "tape": "^4.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "77a82ce6ef98359c7025679ca752470bd90576c0",
        "tarball": "https://registry.npmjs.org/redux-api-middleware/-/redux-api-middleware-1.0.2.tgz"
    },
    "files": [
        "README.md",
        "LICENSE.md",
        "lib/"
    ],
    "gitHead": "e72ac27801cab4f5c5cedfaa8d1787e0ffce6f5b",
    "homepage": "https://github.com/agraboso/redux-api-middleware",
    "keywords": [
        "redux",
        "api",
        "middleware",
        "redux-middleware",
        "flux"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "agraboso"
        }
    ],
    "name": "redux-api-middleware",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/agraboso/redux-api-middleware.git"
    },
    "scripts": {
        "build": "babel src --out-dir lib",
        "clean": "rimraf lib coverage",
        "cover": "babel-node ./node_modules/.bin/babel-istanbul cover test/index.js | tap-spec",
        "lint": "eslint src test",
        "prepublish": "npm run lint && npm test && npm run clean && npm run build",
        "test": "babel-node test/index.js | tap-spec"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
