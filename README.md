# cordova-plugin-ios-decimal-keyboard

A simple plugin to allow the decimal point to be accessible via the keyboard in iOS / iPhone.

<img src=https://github.com/gbrits/cordova-plugin-ios-decimal-keyboard/blob/master/screenshots/keyboard.jpg width=25% height=25% />

### Installing

```
cordova plugin add cordova-plugin-ios-decimal-keyboard
```
## Usage

```
<input type="text" pattern="[0-9]*" decimal="true">
```

### Multiple decimals

```
<input type="text" pattern="[0-9]*" decimal="true" allow-multiple-decimals="true">
```

## Known Issues
* Screen rotation unsupported.
