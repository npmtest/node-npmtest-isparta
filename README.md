# npmtest-isparta

#### test coverage for  [isparta (v4.0.0)](http://github.com/douglasduteil/isparta)  [![npm package](https://img.shields.io/npm/v/npmtest-isparta.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-isparta) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-isparta.svg)](https://travis-ci.org/npmtest/node-npmtest-isparta)

#### A code coverage tool for ES6 (babel)

[![NPM](https://nodei.co/npm/isparta.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/isparta)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-isparta/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-isparta/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-isparta/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-isparta/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-isparta/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-isparta/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-isparta/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-isparta/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-isparta/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-isparta/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-isparta/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-isparta/build/test-report.html](https://npmtest.github.io/node-npmtest-isparta/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-isparta/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-isparta/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-isparta/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-isparta/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-isparta/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-isparta/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-isparta/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-isparta/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Douglas Duteil"
    },
    "bin": {
        "isparta": "./bin/isparta"
    },
    "bugs": {
        "url": "http://github.com/douglasduteil/isparta/issues"
    },
    "dependencies": {
        "babel-core": "^6.1.4",
        "escodegen": "^1.6.1",
        "esprima": "^2.1.0",
        "istanbul": "^0.4.0",
        "mkdirp": "^0.5.0",
        "nomnomnomnom": "^2.0.0",
        "object-assign": "^4.0.1",
        "source-map": "^0.5.0",
        "which": "^1.0.9"
    },
    "description": "A code coverage tool for ES6 (babel)",
    "devDependencies": {
        "babel-cli": "^6.1.4",
        "babel-plugin-transform-object-rest-spread": "^6.1.4",
        "babel-polyfill": "^6.1.4",
        "babel-preset-es2015": "^6.1.4",
        "chai": "^3.2.0",
        "douglasduteil...shelltest": "^2.0.0",
        "hide-stack-frames-from": "^1.0.0",
        "mocha": "^2.2.1",
        "nth": "^0.1.2",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "1de91996f480b22dcb1aca8510255bae1574446e",
        "tarball": "https://registry.npmjs.org/isparta/-/isparta-4.0.0.tgz"
    },
    "files": [
        "bin/",
        "lib/"
    ],
    "gitHead": "749862a7d1810dd25b8c62c9e613720b57d36da1",
    "homepage": "http://github.com/douglasduteil/isparta",
    "keywords": [
        "karma",
        "karma-coverage",
        "karma-traceur-preprocessor",
        "istanbul",
        "6to5",
        "babel",
        "es6",
        "harmony"
    ],
    "license": "WTFPL",
    "main": "./lib/isparta",
    "maintainers": [
        {
            "name": "douglasduteil"
        }
    ],
    "name": "isparta",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/douglasduteil/isparta.git"
    },
    "scripts": {
        "dist": "babel src --out-dir lib",
        "prepublish": "npm run dist",
        "test": "mocha",
        "watch": "npm run dist -- -w"
    },
    "version": "4.0.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
