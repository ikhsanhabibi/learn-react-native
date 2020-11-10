# learn-react-native

- React-Native: Module AppRegistry is not a registered callable module: killall -9 node

# Create app
- expo init AwesomeProject
- npm run eject
- pod install (cd ios folder)

- module unable : npm install <module>

- undefined is not an object(evaluating '_ExpoBarCodeScannerModule.default.BarCodeType')
https://github.com/expo/expo/issues/5215 : pod install

- Nav common mistakes : https://reactnavigation.org/docs/en/common-mistakes.html

- createAppContainer is from "react-native"

- no border TextInput : https://stackoverflow.com/questions/46015572/react-native-bordered-text-input

- center TextInput : https://stackoverflow.com/questions/47203728/center-a-text-in-the-screen-with-react-native

- manage state : https://snack.expo.io/rkDlTKNU-

- Forms: https://medium.com/@muratsert1453/react-native-forms-a0e174ca134f

- passing value between two screen : https://www.javatpoint.com/react-native-passing-value-between-screen

- destructuring : https://dev.to/sarah_chima/object-destructuring-in-es6-3fm

- got matching object : https://stackoverflow.com/questions/13964155/get-javascript-object-from-array-of-objects-by-value-of-property

- changing state : https://reactjs.org/docs/state-and-lifecycle.html#do-not-modify-state-directly and https://stackoverflow.com/questions/46619669/how-to-change-state-inside-the-function

- barcode scanner : https://stackoverflow.com/questions/53141088/writing-type-or-data-of-scanned-barcode-into-text-inputs-on-react-native

- Firebase Realtime Database With React Native : https://medium.com/mindorks/firebase-realtime-database-with-react-native-5f357c6ee13b

- react native camera : https://reactnativemaster.com/react-native-camera-expo-example/

- firebase(How to set a custom ID when pushing a new object into Firebase) : https://stackoverflow.com/questions/18050856/how-to-set-a-custom-id-when-pushing-a-new-object-into-firebase

- navigating to other screen : https://snack.expo.io/?platform=android&name=First%20navigation&dependencies=react-navigation%40%5E4.0.10%2Creact-navigation-tabs%40%5E2.5.6%2Creact-navigation-stack%40%5E1.10.3%2Creact-navigation-drawer%40%5E2.3.3&sourceUrl=https%3A%2F%2Freactnavigation.org%2Fexamples%2F4.x%2Fnew-screen.js

Learning react native :
- https://www.tutorialspoint.com/react_native/react_native_state.htm
- https://www.javatpoint.com/react-native-adding-icons-at-bottom-of-tab-navigation

Ionics
- https://ionicons.com/

Ebook
- https://books.goalkicker.com/ReactNativeBook/

# Redux :
- https://www.tutorialspoint.com/redux/index.htm 
- https://codesandbox.io/s/github/reduxjs/redux/tree/master/examples/counter

# React Native on Windows
- Android emulator-5554 offline: https://stackoverflow.com/questions/18006118/android-emulator-offline-to-online-mode
- Gitignore: https://www.toptal.com/developers/gitignore


# Expo
npm install -g expo-cli
expo --version

- create a new project: npx expo-cli init food (on Windows, please use git CMD, not git bash)


# Problem after creating a new project
- Expo Developer Tools is disconnected from Expo CLI. Use the expo start command to start the CLI again: https://stackoverflow.com/questions/53474846/expo-developer-tools-is-disconnected-from-expo-cli-use-the-expo-start-command-t/56405514

## React Navigation
Installation
1. Install React Navigation
npm install react-navigation

2. Install Dependencies
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

3. Install React Navigation Stack
npm install react-navigation-stack @react-native-community/masked-view

4. Start the app and clear cache with npm start -c

Errors?
If you are still seeing errors and complaints about packages, do the following:
1. rm -r node_modules
2. rm package-lock.json
3. expo upgrade
4. npm start -c

Update Imports
Our imports in the upcoming lecture will now look like this:

import { createAppContainer } from 'react-navigation';
import { createStackNavigator } from 'react-navigation-stack';

# Stackoverflow
- Three dots: https://stackoverflow.com/questions/31048953/what-do-these-three-dots-in-react-do
- react navigation : https://reactnavigation.org/docs/getting-started/
- `createStackNavigator()` has been moved to `react-navigation-stack`: https://stackoverflow.com/questions/57817573/createstacknavigator-has-been-moved-to-react-navigation-stack
- expo icon: https://github.com/expo/vector-icons
- Change app background color in React Native: https://stackoverflow.com/questions/50619693/change-app-background-color-in-react-native
- axios API: https://github.com/axios/axios
- Recycle list (better performance) : https://github.com/Flipkart/recyclerlistview
