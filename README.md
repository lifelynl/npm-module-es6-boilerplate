npm-module-es6-boilerplate
==========

Use this boilerplate to initiate an open source ES6 module for npm. It features Yarn, ESlint and Babel. The boilerplate is React-ready, which means that Babel and ESlint already understand JSX files.

## Installation

1. Download the boilerplate
    - If your project directory is still empty:
        1. `$ git clone git@github.com:lifelynl/npm-module-es6-boilerplate.git .`
        2. `$ rm -rf .git`
    - If your project directory is not empty:
        1. [Download the boilerplate as a zip](https://github.com/lifelynl/npm-module-es6-boilerplate/archive/master.zip)
        2. Extract the zip to your project directory.
2. Update the `env` object in .eslintrc.json, to specify your targeted JavaScript environment(s).
3. [Optional] Update .babelrc and .eslintrc.json if you are not going to use React.
4. [Optional] Remove React-related node modules if you are not going to use React.

## Test your module

Testing your npm module is as easy as running:

    $ yarn compile

This will create a /lib directory containing the compiled module.

## Publish

Bump the version [semantically](https://docs.npmjs.com/misc/semver) in package.json, then publish your npm package using:

    $ yarn publish

You *don't* have to run `$ yarn compile` first.

## You're awesome! 😃

Because you are about to contribute to the wide world of open source. 👍
