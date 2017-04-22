# npmdoc-ssl-root-cas

#### api documentation for  [ssl-root-cas (v1.2.3)](https://github.com/coolaj86/node-ssl-root-cas)  [![npm package](https://img.shields.io/npm/v/npmdoc-ssl-root-cas.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ssl-root-cas) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ssl-root-cas.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ssl-root-cas)

#### The module you need to solve node's SSL woes when including a custom certificate.

[![NPM](https://nodei.co/npm/ssl-root-cas.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ssl-root-cas)

- [https://npmdoc.github.io/node-npmdoc-ssl-root-cas/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ssl-root-cas/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ssl-root-cas/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ssl-root-cas/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ssl-root-cas/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ssl-root-cas/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/coolaj86/node-ssl-root-cas/issues"
    },
    "contributors": [
        {
            "name": "Forrest L Norvell"
        },
        {
            "name": "AJ ONeal",
            "url": "http://coolaj86.com"
        }
    ],
    "dependencies": {
        "bluebird": "^3.4.1",
        "request": "^2.47.0"
    },
    "description": "The module you need to solve node's SSL woes when including a custom certificate.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "8f4ec5cecabe35e764f09d950c146afd1c905d21",
        "tarball": "https://registry.npmjs.org/ssl-root-cas/-/ssl-root-cas-1.2.3.tgz"
    },
    "gitHead": "42e414337fd0fc27c62e621d8f0c2e938a4fdf18",
    "homepage": "https://github.com/coolaj86/node-ssl-root-cas",
    "keywords": [
        "SSL",
        "UNABLE_TO_VERIFY_LEAF_SIGNATURE",
        "CERT_UNTRUSTED",
        "CAS",
        "CA",
        "ROOT",
        "intermediate",
        "leaf",
        "error"
    ],
    "license": "Apache2",
    "main": "ssl-root-cas",
    "maintainers": [
        {
            "name": "coolaj86"
        }
    ],
    "name": "ssl-root-cas",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/coolaj86/node-ssl-root-cas.git"
    },
    "scripts": {
        "prepublish": "node ca-store-generator.js ssl-root-cas.js",
        "test": "node ca-store-generator.js ssl-root-cas-test.js"
    },
    "version": "1.2.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
