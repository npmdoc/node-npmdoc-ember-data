# npmdoc-ember-data

#### api documentation for  ember-data (v2.12.2)  [![npm package](https://img.shields.io/npm/v/npmdoc-ember-data.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-ember-data) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-ember-data.svg)](https://travis-ci.org/npmdoc/node-npmdoc-ember-data)

#### A data layer for your Ember applications.

[![NPM](https://nodei.co/npm/ember-data.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-data)

- [https://npmdoc.github.io/node-npmdoc-ember-data/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-data/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-data/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-data/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-ember-data/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-ember-data/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ember-data",
    "version": "2.12.2",
    "description": "A data layer for your Ember applications.",
    "repository": "git://github.com/emberjs/data.git",
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:testall",
        "node-tests": "node node-tests/nodetest-runner.js",
        "test:optional-features": "ember test --environment=test-optional-features",
        "test:production": "ember test --environment=production",
        "bower": "bower install",
        "production": "ember build --environment=production"
    },
    "engines": {
        "node": ">= 0.10.0"
    },
    "author": "",
    "license": "MIT",
    "dependencies": {
        "amd-name-resolver": "0.0.5",
        "babel-plugin-feature-flags": "^0.2.1",
        "babel-plugin-filter-imports": "^0.2.0",
        "babel5-plugin-strip-class-callcheck": "^5.1.0",
        "babel5-plugin-strip-heimdall": "^5.0.2",
        "broccoli-babel-transpiler": "^5.5.0",
        "broccoli-file-creator": "^1.0.0",
        "broccoli-merge-trees": "^1.0.0",
        "chalk": "^1.1.1",
        "ember-cli-babel": "^5.1.6",
        "ember-cli-path-utils": "^1.0.0",
        "ember-cli-string-utils": "^1.0.0",
        "ember-cli-test-info": "^1.0.0",
        "ember-cli-version-checker": "^1.1.4",
        "ember-inflector": "^1.9.4",
        "ember-runtime-enumerable-includes-polyfill": "^1.0.0",
        "exists-sync": "0.0.3",
        "git-repo-info": "^1.1.2",
        "heimdalljs": "^0.3.0",
        "inflection": "^1.8.0",
        "npm-git-info": "^1.0.0",
        "semver": "^5.1.0",
        "silent-error": "^1.0.0"
    },
    "devDependencies": {
        "bower": "^1.6.5",
        "broccoli-asset-rev": "^2.4.2",
        "broccoli-concat": "0.0.13",
        "broccoli-funnel": "^1.0.0",
        "broccoli-stew": "^1.0.1",
        "broccoli-string-replace": "^0.1.1",
        "broccoli-uglify-sourcemap": "^1.0.1",
        "broccoli-yuidoc": "^2.1.0",
        "ember-ajax": "^2.0.1",
        "ember-cli": "^2.8.0",
        "ember-cli-app-version": "^1.0.0",
        "ember-cli-blueprint-test-helpers": "0.11.0",
        "ember-cli-dependency-checker": "^1.2.0",
        "ember-cli-eslint": "1.3.0",
        "ember-cli-htmlbars": "^1.0.3",
        "ember-cli-htmlbars-inline-precompile": "^0.3.1",
        "ember-cli-inject-live-reload": "^1.4.0",
        "ember-cli-internal-test-helpers": "^0.8.1",
        "ember-cli-pretender": "0.6.0",
        "ember-cli-qunit": "^2.1.0",
        "ember-cli-release": "^0.2.9",
        "ember-cli-sri": "^2.1.0",
        "ember-cli-test-loader": "^1.1.0",
        "ember-cli-uglify": "^1.2.0",
        "ember-dev": "emberjs/ember-dev#bcfb9c3487ec2fd58b932394a15ce16fd9cf7eed",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-disable-proxy-controllers": "^1.0.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.5.1",
        "ember-publisher": "0.0.7",
        "ember-resolver": "^2.0.3",
        "ember-watson": "^0.7.0",
        "express": "^4.14.0",
        "faker": "^3.1.0",
        "github": "^0.2.4",
        "glob": "5.0.13",
        "heimdall-query": "^0.0.5",
        "json-api-mock-server": "0.1.1",
        "loader.js": "^4.2.2",
        "mocha": "2.4.5",
        "mocha-only-detector": "0.0.2",
        "morgan": "^1.7.0",
        "phantomjs-prebuilt": "^2.1.12",
        "pretender": "1.0.0",
        "rimraf": "2.5.2",
        "rsvp": "3.2.1"
    },
    "peerDependencies": {
        "ember-inflector": "^1.9.4"
    },
    "keywords": [
        "ember-addon"
    ],
    "ember-addon": {
        "configPath": "tests/dummy/config",
        "paths": [
            "lib/enable-optional-features-via-url"
        ],
        "after": "ember-cli-mocha"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
