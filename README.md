# csskit-base

Simple base styles built on top of [normalize.css](https://npmjs.com/normalize.css) and [open-color](https://npmjs.com/open-color).

[![npm][npm-image]][npm-url]
[![travis][travis-image]][travis-url]
[![standard][standard-image]][standard-url]
[![conduct][conduct]][conduct-url]

[npm-image]: https://img.shields.io/npm/v/csskit-base.svg?style=flat-square
[npm-url]: https://www.npmjs.com/package/csskit-base
[travis-image]: https://img.shields.io/travis/csskit/csskit-base.svg?style=flat-square
[travis-url]: https://travis-ci.org/csskit/csskit-base
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat-square
[standard-url]: http://npm.im/standard
[conduct]: https://img.shields.io/badge/code%20of%20conduct-contributor%20covenant-green.svg?style=flat-square
[conduct-url]: CONDUCT.md

## About

csskit-base includes a handful of minimal style improvements to help you implement a nice design quickly.

The few colors used are based on the [open-color](https://npmjs.com/open-color) package.

Browser reset is handled by [normalize.css](https://npmjs.com/normalize.css).

## Install

```sh
npm install --save csskit-base
```

## Usage

You can bundle css dependencies using tools like [csskit-cli](https://npmjs.com/csskit-cli) & [sheetify](https://npmjs.com/sheetify).

Import `csskit-base` in you main css file:

```css
@import "csskit-base";

/* your other css rules*/
```

## Unprocessed source file

Want to use the source file before it is processed using [postcss](https://npmjs.com/postcss), [postcss-import](https://npmjs.com/postcss-import), and [postcss-cssnext](https://npmjs.com/postcss-cssnext)?

Import the `csskit-base/source.css` file:

```css
@import "csskit-base/source.css";

/* your other css rules*/
```

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## Conduct

It is important that this project contributes to a friendly, safe, and welcoming environment for all. Read this project's [code of conduct](CONDUCT.md)

## Changelog

Read about the changes to this project in [CHANGELOG.md](CHANGELOG.md). The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## Contact

- **issues** – Please open issues in the [issues queue](https://github.com/sethvincent/base/issues)
- **twitter** – Have a question? [@sethdvincent](https://twitter.com/sethdvincent)
- **email** – Need in-depth support via paid contract? Send an email to sethvincent@gmail.com

## License

[ISC](LICENSE.md)
