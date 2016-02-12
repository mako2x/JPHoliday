JPHoliday
====
[![Version](https://img.shields.io/cocoapods/v/JPHoliday.svg)](http://cocoadocs.org/docsets/JPHoliday)
[![License](https://img.shields.io/cocoapods/l/JPHoliday.svg)](http://cocoadocs.org/docsets/JPHoliday)
[![Platform](https://img.shields.io/cocoapods/p/JPHoliday.svg)](http://cocoadocs.org/docsets/JPHoliday)
[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)

Swift library to deal with holidays in Japan.

## Usage

```swift
JPHoliday.isHoliday(year: 2016, month: 8, day: 11)

for holiday in JPHoliday.holidays(year: 2015) {
  print(holiday.name)
}
```

## Requirement

 - iOS 8.0 or later (by Carthage or CocoaPods) / iOS 7 (by manually)
 - Xcode 7.0 or later

## Install

### Carthage

Specify it in your Cartfile:

```
github "mako2x/JPHoliday"
```

Then, run the following command:

```
$ carthage update
```

### CocoaPods

Specify it in your Podfile:

```ruby
use_frameworks!

pod 'JPHoliday'
```

Then, run the following command:

```
$ pod install
```

### Manually

```
$ git submodule add https://github.com/mako2x/JPHoliday.git <PATH_TO_SUBMODULE>
```

Then just add references of JPHoliday/JPHoliday.swift to your Xcode project.

## Licence

[MIT](https://github.com/mako2x/JPHoliday/blob/master/LICENSE)

## Author

[mako2x](https://github.com/mako2x)
