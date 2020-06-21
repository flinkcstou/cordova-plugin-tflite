# Changelog

## MASTER BRANCH (RECOMMENDED) - UNRELEASED
- [PR #615](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/615) - Correctly handle torch mode in getFlashMode

## v0.12.0 - May 4, 2020 - LATEST RELEASED VERSION
- [PR #605](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/605) - Improve memory usage when capturing multiple photos for both Android and iOS
- [PR #587](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/587) - Add video recording functionality for Android
- [PR #599](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/599) - Use androidx package instead of legacy android support package
- [PR #606](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/606) - Remove `android:required` from manifest to avoid conflict with other plugins

## v0.11.2 - February 12, 2020
- [PR #582](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/582) - Add support for Android devices without Autofocus which can increase the amount of devices for which app installation is allowed by about (~4k at time of)
- [PR #583](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/583) - Fix typescript error CameraPreview.d.ts is not a module 

## v0.11.1 - November 19, 2019
- [PR #573](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/573) - Fetch number of cameras immediately before switching cameras in Android
- [Issue #428](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/issues/428) - Fix mispelling of `continuous` within iOS source code for focus modes (was `cotinuous` before)
- [PR #568](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/568), [PR #570](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/570) - Resolves plugin interaction issues when toBack is set and other plugins like cordova-plugin-googlemaps are changing the layout

## v0.11.0 - May 20, 2019
- [PR #525](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/525) - Add function `takeSnapshot` for quick image captures
- [PR #441](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/441) - Add android only option `storeToFile` for storage in temporary file instead of base64
- [PR#524](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/524) - Add iOS support for `storeToFile`
- [PR #396](http://gitlab.greetgo/aix/card_reader/cordova-plugin-tflite/pull/396) - Add function `getCameraCharacteristics`
- Allow `startCamera` to allow no options object when only callback is provided
- Add Changelog

## v0.10.0 - June 13, 2018
- Merge in features and fixes from various forks

## v0.9.0 - May 9, 2017

## v0.0.8 - March 30, 2015

## v0.0.6 - February 4, 2015

## v0.0.3 - January 12, 2015

## v0.0.2 - January 7, 2015
