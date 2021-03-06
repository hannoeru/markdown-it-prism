# [Changelog](http://keepachangelog.com/)

This project adheres to [Semantic Versioning](http://semver.org/).

## [2.1.4](https://github.com/jGleitz/markdown-it-prism/compare/v2.1.3...v2.1.4) (2020-12-31)


### Bug Fixes

* **deps:** update dependency prismjs to v1.23.0 ([2c48e75](https://github.com/jGleitz/markdown-it-prism/commit/2c48e757a32d74ef3c2e0c234bafee177a2f563e))

## [2.1.3](https://github.com/jGleitz/markdown-it-prism/compare/v2.1.2...v2.1.3) (2020-10-10)


### Bug Fixes

* **deps:** update dependency prismjs to v1.22.0 ([e8265b8](https://github.com/jGleitz/markdown-it-prism/commit/e8265b83ce44c6eb3da7247ad4e77206487a20c7))

## [2.1.2](https://github.com/jGleitz/markdown-it-prism/compare/v2.1.1...v2.1.2) (2020-09-29)


### Bug Fixes

* escape the language class name so it cannot be used to inject HTML ([#137](https://github.com/jGleitz/markdown-it-prism/issues/137)) ([c1c074b](https://github.com/jGleitz/markdown-it-prism/commit/c1c074b88f7ad5a2eeb5eb9e12dde02fc4544946))

## [2.1.1](https://github.com/jGleitz/markdown-it-prism/compare/v2.1.0...v2.1.1) (2020-08-07)


### Bug Fixes

* **deps:** update dependency prismjs to v1.21.0 ([d494125](https://github.com/jGleitz/markdown-it-prism/commit/d4941258b71d8544d22241aeec1a171faf675898))

# [2.1.0](https://github.com/jGleitz/markdown-it-prism/compare/v2.0.6...v2.1.0) (2020-07-09)


### Bug Fixes

* only require Node.JS >= 6 ([5a4176c](https://github.com/jGleitz/markdown-it-prism/commit/5a4176c8ab083f8d395cd07f2ff042e219060894))


### Features

* publish Typescript types ([35ba58b](https://github.com/jGleitz/markdown-it-prism/commit/35ba58b26afed6d149481b4840886cf156bc0d0b))

## [2.0.6](https://github.com/jGleitz/markdown-it-prism/compare/v2.0.5...v2.0.6) (2020-07-06)


### Bug Fixes

* **deps:** update dependency prismjs to v1.20.0 ([a68434f](https://github.com/jGleitz/markdown-it-prism/commit/a68434f6711996115582a47cb0297b6b479aeeda))

## [2.0.5](https://github.com/jGleitz/markdown-it-prism/compare/v2.0.4...v2.0.5) (2020-03-02)


### Bug Fixes

* node >=10.0.0 is supported ([1a442a0](https://github.com/jGleitz/markdown-it-prism/commit/1a442a00fcfdbf155db96e18a84e831a1da61b67))

## [2.0.4] (2020-02-18)
 * Updated Prism JS to 1.19
 
## [2.0.3] (2019-09-07)
 * Updated dependencies

## [2.0.2] (2019-05-29)
### Fixed
 * Languages that have dependencies are now resolved correctly ([#22](https://github.com/jGleitz/markdown-it-prism/issues/22), thanks to @jlice and @RunDevelopment!)
 * Test cases have been adapted to new output of markdown-it prism Java

## [2.0.1] (2018-12-09)
### Fixed
 * Regression that exported the module’s main function only under the `default` key, not also as default export ([#17](https://github.com/jGleitz/markdown-it-prism/issues/17))

## [2.0.0] (2018-12-02)
### Deprecated
 * Deprecate Node.JS 4 and require Node.JS >= 6
### Added
 * Note about adding a stylesheet to the HTML in README
 * Options `defaultLanguage`, `defaultLanguageForUnknown` and `defaultLanguageForUnspecified` to specify fallback prism languages
### Fixed
 * Update all packages and eliminate dependency versions with known security issues
 * Improve the project setup
 * Improve the documentation in code

## [1.1.2] (2018-03-17)
 * Upgrade dependencies

## [1.1.1] (2017-05-22)
 * Removed a bad `\n\t` before the code that was affecting the HTML output.

## [1.1.0] (2017-05-21)
 * Add the `language-*` class also to the `<pre>` tag (not only to `<code>`).
 * Add the class `language-x` if `x` is the defined language, even if `x` cannot be highlighted with Prism.

## [1.0.1] (2016-10-19)
 * Fixed build bug that led to the plugin not being exported correctly.

## 1.0.0 (2016-10-16)
* Initial release.

[2.0.4]: https://github.com/jGleitz/markdown-it-prism/compare/v2.0.3...v2.0.4
[2.0.3]: https://github.com/jGleitz/markdown-it-prism/compare/v2.0.2...v2.0.3
[2.0.2]: https://github.com/jGleitz/markdown-it-prism/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/jGleitz/markdown-it-prism/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/jGleitz/markdown-it-prism/compare/v1.1.2...v2.0.0
[1.1.2]: https://github.com/jGleitz/markdown-it-prism/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/jGleitz/markdown-it-prism/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/jGleitz/markdown-it-prism/compare/v1.0.1...v1.1.0
[1.0.1]: https://github.com/jGleitz/markdown-it-prism/compare/v1.0.0...v1.0.1
