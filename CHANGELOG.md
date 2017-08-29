# Change Log

## 3.2.1 (2017/08/28)
* Fixed AAR hosted on Bintray.

## 3.2.0 (2017/08/24)
* Android Oreo compatibility along with several bugs fixes, stabilty and security improvements.
* User experience improvements via enhanced skippability controls and a new mute/unmute feature.
* Post-install events APIs.
* Crash reporting and a new, convenient test mode feature.

## 3.1.2 (2017/04/06)
* Updates for Unity and Adobe Air plugins.

## 3.1.1 (2017/03/28)
* Removed Compass™ APIs.

## 3.1.0 (2017/03/06)
* MOAT viewability support.
* Added viewable impression tracking metric.
* Added support for our dashboard's play frequency zone setting.
* Fixed edge case IllegalStateException and NullPointerException on our MediaPlayer handler when our interstitial Activity is destroyed.
* No longer setting HTTPUrlConnection redirect property globally.
* Lowered our library's minimum SDK version to fix build issues with apps that support earlier versions. Devices below API 14 will still be blocked at runtime from viewing ads.

## 3.0.7 (2016/12/20)
* Increased safety in the case where our interstitial Activity is destroyed while paused due to memory pressure.

## 3.0.6 (2016/11/30)
* Fixed an edge case NPE in our interstitial Activity.
* General stability improvements.

## 3.0.5 (2016/11/09)
* Exposed onLeftApplication and onClicked ad callbacks.
* Fixed possible ad display issue for apps that configure AdColony post onCreate.

## 3.0.4 (2016/10/10)
* Initial public release.
* Fixed issue with our x86 builds.
* Various stability improvements/bug fixes.
* Added messaging features to Compass, which includes both in-app messages and push notifications.

## 3.0.3.2 (2016/09/14)
* Support for vertical ads and improved ad orientation controls.
* Added armeabi-v7a builds.
* Added support for multi-screen.
* Changed package name to com.adcolony.sdk.
* Removed theme requirement for AdColony Activity manifest declarations.

## 3.0.2.2 (2016/08/10)
* Ensure out of date files from earlier SDK installs are invalidated.

## 3.0.2.1: (2016/07/28)
* Added support for native ads.
* Added support for in-app purchase promo ads.
* Added support for custom messages.
* Introduction of AdColony Compass™.
* Various stability improvements/bug fixes.
