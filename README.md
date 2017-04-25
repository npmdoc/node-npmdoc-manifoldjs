# npmdoc-manifoldjs

#### basic api documentation for  [manifoldjs (v0.7.6)](https://github.com/manifoldjs/ManifoldJS)  [![npm package](https://img.shields.io/npm/v/npmdoc-manifoldjs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-manifoldjs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-manifoldjs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-manifoldjs)

#### Node.js Tool for App Generation

[![NPM](https://nodei.co/npm/manifoldjs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/manifoldjs)

- [https://npmdoc.github.io/node-npmdoc-manifoldjs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-manifoldjs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TBD",
        "url": "TBD"
    },
    "bin": {
        "manifoldjs": "manifoldjs.js"
    },
    "bugs": {
        "url": "https://github.com/manifoldjs/ManifoldJS/issues"
    },
    "config": {
        "travis-cov": {
            "threshold": 80
        }
    },
    "dependencies": {
        "commander": "^2.9.0",
        "manifoldjs-chrome": "^0.1.3",
        "manifoldjs-cordova": "^0.1.3",
        "manifoldjs-edgeextension": "^0.1.8",
        "manifoldjs-firefox": "^0.1.3",
        "manifoldjs-lib": "^1.0.1",
        "manifoldjs-web": "^0.1.3",
        "manifoldjs-windows10": "^0.1.7",
        "q": "^1.4.1"
    },
    "description": "Node.js Tool for App Generation",
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
    "directories": {},
    "dist": {
        "shasum": "8be4070fcebdae380ec2d16db65453799569b762",
        "tarball": "https://registry.npmjs.org/manifoldjs/-/manifoldjs-0.7.6.tgz"
    },
    "engineStrict": true,
    "engines": {
        "node": ">=0.12.0"
    },
    "gitHead": "f1228d184749ce39ee256649ffa7e576e970fb13",
    "homepage": "https://github.com/manifoldjs/ManifoldJS",
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
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/manifoldjs/ManifoldJS/blob/master/LICENSE.txt"
        }
    ],
    "maintainers": [
        {
            "name": "boyofgreen"
        },
        {
            "name": "manifoldjs"
        }
    ],
    "name": "manifoldjs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/manifoldjs/ManifoldJS.git"
    },
    "scripts": {
        "debug-tests": "mocha --debug-brk",
        "test": "grunt"
    },
    "version": "0.7.6"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
