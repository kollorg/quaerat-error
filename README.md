# @kollorg/quaerat-error <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

`[].map(f)` for older browsers

# example

``` js
var map = require('@kollorg/quaerat-error');
var letters = map([97,98,99], function (c) {
	return String.fromCharCode(c);
});
console.log(letters.join(''));
```

output:

```
abc
```

# methods

``` js
var map = require('@kollorg/quaerat-error')
```

## var ys = map(xs, f)

Create a new array `ys` by applying `f(xs[i], i, xs)` to each element in `xs` at
index `i`.

# install

With [npm](https://npmjs.org) do:

```
npm install @kollorg/quaerat-error
```

# license

MIT

[package-url]: https://npmjs.org/package/@kollorg/quaerat-error
[npm-version-svg]: https://versionbadg.es/ljharb/@kollorg/quaerat-error.svg
[deps-svg]: https://david-dm.org/ljharb/@kollorg/quaerat-error.svg
[deps-url]: https://david-dm.org/ljharb/@kollorg/quaerat-error
[dev-deps-svg]: https://david-dm.org/ljharb/@kollorg/quaerat-error/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@kollorg/quaerat-error#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@kollorg/quaerat-error.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@kollorg/quaerat-error.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@kollorg/quaerat-error.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@kollorg/quaerat-error
[codecov-image]: https://codecov.io/gh/ljharb/@kollorg/quaerat-error/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@kollorg/quaerat-error/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@kollorg/quaerat-error
[actions-url]: https://github.com/kollorg/quaerat-error/actions
