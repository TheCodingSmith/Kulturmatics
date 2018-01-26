# Kulturmatics

## Setup Website Local Host

Visit [Node.js](https://nodejs.org/en/) and download the necessary files based on your OS, and then install it.

in console

`$cd Website`

`$npm install`

If necessary:

`$npm install gulp`

To run locally use `$gulp` this will run the gulpfile which processes the Sass, JS and Panini files into the src files and opens a localhost on `http://localhost:3000/`


## Using Sass

Inside of `src/scss` we will create sass files. Or Scss if needed. Gulp will exchange these to the `src/css` folder as `file.css`

[More information on Sass and how to use it](http://sass-lang.com/guide)

All colors will be stored as variables in `src/scss/colors`

All mixins will be stored as variables in `src/scss/mixins`

## Using Panini

[NPM Panini information](https://www.npmjs.com/package/panini)

We are using Panini to re-use all partials so we can keep our code as DRY as possible.
Everything will be sorted into partials and pages. The `nav` and `footer` will be partials on the main layout so we only have to write it once.

`Renders partials/header.html
{{> header}}`

This will be loosely based on the [Atomice Design System.](http://patternlab.io/)

## Links for Globes

  http://examples.webglearth.com/#overlays

  http://www.webglearth.com/#ll=42.36222,18.89182;alt=13076320;h=-6.566;t=-0.417

  http://planetaryjs.com/

  https://cesiumjs.org/about/

  http://globe.chromeexperiments.com/

  https://experiments.withgoogle.com/chrome/globe
