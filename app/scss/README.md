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
