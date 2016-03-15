# HexColors.swift

[![Build status][ci-image]][ci-url]
[![Carthage compatible][carthage-image]][carthage-url]

[ci-image]: https://travis-ci.org/jsw0528/HexColors.swift.svg?branch=master
[ci-url]: https://travis-ci.org/jsw0528/HexColors.swift
[carthage-image]: https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat
[carthage-url]: https://github.com/Carthage/Carthage

## Requirements

- iOS 7.0
- Xcode 7.2 (Swift 2.1)

## Installation

### Using [Carthage](https://github.com/Carthage/Carthage)

Add `github "jsw0528/HexColors.swift"` to your `Cartfile` and run `carthage update --platform iOS`. If unfamiliar with Carthage then checkout their [Getting Started section](https://github.com/Carthage/Carthage#getting-started) or this [sample app](https://github.com/ankurp/DollarCarthageApp)

Then add `import HexColors` to the top of the files using HexColors.swift.

### Manually

Download the file [`HexColors.swift`](HexColors/HexColors.swift) and then add to your project.

## Usage

```swift
UIColor(hex: "#fff")

UIColor(hex: "#ffffff")

UIColor(hex: "#ffffff", alpha: 0.5)
```

## Got `Library not loaded: @rpath/HexColors.framework/HexColors` error?

Please refer to Carthage/Carthage#616

## License

HexColors.swift is released under an MIT license. See the LICENSE file for more information.
