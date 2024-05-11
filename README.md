# @diotoborg/necessitatibus-provident-adipisci <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][deps-svg]][deps-url]
[![dev dependency status][dev-deps-svg]][dev-deps-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Is this value negative zero? === will lie to you.

## Example

```js
var isNegativeZero = require('@diotoborg/necessitatibus-provident-adipisci');
var assert = require('assert');

assert.notOk(isNegativeZero(undefined));
assert.notOk(isNegativeZero(null));
assert.notOk(isNegativeZero(false));
assert.notOk(isNegativeZero(true));
assert.notOk(isNegativeZero(0));
assert.notOk(isNegativeZero(42));
assert.notOk(isNegativeZero(Infinity));
assert.notOk(isNegativeZero(-Infinity));
assert.notOk(isNegativeZero(NaN));
assert.notOk(isNegativeZero('foo'));
assert.notOk(isNegativeZero(function () {}));
assert.notOk(isNegativeZero([]));
assert.notOk(isNegativeZero({}));

assert.ok(isNegativeZero(-0));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/necessitatibus-provident-adipisci
[npm-version-svg]: https://versionbadg.es/inspect-js/@diotoborg/necessitatibus-provident-adipisci.svg
[deps-svg]: https://david-dm.org/inspect-js/@diotoborg/necessitatibus-provident-adipisci.svg
[deps-url]: https://david-dm.org/inspect-js/@diotoborg/necessitatibus-provident-adipisci
[dev-deps-svg]: https://david-dm.org/inspect-js/@diotoborg/necessitatibus-provident-adipisci/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@diotoborg/necessitatibus-provident-adipisci#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/necessitatibus-provident-adipisci.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/necessitatibus-provident-adipisci.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/necessitatibus-provident-adipisci.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/necessitatibus-provident-adipisci
[codecov-image]: https://codecov.io/gh/inspect-js/@diotoborg/necessitatibus-provident-adipisci/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@diotoborg/necessitatibus-provident-adipisci/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@diotoborg/necessitatibus-provident-adipisci
[actions-url]: https://github.com/diotoborg/necessitatibus-provident-adipisci/actions
