# npmtest-gulp-ruby-haml

#### basic test coverage for  [gulp-ruby-haml (v0.0.9)](https://github.com/cheshire137/gulp-ruby-haml#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-ruby-haml.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-ruby-haml) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-ruby-haml.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-ruby-haml)

#### Compile Haml to HTML with Ruby Haml

[![NPM](https://nodei.co/npm/gulp-ruby-haml.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-ruby-haml)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-ruby-haml/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-ruby-haml/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/test-report.html](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-ruby-haml/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-ruby-haml/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sarah Vessels",
        "url": "http://www.sarahvessels.com"
    },
    "bugs": {
        "url": "https://github.com/cheshire137/gulp-ruby-haml/issues"
    },
    "dependencies": {
        "clone": "~0.1.11",
        "gulp-util": "~2.2.0",
        "through2": "~0.4.0",
        "win-spawn": "~2.0.0"
    },
    "description": "Compile Haml to HTML with Ruby Haml",
    "devDependencies": {
        "gulp": "~3.5.2",
        "jscs": "^1.13.1",
        "jshint": "^2.8.0",
        "mocha": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "a88c0024fae1eb36aa334ae7c71c4ca54a3a4a9e",
        "tarball": "https://registry.npmjs.org/gulp-ruby-haml/-/gulp-ruby-haml-0.0.9.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js"
    ],
    "gitHead": "da1515e0b80e572eac8d22e73367c92b5f468c02",
    "homepage": "https://github.com/cheshire137/gulp-ruby-haml#readme",
    "keywords": [
        "gulpplugin",
        "haml",
        "html",
        "compile",
        "preprocessor",
        "markup",
        "ruby"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "cheshire137"
        }
    ],
    "name": "gulp-ruby-haml",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/cheshire137/gulp-ruby-haml.git"
    },
    "scripts": {
        "jscs": "jscs index.js test/test.js",
        "jshint": "jshint index.js test/test.js",
        "style": "npm run-script jscs && npm run-script jshint",
        "test": "npm run-script style && npm run-script unit-test",
        "unit-test": "if [ -d \"tmp\" ]; then if find tmp -mindepth 1 -print -quit | grep -q .; then rm tmp/*; fi; fi; node_modules/.bin/mocha test/test.js"
    },
    "version": "0.0.9",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
