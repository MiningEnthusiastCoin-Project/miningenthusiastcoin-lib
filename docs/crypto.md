# MiningEnthusiastCoin Crypto

## Random
The `miningenthusiastcoincore.crypto.Random` namespace contains a single function, named `getRandomBuffer(size)` that returns a `Buffer` instance with random bytes. It may not work depending on the engine that miningenthusiastcoincore is running on (doesn't work with IE versions lesser than 11).

## BN
The `miningenthusiastcoincore.crypto.BN` class contains a wrapper around [bn.js](https://github.com/indutny/bn.js), the bignum library used internally in miningenthusiastcoincore.

## Point
The `miningenthusiastcoincore.crypto.Point` class contains a wrapper around the class Point of [elliptic.js](https://github.com/indutny/elliptic), the elliptic curve library used internally in miningenthusiastcoincore.

## Hash
The `miningenthusiastcoincore.crypto.Hash` namespace contains a set of hashes and utilities. These are either the native `crypto` hash functions from `node.js` or their respective browser shims as provided by the `browserify` library.

## ECDSA
`miningenthusiastcoincore.crypto.ECDSA` contains a pure JavaScript implementation of the elliptic curve DSA signature scheme based on [elliptic.js](https://github.com/indutny/elliptic).
