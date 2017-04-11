# test coverage for  [modernizr (v3.4.0)](https://github.com/Modernizr/Modernizr#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-modernizr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-modernizr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-modernizr.svg)](https://travis-ci.org/npmtest/node-npmtest-modernizr)
#### Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.

[![NPM](https://nodei.co/npm/modernizr.png?downloads=true)](https://www.npmjs.com/package/modernizr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-modernizr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-modernizr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-modernizr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-modernizr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-modernizr/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-modernizr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-modernizr/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-modernizr/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-modernizr/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-modernizr/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-modernizr%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-modernizr/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-modernizr/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-modernizr%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-modernizr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-modernizr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-modernizr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Modernizr",
        "url": "https://modernizr.com/"
    },
    "bin": {
        "modernizr": "./bin/modernizr"
    },
    "bugs": {
        "url": "https://github.com/Modernizr/Modernizr/issues"
    },
    "contributors": [
        {
            "name": "Faruk Ates",
            "url": "https://twitter.com/KuraFire"
        },
        {
            "name": "Paul Irish",
            "url": "https://twitter.com/paul_irish"
        },
        {
            "name": "Alex Sexton",
            "url": "https://twitter.com/SlexAxton"
        },
        {
            "name": "Ryan Seddon",
            "url": "https://twitter.com/ryanseddon"
        },
        {
            "name": "Patrick Kettner",
            "url": "https://twitter.com/patrickkettner"
        },
        {
            "name": "Stu Cox",
            "url": "https://twitter.com/stucoxmedia"
        },
        {
            "name": "Richard Herrera",
            "url": "https://twitter.com/doctyper"
        }
    ],
    "dependencies": {
        "doctrine": "1.2.3",
        "file": "0.2.2",
        "find-parent-dir": "0.3.0",
        "lodash": "4.17.4",
        "mkdirp": "0.5.1",
        "remarkable": "^1.6.2",
        "requirejs": "2.1.22",
        "yargs": "6.6.0"
    },
    "description": "Modernizr is a JavaScript library that detects HTML5 and CSS3 features in the user’s browser.",
    "devDependencies": {
        "@alrra/travis-scripts": "1.1.1",
        "expect.js": "0.3.1",
        "grunt": "1.0.1",
        "grunt-contrib-clean": "1.0.0",
        "grunt-contrib-connect": "1.0.2",
        "grunt-contrib-copy": "1.0.0",
        "grunt-contrib-jade": "1.0.0",
        "grunt-coveralls": "1.0.1",
        "grunt-env": "0.4.4",
        "grunt-eslint": "^18.1.0",
        "grunt-istanbul": "0.7.1",
        "grunt-mocha": "0.4.15",
        "grunt-mocha-test": "0.12.7",
        "grunt-saucelabs": "9.0.0",
        "joi": "6.10.0",
        "jquery": "1.12.4",
        "json3": "3.3.2",
        "load-grunt-tasks": "3.5.2",
        "proxyquire": "1.7.11",
        "serve-static": "^1.10.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "2eb7617677a6b6bb72a2d3b60fe4e702c4c9d067",
        "tarball": "https://registry.npmjs.org/modernizr/-/modernizr-3.4.0.tgz"
    },
    "gitHead": "32fd455750c53a6233b8a9ebd5742adc5b9af054",
    "greenkeeper": {
        "ignore": [
            "joi",
            "grunt-eslint"
        ]
    },
    "homepage": "https://github.com/Modernizr/Modernizr#readme",
    "inch": {
        "files": {
            "included": [
                "feature-detects/",
                "src/"
            ]
        }
    },
    "keywords": [
        "html5",
        "css3",
        "browser",
        "feature detection"
    ],
    "license": "MIT",
    "main": "./lib/cli",
    "maintainers": [
        {
            "name": "patrickkettner",
            "email": "patrickkettner@gmail.com"
        },
        {
            "name": "paulirish",
            "email": "paul.irish@gmail.com"
        },
        {
            "name": "slexaxton",
            "email": "alexsexton@gmail.com"
        },
        {
            "name": "ryanseddon",
            "email": "seddon.ryan@gmail.com"
        },
        {
            "name": "doctyper",
            "email": "rich@doctyper.com"
        },
        {
            "name": "stucox",
            "email": "stuart.cox@gmail.com"
        }
    ],
    "name": "modernizr",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Modernizr/Modernizr.git"
    },
    "scripts": {
        "test": "grunt test --stack"
    },
    "version": "3.4.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
