# Change log

## [Unreleased][unreleased]

## 1.0.1 - 2017-10-26
### Fixed
- Process of NULL input values

## 1.0.0 - 2017-05-19
### Added
- Support for regular expressions in route definitions
- CORSMiddleware
- OptionsPreflightHandler
- TextApiResponse
- XmlApiResponse

### Changed
- JsonApiResponse

## 0.3.0 - 2016-09-27
### Added
- Logger

## 0.2.0 - 2016-07-18
### Changed
- RouteResolver is not mandatory in Api class constructor (BaseRouteResolver will be used if is not set)
- $rules are optional for Validation

### Added
- getValue($key, $default = null) function to Validation

## 0.1.0 - 2016-07-05
- First tagged version

[unreleased]: https://github.com/ricco24/api-nette/compare/1.0.1...HEAD
[1.0.1]: https://github.com/ricco24/api-nette/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/ricco24/api-nette/compare/0.3.0...1.0.0
[0.3.0]: https://github.com/ricco24/api-nette/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/ricco24/api-nette/compare/0.1.0...0.2.0