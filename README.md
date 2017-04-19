# npmdoc-redux-promise-middleware

#### api documentation for  [redux-promise-middleware (v4.2.0)](https://github.com/pburtchaell/redux-promise-middleware)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-promise-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-promise-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-promise-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-promise-middleware)

#### Redux middleware for handling promises and optimistic updates

[![NPM](https://nodei.co/npm/redux-promise-middleware.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/redux-promise-middleware)

- [https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Burtchaell",
        "url": "pburtchaell.com"
    },
    "bugs": {
        "url": "https://github.com/pburtchaell/redux-promise-middleware/issues"
    },
    "contributors": [
        {
            "name": "Thomas",
            "url": "tomatao.co.uk"
        }
    ],
    "dependencies": {},
    "description": "Redux middleware for handling promises and optimistic updates",
    "devDependencies": {
        "babel-cli": "^6.6.5",
        "babel-core": "^6.7.2",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.4",
        "babel-polyfill": "^6.7.4",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "bluebird": "^3.4.0",
        "chai": "^3.5.0",
        "coveralls": "^2.11.9",
        "eslint": "^3.10.2",
        "eslint-config-airbnb": "^13.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-jsx-a11y": "^2.2.3",
        "eslint-plugin-react": "^6.7.1",
        "express-urlrewrite": "^1.2.0",
        "faker": "^3.1.0",
        "isomorphic-fetch": "^2.2.1",
        "istanbul": "^1.0.0-alpha.2",
        "json-server": "^0.9.1",
        "lodash": "^4.6.1",
        "mocha": "^3.1.2",
        "mocha-lcov-reporter": "^1.2.0",
        "pre-commit": "^1.1.3",
        "react": "^15.0.0",
        "react-dom": "^15.0.0",
        "react-redux": "^4.4.1",
        "react-router": "^2.0.1",
        "redux": "^3.0.4",
        "redux-mock-store": "1.2.1",
        "redux-thunk": "^2.0.1",
        "sinon": "^1.17.2",
        "sinon-chai": "^2.8.0",
        "webpack": "^1.12.14",
        "webpack-dev-middleware": "^1.5.1",
        "webpack-hot-middleware": "^2.10.0"
    },
    "directories": {},
    "dist": {
        "shasum": "052a7ac2df0e3468e196279f14bdefe711d10cac",
        "tarball": "https://registry.npmjs.org/redux-promise-middleware/-/redux-promise-middleware-4.2.0.tgz"
    },
    "gitHead": "9d00371c9d9e351070eb92a26c78b954e6c970b9",
    "homepage": "https://github.com/pburtchaell/redux-promise-middleware",
    "keywords": [
        "redux",
        "middleware",
        "middlewares",
        "promise",
        "promises",
        "optimistic update",
        "optimistic updates",
        "async",
        "example"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "pburtchaell"
        }
    ],
    "name": "redux-promise-middleware",
    "optionalDependencies": {},
    "peerDependencies": {
        "redux": "^2.0.0 || ^3.0.0"
    },
    "pre-commit": [
        "precommit"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pburtchaell/redux-promise-middleware.git"
    },
    "scripts": {
        "build": "npm run build-commonjs & npm run build-umd & npm run build-umd-min",
        "build-commonjs": "'npm bin'/babel src -d dist",
        "build-umd": "'npm bin'/webpack dist/ReduxPromiseMiddleware.js",
        "build-umd-min": "NODE_ENV=production 'npm bin'/webpack dist/ReduxPromiseMiddleware.min.js",
        "lint": "'npm bin'/eslint src/**/*.js examples/**/*.js test/**/*.js",
        "prebuild": "npm run test",
        "precommit": "echo 'Running pre-commit hooks...' && npm run test",
        "prepublish": "npm run build",
        "pretest": "npm run lint",
        "start": "babel-node examples/server.js",
        "test": "./bin/test.sh"
    },
    "version": "4.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
