# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.3.0] - 2016-01-18

### Changed

- BREAKING CHANGE: use official angular-formly package (formly:angular-formly)
- BREAKING CHANGE: (for meteor users) angular-meteor is no longer a dependency

## [1.2.2] - 2015-11-20
### Fixed
- missing dist files

## [1.2.1] - 2015-11-20
### Fixed
- npm package name
- bower package name

## [1.2.0] - 2015-11-20
### Added
- Support for npm
- Support for bower
- Support for webpack
- karma tests
- coverage reports

## [1.1.2] - 2015-11-13
### Removed
- es5-shim package

## [1.1.1] - 2015-11-12
### Fixed
- Undefined variable in transfomer's context createError method

### Added
- Tests of in-context transformer.createError method

## [1.1.0] - 2015-11-12
### Added
- Tests and integration with Travis-Ci
- Documentation of formlyTransformer service

## [1.0.0] - 2015-11-11
### Added
- Extend transformation function to use models, form instance and form configuration
- Transformation function has now helper methods in context
- Method in transfomer context to create new error (this.createError)

### Changed
- Transformation functions are now using formlyConfig.extras.fieldTransform
- Transformation functions run on all angular-formly forms (removed formlyTransformer::transform method)

### Removed
- Transformation functions no longer have unique name
- formlyTransformer::transform method (see formlyConfig.extras.fieldTransform)

## [0.0.2] - 2015-11-10
### Added
- Use wieldo:angular-formly package
- Add angular-meteor to formlyTransformer AngularJS module

## 0.0.1 - 2015-11-09

[1.3.0]: https://github.com/wieldo/angular-formly-transformer/compare/v1.2.2...v1.3.0
[1.2.2]: https://github.com/wieldo/angular-formly-transformer/compare/v1.2.1...v1.2.2
[1.2.1]: https://github.com/wieldo/angular-formly-transformer/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/wieldo/angular-formly-transformer/compare/v1.1.2...v1.2.0
[1.1.2]: https://github.com/wieldo/angular-formly-transformer/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/wieldo/angular-formly-transformer/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/wieldo/angular-formly-transformer/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/wieldo/angular-formly-transformer/compare/v1.0.0...v0.0.2
[0.0.2]: https://github.com/wieldo/angular-formly-transformer/compare/v0.0.1...v0.0.2
