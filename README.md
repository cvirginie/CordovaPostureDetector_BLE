# CordovaPostureDetector_BLE
A cordova app to receive data from Arduino Posture Detector in BLE

The plugin used to communicate in BLE : https://github.com/don/cordova-plugin-ble-central/


### Install the app on iOS :

Clone the repo

`git clone https://github.com/cvirginie/CordovaPostureDetector_BLE.git`


Navigate to the directory

`cd CordovaPostureDetector_BLE/`


Add the ios platform (not tested on Android)

`cordova platform add ios`


Build 

```
cordova build ios
or
cordova build ios --buildFlag='-UseModernBuildSystem=0'
```

Open the project in XCode and deploy on your device.
