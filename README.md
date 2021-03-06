# Kommander

[![Twitter](https://img.shields.io/badge/contact-@intelygenz-0FABFF.svg?style=flat)](http://twitter.com/intelygenz)
[![Version](https://img.shields.io/cocoapods/v/Kommander.svg?style=flat)](http://cocoapods.org/pods/Kommander)
[![License](https://img.shields.io/cocoapods/l/Kommander.svg?style=flat)](http://cocoapods.org/pods/Kommander)
[![Platform](https://img.shields.io/cocoapods/p/Kommander.svg?style=flat)](http://cocoapods.org/pods/Kommander)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)


**Kommander** is a Swift library to manage the task execution in different threads. Through the definition a simple but powerful concept, [**Kommand**](https://en.wikipedia.org/wiki/Command_pattern).

Inspired on the Java library [**Kommander**](https://github.com/Wokdsem/Kommander) from [**Wokdsem**](https://github.com/Wokdsem).


![Kommander](https://raw.githubusercontent.com/intelygenz/Kommander-iOS/master/Kommander.png)

## Features

- [x] Make kommand or multiple kommands
- [x] Execute kommand or multiple kommands
- [x] Cancel kommand or multiple kommands
- [x] Set kommand success block
- [x] Set kommand error block
- [x] Main thread dispatcher
- [x] Current thread dispatcher
- [x] Custom OperationQueue dispatcher
- [x] Custom DispatchQueue dispatcher
- [x] Execute single or multiple Operation
- [x] Execute sequential or concurrent blocks
- [x] Execute DispatchWorkItem
- [x] Swift 2 version
- [x] Objective-C version

## Installation

Kommander is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Kommander'
```

For Swift 2 compatibility use:

```ruby
pod 'Kommander', :git => 'https://github.com/intelygenz/Kommander-iOS.git', :tag => '0.2.2-swift2'
```

For Objective-C compatibility use:

```ruby
pod 'Kommander', :git => 'https://github.com/intelygenz/Kommander-iOS.git', :tag => '0.2.2-objc'
```

#### Or you can install it with [Carthage](https://github.com/Carthage/Carthage):

```ogdl
github "intelygenz/Kommander-iOS"
```

#### Or install it with [Swift Package Manager](https://swift.org/package-manager/):

```swift
dependencies: [
    .Package(url: "https://github.com/intelygenz/Kommander-iOS.git")
]
```

## Usage

```swift
Kommander().makeKommand { () -> Void in
    // Your code here
}.execute()
```

## Etc.

* Contributions are very welcome.
* Attribution is appreciated (let's spread the word!), but not mandatory.

## Authors

[alexruperez](https://github.com/alexruperez), alejandro.ruperez@intelygenz.com

[juantrias](https://github.com/juantrias), juan.trias@intelygenz.com

[RobertoEstrada](https://github.com/RobertoEstrada), roberto.estrada@intelygenz.com'

## License

Kommander is available under the MIT license. See the LICENSE file for more info.
