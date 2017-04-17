# test coverage for  [generator-gulp-angular (v1.1.1)](https://github.com/swiip/generator-gulp-angular#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-generator-gulp-angular.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-generator-gulp-angular) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-generator-gulp-angular.svg)](https://travis-ci.org/npmtest/node-npmtest-generator-gulp-angular)
#### Yeoman generator for AngularJS with Gulp

[![NPM](https://nodei.co/npm/generator-gulp-angular.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/generator-gulp-angular)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-generator-gulp-angular/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-generator-gulp-angular/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-generator-gulp-angular/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/test-report.html](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-generator-gulp-angular/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-generator-gulp-angular/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-gulp-angular/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-gulp-angular/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-generator-gulp-angular/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Matthieu Lux & Mehdy Dara"
    },
    "bugs": {
        "url": "https://github.com/swiip/generator-gulp-angular/issues"
    },
    "contributors": [
        {
            "name": "Matthieu Lux",
            "url": "https://github.com/Swiip"
        },
        {
            "name": "Mehdy Dara",
            "url": "http://eleven-labs.com/"
        }
    ],
    "dependencies": {
        "chalk": "~1.1.1",
        "insight": "~0.7.0",
        "lodash": "~3.10.1",
        "slash": "~1.0.0",
        "underscore.string": "~3.2.2",
        "yeoman-generator": "~0.20.3",
        "yosay": "~1.0.5"
    },
    "description": "Yeoman generator for AngularJS with Gulp",
    "devDependencies": {
        "bluebird": "~2.10.2",
        "bower": "~1.5.3",
        "chai": "~3.3.0",
        "chai-as-promised": "~5.1.0",
        "commander": "~2.8.1",
        "cross-spawn": "~2.0.0",
        "ejs": "~2.3.4",
        "eslint": "~1.6.0",
        "istanbul": "~0.3.22",
        "js-beautify": "~1.5.10",
        "mkdirp": "~0.5.1",
        "mocha": "~2.3.3",
        "mocha-lcov-reporter": "~1.0.0",
        "mz": "~2.0.0",
        "recursive-readdir": "~1.2.1",
        "sinon": "~1.17.1",
        "sinon-chai": "~2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "c41c12a0188be797b82143504dad49c7a23832d1",
        "tarball": "https://registry.npmjs.org/generator-gulp-angular/-/generator-gulp-angular-1.1.1.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "generators"
    ],
    "gitHead": "58e5a66a36ed3fd1c2b68906f6f149a3b5a3a15f",
    "homepage": "https://github.com/swiip/generator-gulp-angular#readme",
    "keywords": [
        "yeoman-generator",
        "angular",
        "gulp",
        "restangular",
        "ui-router",
        "bootstrap",
        "angular-material",
        "foundation",
        "sass",
        "less",
        "es6",
        "babel",
        "traceur",
        "typescript",
        "coffeescript",
        "jade",
        "haml",
        "webpack",
        "eslint"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "swiip"
        },
        {
            "name": "zckrs"
        }
    ],
    "name": "generator-gulp-angular",
    "optionalDependencies": {},
    "preferGlobal": true,
    "repository": {
        "type": "git",
        "url": "git+https://github.com/swiip/generator-gulp-angular.git"
    },
    "scripts": {
        "deploy": "./scripts/deploy-boilerplate.sh",
        "pretest": "./scripts/prepare-test.sh",
        "test": "istanbul cover _mocha -- test/node test/template && mocha test/inception/test-inception.js -ig protractor --no-insight",
        "update-shrinkwrap": "./scripts/update-test-shrinkwrap.sh"
    },
    "version": "1.1.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
