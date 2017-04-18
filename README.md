# npmtest-manifoldjs

test coverage for  [manifoldjs (v0.7.6)](https://github.com/manifoldjs/ManifoldJS)  [![npm package](https://img.shields.io/npm/v/npmtest-manifoldjs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-manifoldjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-manifoldjs.svg)](https://travis-ci.org/npmtest/node-npmtest-manifoldjs)
#### Node.js Tool for App Generation

[![NPM](https://nodei.co/npm/manifoldjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/manifoldjs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-manifoldjs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-manifoldjs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-manifoldjs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-manifoldjs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-manifoldjs/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-manifoldjs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-manifoldjs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-manifoldjs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-manifoldjs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-manifoldjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-manifoldjs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-manifoldjs/build/test-report.html](https://npmtest.github.io/node-npmtest-manifoldjs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-manifoldjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-manifoldjs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-manifoldjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-manifoldjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-manifoldjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "manifoldjs",
    "version": "0.7.6",
    "description": "Node.js Tool for App Generation",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/manifoldjs/ManifoldJS.git"
    },
    "engines": {
        "node": ">=0.12.0"
    },
    "engineStrict": true,
    "author": {
        "name": "TBD",
        "url": "TBD"
    },
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/manifoldjs/ManifoldJS/blob/master/LICENSE.txt"
        }
    ],
    "keywords": [
        "convert manifest",
        "manifest",
        "W3C",
        "Firefox OS",
        "Windows 10",
        "Chrome OS",
        "Android",
        "iOS"
    ],
    "dependencies": {
        "commander": "^2.9.0",
        "q": "^1.4.1",
        "manifoldjs-lib": "^1.0.1",
        "manifoldjs-chrome": "^0.1.3",
        "manifoldjs-cordova": "^0.1.3",
        "manifoldjs-firefox": "^0.1.3",
        "manifoldjs-web": "^0.1.3",
        "manifoldjs-windows10": "^0.1.7",
        "manifoldjs-edgeextension": "^0.1.8"
    },
    "devDependencies": {
        "blanket": "1.1.6",
        "grunt": "^0.4.5",
        "grunt-cli": "^0.1.13",
        "grunt-contrib-jshint": "^0.10.0",
        "grunt-contrib-nodeunit": "^0.4.1",
        "grunt-contrib-watch": "^0.6.1",
        "grunt-mocha-test": "^0.12.7",
        "grunt-sync": "^0.6.2",
        "jshint-stylish": "^1.0.0",
        "jshint-teamcity": "^1.0.6",
        "load-grunt-tasks": "^1.0.0",
        "mocha": "^2.1.0",
        "mocha-teamcity-reporter": "0.0.4",
        "should": "^5.0.1",
        "time-grunt": "^1.0.0",
        "travis-cov": "^0.2.5"
    },
    "scripts": {
        "test": "grunt",
        "debug-tests": "mocha --debug-brk"
    },
    "bin": {
        "manifoldjs": "manifoldjs.js"
    },
    "config": {
        "travis-cov": {
            "threshold": 80
        }
    },
    "bugs": {
        "url": "https://github.com/manifoldjs/ManifoldJS/issues"
    },
    "homepage": "https://github.com/manifoldjs/ManifoldJS",
    "gitHead": "f1228d184749ce39ee256649ffa7e576e970fb13",
    "dist": {
        "shasum": "8be4070fcebdae380ec2d16db65453799569b762",
        "tarball": "https://registry.npmjs.org/manifoldjs/-/manifoldjs-0.7.6.tgz"
    },
    "maintainers": [
        {
            "name": "boyofgreen"
        },
        {
            "name": "manifoldjs"
        }
    ],
    "directories": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
