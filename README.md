# Unity LevelPlay iAds iOS SDK

Unity LevelPlay & iAds iOS SDK for Swift Package Manager.

## Installation

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for managing the distribution of Swift code. It’s integrated with the Swift build system to automate the process of downloading, compiling, and linking dependencies.

To integrate the Unity LevelPlay iAds SDK into your Xcode project using Swift Package Manager:

1. Add it to the `dependencies` of your `Package.swift`:

```swift
dependencies: [
    .package(url: "https://github.com/ironsource-mobile/Unity-Mediation-iAds-Swift-Package", .upToNextMajor(from: "9.3.0"))
]
```

2. Enable the `-ObjC` flag in Xcode: click on your project settings, go to **Build Settings**, search for **Other Linker Flags** and add `-ObjC`.
