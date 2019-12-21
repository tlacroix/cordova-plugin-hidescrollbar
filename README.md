# cordova-plugin-hidescrollbar

This plugin allows you to hide the scrollbar in an iOS app.

```
document.addEventListener("deviceready", onDeviceReady, false);
function onDeviceReady() {
    plugins.hideScrollbar.hide(function(){
        // Success
    });
}
```

## Supported platforms

- iOS

## Installation

    cordova plugin add cordova-plugin-hidescrollbar

## Examples

### Hide the scrollbar

```
plugins.hideScrollbar.hide(function(){
    // Success
});
```

### Show the scrollbar

```
plugins.showScrollbar.hide(function(){
    // Success
});
```