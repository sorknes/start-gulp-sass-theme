## Default folder structure ##

> * http://thesassway.com/beginner/how-to-structure-a-sass-project

    project_folder/
    |
    |- app/
        |- css/
        |- fonts/
        |- images/
        |- index.html
        |- js/
        |- scss/
    |- dist/
    |- gulpfile.js
    |- node_modules/
    |- package.json

    stylesheets/
    |
    |- modules/                # Common modules
    |   |- all.scss            # include to get all modules
    |   |- utility.scss        # module name
    |   |- colors.scss         # colors
    |   |- functions/          # Common functions
    |   |- |-- pxtoem.scss     # convert px to em
    |   |- mixins/             # Common mixins
    |   |- |-- bem.scss        # cssBem helper
    |   ...
    |
    |- partials/               # Partials
    |   |- base.sass           # imports for all mixins + global project variables
    |   |- config.scss         # settings
    |   |- grid.scss           # grid
    |   |- global.scss         # global
    |   ...
    |
    |-- vendor/                  # CSS or Sass from other projects
    |   ...
    |
    |-- main.scss                # Primary Sass file


## These are the NMP packages incuded in this project ##
* In your project folder, run `npm install` to install all packages

## These are the NMP packages incuded in this project ##

> * https://css-tricks.com/gulp-for-beginners/

* Create gulp project:                             `$ npm init`
* Install gulp on project:                         `$ npm install gulp --save-dev`
* Pipe CSS through several processors              `$ npm install --save-dev gulp-postcss`
* Add autoprefix to CSS                            `$ npm install --save-dev gulp-autoprefixer`
* Preprocessing with Gulp:                         `$ npm install gulp-sass --save-dev`
* Handling dependencies between files              `$ npm install --save-dev gulp-dependencies`
* Live-reloading with Browser Sync:                `$ npm install browser-sync --save-dev`
* Optimizing CSS and JavaScript files:             `$ npm install gulp-useref --save-dev`
* Minifying JavaScript files:                      `$ npm install gulp-uglify --save-dev`
* Minify the concatenated CSS:                     `$ npm install gulp-cssnano`
* Optimizing Images:                               `$ npm install gulp-imagemin --save-dev`
* Cache files:                                     `$ npm install gulp-cache --save-dev`
* Cleaning up generated files automatically:       `$ npm install del --save-dev (run gulp clean:dist)`
* Run correct sequence:                            `$ npm install run-sequence --save-dev`
* Add normalize.css                                `$ npm install --save normalize.css` Copy the normalize.css files to your css directory
* Add Susy grid framework                          `$ npm install susy --save-dev`
* Really Simple Media Queries with Sass            `$ npm install breakpoint-sass`


## Nice to have packages ##
> * https://www.npmjs.com/package/postcss-package-css
> * https://github.com/jkphl/gulp-svg-sprite
