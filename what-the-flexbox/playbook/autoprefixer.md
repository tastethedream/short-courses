 ## Cross browser Flexbox support and AutoPrefixer - video 13

 - will change your code to older versions for use with older browsers using `gulp.js`

 - works with nodejs

 -  needs a package.json `npm init`

 - install gulp globally `npm install gulp -g` may need sudo

 - make a file `touch gulpfile.js`

 - Install plugins  
    1. local version of gulp `npm install gulp --save-dev`
    2. Autoprefixer `npm install gulp-autoprefixer --save-dev`

-  Require gulp and plugins in gulp.js 
    1. `const gulp = require('gulp');`
     1. `const autoprefixer = require('gulp-autoprefixer');`

     - Make a task 
     ```
     gulp.task('styles', function() {
         gulp.src('css/styles.css')
         .pipe(autoprefixer())
         .pipe(gulp.dest('build'))
     });
     ```

     - run autoprefixer `gulp styles`

     - Change you link in html to build `<link rel ="stylesheet" href="build/styles.css">`

     - Add a watch task so you do not have to keep running gulp styles

     <gulp.js>

     ```
     gulp.task('default', function(){
         gulp.watch('css/styles.css', ['styles'])
     });
     ```

     - Now run with `gulp watch` this will occupy the command window and update on each code save

