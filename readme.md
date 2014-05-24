Bourbon Old Fashioned Simplified
===

Super simple starter project for responsive layouts. Mobile-first, IE7+ friendly.

A simplified version of https://github.com/ActionScripted/Bourbon-Old-Fashioned

This is a slightly opinionated starter project. It's built mobile-first, meaning the core styles are built for mobile with breakpoints via media queries that apply layout change for larger sizes. Simply put, the site is designed for a fluid, mobile size and then we override those styles specifically for larger sizes.


Quick Start
---
* Clone project
* Install SASS (`gem install sass`)
* From the project root, run `sass --watch sass:css` (`sass --watch sass:css --style compressed` for production CSS)
* Make CSS changes in `sass`. `sass/main.scss` is your primary starting point.


What's Included
---

* [Bourbon](http://bourbon.io/): SASS mixin library, sort of like Compass
* [Bourbon Neat](http://neat.bourbon.io/): Semantic grid framework for easy responsive layouts
* [jQuery](http://jquery.com/): Utility library (if you don't know about jQuery, this might not be for you)
* [html5shiv-print](http://code.google.com/p/html5shiv/): HTML5 tag polyfill including print support
* [selectivizr](http://selectivizr.com/): CSS3 selectors for IE
* [Respond.js](https://github.com/scottjehl/Respond): media query polyfill for IE 6-8
