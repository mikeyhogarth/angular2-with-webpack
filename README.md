# Angular 2 and Webpack Skeleton App

[![Build Status](https://travis-ci.org/mikeyhogarth/angular2-with-webpack.svg?branch=master)](https://travis-ci.org/mikeyhogarth/angular2-with-webpack)

Includes:

* Angular 2 RC 6
* Routing 3 RC 2
* Pug (formerly Jade) templates
* SCSS styles
* One spec, component, template, module and stylesheet
* Tests with Karma

Largely inspired by the angular 2 example webpack setup but with a few bells and whistles.

# Getting Started
```
npm install && typings install
```

Requires npm and typings to be pre installed (if you've never used typings before, 
it's basically a package manager for typescript definition files - as if the universe
needed any more package managers!). It'll actually try and run `typings install` for you as a 
post install script - if it breaks because of this just take it out of the package.json 
file and get typings installed on your system.

Once installation completes;

```
npm test        # run the specs
npm start       # start webpack dev server on port 8080
npm run build   # build production dist
```
