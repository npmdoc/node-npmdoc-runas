# npmdoc-runas

#### basic api documentation for  [runas (v3.1.1)](https://github.com/atom/node-runas#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-runas.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-runas) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-runas.svg)](https://travis-ci.org/npmdoc/node-npmdoc-runas)

#### Run command synchronously with administrator privilege.

[![NPM](https://nodei.co/npm/runas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/runas)

- [https://npmdoc.github.io/node-npmdoc-runas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-runas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-runas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-runas/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-runas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-runas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/atom/node-runas/issues"
    },
    "dependencies": {
        "nan": "2.x"
    },
    "description": "Run command synchronously with administrator privilege.",
    "devDependencies": {
        "coffee-script": "~1.6.2",
        "grunt": "~0.4.1",
        "grunt-cli": "~0.1.7",
        "grunt-contrib-coffee": "~0.6.6",
        "grunt-shell": "~0.2.2",
        "jasmine-focused": "^1.0.5",
        "node-cpplint": "~0.1.5"
    },
    "directories": {},
    "dist": {
        "shasum": "52dd538db0e41745399535a347091ba45cc0eab0",
        "tarball": "https://registry.npmjs.org/runas/-/runas-3.1.1.tgz"
    },
    "gitHead": "dc0dcf3711ae265367b90d9ee02f77cf1c26bad8",
    "gypfile": true,
    "homepage": "https://github.com/atom/node-runas#readme",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/atom/node-runas/raw/master/LICENSE.md"
        }
    ],
    "main": "./lib/runas.js",
    "maintainers": [
        {
            "name": "zcbenz"
        },
        {
            "name": "kevinsawicki"
        },
        {
            "name": "nathansobo"
        },
        {
            "name": "benogle"
        }
    ],
    "name": "runas",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/atom/node-runas.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "prepublish": "grunt coffee",
        "test": "node node_modules/jasmine-focused/bin/jasmine-focused --captureExceptions --coffee spec"
    },
    "version": "3.1.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
