# api documentation for  [redux-promise-middleware (v4.2.0)](https://github.com/pburtchaell/redux-promise-middleware)  [![npm package](https://img.shields.io/npm/v/npmdoc-redux-promise-middleware.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-redux-promise-middleware) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-redux-promise-middleware.svg)](https://travis-ci.org/npmdoc/node-npmdoc-redux-promise-middleware)
#### Redux middleware for handling promises and optimistic updates

[![NPM](https://nodei.co/npm/redux-promise-middleware.png?downloads=true)](https://www.npmjs.com/package/redux-promise-middleware)

[![apidoc](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-redux-promise-middleware_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-redux-promise-middleware/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Patrick Burtchaell",
        "email": "patrick@pburtchaell.com",
        "url": "pburtchaell.com"
    },
    "bugs": {
        "url": "https://github.com/pburtchaell/redux-promise-middleware/issues"
    },
    "contributors": [
        {
            "name": "Thomas",
            "email": "iammotivated@gmail.com",
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
            "name": "pburtchaell",
            "email": "patrick@pburtchaell.com"
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
    "readme": "ERROR: No README data found!",
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



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module redux-promise-middleware](#apidoc.module.redux-promise-middleware)
1.  [function <span class="apidocSignatureSpan">redux-promise-middleware.</span>default ()](#apidoc.element.redux-promise-middleware.default)



# <a name="apidoc.module.redux-promise-middleware"></a>[module redux-promise-middleware](#apidoc.module.redux-promise-middleware)

#### <a name="apidoc.element.redux-promise-middleware.default"></a>[function <span class="apidocSignatureSpan">redux-promise-middleware.</span>default ()](#apidoc.element.redux-promise-middleware.default)
- description and source-code
```javascript
function promiseMiddleware() {
  var config = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  var promiseTypeSuffixes = config.promiseTypeSuffixes || defaultTypes;

  return function (ref) {
    var dispatch = ref.dispatch;


    return function (next) {
      return function (action) {
        if (action.payload) {
          if (!(0, _isPromise2.default)(action.payload) && !(0, _isPromise2.default)(action.payload.promise)) {
            return next(action);
          }
        } else {
          return next(action);
        }

        // Deconstruct the properties of the original action object to constants
        var type = action.type,
            payload = action.payload,
            meta = action.meta;

        // Assign values for promise type suffixes

        var _promiseTypeSuffixes = _slicedToArray(promiseTypeSuffixes, 3),
            PENDING = _promiseTypeSuffixes[0],
            FULFILLED = _promiseTypeSuffixes[1],
            REJECTED = _promiseTypeSuffixes[2];

<span class="apidocCodeCommentSpan">        /**
         * @function getAction
         * @description Utility function for creating a rejected or fulfilled
         * flux standard action object.
         * @param {boolean} Is the action rejected?
         * @returns {object} action
         */
</span>

        var getAction = function getAction(newPayload, isRejected) {
          return _extends({
            type: type + '_' + (isRejected ? REJECTED : FULFILLED)
          }, newPayload === null || typeof newPayload === 'undefined' ? {} : {
            payload: newPayload
          }, meta !== undefined ? { meta: meta } : {}, isRejected ? {
            error: true
          } : {});
        };

        /**
         * Assign values for promise and data variables. In the case the payload
         * is an object with a 'promise' and 'data' property, the values of those
         * properties will be used. In the case the payload is a promise, the
         * value of the payload will be used and data will be null.
         */
        var promise = void 0;
        var data = void 0;

        if (!(0, _isPromise2.default)(action.payload) && _typeof(action.payload) === 'object') {
          promise = payload.promise;
          data = payload.data;
        } else {
          promise = payload;
          data = undefined;
        }

        /**
         * First, dispatch the pending action. This flux standard action object
         * describes the pending state of a promise and will include any data
         * (for optimistic updates) and/or meta from the original action.
         */
        next(_extends({
          type: type + '_' + PENDING
        }, data !== undefined ? { payload: data } : {}, meta !== undefined ? { meta: meta } : {}));

        /*
         * @function handleReject
         * @description Dispatch the rejected action and return
         * an error object. The error object is the original error
         * that was thrown. The user of the library is responsible for
         * best practices in ensure that they are throwing an Error object.
         * @params reason The reason the promise was rejected
         * @returns {object}
         */
        var handleReject = function handleReject(reason) {
          var rejectedAction = getAction(reason, true);
          dispatch(rejectedAction);
          throw reason;
        };

        /*
         * @function handleFulfill
         * @description Dispatch the fulfilled action and
         * return the success object. The success object should
         * contain the value and the dispatched action.
         * @param value The value the promise was resloved with
         * @returns {object}
         */
        var handleFulfill = function handleFulfill() {
          var value = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : null;

          var resolvedAction = getAction(value, false);
          dispatch(resolvedAction);

          return { value: value, action: resolvedAction };
        };

        /**
         * Second, dispatch a rejected or fulfilled action. This flux standard ...
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
