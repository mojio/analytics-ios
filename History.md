0.0.5 / 2013-4-1
================
* Merged fix from @pkamb to fix types in logging statements.

0.0.4 / 2013-3-23
==================
* Removed UDID usage after Apple's announcement that it will no longer be accepted in the app store https://developer.apple.com/news/?id=3212013a
* Renamed repo to analytics-ios-osx

0.0.3 / 2013-3-13
==================
* Made timestamp more accurate
* Added max batch size

0.0.2 / 2013-3-12
==================
* Merged in numerous improvements from [tonyxiao](https://github.com/tonyxiao)
    * support for OSX apps
    * a shared dispatch queue and async flushing
    * removed JSON library dependency to use native JSON support
* Added enqueueAction to DRY things up
* Added an optional initialization method that reveals flushAt and flushAfter
* Added Cocoapods podspec

0.0.1 / 2013-3-9
==================
* Added working library for iOS
* Added README