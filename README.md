# node-find-java-home-sync [![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Coveralls Status][coveralls-image]][coveralls-url]

Returns the location of JAVA_HOME as an absolute path on windows, mac, and
linux.  It forked from [find-java-home](https://github.com/jsdevel/node-find-java-home) and runs synchronously.

## Prerequisites
* Node v0.11.12+

## Installation
`npm install node-java-home-sync`

## Example
````javascript
require('find-java-home-sync')(function(err, home){
  if(err)return console.log(err);
  console.log(home);
});
````


[downloads-image]: http://img.shields.io/npm/dm/find-java-home-sync.svg
[npm-url]: https://npmjs.org/package/find-java-home-sync
[npm-image]: https://badge.fury.io/js/find-java-home-sync.svg

[travis-url]: https://travis-ci.org/lazyjin/node-find-java-home-sync
[travis-image]: https://travis-ci.org/lazyjin/node-find-java-home-sync.svg?branch=master

[coveralls-url]: https://coveralls.io/github/lazyjin/node-find-java-home-sync?branch=master
[coveralls-image]: https://coveralls.io/repos/github/lazyjin/node-find-java-home-sync/badge.svg?branch=master
