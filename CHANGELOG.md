# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [2.0.1] - 2016-08-10

* Fixed `main` file.
* Adjusted README.md.

## [2.0.0] - 2016-08-09

* Switched to es2015 for source code.
* Switched to NPM as build script.
* Made plugin use postcss friendly things like `appendAfter` and `clone`.
* Removed rework dependencies.
* Improved documentation (README.md).

## [1.0.0] - 2015-10-17

**Note:** This release will be deleted as it doesn't adhere to [postcss plugin guidelines](https://github.com/postcss/postcss/blob/master/docs/guidelines/plugin.md) and needs to be replaced.

### Added

* Put a Hack of a solution together by wrapping the rework plugin in a postcss plugin. Does not use sourcemapping or anything useful.