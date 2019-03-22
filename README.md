# escapethepod.com

Source code for [Escape The Pod](https://www.escapethepod.com).  

This version is built with [Eleventy](https://www.11ty.io) and based off of code from [mxb.dev](https://github.com/maxboeck/mxb/).

## Features

* Static Files
* BEM-flavoured Sass (w/ Embedded Critical CSS)
* Vanilla JS (ES6 / Babel)
* System Fonts & FOUT
* Offline Support w/ Service Worker
* Webmention.io Support
* Auto-publish notes on twitter via AWS Lambda Function
* Focus on Speed and Accessibility

## Installation

Eleventy is a static site generator based on Javascript, so you will need node and npm/yarn to run it.
Inside the project root, run `npm install` or `yarn` to install the dependencies.

## Getting Started

The local development environment uses gulp to process various stuff for the site. 
The most important commands can be run as npm scripts:

`npm start`: make a development build and serve the site through browsersync  
`npm run build`: make a production build  
`npm run serve`: serve the current build `dist` directory  
`npm run debug`: start Eleventy in debug mode and serve the site  
`npm run serve:lambda`: serve lambda functions with netlify-lambda  
`npm run build:lambda`: compile lambda functions for production  
