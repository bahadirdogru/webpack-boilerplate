Webpack Bootstrap Boilerplate
=========

### Make your project simple as possible!

This Boilerplate uses Webpack4 and typescript instead of Babel. Typescript is easier to configure and compile with it.
Instead of building bootstrap from node_modules this Boilerplate uses already compiled version of it.
In this boilerplate you can use SASS + Jquery + Bootstrap + Esnext.
What is special for this repo: I love keep css is just css, js is js and html is html. Not css in js or not html in js.

What you need?

- Node.js obviously.
- Git Bash if you working on Windows. You can find it here: <https://git-scm.com/downloads>
- For better experience I recommend VSCode and Live Server extension. It is better than webpack-dev-server.

#### Usage

**CSS code:**

- All your src/scss files compiled to dist/css by node-sass

**HTML code:**

- All your html is should be in dist/ 

**JavaScript code:**
- All src/js files bundled and compiled(es5) with typescript engine to /dist/js/bundle.js

**Nodejs Scripts:**

You can run these scripts like "npm run start" in git bash / terminal.

     -   cp-bootstrap: Copy bootstrap files to dist/css.
     -   comp-css: Compile src/scss to dist/css.
     -   webpack-dev: Webpack with development mode.
     -   webpack-dev-watch: Webpack development mode with --watch.
     -   webpack-prod: Webpack with production mode.
     -   webpack-server: I deprecated it but if you want to its run the webpack-dev-server.
     -   start: Just begin for development.
     -   build: Build project for production.


#### What is included

- jQuery 3 used.
- Popper.js used for Bootstrap
- Bootstrap 4 used.


#### License

Released under a MIT license