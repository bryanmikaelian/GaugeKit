# GaugeKit

[![Version](https://img.shields.io/cocoapods/v/GaugeKit.svg?style=flat)](http://cocoapods.org/pods/GaugeKit)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![License](https://img.shields.io/cocoapods/l/GaugeKit.svg?style=flat)](http://cocoapods.org/pods/GaugeKit)
[![Platform](https://img.shields.io/cocoapods/p/GaugeKit.svg?style=flat)](http://cocoapods.org/pods/GaugeKit)
![language](https://img.shields.io/badge/Language-%20Swift%20-orange.svg)

<img src="https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/GK.PNG" width="200">


##Kit for building custom gauges + easy reproducible Apple's style ring gauges.

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/appleFitness.png)
->
![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/gauge.gif)

## Example Usage

Just open `GaugeKit.xcworkspace` and run Example project.

## Installation

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects.

GaugeKit is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

pod "GaugeKit"
```

### Carthage

To integrate GaugeKit into your Xcode project using Carthage, specify it in your `Cartfile`:

```ogdl
github "skywinder/GaugeKit" >= 0.2
```


#### Embedded Framework

Add GaugeKit as a [submodule](http://git-scm.com/docs/git-submodule) by opening the Terminal, `cd`-ing into your top-level project directory, and entering the following command:

```bash
$ git submodule add https://github.com/skywinder/GaugeKit.git
```

### Manually

If you prefer not to use either of the aforementioned dependency managers, you can simply add swift files into your project manually.


## Features :sparkles:

- Flexible and high-customizible gauges
- Auto-resized views
- Support `@IBInspectable` & `@IBDesignable`
- Written with vanilla `Swift` flavor :baby_chick:

## Usage :rainbow:

- Put on storyboard `UIView`, and set them class `Gauge` and module `GaugeKit`:

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/IB_class.png)

- Select type of gauge (property `type` in class or `gaugeTypeInt` for changes directly in Interface builder)

       - case `Circle`
       - case `Left`
       - case `Right`
       - case `Line`

##Example:

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/GaugeKit_sreenshot.png)
![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/SWGauge_example.gif)

###IB Example:

![GaugeKit](https://raw.githubusercontent.com/skywinder/GaugeKit/master/Images/ib_example_1.gif)

## Requirements

- iOS SDK **7.0** or later (iOS SDK **8.0** if you use it as a Framework)
- **Swift 1.2** and **Xcode 6.3** or later

## Communication :speaker:

Bug reports, feature requests, patches, well-wishes are always welcome! 

- If you need help, open an issue.
- If you found a bug, open an issue.
- If you have a feature request, open an issue.
- If you want to contribute, see [Contributing](https://github.com/skywinder/GaugeKit#contributing-octocat) section.

## Contributing :octocat:
I'd love to see your ideas for improving this library.

The best way to contribute is by submitting a pull request.
I'll do my best to respond to you as soon as possible.

## Author

Petr Korolev, sky4winder@gmail.com

## License

GaugeKit is available under the MIT license. See the LICENSE file for more info.
