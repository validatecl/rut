# @validatecl/rut

[![Build Status](https://travis-ci.org/validatecl/rut.svg?branch=master)](https://travis-ci.org/validatecl/rut)
![GitHub](https://img.shields.io/github/license/validatecl/rut)
![GitHub last commit](https://img.shields.io/github/last-commit/validatecl/rut)
![npm (scoped)](https://img.shields.io/npm/v/@validatecl/rut)
![npm](https://img.shields.io/npm/dw/@validatecl/rut)

Dependency-free, Chilean RUT utils for Node.js and browsers (transpiled).

## Requirements

This library has been tested with **Node.js v12.x** and **NPM v6.x**.

## Installation

```sh
npm i @validatecl/rut
```

## Usage

### Node.js

Require or import it into you projects as `'@validatecl/rut'`:

```js
const clRut = require('@validatecl/rut');
```

```ts
import clRut from '@validatecl/rut';
```

## Examples

```ts
import clRut from '@validatecl/rut';

const value = '22222222';

const calculated = clRut.calculate(value);
const verififer = clRut.verifier(value);
const isValid = clRut.validate(value);
const formatted = clRut.format(value);
const digits = clRut.digits(value);
const clean = clRut.clean(value);
```

## Documentation

Please see [the documentation page](https://validatecl.github.io/rut/) for more details.
