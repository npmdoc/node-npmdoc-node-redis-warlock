# npmdoc-node-redis-warlock

#### api documentation for  [node-redis-warlock (v0.2.0)](https://github.com/thedeveloper/warlock)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-redis-warlock.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-redis-warlock) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-redis-warlock.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-redis-warlock)

#### Battle-hardened distributed locking using redis

[![NPM](https://nodei.co/npm/node-redis-warlock.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-redis-warlock)

- [https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-redis-warlock/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-redis-warlock",
    "version": "0.2.0",
    "description": "Battle-hardened distributed locking using redis",
    "main": "lib/warlock.js",
    "scripts": {
        "test": "mocha -R list ./test/warlock",
        "bench": "mocha -R list ./test/bench"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/thedeveloper/warlock"
    },
    "keywords": [
        "node.js",
        "redis",
        "lock"
    ],
    "author": "Geoff Wagstaff",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/thedeveloper/warlock/issues"
    },
    "homepage": "https://github.com/thedeveloper/warlock",
    "dependencies": {
        "node-redis-scripty": "0.0.5",
        "uuid": "^2.0.1"
    },
    "devDependencies": {
        "async": "^1.5.1",
        "mocha": "^2.3.4",
        "redis": "^2.4.2",
        "should": "^8.0.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
