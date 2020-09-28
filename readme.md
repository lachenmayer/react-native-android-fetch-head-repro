This a minimal repro created using `create-react-native-app` to demonstrate https://github.com/facebook/react-native/issues/30055.

To reproduce, run this app on an Android device using `yarn android`.

**Expected**: The app `console.warn`s a successful response object.

**Actual**: The app `console.error`s the message "Network request failed".

You can observe the correct behavior on iOS.