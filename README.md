# npmdoc-karma-fixture

#### basic api documentation for  [karma-fixture (v0.2.6)](https://github.com/billtrik/karma-fixture)  [![npm package](https://img.shields.io/npm/v/npmdoc-karma-fixture.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-karma-fixture) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-karma-fixture.svg)](https://travis-ci.org/npmdoc/node-npmdoc-karma-fixture)

#### A plugin for the Karma test runner that loads .html and .json fixtures

[![NPM](https://nodei.co/npm/karma-fixture.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/karma-fixture)

- [https://npmdoc.github.io/node-npmdoc-karma-fixture/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-karma-fixture/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-karma-fixture/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-karma-fixture/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-karma-fixture/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-karma-fixture/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Bill Trikalinos"
    },
    "bugs": {
        "url": "https://github.com/billtrik/karma-fixture/issues"
    },
    "dependencies": {},
    "description": "A plugin for the Karma test runner that loads .html and .json fixtures",
    "devDependencies": {
        "coffee-script": "^1.7.1",
        "karma": "^0.12.31",
        "karma-chai": "^0.1.0",
        "karma-cli": "0.0.4",
        "karma-coffee-preprocessor": "^0.2.1",
        "karma-mocha": "^0.1.3",
        "karma-mocha-reporter": "^1.0.0",
        "karma-phantomjs-launcher": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "971cea8c216d73f07043964cb73f10e0830018ef",
        "tarball": "https://registry.npmjs.org/karma-fixture/-/karma-fixture-0.2.6.tgz"
    },
    "gitHead": "2cd6463e761e0c26c3180ba01d27f45e0b3aa892",
    "homepage": "https://github.com/billtrik/karma-fixture",
    "keywords": [
        "karma",
        "karma-plugin",
        "fixtures",
        "fixture"
    ],
    "license": "MIT",
    "main": "./lib/index.js",
    "maintainers": [
        {
            "name": "billtrik"
        }
    ],
    "name": "karma-fixture",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/billtrik/karma-fixture.git"
    },
    "scripts": {
        "prepublish": "coffee -o lib -c src/*.coffee",
        "test": "node ./node_modules/karma/bin/karma start --single-run"
    },
    "version": "0.2.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
