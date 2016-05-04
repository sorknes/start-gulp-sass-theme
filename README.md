## Default folder structure ##

> * http://thesassway.com/beginner/how-to-structure-a-sass-project

stylesheets/
|
|-- modules/                 # Common modules
|   |-- _all.scss            # include to get all modules
|   |-- _utility.scss        # module name
|   |-- _colors.scss         # colors
|   |-- functions/           # Common functions
|   |-- |-- _pxtoem.scss     # convert px to em
|   |-- mixins/              # Common mixins
|   |-- |-- _bem.scss        # cssBem helper
|   ...
|
|-- partials/                # Partials
|   |-- _base.sass           # imports for all mixins + global project variables
|   |-- _config.scss         # settings
|   |-- _grid.scss           # grid
|   |-- _global.scss         # global
|   ...
|
|-- vendor/                  # CSS or Sass from other projects
|   ...
|
|-- main.scss                # Primary Sass file


## Task to be execute in the terminal on any new projects ##

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
