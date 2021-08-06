# @validatecl/cl-rut

[![Build Status](https://travis-ci.org/validatecl/cl-rut.svg?branch=master)](https://travis-ci.org/validatecl/cl-rut)
![GitHub](https://img.shields.io/github/license/validatecl/cl-rut)
![GitHub last commit](https://img.shields.io/github/last-commit/validatecl/cl-rut)
![npm (scoped)](https://img.shields.io/npm/v/@validatecl/cl-rut)
![npm](https://img.shields.io/npm/dw/@validatecl/cl-rut)

Dependency-free, Chilean RUT utils for Node.js and browsers (transpiled).

## Requirements

This library has been tested with **Node.js 12, 14** and **NPM 6**.

## Installation

```sh
npm i @validatecl/cl-rut
```

## Usage

### Node.js

Import it into you projects as `'@validatecl/cl-rut'`:

```ts
import {
  cleanParts,
  calculate,
  verifier,
  validate,
  format,
  digits,
  clean,
} from '@validatecl/cl-rut';
```

## Examples

```ts
import clRut from '@validatecl/cl-rut';

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

Please see [the documentation page](https://validatecl.github.io/cl-rut/) for more details.
