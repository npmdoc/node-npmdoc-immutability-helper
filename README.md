# npmdoc-immutability-helper

#### api documentation for  [immutability-helper (v2.1.2)](https://github.com/kolodny/immutability-helper#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-immutability-helper.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-immutability-helper) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-immutability-helper.svg)](https://travis-ci.org/npmdoc/node-npmdoc-immutability-helper)

#### mutate a copy of data without changing the original source

[![NPM](https://nodei.co/npm/immutability-helper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/immutability-helper)

- [https://npmdoc.github.io/node-npmdoc-immutability-helper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-immutability-helper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "immutability-helper",
    "version": "2.1.2",
    "description": "mutate a copy of data without changing the original source",
    "main": "index.js",
    "scripts": {
        "test-cov": "nyc npm test && nyc report --reporter=lcov",
        "test-travis": "nyc npm test && nyc report --reporter=lcov",
        "test": "mocha test.js"
    },
    "keywords": [
        "immutability"
    ],
    "author": "Moshe Kolodny",
    "license": "MIT",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "expect": "^1.14.0",
        "mocha": "^2.4.5",
        "nyc": "^5.6.0"
    },
    "dependencies": {
        "invariant": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/kolodny/immutability-helper.git"
    },
    "bugs": {
        "url": "https://github.com/kolodny/immutability-helper/issues"
    },
    "homepage": "https://github.com/kolodny/immutability-helper#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
