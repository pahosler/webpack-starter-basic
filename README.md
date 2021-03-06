# webpack-starter-basic
[![forthebadge](http://forthebadge.com/images/badges/fo-real.svg)](http://forthebadge.com)[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

[![dependencies](https://david-dm.org/lifenautjoe/webpack-starter-basic.svg)](https://david-dm.org/lifenautjoe/webpack-starter-basic)

A simple **webpack3 starter project** for your basic web development needs.

Read more on the [demo website](https://lifenautjoe.github.io/webpack-starter-basic/) or continue reading below.

## Motivation

I needed to make a plain ol' "drop your mail to stay updated of ongoing developments" page.

I did not need anything fancy, no frontend framework, no unit testing, simply a **starter project that would let me use sass, ES6, load assets, add vendor prefixes, start a dev server, generate sourcemaps and optimize everything for production.**

I looked around and all I found were heavily specialized and complicated webpack starter projects (`webpack-angular-starter`, `webpack-react-starter`, etc) that are so intertwined with plugins that stripping undesired functionality is almost impossible. 

So I did this.

## Features

* Separated development and production webpack settings you can understand
* Sass
* ES6
* Asset loading
* CSS Vendor prefixing
* Development server
* Sourcemaps
* Favicons generation
* Production optimizations

## Requirements

* [Node](https://nodejs.org) > 7.6

## Usage

Substitute `PROJECT-NAME` for your project name.

Clone the repository

```sh
 git clone https://github.com/lifenautjoe/webpack-starter-basic PROJECT-NAME
 cd PROJECT-NAME
```

Install npm dependencies

```sh
 npm install 
```

Run the kickstart command
```sh
npm run kickstart
```

**After the project has been kickstarted**

To start the development server

```sh
npm start
```

To build for production

```sh
npm run build
```

## FAQ

### When should I use this starter?

You should use this starter if any of the following are true:

* You want to make a static page. e.g. splash screen, onboarding screen, phaser game, threejs visualization, countdown.
* You found no good starter kit for whatever you want to do and need a solid place to start from.

**Please note**: If you are going to use a frontend framework like angular or react, you can of course add the required plugins and 
configuration but it's normally complicated and quirky enough that it's highly recommended to use one of the existing 
starter projects such as [react-webpack-babel](https://github.com/alicoding/react-webpack-babel) or for angular projects the [angular-cli](https://github.com/angular/angular-cli).

### Where's the common webpack config?

**There is none and that is good thing.**

The pattern creates unnecessary confusion over the setup, at the end the config will always be different across environments.
People just put booleans everywhere on the common config to switch between these differing configuration options which is just awful to see and confusing for someone who's just starting on webpack.

The only truly shared config between these files are the entry js point and the main html template.



___
Author [Joel Hernandez](www.lifenautjoe.com)

