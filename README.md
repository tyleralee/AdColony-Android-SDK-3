# AdColony Android SDK
* Modified: April 6, 2017
* SDK Version: 3.1.2

## Overview
Increase your revenue with the advertising SDK trusted by the world’s top publishers. AdColony delivers high-definition Instant-Play™ video ads that can be displayed anywhere within your application. AdColony contains V4VC™, a secure system for rewarding users of your app with virtual currency upon the completion of video plays.

For detailed information about the AdColony SDK, see our [Android SDK documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki).

**Note:** The AdColony Compass™ early access program has ended, and we are no longer accepting new partners. Publishers who are currently using those services should email compass@adcolony.com for more details.

## Usage

### Installation

#### Manual

* Drag and drop the adcolony.jar into your project.
* Drag and drop the native libraries your application supports into your project.

#### Via Gradle
* See the [project setup page](https://github.com/AdColony/AdColony-Android-SDK-3/wiki/Project-Setup) on our Wiki.

#### Updating from 2.x:
Please note that updating from our 2.x SDK is not a drag and drop update, but rather includes breaking API and process changes. In order to take advantage of the 3.x SDK, a complete re-integration is necessary. Please review our [documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki) to get a better idea on what changes will be necessary in your app.

### Quick Start
The basics of using the AdColony SDK to serve ads to your users are:
1. Configure the service
1. Request an ad *(We recommend requesting a new ad when an ad expires)*
1. Show the ad

For example:

```Java
AdColonyInterstitial _ad = null;
AdColonyInterstitialListener _listener = null;

void configure() {
    AdColony.configure(activity, null, /*app_id*/, /* zone_id_1, zone_id_2 */);

    _listener = new AdColonyInterstitialListener() {
        @Override
        public void onRequestFilled(AdColonyInterstitial ad) {
            _ad = ad;
        }
    };
}

void request() {
    AdColony.requestInterstitial(/* zone_id_1 */, activity, null);
}

void show() {
    if (_ad != null) {
        _ad.show();
    }
}
```

For detailed information about the AdColony SDK, see our [Android SDK documentation](https://github.com/AdColony/AdColony-Android-SDK-3/wiki).

## Legal Requirements
By downloading the AdColony SDK, you are granted a limited, non-commercial license to use and review the SDK solely for evaluation purposes.  If you wish to integrate the SDK into any commercial applications, you must register an account with AdColony and accept the terms and conditions on the AdColony website.

Note that U.S. based companies will need to complete the W-9 form and send it to us before publisher payments can be issued.

## Contact Us
For more information, please visit AdColony.com. For questions or assistance, please email us at support@adcolony.com.
