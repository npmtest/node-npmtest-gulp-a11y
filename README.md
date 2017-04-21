# npmtest-gulp-a11y

#### basic test coverage for  [gulp-a11y (v0.1.2)](http://github.com/mpezzi/gulp-a11y)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-a11y.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-a11y) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-a11y.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-a11y)

#### A Gulp plugin for a11y to run accessibility audits on html files.

[![NPM](https://nodei.co/npm/gulp-a11y.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-a11y)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-a11y/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-a11y/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-a11y/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-a11y/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-a11y/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-a11y/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-a11y/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-a11y/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-a11y/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-a11y/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-a11y/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-a11y/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-a11y/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-a11y/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-a11y/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-a11y/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-a11y/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-a11y/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-a11y/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-a11y",
    "version": "0.1.2",
    "description": "A Gulp plugin for a11y to run accessibility audits on html files.",
    "main": "./src/index.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/mpezzi/gulp-a11y"
    },
    "homepage": "http://github.com/mpezzi/gulp-a11y",
    "bugs": "https://github.com/mpezzi/gulp-a11y/issues",
    "keywords": [
        "a11y",
        "gulpplugin"
    ],
    "scripts": {
        "test": "mocha --timeout 10000"
    },
    "author": "Michael Pezzi <mike@thespiral.ca>",
    "license": "MIT",
    "dependencies": {
        "a11y": "^0.4.1",
        "gulp-util": "^3.0.2",
        "indent-string": "^1.2.0",
        "log-symbols": "^1.0.1",
        "map-stream": "0.0.5"
    },
    "devDependencies": {
        "gulp": "^3.8.10",
        "gulp-eslint": "^0.2.2",
        "mocha": "^2.1.0",
        "should": "^4.6.2"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
