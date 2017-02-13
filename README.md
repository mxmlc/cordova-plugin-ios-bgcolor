# cordova-plugin-ios-bgcolor
This plugin activates the color changing of UIWebView and UIScrollView background color.

## Installation

    cordova plugin add https://github.com/mxmlc/cordova-plugin-ios-bgcolor


Preferences
-----------

#### config.xml

-  __BackgroundColor__ Set the app's background color. Supports a four-byte hex
   value, with the first byte representing the alpha channel, and standard RGB
   values for the following three bytes. This example specifies blue:

        <preference name="BackgroundColor" value="0xff0000ff"/>


Permissions
-----------

#### config.xml

        <feature name="BackgroundColor">
            <param name="ios-package" value="CDVBackgroundColor" onload="true" />
        </feature>


Description
-----------

The plugin allows to change the UIWebView and UIScrollView. By default, UIScrollView
is gray and cannot be change without intervention in iOS code.


Supported Platforms
-------------------

- iOS

