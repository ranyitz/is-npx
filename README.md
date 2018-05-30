# is-npx
> A small utility that checks if the process is running using npx

## installation

```bash
npm install is-npx
```

## Usage

## Running with npx

```bash
npx node-module
```

```js
// node-module/index.js

const isNpx = require('is-npx');

console.log(isNpx()) // true
```

## Running without npx

```bash
node node-module/index.js
```

```js
// node-module/index.js

const isNpx = require('is-npx');

console.log(isNpx()) // false
```