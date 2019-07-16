result of `yarn babel src`:

```
yarn run v1.12.3
$ /usr/local/google/home/cjamcl/code/scratch/babel-esmodule-preset/node_modules/.bin/babel src
@babel/preset-env: `DEBUG` option

Using targets:
{
  "chrome": "61",
  "edge": "16",
  "firefox": "60",
  "ios": "10.3",
  "opera": "48",
  "safari": "10.1"
}

Using modules transform: auto

Using plugins:
  transform-template-literals { "ios":"10.3", "safari":"10.1" }
  transform-function-name { "edge":"16" }
  transform-dotall-regex { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  transform-unicode-regex { "ios":"10.3", "safari":"10.1" }
  transform-parameters { "edge":"16" }
  transform-block-scoping { "ios":"10.3", "safari":"10.1" }
  transform-async-to-generator { "ios":"10.3", "safari":"10.1" }
  proposal-async-generator-functions { "chrome":"61", "edge":"16", "ios":"10.3", "opera":"48", "safari":"10.1" }
  proposal-object-rest-spread { "edge":"16", "ios":"10.3", "safari":"10.1" }
  proposal-unicode-property-regex { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  proposal-json-strings { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  proposal-optional-catch-binding { "chrome":"61", "edge":"16", "ios":"10.3", "opera":"48", "safari":"10.1" }
  transform-named-capturing-groups-regex { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }

Using polyfills with `entry` option:

[/usr/local/google/home/cjamcl/code/scratch/babel-esmodule-preset/src/main.js] Replaced @babel/polyfill entries with the following polyfills:
  es7.array.flat-map { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  es6.array.sort { "chrome":"61", "ios":"10.3", "opera":"48", "safari":"10.1" }
  es6.number.is-finite { "opera":"48" }
  es6.number.is-nan { "opera":"48" }
  es7.object.define-getter { "chrome":"61", "opera":"48" }
  es7.object.define-setter { "chrome":"61", "opera":"48" }
  es7.object.lookup-getter { "chrome":"61", "edge":"16", "opera":"48" }
  es7.object.lookup-setter { "chrome":"61", "edge":"16", "opera":"48" }
  es6.object.is { "opera":"48" }
  es7.promise.finally { "chrome":"61", "edge":"16", "ios":"10.3", "opera":"48", "safari":"10.1" }
  es6.regexp.constructor { "edge":"16" }
  es6.regexp.flags { "edge":"16" }
  es6.regexp.match { "edge":"16" }
  es6.regexp.replace { "edge":"16" }
  es6.regexp.split { "edge":"16" }
  es6.regexp.search { "edge":"16" }
  es6.regexp.to-string { "edge":"16" }
  es6.symbol { "edge":"16" }
  es7.symbol.async-iterator { "chrome":"61", "edge":"16", "ios":"10.3", "opera":"48", "safari":"10.1" }
  es6.string.anchor { "opera":"48" }
  es6.string.big { "opera":"48" }
  es6.string.blink { "opera":"48" }
  es6.string.bold { "opera":"48" }
  es6.string.fixed { "opera":"48" }
  es6.string.fontcolor { "opera":"48" }
  es6.string.fontsize { "opera":"48" }
  es6.string.italics { "opera":"48" }
  es6.string.link { "opera":"48" }
  es6.string.small { "opera":"48" }
  es6.string.strike { "opera":"48" }
  es6.string.sub { "opera":"48" }
  es6.string.sup { "opera":"48" }
  es7.string.trim-left { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  es7.string.trim-right { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  web.timers { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  web.immediate { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
  web.dom.iterable { "chrome":"61", "edge":"16", "firefox":"60", "ios":"10.3", "opera":"48", "safari":"10.1" }
"use strict";

require("core-js/modules/es7.array.flat-map");

require("core-js/modules/es6.array.sort");

require("core-js/modules/es6.number.is-finite");

require("core-js/modules/es6.number.is-nan");

require("core-js/modules/es7.object.define-getter");

require("core-js/modules/es7.object.define-setter");

require("core-js/modules/es7.object.lookup-getter");

require("core-js/modules/es7.object.lookup-setter");

require("core-js/modules/es6.object.is");

require("core-js/modules/es7.promise.finally");

require("core-js/modules/es6.regexp.constructor");

require("core-js/modules/es6.regexp.flags");

require("core-js/modules/es6.regexp.match");

require("core-js/modules/es6.regexp.replace");

require("core-js/modules/es6.regexp.split");

require("core-js/modules/es6.regexp.search");

require("core-js/modules/es6.regexp.to-string");

require("core-js/modules/es6.symbol");

require("core-js/modules/es7.symbol.async-iterator");

require("core-js/modules/es6.string.anchor");

require("core-js/modules/es6.string.big");

require("core-js/modules/es6.string.blink");

require("core-js/modules/es6.string.bold");

require("core-js/modules/es6.string.fixed");

require("core-js/modules/es6.string.fontcolor");

require("core-js/modules/es6.string.fontsize");

require("core-js/modules/es6.string.italics");

require("core-js/modules/es6.string.link");

require("core-js/modules/es6.string.small");

require("core-js/modules/es6.string.strike");

require("core-js/modules/es6.string.sub");

require("core-js/modules/es6.string.sup");

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

Done in 0.44s.

```