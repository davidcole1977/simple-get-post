# simple-get-post

[![Build Status](https://travis-ci.org/davidcole1977/simple-get-post.svg)](https://travis-ci.org/davidcole1977/simple-get-post)

A simple helper module to get JSON data from, or post data to, a URL end point

## Set up

coming soon...

## Basic useage

```js
var get = require('simple-get-post').get;

function callback (error, data) {
  if (error) {
    throw error;
  } else {
    console.log(data);
  }
}

get({
  url: 'http://requestURL.com/',
  params: {
    foo: 'bar'
  },
  callback: callback
});
```

## API

coming soon...

## Development

coming soon...

## Known issues

coming soon...

## Release history

### 0.1.0
* Added get() method

### 0.1.1
* Minor module refactoring to aid readability and testability
* Updated karma config to use firefox instead of phantomjs (supports function.prototype.bind)
