# JSQCoreDataKit

[![Build Status](https://secure.travis-ci.org/jessesquires/JSQCoreDataKit.svg)](http://travis-ci.org/jessesquires/JSQCoreDataKit) [![Version Status](https://img.shields.io/cocoapods/v/JSQCoreDataKit.svg)][podLink] [![license MIT](https://img.shields.io/cocoapods/l/JSQCoreDataKit.svg)][mitLink] [![codecov](https://codecov.io/gh/jessesquires/JSQCoreDataKit/branch/develop/graph/badge.svg)](https://codecov.io/gh/jessesquires/JSQCoreDataKit) [![Platform](https://img.shields.io/cocoapods/p/JSQCoreDataKit.svg)][docsLink] [![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

*A swifter Core Data stack*

## About

This library aims to do the following:

* Encode Core Data best practices, so you don't have to think "is this correct?" or "is this the right way to do this?"
* Provide better interoperability with Swift
* Harness Swift features and enforce Swift paradigms
* Bring functional paradigms to Core Data
* Make Core Data more *Swifty*
* Simplify the processes of standing up the Core Data stack
* Aid in testing your Core Data models
* Reduce the boilerplate involved with Core Data

> **Further reading on Core Data:**
>
> * [Core Data Programming Guide](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CoreData/cdProgrammingGuide.html)
> * [Core Data Core Competencies Guide](https://developer.apple.com/library/ios/documentation/DataManagement/Devpedia-CoreData/coreDataStack.html#//apple_ref/doc/uid/TP40010398-CH25-SW1)
> * [objc.io issue #4 on Core Data](https://www.objc.io/issue-4/)
> * [Concurrent Core Data Stacks – Performance Shootout](http://floriankugler.com/2013/04/29/concurrent-core-data-stack-performance-shootout/)
> * [Backstage with Nested Managed Object Contexts](http://floriankugler.com/2013/05/13/backstage-with-nested-managed-object-contexts/)

## Requirements

* Xcode 11+
* Swift 5.1+
* iOS 11.0+
* macOS 10.12+
* tvOS 11.0+
* watchOS 4.0+
* [SwiftLint](https://github.com/realm/SwiftLint)

## Installation

#### [CocoaPods](http://cocoapods.org) (recommended)

````ruby
use_frameworks!

# Latest release in CocoaPods
pod 'JSQCoreDataKit'

# Latest on develop branch
pod 'JSQCoreDataKit', :git => 'https://github.com/jessesquires/JSQCoreDataKit.git', :branch => 'develop'
````

## Documentation

Read the [docs][docsLink]. Generated with [jazzy](https://github.com/realm/jazzy). Hosted by [GitHub Pages](https://pages.github.com).

#### Generate

````bash
$ ./scripts/build_docs.sh
````

#### Preview

````bash
$ open index.html -a Safari
````

## Contribute

Please follow these sweet [contribution guidelines](https://github.com/jessesquires/HowToContribute).

## Credits

Created and maintained by [**@jesse_squires**](https://twitter.com/jesse_squires).

## License

`JSQCoreDataKit` is released under an [MIT License][mitLink]. See `LICENSE` for details.

>**Copyright &copy; 2015-present Jesse Squires.**

*Please provide attribution, it is greatly appreciated.*

[podLink]:https://cocoapods.org/pods/JSQCoreDataKit
[docsLink]:https://jessesquires.github.io/JSQCoreDataKit
[mitLink]:https://opensource.org/licenses/MIT
