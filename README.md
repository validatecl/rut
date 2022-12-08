# @validatecl/rut

[![Build Status](https://travis-ci.com/validatecl/rut.svg?branch=main)](https://travis-ci.org/validatecl/rut)
![GitHub](https://img.shields.io/github/license/validatecl/rut)
![GitHub last commit](https://img.shields.io/github/last-commit/validatecl/rut)
![npm (scoped)](https://img.shields.io/npm/v/@validatecl/rut)
![npm](https://img.shields.io/npm/dw/@validatecl/rut)

Dependency-free, Chilean RUT utils for Node.js and browsers (transpiled).

## Requirements

This library has been tested with **Node.js 16, 19** and **NPM 8**.

## Installation

```sh
npm i @validatecl/rut
yarn add @validatecl/rut
```

## Usage

### Node.js

Import it into you projects as `'@validatecl/rut'`:

```ts
import {
  cleanParts,
  calculate,
  verifier,
  validate,
  format,
  digits,
  clean,
} from '@validatecl/rut';
```

## Examples

```ts
import clRut from '@validatecl/rut';

const value = '22222222';

const calculated = calculate(value);
const verifier = verifier(value);
const isValid = validate(value);
const formatted = format(value);
const parts = cleanParts(value);
const digits = digits(value);
const clean = clean(value);
```

## Documentation

Please see [the documentation page](https://validatecl.github.io/rut/) for more details.
