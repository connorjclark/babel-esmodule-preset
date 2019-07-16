result of `yarn babel src-ios-10-3`:

```
yarn run v1.12.3
$ /usr/local/google/home/cjamcl/code/scratch/babel-esmodule-preset/node_modules/.bin/babel src-ios-10-3
@babel/preset-env: `DEBUG` option

Using targets:
{
  "ios": "10.3"
}

Using modules transform: auto

Using plugins:
  transform-template-literals { "ios":"10.3" }
  transform-dotall-regex { "ios":"10.3" }
  transform-unicode-regex { "ios":"10.3" }
  transform-block-scoping { "ios":"10.3" }
  transform-async-to-generator { "ios":"10.3" }
  proposal-async-generator-functions { "ios":"10.3" }
  proposal-object-rest-spread { "ios":"10.3" }
  proposal-unicode-property-regex { "ios":"10.3" }
  proposal-json-strings { "ios":"10.3" }
  proposal-optional-catch-binding { "ios":"10.3" }
  transform-named-capturing-groups-regex { "ios":"10.3" }

Using polyfills with `entry` option:

[/usr/local/google/home/cjamcl/code/scratch/babel-esmodule-preset/src-ios-10-3/main.js] Replaced @babel/polyfill entries with the following polyfills:
  es7.array.flat-map { "ios":"10.3" }
  es6.array.sort { "ios":"10.3" }
  es7.promise.finally { "ios":"10.3" }
  es7.symbol.async-iterator { "ios":"10.3" }
  es7.string.trim-left { "ios":"10.3" }
  es7.string.trim-right { "ios":"10.3" }
  web.timers { "ios":"10.3" }
  web.immediate { "ios":"10.3" }
  web.dom.iterable { "ios":"10.3" }
"use strict";

require("core-js/modules/es7.array.flat-map");

require("core-js/modules/es6.array.sort");

require("core-js/modules/es7.promise.finally");

require("core-js/modules/es7.symbol.async-iterator");

require("core-js/modules/es7.string.trim-left");

require("core-js/modules/es7.string.trim-right");

require("core-js/modules/web.timers");

require("core-js/modules/web.immediate");

require("core-js/modules/web.dom.iterable");

function asyncGeneratorStep(gen, resolve, reject, _next, _throw, key, arg) { try { var info = gen[key](arg); var value = info.value; } catch (error) { reject(error); return; } if (info.done) { resolve(value); } else { Promise.resolve(value).then(_next, _throw); } }

function _asyncToGenerator(fn) { return function () { var self = this, args = arguments; return new Promise(function (resolve, reject) { var gen = fn.apply(self, args); function _next(value) { asyncGeneratorStep(gen, resolve, reject, _next, _throw, "next", value); } function _throw(err) { asyncGeneratorStep(gen, resolve, reject, _next, _throw, "throw", err); } _next(undefined); }); }; }

function start() {
  return _start.apply(this, arguments);
}

function _start() {
  _start = _asyncToGenerator(function* () {
    yield Promise.resolve();
  });
  return _start.apply(this, arguments);
}

start();

Done in 0.45s.

```