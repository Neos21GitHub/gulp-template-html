# @neos21/gulp-template-html : gulp-template-html

[![NPM Version](https://img.shields.io/npm/v/@neos21/gulp-template-html.svg)](https://www.npmjs.com/package/@neos21/gulp-template-html) [![GPR Version](https://img.shields.io/github/package-json/v/neos21/gulp-template-html?label=github)](https://github.com/Neos21/gulp-template-html/packages/328042)

Gulp plugin uses [@neos21/template-html](https://github.com/Neos21/template-html) to generate static HTML files from templates and content files.


## Installation

```sh
$ npm install @neos21/gulp-template-html
```


## Gulpfile

```javascript
var gulp = require('gulp');
var template = require('@neos21/gulp-template-html');

gulp.task('default', () => {
  return gulp
    .src('content/*.html')
    .pipe(template('templates/template.html'))
    .pipe(gulp.dest('dist'));
});
```


## Example Usage

See the [examples](./examples) directory for an example of how to generate static HTML files from a template.


## How to contribute

1. File an issue in the repository, using the bug tracker, describing the
   contribution you'd like to make. This will help us to get you started on the
   right foot.
2. Fork the project in your account and create a new branch:
   `your-great-feature`.
3. Commit your changes in that branch.
4. Open a pull request, and reference the initial issue in the pull request
   message.


## License

See the [LICENSE](./LICENSE) file.


## Links

- [Neo's World](https://neos21.net/)
- [GitHub - Neos21](https://github.com/Neos21/)
- [GitHub - gulp-template-html](https://github.com/Neos21/gulp-template-html)
- [npm - @neos21/gulp-template-html](https://www.npmjs.com/package/@neos21/gulp-template-html)
