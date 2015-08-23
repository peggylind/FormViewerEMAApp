Form Viewer App
===========

FormBuilder is a dynamic form building web application that works with dynamic forms and provides sharing functionality. It communicates to a Java Backend located in FormBuilderBackend repo.

### Getting Started
1. Run `bower install`. This uses `bower.json` and install local dependencies.

2. Run `ionic serve`. This uses `ionic.xml` and will serve as local node server. Live updates when you make changes to the code.

3. Add the follow plugins using `cordova plugin add <PLUGIN_NAME>`
  - https://github.com/wildabeast/BarcodeScanner.git (NOTE: Only needed if planning to use QR Code component in deployed mobile application)
  - cordova-plugin-whitelist

4. Run `cordova platform add android` or  `cordova platform add ios`

5. Run `ionic resources` to generate icons and splash screens from resources/icon.png and resources/splash.png

6. Run `cordova run android` or  `cordova run ios`
