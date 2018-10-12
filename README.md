# dock-ops

[![build status](https://img.shields.io/travis/joechimo/dock-ops.svg)](https://travis-ci.com/joechimo/dock-ops)
[![code coverage](https://img.shields.io/codecov/c/github/joechimo/dock-ops.svg)](https://codecov.io/gh/joechimo/dock-ops)
[![code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![made with lass](https://img.shields.io/badge/made_with-lass-95CC28.svg)](https://lass.js.org)
[![license](https://img.shields.io/github/license/joechimo/dock-ops.svg)](LICENSE)
[![npm downloads](https://img.shields.io/npm/dt/dock-ops.svg)](https://npm.im/dock-ops)

> A module for orchestrating the start up of services in a docker-compose.


## Table of Contents

* [Install](#install)
* [Usage](#usage)
* [Contributors](#contributors)
* [License](#license)


## Install

[npm][]:

```sh
npm install dock-ops
```

[yarn][]:

```sh
yarn add dock-ops
```


## Usage

```js
const DockOps = require('dock-ops');

const dockOps = new DockOps();

console.log(dockOps.renderName());
// script
```


## Contributors

| Name                | Website                       |
| ------------------- | ----------------------------- |
| **Joe Cimaszewski** | <https://github.com/joechimo> |


## License

[MIT](LICENSE) © [Joe Cimaszewski](https://github.com/joechimo)


## 

[npm]: https://www.npmjs.com/

[yarn]: https://yarnpkg.com/
