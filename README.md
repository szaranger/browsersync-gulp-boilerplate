# BrowserSync Gulp Boilerplate App

This project serves as either a **very simple** boilerplate to start building an application using BrowserSync & Gulp.

Please see the [walkthrough](http://seanamarasinghe.com/developer/browsersync-gulp/) for a more thorough explanation of the code.

## Stack

- BrowserSync
- Gulp
- SASS

## Installation instructions

 In the project's directory, run the following commands:
```
 $ npm install
 $ gulp
```

In Windows npm can not yet run operation in parallel so we add in npm-run-all<br />
Change the start command in package.json to:<br />

```
"start": "npm-run-all --parallel watch-js dev-server server",
```
Now install the packages with the following commands:

```
$ npm install
$ npm install --save-dev npm-run-all
$ gulp
```
