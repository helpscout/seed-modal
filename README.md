# seed-modal [![npm version](https://badge.fury.io/js/seed-modal.svg)](https://badge.fury.io/js/seed-modal)

Modal component pack for [Seed](https://github.com/helpscout/seed)!

## Install
```
npm install seed-modal --save
```


## Basic Usage

### SCSS
This seed pack needs to be imported into your sass pipeline. Below is an example using Gulp:


```javascript
var gulp = require('gulp');
var sass = require('gulp-sass');
var pack = require('seed-modal');

gulp.task('sass', function () {
  return gulp.src('./sass/**/*.scss')
    .pipe(sass({
      includePaths: pack
    }))
    .pipe(gulp.dest('./css'));
});
```

Once that is setup, simply `@import` *seed-modal* as needed in your `.scss` file:

```scss
// Packs
@import "pack/seed-modal/_index";
```

## Options

The following variables can be found in `_config.scss`

```scss
seed-modal config options
```
