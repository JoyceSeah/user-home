# user-home [![Build Status](https://travis-ci.org/sindresorhus/user-home.svg?branch=master)](https://travis-ci.org/sindresorhus/user-home)

> Get the path to the user home directory


## Install

```sh
$ npm install --save user-home
```


## Usage

```js
var userHome = require('user-home');

console.log(userHome);
//=> /Users/sindresorhus
```

Returns `null` in the very unlikely scenario that it can't find the home directory.


## CLI

```sh
$ npm install --global user-home
```

```sh
$ user-home --help

Example
  $ user-home
  /Users/sindresorhus
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
