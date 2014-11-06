#  [![Build Status](https://secure.travis-ci.org/nfriedly/approximate-number.png?branch=master)](http://travis-ci.org/nfriedly/approximate-number)

Converts numbers into a more human-friendly format, similar to `ls`'s `--human-readable` flag (`ls -lh`) or Stack
Overflow's reputation numbers. For example, 123456 becomes '123k'. See [tests] for more examples.

Works in Node, browsers, and on the command line.,


## Getting Started

Install node module with: `npm install approximate-number`

```js
var approx = require('approximate-number');
approx(123456) // 123k
```

Or use the browser module with: `bower install approximate-number`

```html
<script src="/bower_components/approximate-number/lib/approximate-number.js"></script>
<script>
alert(approximate(1234567890)); // 1.2b
</script>
```

Or install with `-g` for command line usage

```sh
$ npm install -g approximate-number
$ approximate-number 78910 #78k
```

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com).


## License

Copyright (c) 2014 Nathan Friedly  
Licensed under the MIT license.


[tests]: https://github.com/nfriedly/approximate-number