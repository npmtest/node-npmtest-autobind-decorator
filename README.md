# npmtest-autobind-decorator

#### basic test coverage for  [autobind-decorator (v1.4.0)](https://github.com/andreypopp/autobind-decorator#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-autobind-decorator.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-autobind-decorator) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-autobind-decorator.svg)](https://travis-ci.org/npmtest/node-npmtest-autobind-decorator)

#### Decorator for binding method to an object

[![NPM](https://nodei.co/npm/autobind-decorator.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/autobind-decorator)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-autobind-decorator/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-autobind-decorator/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-autobind-decorator/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-autobind-decorator/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-autobind-decorator/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-autobind-decorator/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-autobind-decorator/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-autobind-decorator/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-autobind-decorator/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-autobind-decorator/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-autobind-decorator/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-autobind-decorator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-autobind-decorator/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-autobind-decorator/build/test-report.html](https://npmtest.github.io/node-npmtest-autobind-decorator/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-autobind-decorator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-autobind-decorator/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-autobind-decorator/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-autobind-decorator/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-autobind-decorator/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-autobind-decorator/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-autobind-decorator/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-autobind-decorator/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Andrey Popp"
    },
    "bugs": {
        "url": "https://github.com/andreypopp/autobind-decorator/issues"
    },
    "dependencies": {},
    "description": "Decorator for binding method to an object",
    "devDependencies": {
        "babel-cli": "^6.16.0",
        "babel-eslint": "^7.0.0",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-preset-es2015": "^6.16.0",
        "babelify": "^7.3.0",
        "core-js": "^0.9.18",
        "eslint": "^3.8.0",
        "mochify": "^2.18.1",
        "phantomjs": "^2.1.7"
    },
    "directories": {},
    "dist": {
        "shasum": "c56b560a0d31318c0fcfc22d0597992358799872",
        "tarball": "https://registry.npmjs.org/autobind-decorator/-/autobind-decorator-1.4.0.tgz"
    },
    "gitHead": "cc1820154b50646a33ba2ef4c77d85cf14ee804d",
    "homepage": "https://github.com/andreypopp/autobind-decorator#readme",
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "andreypopp"
        },
        {
            "name": "domarmstrong"
        },
        {
            "name": "stevemao"
        }
    ],
    "name": "autobind-decorator",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/andreypopp/autobind-decorator.git"
    },
    "scripts": {
        "build": "make build",
        "build-test": "make build-test",
        "lint": "make lint",
        "preversion": "npm run build && npm run build-test && npm run lint && npm run test",
        "test": "make test"
    },
    "types": "./index.d.ts",
    "version": "1.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
