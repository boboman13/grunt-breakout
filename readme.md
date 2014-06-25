# Grunt Breakout

> This is a fork of [connor4312's](https://github.com/connor4312/grunt-breakout) version, except this one is in Coffeescript and tailored to my wishes.

Breakout build environment for web development. MIT license, do what you'd like with it.

### Installation
```bash
$ git clone https://github.com/boboman13/grunt-breakout
$ npm install
$ bower install
```

### Usage

 * `grunt` - Compiles, but does not minify, assets.
 * `grunt spy` - File watcher for html, less, js, images, and coffeescript.
 * `grunt dist` - Compiles and minifies all assets.
 * `grunt pack` - Compiles and minifies all assets, and puts them in dist.zip for sharing/distribution.