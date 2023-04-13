# AlgOS - Landing Page

This landing page is based on the [Landing Page](https://startbootstrap.com/theme/landing-page/) 
template for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/).


## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/StartBootstrap/startbootstrap-landing-page/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-landing-page.svg)](https://www.npmjs.com/package/startbootstrap-landing-page)


## Usage

We use what they call the [advanced usage](https://github.com/startbootstrap/startbootstrap-landing-page#advanced-usage),
i.e. edits are done in the `src/` folder and then build via `npm` into the `dist/` folder from where they are served.
Manual edits in the `dist/` folder will be overriden by the next build.  
When you want to change the styling make your adjustments in the sass files in `src/sass/` folder when you want to make 
changes to the page's markup do so in the pug files in `src/pug/` and run the according npm command  

More information about [sass](https://sass-lang.com/) and [pug](https://pugjs.org/api/getting-started.html).

#### npm Scripts

* `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
* `npm run build:assets` copies the files in the `src/assets/` directory into `dist`
* `npm run build:pug` compiles the Pug located in the `src/pug/` directory into `dist`
* `npm run build:scripts` brings the `src/js/scripts.js` file into `dist`
* `npm run build:scss` compiles the SCSS files located in the `src/scss/` directory into `dist`
* `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
* `npm run start:debug` runs the project in debug mode
* `npm start` or `npm run start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`

You must have npm installed in order to use this build environment.
