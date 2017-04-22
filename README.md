# npmtest-jssip

#### basic test coverage for  [jssip (v3.0.7)](http://jssip.net)  [![npm package](https://img.shields.io/npm/v/npmtest-jssip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jssip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jssip.svg)](https://travis-ci.org/npmtest/node-npmtest-jssip)

#### the Javascript SIP library

[![NPM](https://nodei.co/npm/jssip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jssip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jssip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jssip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jssip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jssip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jssip/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jssip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jssip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jssip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jssip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jssip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jssip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jssip/build/test-report.html](https://npmtest.github.io/node-npmtest-jssip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jssip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jssip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jssip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jssip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jssip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jssip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jssip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jssip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "José Luis Millán",
        "url": "https://github.com/jmillan"
    },
    "bugs": {
        "url": "https://github.com/versatica/JsSIP/issues"
    },
    "contributors": [
        {
            "name": "Iñaki Baz Castillo",
            "url": "https://github.com/ibc"
        },
        {
            "name": "Saúl Ibarra Corretgé",
            "url": "https://github.com/saghul"
        }
    ],
    "dependencies": {
        "debug": "^2.6.3",
        "sdp-transform": "^2.3.0",
        "webrtc-adapter": "^3.2.0"
    },
    "description": "the Javascript SIP library",
    "devDependencies": {
        "browserify": "^14.1.0",
        "gulp": "git+https://github.com/gulpjs/gulp.git#4.0",
        "gulp-expect-file": "0.0.7",
        "gulp-header": "1.8.8",
        "gulp-jshint": "^2.0.4",
        "gulp-nodeunit-runner": "^0.2.2",
        "gulp-rename": "^1.2.2",
        "gulp-uglify": "^2.1.2",
        "gulp-util": "^3.0.8",
        "jshint": "^2.9.4",
        "jshint-stylish": "^2.2.1",
        "pegjs": "0.7.0",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0c264cafe42706cfa1273358327bca86976ccda4",
        "tarball": "https://registry.npmjs.org/jssip/-/jssip-3.0.7.tgz"
    },
    "gitHead": "dcfd07fcbaa1d1a6f2ef4cc097389219e3b873cf",
    "homepage": "http://jssip.net",
    "keywords": [
        "sip",
        "websocket",
        "webrtc",
        "node",
        "browser",
        "library"
    ],
    "license": "MIT",
    "main": "lib/JsSIP.js",
    "maintainers": [
        {
            "name": "ibc"
        },
        {
            "name": "jmillan"
        }
    ],
    "name": "jssip",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/versatica/JsSIP.git"
    },
    "scripts": {
        "test": "gulp test"
    },
    "title": "JsSIP",
    "version": "3.0.7",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
