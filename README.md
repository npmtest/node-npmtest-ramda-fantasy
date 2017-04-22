# npmtest-ramda-fantasy

#### basic test coverage for  [ramda-fantasy (v0.8.0)](https://www.github.com/ramda/ramda-fantasy)  [![npm package](https://img.shields.io/npm/v/npmtest-ramda-fantasy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ramda-fantasy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ramda-fantasy.svg)](https://travis-ci.org/npmtest/node-npmtest-ramda-fantasy)

#### Fantasy Land compatible types for easy integration with Ramda

[![NPM](https://nodei.co/npm/ramda-fantasy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ramda-fantasy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ramda-fantasy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ramda-fantasy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ramda-fantasy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ramda-fantasy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ramda-fantasy/build/test-report.html](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ramda-fantasy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ramda-fantasy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ramda-fantasy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ramda-fantasy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ramda-fantasy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Michael Hurley",
        "url": "buzzdecafe.com"
    },
    "bugs": {
        "url": "https://github.com/ramda/ramda-fantasy/issues"
    },
    "contributors": [
        {
            "name": "Michael Hurley",
            "url": "http://buzzdecafe.com"
        },
        {
            "name": "Ludwig Magnusson"
        }
    ],
    "dependencies": {
        "ramda": ">=0.15.0"
    },
    "description": "Fantasy Land compatible types for easy integration with Ramda",
    "devDependencies": {
        "browserify": "13.1.x",
        "derequire": "^2.0.3",
        "jscs": "1.13.x",
        "jshint": "~2.7.0",
        "jsverify": "^0.7.1",
        "mocha": "^2.1.0",
        "promise": "7.1.1",
        "uglify-js": "2.4.x",
        "xyz": "0.5.x"
    },
    "directories": {},
    "dist": {
        "shasum": "9e8c37d93ec0a70796cfc10873dd9c50850390f6",
        "tarball": "https://registry.npmjs.org/ramda-fantasy/-/ramda-fantasy-0.8.0.tgz"
    },
    "gitHead": "8cf0d5f217e387f28d963ef7a07273434cd7e083",
    "homepage": "https://www.github.com/ramda/ramda-fantasy",
    "license": "MIT",
    "maintainers": [
        {
            "name": "buzzdecafe"
        },
        {
            "name": "theludd"
        },
        {
            "name": "scott-christopher"
        }
    ],
    "name": "ramda-fantasy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/ramda/ramda-fantasy.git"
    },
    "scripts": {
        "build": "browserify -r ./index.js -s RF | derequire > dist/ramda-fantasy.js ",
        "jscs": "jscs src/* test/*",
        "jshint": "jshint src/* test/*",
        "postbuild": "uglifyjs dist/ramda-fantasy.js -m -c unused=false -o dist/ramda-fantasy.min.js",
        "pretest": "npm run jshint",
        "release-major": "xyz --repo git@github.com:ramda/ramda-fantasy.git --increment major",
        "release-minor": "xyz --repo git@github.com:ramda/ramda-fantasy.git --increment minor",
        "release-patch": "xyz --repo git@github.com:ramda/ramda-fantasy.git --increment patch",
        "test": "mocha"
    },
    "version": "0.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
