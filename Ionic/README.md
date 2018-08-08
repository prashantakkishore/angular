# Ionic
This uses Ionic and Cordova framewpork to build apps in Angular and deploy 
to native environment like Android and IOS
* Ionic: https://ionicframework.com/
* Cordova: https://cordova.apache.org/

## Setup

* Run `npm install -g ionic cordova` to install `ionic` and `cordova`
* Run `ionic` to see all commands.
* Run `ionic start --list` to see all templates.
* Run `ionic cordova platform add android` or `ionic platform add android` (older versions)  to add android specific environment, so it can run in native android.
* Run `ionic cordova build android` or `ionic build android` to build native android app, this depends on __Android SDK__ installed.
* Run `ionic cordova run android` or `ionic build android` to run on actual devide which should be connected, this depends on __Android SDK__ installed.

## Setup Android SDK

1. Download latest studio and install https://developer.android.com/studio/
2. Accept licenses : Run `$ANDROID_HOME/tools/bin/sdkmanager --licenses` and accept all licenses.

## Setup Android device

1. Connect phone using USB
2. Enable USB debugging or just and run `ionic cordova run android` to run on device cordova will prompt and ask for permission to start USB debuggging if not started by default.

## Setup IOS device
Coming Soon ...