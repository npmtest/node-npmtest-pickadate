# npmtest-pickadate

#### basic test coverage for  [pickadate (v3.5.6)](http://amsul.ca/pickadate.js)  [![npm package](https://img.shields.io/npm/v/npmtest-pickadate.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pickadate) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pickadate.svg)](https://travis-ci.org/npmtest/node-npmtest-pickadate)

#### The mobile-friendly, responsive, and lightweight jQuery date & time input picker.

[![NPM](https://nodei.co/npm/pickadate.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pickadate)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pickadate/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pickadate/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pickadate/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pickadate/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pickadate/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-pickadate/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-pickadate/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pickadate/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pickadate/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pickadate/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pickadate/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pickadate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pickadate/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pickadate/build/test-report.html](https://npmtest.github.io/node-npmtest-pickadate/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pickadate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pickadate/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pickadate/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pickadate/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pickadate/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pickadate/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pickadate/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pickadate/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Amsul",
        "url": "http://amsul.ca"
    },
    "bugs": {
        "url": "https://github.com/amsul/pickadate.js/issues"
    },
    "dependencies": {
        "jquery": ">=1.7"
    },
    "description": "The mobile-friendly, responsive, and lightweight jQuery date & time input picker.",
    "devDependencies": {
        "commander": "^2.8.0",
        "glob": "^5.0.5",
        "grunt": "^0.4.5",
        "grunt-autoprefixer": "^3.0.0",
        "grunt-contrib-copy": "^0.8.0",
        "grunt-contrib-cssmin": "^0.12.2",
        "grunt-contrib-jshint": "^0.11.2",
        "grunt-contrib-less": "^1.0.1",
        "grunt-contrib-qunit": "^0.7.0",
        "grunt-contrib-uglify": "^0.9.1",
        "grunt-contrib-watch": "^0.6.1",
        "phantomjs": "^1.9.16",
        "semver": "^4.3.3",
        "shelljs": "^0.4.0",
        "zlib-browserify": "0.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "c998302343b79a19954fc49c45cc708347602806",
        "tarball": "https://registry.npmjs.org/pickadate/-/pickadate-3.5.6.tgz"
    },
    "files": [
        "lib",
        "tests",
        "README.md",
        "Gruntfile.js"
    ],
    "gitHead": "b704a8a8a19df24481f8291dd3e6c008501f04f1",
    "homepage": "http://amsul.ca/pickadate.js",
    "keywords": [
        "date",
        "time",
        "picker",
        "input",
        "responsive"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "amsul"
        }
    ],
    "name": "pickadate",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/amsul/pickadate.js.git"
    },
    "scripts": {
        "bump": "node ./version-bump.js",
        "postbump": "grunt package && node ./version-commit.js",
        "prebump": "npm test",
        "push": "git push && git push origin --tags && npm publish",
        "test": "grunt test --verbose"
    },
    "title": "pickadate.js",
    "version": "3.5.6",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
