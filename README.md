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

1. Add test runner
