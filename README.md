# HexColors.swift

[![Build status][ci-image]][ci-url]
[![Carthage compatible][carthage-image]][carthage-url]

[ci-image]: https://travis-ci.org/jsw0528/HexColors.swift.svg?branch=master
[ci-url]: https://travis-ci.org/jsw0528/HexColors.swift
[carthage-image]: https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat
[carthage-url]: https://github.com/Carthage/Carthage

## Requirements

- iOS 7.2
- Xcode 7.2 (Swift 2.1)

## Installation

### Carthage

To integrate HexColors.swift into your project using Carthage add the following to your `Cartfile`:

```
github "jsw0528/HexColors.swift"
```

Then add `import HexColors` to the top of the files using HexColors.swift.

### Manually

Download the file [`HexColors.swift`](HexColors/HexColors.swift) and then add to your project.

## Usage

```swift
UIColor(hex: "#fff")

UIColor(hex: "#ffffff")

UIColor(hex: "#ffffff", alpha: 0.5)
```

## License

HexColors.swift is released under an MIT license. See the LICENSE file for more information.
