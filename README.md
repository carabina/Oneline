# Oneline
[![Language][lang-image]](https://swift.org/) [![License][license-image]](LICENSE) ![Platform][platform-image] ![Pod Version][pod-version-image]

## How to use
Initialize UIView then chain setting its properties.

```swift
let label = UILabel().text("Hi, there!").font(.systemFont(ofSize: 12)).textColor(.blue).numberOfLines()
```
Instead of
```swift
let label = UILabel()
label.text = "Hi, there!"
label.font = .systemFont(ofSize: 12)
label.textColor = .blue
label.numberOfLines = 0
```
### Cocoapods
**For iOS 8+**
Add the following entry in your Podfile

```
pod 'Oneline'
```

Then run `pod install`.

### Contribution
Feel free to fork, pull to request for your commonly used UIView subclasses.
### License

Oneline is released under an MIT license.

[lang-image]: https://img.shields.io/badge/swift-4.0-orange.svg
[license-image]: https://img.shields.io/github/license/mashape/apistatus.svg
[platform-image]: https://img.shields.io/badge/platform-iOS-lightGrey.svg
[pod-version-image]: https://img.shields.io/badge/pod-0.1.0-blue.svg
