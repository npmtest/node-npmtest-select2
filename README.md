# npmtest-select2

#### basic test coverage for  [select2 (v4.0.3)](https://select2.github.io)  [![npm package](https://img.shields.io/npm/v/npmtest-select2.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-select2) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-select2.svg)](https://travis-ci.org/npmtest/node-npmtest-select2)

#### Select2 is a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.

[![NPM](https://nodei.co/npm/select2.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/select2)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-select2/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-select2/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-select2/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-select2/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-select2/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-select2/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-select2/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-select2/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-select2/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-select2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-select2/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-select2/build/test-report.html](https://npmtest.github.io/node-npmtest-select2/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-select2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-select2/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-select2/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-select2/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-select2/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-select2/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-select2/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-select2/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "select2",
    "description": "Select2 is a jQuery based replacement for select boxes. It supports searching, remote data sets, and infinite scrolling of results.",
    "homepage": "https://select2.github.io",
    "author": {
        "name": "Kevin Brown",
        "url": "https://github.com/kevin-brown"
    },
    "contributors": [
        {
            "name": "Igor Vaynberg",
            "url": "https://github.com/ivaynberg"
        }
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/select2/select2.git"
    },
    "bugs": {
        "url": "https://github.com/select2/select2/issues"
    },
    "keywords": [
        "select",
        "autocomplete",
        "typeahead",
        "dropdown",
        "multiselect",
        "tag",
        "tagging"
    ],
    "license": "MIT",
    "main": "dist/js/select2.js",
    "files": [
        "src",
        "dist"
    ],
    "version": "4.0.3",
    "jspm": {
        "main": "js/select2",
        "directories": {
            "lib": "dist"
        }
    },
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-clean": "^0.6.0",
        "grunt-contrib-concat": "^0.4.0",
        "grunt-contrib-connect": "^0.9.0",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-contrib-nodeunit": "~0.3.3",
        "grunt-contrib-qunit": "~0.4.0",
        "grunt-contrib-requirejs": "^0.4.4",
        "grunt-contrib-symlink": "^0.3.0",
        "grunt-contrib-uglify": "~0.4.0",
        "grunt-contrib-watch": "~0.6.0",
        "grunt-gh-pages": "^0.9.1",
        "grunt-jekyll": "^0.4.2",
        "grunt-sass": "^1.0.0",
        "grunt-saucelabs": "^8.6.0"
    },
    "dependencies": {
        "almond": "~0.3.1",
        "jquery-mousewheel": "~3.1.13"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
