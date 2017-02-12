# "Hello, World" in Angular 2

This is a minimal "Hello, World" application built using Webpack.

There is one unit test, just sufficient to prove that Karma and Jasmine are working.

It is based on the [Webpack introduction from the Angular 2 documentation](https://angular.io/docs/ts/latest/guide/webpack.html), but with a few corrections so that it actually compiles:

* Updates to some NPM package versions
* Corrected path to `tsconfig.json` in the Webpack configuration. (The instructions tell you to put this file in the root directory, but the sample `webpack.common.js` looks for it in the `src/` subfolder.)

## Getting started

### To run the application

1. `npm install`
2. `npm start`
3. Open browser and go to [http://localhost:8080](http://localhost:8080)

### To run unit tests

`npm run test`

This should detect and run tests in any files named `*.spec.ts`.
