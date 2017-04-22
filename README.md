# npmtest-i18n-react

#### basic test coverage for  i18n-react (v0.3.0-ts1)  [![npm package](https://img.shields.io/npm/v/npmtest-i18n-react.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-i18n-react) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-i18n-react.svg)](https://travis-ci.org/npmtest/node-npmtest-i18n-react)

#### React JS text internationalization and externalizing

[![NPM](https://nodei.co/npm/i18n-react.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/i18n-react)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-i18n-react/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n-react/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-i18n-react/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-i18n-react/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-i18n-react/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-i18n-react/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-i18n-react/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-i18n-react/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-i18n-react/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-i18n-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-i18n-react/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-i18n-react/build/test-report.html](https://npmtest.github.io/node-npmtest-i18n-react/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-i18n-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-i18n-react/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-i18n-react/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-i18n-react/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-i18n-react/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-i18n-react/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-i18n-react/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-i18n-react/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "i18n-react",
    "version": "0.3.0-ts1",
    "description": "React JS text internationalization and externalizing",
    "main": "dist/i18n-react.js",
    "typescript": {
        "definition": "dist/i18n-react.ext.d.ts"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/alexdrel/i18n-react"
    },
    "scripts": {
        "start": "tsc -p src -d -watch",
        "prebuild": "tsc -p src -d",
        "build": "webpack -d --config webpack-umd.config.js && webpack -p --config webpack-umd.config.js --output-filename i18n-react.umd.min.js",
        "examples": "webpack-dev-server --config webpack-ex.config.js --port 1818 -d",
        "build:examples": "webpack --config webpack-ex.config.js -d --progress",
        "test": "karma start karma.config.js --browsers Firefox --single-run",
        "test:watch": "karma start karma.config.js"
    },
    "keywords": [
        "i18n",
        "react",
        "external",
        "text"
    ],
    "author": "Alex Drel",
    "license": "MIT",
    "engines": {
        "node": "0.12.x || 4.x.x",
        "npm": "2.x.x"
    },
    "dependencies": {},
    "devDependencies": {
        "@types/jasmine": "^2.2.26-alpha",
        "@types/react": "^0.14.25-alpha",
        "jasmine-core": "^2.4.1",
        "json-loader": "^0.5.4",
        "jsx-loader": "^0.13.2",
        "karma": "^1.1.1",
        "karma-chrome-launcher": "^1.0.1",
        "karma-firefox-launcher": "^1.0.0",
        "karma-jasmine": "^1.0.2",
        "karma-sourcemap-loader": "^0.3.7",
        "karma-webpack": "^1.7.0",
        "node-libs-browser": "^1.0.0",
        "ts-loader": "^0.8.2",
        "typescript": "^2.0.0-dev.20160706",
        "webpack": "^1.13.1",
        "webpack-dev-server": "^1.14.1",
        "yaml-loader": "^0.2.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
