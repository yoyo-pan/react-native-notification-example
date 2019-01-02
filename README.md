# React Native Notification Example (Android)

事前安裝參考步驟，以[macOS + Android](https://facebook.github.io/react-native/docs/getting-started)為例 

若要在windows環境開發請切換官網的Development OS至windows即可

  - [Node.js](https://facebook.github.io/react-native/docs/getting-started#node-watchman)
  - [React Native Cli](https://facebook.github.io/react-native/docs/getting-started#the-react-native-cli)
  - [Java 8](https://facebook.github.io/react-native/docs/getting-started#java-development-kit)
  - [Android Studio](https://facebook.github.io/react-native/docs/getting-started#1-install-android-studio)
  - [設定$HOME](https://facebook.github.io/react-native/docs/getting-started#3-configure-the-android-home-environment-variable)

[手機開啟開發者模式](https://facebook.github.io/react-native/docs/getting-started#preparing-the-android-device)
請務必使用實體手機測試，virtual device可能會收不到notification

[Firebase設定](https://console.firebase.google.com/project/reactnativebletest/settings/general/android:com.reactnativebletest?hl=en) 一次性設定，只需在code中follow firebase的專案ID(reactnativebletest)即可

# 啟動步驟

  - cd react-native-notification-example
  - npm install
  - react-native run-android