# react-native-action-sheet-module
ReactNative RNActionSheet extended
Version 0.0.1

## Installation

```bash
npm install --save react-native-action-sheet-module
```
```bash
react-native link react-native-action-sheet-module
```

## Usage
```js
// Import
import ShareModule from 'react-native-action-sheet-module';
```

This package exists to replace Share for iOS. It fixes some bugs.
[Original documentation](https://facebook.github.io/react-native/docs/share.html)

## Fixes
- Sharing image as base64. Facebook Messenger didn't except NSData, it does accept a UIImage