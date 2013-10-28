# ngLouellyn

ngLouellyn  - Another tool that will help you build cool angular web apps and modules.

## Installation

Install node packages using `npm` command line. This will install all the necessary packages for the development.

The packages are the following:
* Bower
* Jade
* Stylus
* CoffeeScript
* Livereload
* Grunt
* Grunt-cli
* Grunt-contrib-[jade, watch, coffee, stylus, connect, livereload]

First, make sure you have installed NodeJS in your computer. If you haven't, you can download and install NodeJS here: http://nodejs.org/download/

## Requirements

Bower should be installed in your environment.

$ npm install bower -g

## Quickstart

```bash
$ npm install
$ bower install
$ grunt compile
$ grunt start
```

#### Explanations

1. Install the packages.
```bash
$ npm install
```

2. Install angular and angular-* modules using bower. You can also change the angular version but editing bower.json.
```bash
$ bower install
````

3. Compile jade, stylus, and coffee-scripts.
```bash
$ grunt compile
```

4. Run Grunt watch
```bash
$ grunt start
```

4. Navigate to `http://localhost:3333/`


## TODO

* Add normalize-css ( $ bower install normalize-css )
* Add test runner
* Add grunt shell
* Add `grunt install` - bower install and grunt compile

- 10/28/2013
* [done] Fix layout/_main.jade
* [done][ Fix angular path in layout/_main.jade
* [done] Remove public/css
* [done] change and improve stylus config
* [done] change and improve coffee-script config
* [done] add js router.coffee, directives, servies, filters, and models
