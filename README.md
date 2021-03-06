# iOS Sample App

[![Travis CI](https://travis-ci.org/igorkulman/iOSSampleApp.svg?branch=master)](https://travis-ci.org/igorkulman/iOSSampleApp)
[![codecov](https://codecov.io/gh/igorkulman/iOSSampleApp/branch/master/graph/badge.svg)](https://codecov.io/gh/igorkulman/iOSSampleApp)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Platforms](https://img.shields.io/badge/platform-iOS-lightgrey.svg)
[![Swift Version](https://img.shields.io/badge/Swift-4.1-F16D39.svg?style=flat)](https://developer.apple.com/swift)
[![Twitter](https://img.shields.io/badge/twitter-@igorkulman-blue.svg)](http://twitter.com/igorkulman)

Sample iOS app written the way I write iOS apps because I cannot share the app I currently work on.

## Shown concepts

### Architecture concepts

* [Coordinators](https://blog.kulman.sk/architecting-ios-apps-coordinators/)
* Dependency Injection
* MVVM
* [Data Binding](https://blog.kulman.sk/using-data-binding-in-ios/)
* Dependencies management

### Other concepts

* Localization to 2 languages with [safer string usage](https://blog.kulman.sk/using-ios-strings-in-a-safer-way/) and checking for missing translations
* Continuous integration
* Unit testing, including testing view controllers for leaks
* Using (multiple) Storyboards just as glorified XIBs
* Creating a view controller in code when Storyboard cannot be used
* Using static UITableView cells in a typed way with enums
* Image literals
* Automated AppStore screenshots taking in multiple languages
* Adding custom reactive properties

## Getting started

### Prerequisites

* XCode 10+
* [Carthage](https://github.com/Carthage/Carthage)
* [SwiftGen](https://github.com/SwiftGen/SwiftGen)
* [SwifLint](https://github.com/realm/SwiftLint) (optional)
* [Fastlane](https://fastlane.tools/) (optional)

### Bootstraping the project

To get started with the project run

```bash
sh ./bootstrap.sh` 
```

to install Carthage, SwifLint, SwiftGen, Fastlane and build all the Carthage dependencies. 

If you already have Carthage installed and do not want or need the other tools, just run `carthage bootstrap --platform iOS` to build all the Carthage dependencies. 

This need to be done **just once** for the initial setup.

## Built With

- [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift 
- [RxSwiftExt](https://github.com/RxSwiftCommunity/RxSwiftExt) - A collection of Rx operators & tools not found in the core RxSwift distribution 
- [Swinject](https://github.com/Swinject/Swinject) - Dependency injection framework for Swift
- [SwinjectStoryboard](https://github.com/Swinject/SwinjectStoryboard) - Swinject extension for automatic dependency injection via Storyboard 
- [CleanroomLogger](https://github.com/emaloney/CleanroomLogger) - CleanroomLogger provides an extensible Swift-based logging API that is simple, lightweight and performant 
- [Reusable](https://github.com/AliSoftware/Reusable) - A Swift mixin for reusing views easily and in a type-safe way
- [Nuke](https://github.com/kean/Nuke) - A powerful image loading and caching system
- [RxNuke](https://github.com/kean/RxNuke) - RxSwift extensions for Nuke 
- [FeedKit](https://github.com/nmdias/FeedKit) - An RSS, Atom and JSON Feed parser written in Swift 
- [CRToast](https://github.com/cruffenach/CRToast) - A modern iOS toast view that can fit your notification needs 
- [Defaults](https://github.com/sindresorhus/Defaults) - Swifty and modern UserDefaults 
- [SimulatorStatusMagic](shinydevelopment/SimulatorStatusMagic) - Clean up your status bar for taking screenshots on the iOS simulator
- [SpecLeaks](leandromperez/specleaks) - Unit Tests Memory Leaks in Swift. Write readable tests for mem leaks easily with these Quick and Nimble extensions

## Author

Igor Kulman - igor@kulman.sk

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
