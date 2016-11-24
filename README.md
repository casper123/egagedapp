# Egaged Test App

  - Ionic app in version 1.3
  - Side menu enabled
  - Facebook login integrated
  - Test with both android and ios

### Installation

Facebook AppID: 598814510268635
Facebook App Name: NerdHyve

Install the dependencies, plugins and add platforms

```sh
$ cordova plugin add cordova-plugin-facebook4 --save --variable APP_ID="598814510268635" --variable APP_NAME="NerdHyve"
$ ionic state reset
$ ionic platform add android
$ ionic platform add ios
$ ionic build android
$ ionic build ios
```

### Plugins

App is currently extended with the following plugins

* Facebook plugin by telerik verified plugins
* pre installed plugins by ionic