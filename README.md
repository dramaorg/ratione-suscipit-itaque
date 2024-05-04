# Mocha Suppress Logs

[![CircleCI][circleci-image]][circleci-url]
[![NPM Version][npm-image]][npm-url]
[![Coverage Status][coveralls-image]][coveralls-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]


Suppress console output of successful mocha tests.

Ideal if you want to keep your test's report clean while still being able to debug the output of failed tests.

**Note**: For `mocha` version 7 or earlier, you must use version [0.2.0](https://www.npmjs.com/package/@dramaorg/ratione-suscipit-itaque/v/0.2.0) of this package.

## Requirements

* [mocha](https://www.npmjs.com/package/mocha) (8.0.0 or higher)

## Installation

```bash
npm install --save-dev @dramaorg/ratione-suscipit-itaque
```

## Usage

Simply require `@dramaorg/ratione-suscipit-itaque` when running `mocha`:

```bash
mocha --require @dramaorg/ratione-suscipit-itaque
```

<br>

Or put it in your [`.mocharc`](https://mochajs.org/#configuring-mocha-nodejs) to make it default behavior:

```json
{
    "require": "@dramaorg/ratione-suscipit-itaque"
}
```

[circleci-image]: https://circleci.com/gh/AleG94/@dramaorg/ratione-suscipit-itaque.svg?style=svg
[circleci-url]: https://circleci.com/gh/AleG94/@dramaorg/ratione-suscipit-itaque
[coveralls-image]: https://coveralls.io/repos/github/AleG94/@dramaorg/ratione-suscipit-itaque/badge.svg?branch=master
[coveralls-url]: https://coveralls.io/github/AleG94/@dramaorg/ratione-suscipit-itaque?branch=master
[npm-image]: https://img.shields.io/npm/v/@dramaorg/ratione-suscipit-itaque.svg
[npm-url]: https://npmjs.org/package/@dramaorg/ratione-suscipit-itaque
[license-image]: https://img.shields.io/npm/l/@dramaorg/ratione-suscipit-itaque.svg
[license-url]: https://github.com/dramaorg/ratione-suscipit-itaque/blob/master/LICENSE
[downloads-image]: https://img.shields.io/npm/dt/@dramaorg/ratione-suscipit-itaque
[downloads-url]: https://npmjs.org/package/@dramaorg/ratione-suscipit-itaque
