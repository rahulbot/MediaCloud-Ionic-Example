Example MediaCloud Ionic App
============================

This is a sample [Ionic](http://ionicframework.com) mobile app that shows results from the MediaCloud API.

Installation
------------

1. Install [Node.js](https://nodejs.org/en/)
2. Install Ionic: `npm install -g ionic cordova`
3. Checkout this github repo
4. Copy `www/js/config.js.template` to `www/js/config.js` and edit it to put in your MediaCloud API key

Testing
-------

### In the Browser

To test in the browser on your computer, run `ionic serve` on the terminal in this directory. This will open your browser to a webpage showing your app running. Use `console.log("some message")` in the JS source code to debug things in the browser.  Don't be surprised if the results don't come back in the browser (this is some Chrome cross-scripting permissions problem)... it works on the phone.

### On an iOS device

To run it on your iOS phone, you first need to add iOS as a build platform.  You only need to do this once: `ionic platform add ios`.  To install and open it on your device, do `ionic run ios`. This will create and ios project in `platforms/ios/`.  Open the `.xcodeproj` project file in with xCode.  Then click the run button in xCode and it should build and run in a simulator.

### On an Android device

To run it on your Android phone, you first need to add Android as a build platform.  You only need to do this once: `ionic platform add android`.  To install and open it on your device, do `ionic run android`. To see console log messages, install [Chrome](https://www.google.com/chrome/) and visit `chrome://inspect/devices#devices`, then click `inspect` next to your device on the list.
