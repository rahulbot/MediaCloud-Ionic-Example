Example MediaCloud Ionic App
============================

This is a sample [Ionic](http://ionicframework.com) mobile app that shows results from the MediaCloud API.

Installation
------------

1. Install [Node.js](https://nodejs.org/en/)
2. Install Ionic: `npm install -g cordova ionic`
3. Checkout this github repo
4. Copy `www/js/config.js.template` to `www/js/config.js` and edit it to put in your MediaCloud API key

Testing
-------

### In the Browser

To test in the browser on your computer, run `ionic serve` on the terminal in this directory. Use `console.log` in the JS source code to debug things in the browser.

### On an Android device

To run it on your Android phone, you first need to add Android as a platform.  You only need to do 
this once: `ionic platform add android`.  To intsall and open it on your device, do `ionic run android`. To see console log messages, install [Chrome](https://www.google.com/chrome/) and visit `chrome://inspect/devices#devices`, then click `inspect` next to your device on the list.
