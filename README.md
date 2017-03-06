AdColony Android SDK
==================================
Modified: March 6, 2017<br>
SDK Version: 3.1.0

Getting Started with AdColony:
----------------------------------
First time and returning users should review the [documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki).

Thanks for joining AdColony on the next step in mobile monetization. We're committed to giving our partners the tools to grow, engage, and monetize successfully. Our Aurora SDK contains huge leaps forward in our capabilities, with benefits for both publishers and advertisers. We would also like to highlight the addition of AdColony Compass™ to our suite of products. AdColony Compass provides publishers with intuitive marketing tools to maximize the value of users throughout your app economy, like creating rewards, achievements, push notifications and in-app messaging.

AdColony Compass™ provides the tools to increase user engagement through targeted user communications, achievements and rewards.

Combined with AdColony’s award-winning Instant-Play™ HD video ads, Compass™ features can also stimulate monetization within apps. Compass™ tools allow publishers to incentivize desired user behaviors and improve KPI's for apps without heavy development work or altering carefully balanced in-app economies.

The Compass™ early access program has ended, and we are no longer accepting new partners for Compass™ access. Publishers who are currently using AdColony Compass™ services should email compass@adcolony.com for more details.


Updating from Our 2.x SDK:
----------------------------------
Updating from our AdColony 2.x SDK is not a drag and drop update, but rather includes breaking API and process changes. Please review our [documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki) to get a better idea on what changes will be necessary in your app.

Download:
----------------------------------
####Manually:####
Click the "Download ZIP" button above to download our SDK distribution manually.

####Via Gradle:####
See the [project setup page](https://github.com/AdColony/AdColony-Android-SDK-3/wiki/Project-Setup) on our Wiki.

Change Logs:
----------------------------------
####3.1.0####
1. Added capability to retrieve the net CPM bid value for a zone's next ad. <br>
2. MOAT viewability support. <br>
3. Added viewable impression tracking metric. <br>
4. Added support for our dashboard's play frequency zone setting. <br>
5. Fixed edge case IllegalStateException and NullPointerException on our MediaPlayer handler when our interstitial Activity is destroyed.<br>
6. No longer setting HTTPUrlConnection redirect property globally. <br>
7. Lowered our library's minimum SDK version to fix build issues with apps that support earlier versions. Devices below API 14 will still be blocked at runtime from viewing ads.

===
####3.0.7####
1. Increased safety in the case where our interstitial Activity is destroyed while paused due to memory pressure.

===
####3.0.6####
1. Fixed an edge case NPE in our interstitial Activity.<br>
2. General stability improvements.

===
####3.0.5####
1. Exposed onLeftApplication and onClicked ad callbacks.<br>
2. Fixed possible ad display issue for apps that configure AdColony post onCreate.

===
####3.0.4####
1. Initial public release.<br>
2. Fixed issue with our x86 builds.<br>
3. Various stability improvements/bug fixes.
4. Added messaging features to Compass, which includes both in-app messages and push notifications.

===
####3.0.3.2####
1. Support for vertical ads and improved ad orientation controls.<br>
2. Added armeabi-v7a builds.<br>
3. Added support for multi-screen.<br>
4. Changed package name to com.adcolony.sdk.<br>
5. Removed theme requirement for AdColony Activity manifest declarations.

===
####3.0.2.2####
1. Ensure out of date files from earlier SDK installs are invalidated.

===
####3.0.2.1:####
1. Added support for native ads.<br>
2. Added support for in-app purchase promo ads.<br>
3. Added support for custom messages.<br>
4. Introduction of AdColony Compass™.<br>
5. Various stability improvements/bug fixes.

Legal Requirements:
----------------------------------
By downloading the AdColony SDK, you are granted a limited, non-commercial license to use and review the SDK solely for evaluation purposes.  If you wish to integrate the SDK into any commercial applications, you must register an account with AdColony and accept the terms and conditions on the AdColony website.

Note that U.S. based companies will need to complete the W-9 form and send it to us before publisher payments can be issued.


Contact Us:
----------------------------------
For more information, please visit AdColony.com. For questions or assistance, please email us at support@adcolony.com.
