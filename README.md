# SceneApiAlertTest
A Rect Native demo app using the iOS scenes API. Displaying an Alert when using the iOS scene API in React Native currently does not work. This is because UIApplication.keyWindow is not valid when using the Scene API. This example app points to a fork of `React-Native` which fixes this issue, and demonstrates that it works. 

1. Adds `Application Scene Manifest` to Info.plist. This enables the Scenes API (iOS13+)
2. Uses class SceneDelegate (implementing UISceneDelegate) to handle the React Native setup.
3. UI displays Alert popups in accordance with https://reactnative.dev/docs/alert
4. Using Fork of React Native [found here](https://github.com/mixcloud/react-native/tree/support-scenes-api-alerts), this popup displays. 

