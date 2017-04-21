# npmtest-grapnel.js

#### basic test coverage for  [grapnel.js (v0.6.4)](http://grapnel.js.org)  [![npm package](https://img.shields.io/npm/v/npmtest-grapnel.js.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grapnel.js) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grapnel.js.svg)](https://travis-ci.org/npmtest/node-npmtest-grapnel.js)

#### The smallest JavaScript Router with PushState & Named Parameter support

[![NPM](https://nodei.co/npm/grapnel.js.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grapnel.js)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grapnel.js/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grapnel.js/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grapnel.js/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grapnel.js/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grapnel.js/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grapnel.js/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grapnel.js/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grapnel.js/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grapnel.js/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grapnel.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grapnel.js/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grapnel.js/build/test-report.html](https://npmtest.github.io/node-npmtest-grapnel.js/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grapnel.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grapnel.js/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grapnel.js/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grapnel.js/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grapnel.js/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grapnel.js/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grapnel.js/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grapnel.js/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "grapnel.js",
    "version": "0.6.4",
    "description": "The smallest JavaScript Router with PushState & Named Parameter support",
    "main": "src/grapnel.js",
    "scripts": {
        "test": "pushd ./test; python -m SimpleHTTPServer 3002; popd"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/baseprime/grapnel.git"
    },
    "keywords": [
        "grapnel",
        "route",
        "routing",
        "router",
        "hash",
        "anchor",
        "express",
        "server",
        "tiny",
        "require",
        "named parameters",
        "middleware",
        "backbone",
        "routie",
        "pushState",
        "api"
    ],
    "author": "Greg Sabia Tucker <greg@narrowlabs.com>",
    "link": "http://basepri.me",
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/baseprime/grapnel/issues"
    },
    "homepage": "http://grapnel.js.org",
    "devDependencies": {
        "grunt": "^0.4.5",
        "grunt-contrib-concat": "^0.5.0",
        "grunt-contrib-qunit": "^0.5.2",
        "grunt-contrib-uglify": "^0.7.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
