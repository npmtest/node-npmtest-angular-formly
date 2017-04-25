# npmtest-angular-formly

#### basic test coverage for  [angular-formly (v8.4.1)](http://formly-js.github.io/angular-formly/)  [![npm package](https://img.shields.io/npm/v/npmtest-angular-formly.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-angular-formly) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-angular-formly.svg)](https://travis-ci.org/npmtest/node-npmtest-angular-formly)

#### AngularJS directive which takes JSON representing a form and renders to HTML

[![NPM](https://nodei.co/npm/angular-formly.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/angular-formly)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-angular-formly/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-formly/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-angular-formly/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-angular-formly/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-angular-formly/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-angular-formly/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-angular-formly/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-angular-formly/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-angular-formly/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-angular-formly/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-angular-formly/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-angular-formly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-angular-formly/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-angular-formly/build/test-report.html](https://npmtest.github.io/node-npmtest-angular-formly/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-angular-formly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-angular-formly/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-angular-formly/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-angular-formly/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-angular-formly/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-angular-formly/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-angular-formly/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-angular-formly/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Astrism"
    },
    "bugs": {
        "url": "https://github.com/formly-js/angular-formly/issues"
    },
    "config": {
        "ghooks": {
            "commit-msg": "validate-commit-msg && npm run eslint && npm t && npm run check-coverage"
        },
        "commitizen": {
            "path": "node_modules/cz-conventional-changelog"
        }
    },
    "contributors": [
        {
            "name": "Astrism"
        },
        {
            "name": "Kent C. Dodds"
        }
    ],
    "dependencies": {},
    "description": "AngularJS directive which takes JSON representing a form and renders to HTML",
    "devDependencies": {
        "angular": "1.5.0",
        "angular-mocks": "1.5.0",
        "api-check": "7.5.5",
        "argv-set-env": "1.0.1",
        "babel": "5.8.23",
        "babel-eslint": "4.1.3",
        "babel-loader": "5.3.2",
        "chai": "3.5.0",
        "codecov.io": "0.1.6",
        "commitizen": "2.7.2",
        "cracks": "3.1.2",
        "cz-conventional-changelog": "1.1.5",
        "deindent": "0.1.0",
        "eslint": "1.7.3",
        "eslint-config-kentcdodds": "5.0.0",
        "eslint-loader": "1.1.0",
        "eslint-plugin-mocha": "1.0.0",
        "ghooks": "1.0.3",
        "gulp": "3.9.1",
        "gulp-replace": "0.5.4",
        "http-server": "0.9.0",
        "isparta": "3.1.0",
        "isparta-loader": "1.0.0",
        "istanbul": "0.4.2",
        "karma": "0.13.22",
        "karma-chai": "0.1.0",
        "karma-chrome-launcher": "0.2.2",
        "karma-coverage": "0.5.5",
        "karma-firefox-launcher": "0.1.7",
        "karma-mocha": "0.2.2",
        "karma-sinon": "1.0.4",
        "karma-sinon-chai": "1.2.0",
        "karma-webpack": "1.7.0",
        "lodash": "4.6.1",
        "lolex": "1.4.0",
        "mocha": "2.4.5",
        "ng-annotate": "1.2.1",
        "ng-annotate-loader": "0.1.0",
        "node-libs-browser": "1.0.0",
        "path-here": "1.1.0",
        "publish-latest": "1.1.2",
        "raw-loader": "0.5.1",
        "semantic-release": "4.3.5",
        "sinon": "1.17.3",
        "sinon-chai": "2.8.0",
        "validate-commit-msg": "2.3.1",
        "webpack": "1.12.14",
        "webpack-notifier": "1.3.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5f89c8a1bef42ba0139f3a8a0d5b2c93713601af",
        "tarball": "https://registry.npmjs.org/angular-formly/-/angular-formly-8.4.1.tgz"
    },
    "gitHead": "42b47c6ae0c5cdafca2696ffa27080e239431298",
    "homepage": "http://formly-js.github.io/angular-formly/",
    "jspm": {
        "peerDependencies": {
            "angular": "*"
        }
    },
    "keywords": [
        "angular",
        "forms",
        "angular-formly",
        "formly",
        "angularjs",
        "angular forms",
        "json forms",
        "form library"
    ],
    "license": "MIT",
    "main": "dist/formly.js",
    "maintainers": [
        {
            "name": "astrism"
        },
        {
            "name": "kentcdodds"
        }
    ],
    "name": "angular-formly",
    "optionalDependencies": {},
    "peerDependencies": {
        "angular": "^1.2.x || >= 1.4.0-beta.0 || >= 1.5.0-beta.0",
        "api-check": "^7.0.0"
    },
    "release": {
        "verfiyRelease": {
            "path": "cracks",
            "paths": [
                "src",
                "package.json"
            ],
            "silent": false
        }
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/formly-js/angular-formly.git"
    },
    "scripts": {
        "build": "npm run build:dist & npm run build:prod",
        "build:dist": "webpack --progress --colors --set-env-NODE_ENV=development",
        "build:prod": "webpack --progress --colors --set-env-NODE_ENV=production",
        "check-coverage": "istanbul check-coverage --statements 93 --branches 89 --functions 92 --lines 92",
        "commit": "git-cz",
        "eslint": "npm run eslint:test -s && npm run eslint:src -s",
        "eslint:src": "eslint -c other/src.eslintrc --ignore-pattern !**/*.{test,mock}.js src/",
        "eslint:test": "eslint -c other/test.eslintrc --ignore-pattern **/*.{test,mock}.js src/",
        "meteor": "gulp meteor",
        "publish-latest": "publish-latest --user-email kent+formly-bot@doddsfamily.us --user-name formly-bot",
        "report-coverage": "cat ./coverage/lcov.info | node_modules/.bin/codecov",
        "semantic-release": "semantic-release pre && npm run build && npm run meteor && npm publish && npm run publish-latest && semantic-release post",
        "start": "npm run test:watch",
        "test": "karma start --single-run --set-env-COVERAGE=true --set-env-NODE_ENV=test",
        "test:debug": "karma start --browsers Chrome --set-env-NODE_ENV=test",
        "test:watch": "karma start --set-env-COVERAGE=true --set-env-NODE_ENV=test"
    },
    "version": "8.4.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
