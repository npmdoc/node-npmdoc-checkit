# npmdoc-checkit

#### basic api documentation for  [checkit (v0.7.0)](https://github.com/tgriesser/checkit#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-checkit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-checkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-checkit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-checkit)

#### Simple validations for node and the browser.

[![NPM](https://nodei.co/npm/checkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/checkit)

- [https://npmdoc.github.io/node-npmdoc-checkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-checkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-checkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-checkit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-checkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-checkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Tim Griesser",
        "url": "https://github.com/tgriesser"
    },
    "bugs": {
        "url": "https://github.com/tgriesser/checkit/issues"
    },
    "dependencies": {
        "inherits": "^2.0.1",
        "lodash": "^4.0.0"
    },
    "description": "Simple validations for node and the browser.",
    "devDependencies": {
        "mocha": "~2.4.5",
        "node-uuid": "~1.4.1",
        "webpack": "1.12.13"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "14979abc93018346bfcfdcbabc19ab54c0bfd74a",
        "tarball": "https://registry.npmjs.org/checkit/-/checkit-0.7.0.tgz"
    },
    "gitHead": "ce4d05479399e5f8284571ec90188bdf20786b96",
    "homepage": "https://github.com/tgriesser/checkit#readme",
    "keywords": [
        "validation"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "tgriesser"
        },
        {
            "name": "rhys-vdw"
        }
    ],
    "name": "checkit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/tgriesser/checkit.git"
    },
    "scripts": {
        "build": "npm run build:main && npm run build:dist",
        "build:dist": "webpack --output-library Checkit --output-library-target umd --optimize-minimize index.js dist/checkit.min.js",
        "build:main": "webpack --output-library Checkit --output-library-target umd index.js dist/checkit.js",
        "prepublish": "npm test && npm run build",
        "test": "mocha -R spec test/index.js"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
