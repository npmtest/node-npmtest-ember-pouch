# npmtest-ember-pouch

#### basic test coverage for  ember-pouch (v4.2.4)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-pouch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-pouch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-pouch.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-pouch)

#### PouchDB adapter for Ember Data

[![NPM](https://nodei.co/npm/ember-pouch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-pouch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-pouch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-pouch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-pouch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-pouch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-pouch/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-pouch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-pouch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-pouch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-pouch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-pouch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-pouch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-pouch/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-pouch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-pouch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-pouch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-pouch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-pouch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-pouch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-pouch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-pouch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-pouch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-pouch",
    "version": "4.2.4",
    "description": "PouchDB adapter for Ember Data",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/nolanlawson/ember-pouch.git"
    },
    "keywords": [
        "ember-addon",
        "Ember",
        "Data",
        "adapter",
        "PouchDB",
        "CouchDB"
    ],
    "engines": {
        "node": ">= 0.10.0"
    },
    "author": "Nolan Lawson",
    "license": "Apache-2.0",
    "bugs": {
        "url": "https://github.com/nolanlawson/ember-pouch/issues"
    },
    "devDependencies": {
        "broccoli-asset-rev": "^2.4.2",
        "ember-cli": "2.8.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-jshint": "^1.0.0",
        "ember-cli-qunit": "^2.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-data": "^2.8.0",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-getowner-polyfill": "1.0.1",
        "ember-load-initializers": "^0.5.1",
        "ember-resolver": "^2.0.3",
        "loader.js": "^4.0.1"
    },
    "dependencies": {
        "broccoli-stew": "^1.3.1",
        "pouchdb": "^6.1.2",
        "relational-pouch": "^1.4.5",
        "pouchdb-find": "^0.10.3",
        "ember-cli-babel": "^5.1.6"
    },
    "ember-addon": {
        "configPath": "tests/dummy/config"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
