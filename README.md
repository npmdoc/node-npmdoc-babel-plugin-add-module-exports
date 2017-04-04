# api documentation for  [babel-plugin-add-module-exports (v0.2.1)](https://github.com/59naga/babel-plugin-add-module-exports#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-babel-plugin-add-module-exports.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-babel-plugin-add-module-exports) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-babel-plugin-add-module-exports.svg)](https://travis-ci.org/npmdoc/node-npmdoc-babel-plugin-add-module-exports)
#### Fix babel/babel#2212

[![NPM](https://nodei.co/npm/babel-plugin-add-module-exports.png?downloads=true)](https://www.npmjs.com/package/babel-plugin-add-module-exports)

[![apidoc](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-babel-plugin-add-module-exports_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-babel-plugin-add-module-exports/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "abigail": {
        "plugins": {
            "log": false,
            "parse": "raw",
            "watch": false
        }
    },
    "author": {
        "name": "59naga",
        "email": "i59naga@icloud.com",
        "url": "http://berabou.me"
    },
    "bugs": {
        "url": "https://github.com/59naga/babel-plugin-add-module-exports/issues"
    },
    "dependencies": {},
    "description": "Fix babel/babel#2212",
    "devDependencies": {
        "abigail": "^1.6.1",
        "babel-cli": "^6.5.1",
        "babel-core": "^6.5.1",
        "babel-plugin-transform-export-extensions": "^6.5.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-power-assert": "^1.0.0",
        "chokidar": "^1.4.3",
        "codeclimate-test-reporter": "^0.3.1",
        "eslint": "^2.8.0",
        "eslint-config-standard": "^5.1.0",
        "eslint-plugin-mocha": "^2.2.0",
        "eslint-plugin-promise": "^1.1.0",
        "eslint-plugin-standard": "^1.3.1",
        "mocha": "^2.4.5",
        "npm-statement": "^0.0.0",
        "nyc": "^6.4.0",
        "power-assert": "^1.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "9ae9a1f4a8dc67f0cdec4f4aeda1e43a5ff65e25",
        "tarball": "https://registry.npmjs.org/babel-plugin-add-module-exports/-/babel-plugin-add-module-exports-0.2.1.tgz"
    },
    "files": [
        "lib"
    ],
    "gitHead": "aa37f68bb570042f57e7213c014fa04e8ff5e59b",
    "homepage": "https://github.com/59naga/babel-plugin-add-module-exports#readme",
    "keywords": [
        "babel-plugin",
        "module.exports"
    ],
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "59naga",
            "email": "i59naga@icloud.com"
        },
        {
            "name": "lijunle",
            "email": "lijunle@gmail.com"
        }
    ],
    "name": "babel-plugin-add-module-exports",
    "nyc": {
        "exclude": [
            "spec"
        ]
    },
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/59naga/babel-plugin-add-module-exports.git"
    },
    "scripts": {
        "build": "abby compile --log --env",
        "compile": "abby compile:* --parse serial",
        "compile:copy": "cp test/spec.js spec/spec.js",
        "compile:src": "babel src --out-dir lib --source-maps",
        "compile:test": "babel test --out-dir spec --ignore test/spec.js",
        "compile:version": "babel -V",
        "cover": "abby cover:* --parse serial --launch force",
        "cover:report": "npm-if TRAVIS \"codeclimate-test-reporter < coverage/lcov.info\"",
        "cover:test": "nyc --reporter=lcov --reporter=text npm test",
        "lint": "eslint src test",
        "mocha": "mocha spec/index.js",
        "postversion": "node changelog.js > CHANGELOG.md && git add CHANGELOG.md && echo ':wq' | git commit --amend && git push --follow-tags",
        "start": "abby compile, watch:*",
        "test": "abby compile, mocha.",
        "watch:copy": "abby compile:copy --watch test/spec.js",
        "watch:mocha": "abby mocha --log --watch lib/**/*.js,spec/**/*.js",
        "watch:src": "babel src --out-dir lib --watch",
        "watch:test": "babel test --out-dir spec --ignore test/spec.js --watch"
    },
    "version": "0.2.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module babel-plugin-add-module-exports](#apidoc.module.babel-plugin-add-module-exports)



# <a name="apidoc.module.babel-plugin-add-module-exports"></a>[module babel-plugin-add-module-exports](#apidoc.module.babel-plugin-add-module-exports)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
