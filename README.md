# keccak256

> A wrapper for the [`keccak`](https://www.npmjs.com/package/keccak) library to compute 256 bit keccak hash in JavaScript.

[![License](http://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/indeliblelabs/keccak256/main/LICENSE.md)

## Install

```bash
npm install @indeliblelabs/keccak256
```


## Usage

- **keccak256**(data) -> {Buffer}
  - {String | Buffer} data - data string or Buffer

  Returns a Buffer

## Getting Started

```js
const keccak256 = require('@indeliblelabs/keccak256')

console.log(keccak256('hello').toString('hex')) // "1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8"

console.log(keccak256(Buffer.from('hello')).toString('hex')) // "1c8aff950685c2ed4bc3174f3472287b56d9517b9c948127319a09a7a36deac8"
```


## Test

```bash
npm test
```

## License

MIT
