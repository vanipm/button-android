# Button Android Deep Link Commerce

<p align="center"><img src="http://www.usebutton.com/img/sdk/img_dlc-preview.png" width="204"/>
</p>

<h1 align="center">Button DeepLink Commerce</h1>

## Overview

Button DeepLink Commerce enables rich cross-application functionality initiated from drop-in `Buttons`. Buttons act as the entry point to highly-contextual, fully attributed actions across apps.

The DeepLink Commerce (DLC) SDK provides full functionality for both sending and receiving users, attributed within the DLC network.

Add a `Button` to your app, pass it some `context` and it will render & display itself. e.g...

<p align="center"><img src="http://www.usebutton.com/img/sdk/img_dlc-uber-button.png" width="300" />
<br/>
<code>Ride</code> use-case with an <code>end-location</code>
</p>

## Getting started

### Gradle integration

We highly recommend that you use our SDK with Gradle, all you need to do is make sure you have `jcenter()` as one of your app's repositories.

```
repositories {
    jcenter()
}
```

Latest version: ![Download](https://api.bintray.com/packages/button/Public/android-sdk/images/download.svg).

```
dependencies {
    // Add the Button SDK dependency to the list of dependencies, 
    // you can see the latest version in the badge above
    // Replace + with this number, e.g. 1.0.0
    compile 'com.usebutton:android-sdk:+'
}
```

### Manual integration

But you can also include us manually by dropping our `aar` into you `/libs` folder, click [ ![Download](https://api.bintray.com/packages/button/Public/android-sdk/images/download.svg) ](https://bintray.com/button/Public/android-sdk/_latestVersion) to get the latest version.


### Next Steps

1. Get an Application ID by signing up here: [app.usebutton.com](https://app.usebutton.com/).
2. Follow the [DeepLink Commerce Integration Guide](https://www.usebutton.com/sdk/deep-link-commerce-android/) to get DLC in your app!


You can find the full [SDK Documentation](http://building.usebutton.com/button-android/latest/reference/com/usebutton/sdk/Button.html) here.

## Samples

You can find relevant example code and a fully working sample application in our [button-android-sample](https://github.com/usebutton/button-android-samples) repository.

## Release notes
### [5.8.0 Docs](http://building.usebutton.com/button-android/history/5.8.0/reference/com/usebutton/sdk/Button.html)
- Adds a method to detect whether a url can be exchanged for an app action
- Adds a method to exchange a url for an app action
- Fixes an intermittent web checkout issue where navigation chrome overlaps on-page controls

### [5.7.0 Docs](http://building.usebutton.com/button-android/history/5.7.0/reference/com/usebutton/sdk/Button.html)
* Adds support for publishers to pass through a value (e.g. click Id) to be associated with downstream merchant conversions
* Fix to allow Merchants shown in an Android web view and using local storage to render correctly

### [5.6.0 Docs](http://building.usebutton.com/button-android/history/5.6.0/reference/com/usebutton/sdk/Button.html)
* Support for getting action with merchant Id
* Misc improvements

### [5.5.0 Docs](http://building.usebutton.com/button-android/history/5.5.0/reference/com/usebutton/sdk/Button.html)
* New events persistence (from file to database)
* Fix for stale intents in install notification
* Viewed event for custom UI buttons
* Fix for potential crash after attended install

### [5.3.1 Docs](http://building.usebutton.com/button-android/history/5.3.1/reference/com/usebutton/sdk/Button.html)
* New loading state
* Fix for flicker in InteractiveButton

### [5.3.0 Docs](http://building.usebutton.com/button-android/history/5.3.0/reference/com/usebutton/sdk/Button.html)
* Misc improvements & bug fixes

### [5.2.0 Docs](http://building.usebutton.com/button-android/history/5.2.0/reference/com/usebutton/sdk/Button.html)
* A brand new Button - InteractiveButton
* Misc bug fixes

### [5.1.1 Docs](http://building.usebutton.com/button-android/history/5.1.1/reference/com/usebutton/sdk/Button.html)
* Bug fix related to persisted events

### [4.3.5 Docs](http://building.usebutton.com/button-android/history/4.3.5/reference/com/usebutton/sdk/Button.html)
* Bug fix related to persisted events
* Fix for ViewPager and support-v4:24.0.0 crashing

### [5.1.0 Docs](http://building.usebutton.com/button-android/history/5.1.0/reference/com/usebutton/sdk/Button.html)
* Post-install notification to make the install process better
* Deprecated SDK order reporting, please see our [developer docs](https://www.usebutton.com/developers/api-reference/).

### [5.0.1 Docs](http://building.usebutton.com/button-android/history/5.0.1/reference/com/usebutton/sdk/Button.html)
* Fix for crash with support-v4:24.0.0 due to incorrect handling of decor views in [ViewPager](b.android.com/213359)

### [5.0.0 Docs](http://building.usebutton.com/button-android/history/5.0.0/reference/com/usebutton/sdk/Button.html)
* A number of performance improvements
* Bug fixes

### [4.3.4 Docs](http://building.usebutton.com/button-android/history/4.3.4/reference/com/usebutton/sdk/Button.html)
* Bug fixes related to handling incoming deep links and language change

### [4.3.2 Docs](http://building.usebutton.com/button-android/history/4.3.2/reference/com/usebutton/sdk/Button.html)
* Bug fixes
* Preview heading

### [4.3.1 Docs](http://building.usebutton.com/button-android/history/4.3.1/reference/com/usebutton/sdk/Button.html)
* Fixed bug when trying to install app on Genymotion (NPE)

### [4.3.0 Docs](http://building.usebutton.com/button-android/history/4.3.0/reference/com/usebutton/sdk/Button.html)
* Reduced network usage for event reporting
* Miscellaneous bug fixes
* Support for intent flags for invoking custom UI

### [4.2.0 Docs](http://building.usebutton.com/button-android/history/4.2.0/reference/com/usebutton/sdk/Button.html)
* Removed dependency on CardView and compat-v7

### [4.1.5 Docs](http://building.usebutton.com/button-android/history/4.1.5/reference/com/usebutton/sdk/Button.html)
* Removed backup attribute from AndroidManifest
* Ability to disable interaction on the ButtonDropin

### [4.1.3 Docs](http://building.usebutton.com/button-android/history/4.1.3/reference/com/usebutton/sdk/Button.html)
* Fixed attribution bug

### [4.1.0 Docs](http://building.usebutton.com/button-android/history/4.1.0/reference/com/usebutton/sdk/Button.html)
* Make your own buttons
* Significant performance improvements
* Disk based caching of images

### [4.0.0 Docs](http://building.usebutton.com/button-android/history/4.0.0/reference/com/usebutton/sdk/Button.html)
* Automatic intent handling of incoming deep links
* Line item reporting
* BETA support for a new feature

### [3.2.0 Docs](http://building.usebutton.com/button-android/history/3.2.0/reference/com/usebutton/sdk/Button.html)
* Improved network access
* Misc improvements

### [3.1.0 Docs](http://building.usebutton.com/button-android/history/3.1.0/reference/com/usebutton/sdk/Button.html)
* Minor bug fixes and improvement

### [3.0.1 Docs](http://building.usebutton.com/button-android/history/3.0.1/reference/com/usebutton/sdk/Button.html)
* Ability to report custom attribution events

### [3.0.0 Docs](http://building.usebutton.com/button-android/history/3.0.0/reference/com/usebutton/sdk/Button.html)
* Introduced new structured taxonomy for context

### [2.3.0 Docs](http://building.usebutton.com/button-android/history/2.3.0/reference/com/usebutton/sdk/Button.html)
* Added ability to set your own user ID via [setThirdPartyId](http://building.usebutton.com/button-android/history/2.3.0/reference/com/usebutton/sdk/Button.html\#setThirdpartyId\(java.lang.String\)).
* Improved caching and reduced network traffic

### [2.2.1 Docs](http://building.usebutton.com/button-android/history/2.2.1/reference/com/usebutton/sdk/Button.html)
* Minor bug fix.

### [2.2.0 Docs](http://building.usebutton.com/button-android/history/2.2.0/reference/com/usebutton/sdk/Button.html)
* New card type
* Button text styling

### [2.1.0 Docs](http://building.usebutton.com/button-android/history/2.1.0/reference/com/usebutton/sdk/Button.html)
* Dynamic inventory item cells
* Support for 9-patch backgrounds
* Support for gravity in Button
* Misc bug fixes and performance improvements

### [2.0.1 Docs](http://building.usebutton.com/button-android/history/2.0.1/reference/com/usebutton/sdk/Button.html)
* Option to create, style and add a ButtonDropin by code instead of layout XML.
* Misc bug fixes.

### [2.0.0 Docs](http://building.usebutton.com/button-android/history/2.0.0/reference/com/usebutton/sdk/Button.html)
* Debug logging to verify & debug Button integration
* Full support for grouped inventory, stay tuned for new integrations!
* btn_ namespace on all attributes to avoid collision. Note: breaking change from 1.n.n, see [Integration Docs](https://www.usebutton.com/developers/deep-link-commerce-android/) for details.


### [1.5.0 Docs](http://building.usebutton.com/button-android/history/1.5.0/reference/com/usebutton/sdk/Button.html)
* Grouped inventory commerce card support.

### [1.4.1 Docs](http://building.usebutton.com/button-android/history/1.4.1/reference/com/usebutton/sdk/Button.html)
* Delayed all SDK init until app foreground to support frequent BroadcastReceivers

### [1.4.0 Docs](http://building.usebutton.com/button-android/history/1.4.0/reference/com/usebutton/sdk/Button.html)
* Modest bug fixes and performance improvements

### [1.3.2 Docs](http://building.usebutton.com/button-android/history/1.3.2/reference/com/usebutton/sdk/Button.html)
* Removed obsolete permission

### [1.3.1 Docs](http://building.usebutton.com/button-android/history/1.3.1/reference/com/usebutton/sdk/Button.html)
* Fixed missing dialog background

### [1.3.0 Docs](http://building.usebutton.com/button-android/history/1.3.0/reference/com/usebutton/sdk/Button.html)
* New languages can now be switched on remotely
* Buttons are now cached for fasting loading
* SDK reporting and configuration behaviors can be updated remotely
* Assorted minor performance improvements
* Resolves issue where tapping on a card can cause a crash on Android 4.0

### [1.2.0 Docs](http://building.usebutton.com/button-android/history//reference/com/usebutton/sdk/Button.html)
* DLC Recipient Functionality (Production)
* Button now supports localization for Turkish, Portuguese, Russian & Spanish
* Custom font support for your Button

### [1.1.0 Docs](http://building.usebutton.com/button-android/history/1.1.0/reference/com/usebutton/sdk/Button.html)
* DLC Recipient Functionality (BETA)
* Minor bugfixes
* More reliable fetching of Identifier for Advertiser

### [1.0.0 Docs](http://building.usebutton.com/button-android/history/1.0.0/reference/com/usebutton/sdk/Button.html)
* First public release of the DLC SDK
* Supports Uber ride picker
* Supports generic promotions and install cards
