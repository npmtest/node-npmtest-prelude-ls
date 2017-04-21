# npmtest-prelude-ls

#### basic test coverage for  [prelude-ls (v1.1.2)](http://preludels.com)  [![npm package](https://img.shields.io/npm/v/npmtest-prelude-ls.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-prelude-ls) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-prelude-ls.svg)](https://travis-ci.org/npmtest/node-npmtest-prelude-ls)

#### prelude.ls is a functionally oriented utility library. It is powerful and flexible. Almost all of its functions are curried. It is written in, and is the recommended base library for, LiveScript.

[![NPM](https://nodei.co/npm/prelude-ls.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/prelude-ls)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-prelude-ls/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-prelude-ls/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-prelude-ls/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-prelude-ls/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-prelude-ls/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-prelude-ls/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-prelude-ls/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-prelude-ls/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-prelude-ls/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-prelude-ls/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-prelude-ls/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-prelude-ls/build/test-report.html](https://npmtest.github.io/node-npmtest-prelude-ls/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-prelude-ls/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-prelude-ls/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-prelude-ls/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-prelude-ls/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-prelude-ls/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-prelude-ls/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-prelude-ls/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-prelude-ls/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "prelude-ls",
    "version": "1.1.2",
    "author": "George Zahariev <z@georgezahariev.com>",
    "description": "prelude.ls is a functionally oriented utility library. It is powerful and flexible. Almost all of its functions are curried. It is written in, and is the recommended base library for, LiveScript.",
    "keywords": [
        "prelude",
        "livescript",
        "utility",
        "ls",
        "coffeescript",
        "javascript",
        "library",
        "functional",
        "array",
        "list",
        "object",
        "string"
    ],
    "main": "lib/",
    "files": [
        "lib/",
        "README.md",
        "LICENSE"
    ],
    "homepage": "http://preludels.com",
    "bugs": "https://github.com/gkz/prelude-ls/issues",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://raw.github.com/gkz/prelude-ls/master/LICENSE"
        }
    ],
    "engines": {
        "node": ">= 0.8.0"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/gkz/prelude-ls.git"
    },
    "scripts": {
        "test": "make test"
    },
    "devDependencies": {
        "livescript": "~1.4.0",
        "uglify-js": "~2.4.12",
        "mocha": "~2.2.4",
        "istanbul": "~0.2.4",
        "browserify": "~3.24.13",
        "sinon": "~1.10.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
