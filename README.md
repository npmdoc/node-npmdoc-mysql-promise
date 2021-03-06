# npmdoc-mysql-promise

#### api documentation for  mysql-promise (v4.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-mysql-promise.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mysql-promise) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mysql-promise.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mysql-promise)

#### Small wrapper for mysql that use promises.

[![NPM](https://nodei.co/npm/mysql-promise.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mysql-promise)

- [https://npmdoc.github.io/node-npmdoc-mysql-promise/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mysql-promise/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "mysql-promise",
    "version": "4.1.0",
    "description": "Small wrapper for mysql that use promises.",
    "main": "index.js",
    "scripts": {
        "test": "NODE_ENV=test npm run lint && istanbul cover -i 'index.js' _mocha -- -u exports -R spec 'test/**/*.test.js'",
        "lint": "eslint --ext '.js' test index.js",
        "release": "npm test && release-it -n -i patch",
        "release:minor": "npm test && release-it -n -i minor",
        "release:major": "npm test && release-it -n -i major"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/martinj/node-mysql-promise"
    },
    "keywords": [
        "mysql",
        "promise"
    ],
    "author": "Martin Jonsson <martin.jonsson@gmail.com>",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/martinj/node-mysql-promise/issues"
    },
    "dependencies": {
        "bluebird": "^3.4.6",
        "mysql": "^2.12.0"
    },
    "devDependencies": {
        "@aptoma/eslint-config": "^5.0.1",
        "eslint": "^2.13.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.1.2",
        "mysql2": "^1.1.2",
        "release-it": "^2.5.1",
        "should": "^11.1.1",
        "sinon": "^1.17.6"
    },
    "greenkeeper": {
        "ignore": [
            "eslint"
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
