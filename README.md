# @patrtorg/perspiciatis-ipsam <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @patrtorg/perspiciatis-ipsam
```

## Usage/Examples

```js
var regexTester = require('@patrtorg/perspiciatis-ipsam');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@patrtorg/perspiciatis-ipsam
[npm-version-svg]: https://versionbadg.es/ljharb/@patrtorg/perspiciatis-ipsam.svg
[deps-svg]: https://david-dm.org/ljharb/@patrtorg/perspiciatis-ipsam.svg
[deps-url]: https://david-dm.org/ljharb/@patrtorg/perspiciatis-ipsam
[dev-deps-svg]: https://david-dm.org/ljharb/@patrtorg/perspiciatis-ipsam/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@patrtorg/perspiciatis-ipsam#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@patrtorg/perspiciatis-ipsam.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@patrtorg/perspiciatis-ipsam.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@patrtorg/perspiciatis-ipsam.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@patrtorg/perspiciatis-ipsam
[codecov-image]: https://codecov.io/gh/ljharb/@patrtorg/perspiciatis-ipsam/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@patrtorg/perspiciatis-ipsam/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@patrtorg/perspiciatis-ipsam
[actions-url]: https://github.com/patrtorg/perspiciatis-ipsam/actions
