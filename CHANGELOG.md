# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Refine _slider_ design. The scroll shadow on the right is smaller and more realistic

## [0.0.15] - 2021-02-25

### Changed

- Change how _button_ are styled. Now, you have to add `.c-button--default` to have the default style
- Refactor _quotes_ component bay adding a variant for big quotes
- Change icons in _footer_, _arrow_ and _hero_

### Added

- New SVG components with all icons
- New _button--transparent-alt_ variant
- Added _slider_ component with basic style
- Added support for [CSS Extend Rule](https://github.com/csstools/postcss-extend-rule).

### Fixed

- Button containing spaces are on one line

## [0.0.14] - 2021-02-24

### Added

- Add a build process for non vectors images

### Changed

- Make _highlight_ more accessible
- Get the right SVG file and fallback image for _logo_

## [0.0.13] - 2021-02-23

### Removed

- _text media_ has been removed. It is replaced by _grid_

### Changed

- Adapt style of the _footer_ to the latest design
- _grid_ is now an object

### Fixed

- Refine margin of _content_ heading
- _content_ is on one column on mobile

## [0.0.12] - 2021-02-19

### Added

- Add _content_ component
- Add _grid_ component

## [0.0.11] - 2021-02-19

### Changed

- Add shema.org meta data to the _breadcrumb_

## [0.0.10] - 2021-02-19

### Changed

- In _breadcrumb_, all items except the last two are hidden and all items except the last one are clamp to one line

## [0.0.9] - 2021-02-17

### Removed

- _hero--contained_ are removed because they are no more used

### Changed

- Refine structure of _quote_ and add schema.org metadata
- Colors have been changed to match the design. You have to update the custom variables in `<head>`. Take a look at _color-inc_.
- _arrow_ are presentation graphics and not a link

### Fixed

- Fine tune typography

## [0.0.8] - 2021-02-17

### Changed

- Add `role=contentinfo` on the _footer_ for accessibility

### Fixed

- Fixed accessibility issues with link to nowhere `#`

## [0.0.7] - 2021-02-17

### Added

- Add CSS rules that check if there is accessibility issue

### Changed

- _figure_ component accept `srcset` to let the user agent select the best image depending of the viewport width

### Fixed

- Roboto is the default font

## [0.0.6] - 2021-02-16

### Added

- Add _breadcrumb_ component
- Add transparent variant of _button_

### Changed

- Structure of the _hero_ as changed to
  - push _button_ and _arrow_ at the bottom of the component and improve accessibility
  - make background image responsive

### Fixed

- Add a background on the preview of _logo_ to see it
- _arrow_ and _button_ is centered on mobile in an _hero_
- Text is responsive

## [0.0.5] - 2021-02-12

### Fixed

- Gradient on _quote_ display correctly on Safari
- Fix gap between column not being supported in Safari
- Add a background on _arrow_ preview page to be able to see the component
- Enable smooth scrolling

### Removed

- _header_ components is removed. It is replaced by _hero--title_

## [0.0.4] - 2021-02-11

### Fixed

- Build files are included in the node package

## [0.0.3] - 2021-02-11

### Added

- Add a variant without image for _hero_ component
- Add _arrow_ component
- Add _hero--title_ and _hero--contained_ variants of _hero_ components

### Fixed

- Make underline of links and anchors style thicker with a background effect on hover stats
- Fix link in README
- Fix links in CHANGELOG
- Fix missing styles on links in _footer_
- Maximum width of _quote_ and _highlight_ is 65 characters instead of a fixed units

## [0.0.2] - 2021-02-11

### Added

- Add _colors_ design tokens
- Add _headings_ design utility
- Add _visually hidden_ utility
- Add _auto grid_ object
- Add _container_ object
- Add _list-inline_ object
- Add _prose_ object
- Add _region_ object
- Add _split pair_ object
- Add _stack_ object
- Add _avatar_ component
- Add _button_ component
- Add _card_ component
- Add _figure_ component
- Add _footer_ component
- Add _header_ component
- Add _hero_ component
- Add _highlight_ component
- Add _logo_ component
- Add _navigation_ component
- Add _quote_ component
- Add _text-media_ component
- Add _content_ prototype
- Add _standard_ prototype
- Add `lint` and `beautify` npm script

## [0.0.1] - 2021-01-21

### Added

- Setup Fractal
- Basic styles

[unreleased]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.15...HEAD
[0.0.15]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.14...v0.0.15
[0.0.14]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.13...v0.0.14
[0.0.13]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.12...v0.0.13
[0.0.12]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.11...v0.0.12
[0.0.11]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.10...v0.0.11
[0.0.10]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.9...v0.0.10
[0.0.9]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.8...v0.0.9
[0.0.8]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.7...v0.0.8
[0.0.7]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.6...v0.0.7
[0.0.6]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.4...v0.0.5
[0.0.4]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/DSI-VD/joran-design-system/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/DSI-VD/joran-design-system/releases/tag/v0.0.1
