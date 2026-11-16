# Prime Number Checker Module

A small Node.js npm module (`prime-checker`) that exports an `isPrime` function to check whether a number is prime.

> This is a practice project built as part of the **freeCodeCamp Back End Development and APIs** certification ("Build a Prime Number Checker Module").

## Features

- `isPrime(number)` returns `true` for prime numbers and `false` otherwise.
- Returns `false` for non-numbers, non-integers, and numbers less than or equal to 1.
- Checks divisors only up to the square root of the number.
- No dependencies.

## Installation

Clone the repository:

```bash
git clone https://github.com/FedaaM7md/fcc-prime-number-checker-module.git
cd fcc-prime-number-checker-module
```

The module has no dependencies, so no `npm install` is required.

## Usage

```js
const { isPrime } = require("./index.js");

isPrime(7);   // true
isPrime(10);  // false
isPrime(1);   // false
isPrime(2.5); // false
```

Quick check from the terminal:

```bash
node -e 'const { isPrime } = require("./index.js"); console.log(isPrime(97));'
```

## Project Structure

| File | Purpose |
|---|---|
| `index.js` | Defines and exports `isPrime` via `module.exports` |
| `package.json` | npm package metadata (`prime-checker`) |

## Technologies

- JavaScript (Node.js, CommonJS modules)
- npm

## Author

Fedaa Mohamed ([@FedaaM7md](https://github.com/FedaaM7md))
