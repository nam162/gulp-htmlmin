# gulp-htmlmin [![NPM version](https://badge.fury.io/js/gulp-htmlmin.svg)](http://badge.fury.io/js/gulp-htmlmin)  [![Build Status](jonschlinkert/gulp-htmlmin.svg)](jonschlinkert/gulp-htmlmin) 

> gulp plugin to minify HTML.

## Install with [npm](npmjs.org)

```bash
npm i gulp-htmlmin --save-dev
```

## Usage

```js
var gulp = require('gulp');
var htmlmin = require('gulp-htmlmin');

gulp.task('minify', function() {
  gulp.src('src/*.html')
    .pipe(htmlmin({collapseWhitespace: true}))
    .pipe(gulp.dest('dist'))
});
```

See the [html-minifer docs](https://github.com/kangax/html-minifier) for options.

## Run tests

Install dev dependencies:

```bash
node i -d && mocha
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/jonschlinkert/gulp-htmlmin/issues)

## Author

**Jon Schlinkert**
 
+ [github/jonschlinkert](https://github.com/jonschlinkert)
+ [twitter/jonschlinkert](http://twitter.com/jonschlinkert) 

## License
Copyright (c) 2014-2015 Jon Schlinkert  
Released under the MIT license

***

_This file was generated by [verb](https://github.com/assemble/verb) on January 09, 2015._
