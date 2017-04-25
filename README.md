# npmtest-netbeast-cli

#### basic test coverage for  [netbeast-cli (v0.5.9)](https://github.com/netbeast/dashboard#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-netbeast-cli.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-netbeast-cli) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-netbeast-cli.svg)](https://travis-ci.org/npmtest/node-npmtest-netbeast-cli)

#### Netbeast OS dashboard, IoT apps manager

[![NPM](https://nodei.co/npm/netbeast-cli.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/netbeast-cli)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-netbeast-cli/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-netbeast-cli/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-netbeast-cli/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-netbeast-cli/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-netbeast-cli/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-netbeast-cli/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-netbeast-cli/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-netbeast-cli/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-netbeast-cli/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-netbeast-cli/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-netbeast-cli/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-netbeast-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-netbeast-cli/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-netbeast-cli/build/test-report.html](https://npmtest.github.io/node-npmtest-netbeast-cli/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-netbeast-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-netbeast-cli/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-netbeast-cli/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-netbeast-cli/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-netbeast-cli/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-netbeast-cli/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-netbeast-cli/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-netbeast-cli/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "staff@netbeast"
    },
    "bin": {
        "beast": "bin/cli.js",
        "netbeast": "bin/cli.js"
    },
    "bugs": {
        "url": "https://github.com/netbeast/dashboard/issues"
    },
    "contributors": [
        {
            "name": "Jesus Rivera"
        },
        {
            "name": "Pablo Pizarro"
        },
        {
            "name": "Luis Pinto"
        },
        {
            "name": "Jon Senra"
        },
        {
            "name": "Fran Ríos"
        },
        {
            "name": "Cayetano Rodríguez"
        },
        {
            "name": "Lourdes Liró"
        },
        {
            "name": "Ismael Martin"
        }
    ],
    "dependencies": {
        "aedes": "^0.17.1",
        "bluebird": "^3.2.2",
        "body-parser": "^1.12.2",
        "chalk": "^1.1.1",
        "cli-spinner": "^0.2.1",
        "commander": "^2.7.1",
        "cookie-parser": "^1.4.1",
        "dotenv": "^2.0.0",
        "express": "^4.12.3",
        "freeport": "^1.0.5",
        "fs-extra": "^0.26.0",
        "fstream": "^1.0.8",
        "fstream-ignore": "^1.0.3",
        "getmac": "^1.0.7",
        "gift": "^0.6.1",
        "http-proxy": "^1.13.2",
        "inquirer": "^1.0.2",
        "lodash": "^4.12.0",
        "mixpanel": "^0.4.0",
        "morgan": "^1.5.2",
        "mqtt": "^1.6.3",
        "multer": "^1.1.0",
        "netbeast": "^1.0.5",
        "serve-favicon": "^2.2.0",
        "sqlite3": "^3.1.3",
        "superagent": "^1.7.2",
        "superagent-bluebird-promise": "^3.0.0",
        "websocket-stream": "^3.1.0"
    },
    "description": "Netbeast OS dashboard, IoT apps manager",
    "devDependencies": {
        "babel-preset-es2015": "^6.3.13",
        "babel-preset-react": "^6.3.13",
        "babelify": "^7.2.0",
        "browserify": "^13.0.1",
        "chai": "^3.2.0",
        "chart.js": ">= 1.1.1 & < 2.0",
        "electron-prebuilt": "^0.37.2",
        "envify": "^3.4.0",
        "enzyme": "^2.3.0",
        "gulp": "^3.9.0",
        "gulp-autoprefixer": "^3.1.0",
        "gulp-bg": "^0.0.8",
        "gulp-cssnano": "^2.1.0",
        "gulp-istanbul": "^0.10.3",
        "gulp-livereload": "^3.8.1",
        "gulp-load-plugins": "^1.1.0",
        "gulp-mocha": "^2.2.0",
        "gulp-nodemon": "^2.0.3",
        "gulp-plumber": "^1.0.1",
        "gulp-sass": "^2.0.1",
        "gulp-sourcemaps": "^1.5.2",
        "gulp-util": "^3.0.4",
        "gulp-wait": "^0.0.2",
        "istanbul": "^0.4.0",
        "jquery": "^2.2.3",
        "livereload": "^0.4.1",
        "mocha": "^2.3.3",
        "pre-commit": "^1.1.3",
        "react": "^0.14.0",
        "react-avatar": "^0.7.2",
        "react-bootstrap": "^0.29.4",
        "react-chartjs": "^0.7.3",
        "react-color": "^2.0.0",
        "react-dom": "^0.14.0",
        "react-dropzone": "^3.3.2",
        "react-router": "^2.0.0-rc5",
        "react-typist": "^0.3.0",
        "vinyl-buffer": "^1.0.0",
        "vinyl-source-stream": "^1.1.0",
        "watchify": "^3.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "a6427938f736c4897862391b13e1b9c7609c8d73",
        "tarball": "https://registry.npmjs.org/netbeast-cli/-/netbeast-cli-0.5.9.tgz"
    },
    "engines": {
        "node": ">=0.12"
    },
    "gitHead": "61673dec05bc51cdb486b14d33c73a11864a507b",
    "homepage": "https://github.com/netbeast/dashboard#readme",
    "keywords": [
        "netbeast",
        "beast",
        "iot",
        "node",
        "dashboard",
        "smart",
        "router"
    ],
    "license": "AGPL-3.0",
    "main": "electron.js",
    "maintainers": [
        {
            "name": "cayrodmed1"
        },
        {
            "name": "fcojriosbello"
        },
        {
            "name": "ismael"
        },
        {
            "name": "jesusdario"
        },
        {
            "name": "joncy"
        },
        {
            "name": "loulirsal"
        },
        {
            "name": "luisfpinto"
        },
        {
            "name": "netbeast"
        },
        {
            "name": "pablo.pi"
        }
    ],
    "name": "netbeast-cli",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/netbeast/dashboard.git"
    },
    "scripts": {
        "build": "gulp build",
        "clean": "rm -r ./test/coverage; rm .database.sqlite",
        "coverage": "gulp coverage",
        "dev": "gulp",
        "electron": "electron electron.js",
        "prepublish": "npm run build",
        "release:major": "npm version major && npm publish && git push --follow-tags",
        "release:minor": "npm version minor && npm publish && git push --follow-tags",
        "release:patch": "npm version patch && npm publish && git push --follow-tags",
        "start": "node index.js",
        "test": "gulp test"
    },
    "version": "0.5.9"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
