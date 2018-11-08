# Base template for Gulp

Template to start from before starting frontend projects.

## Install template

``` sh
$ git clone https://github.com/mate-academy/gulp-template.git project-name
$ cd project-name
$ npm install
```

All packages will be installed after executing the script above. пакеты.

## Build the project

```sh
$ gulp build
```

## Development mode 

```sh
$ gulp serve
```

## Project structure

- `src/` - directory for html, css, sass, js, image files
- `dist/` - directory for built pages

You should be writing code in `src/` directory.

### Livereload and syncronization with browsers

Task `$ gulp serve`

When task is executed, gulp starts local web server BrowserSync and opens index.html.  

[About BrowserSync](http://www.browsersync.io/)  

Server uses `dist/` as a project root.
