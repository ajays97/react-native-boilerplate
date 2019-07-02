# React Native BoilerPlate 2019

- React Native version: 0.59.9
- React Native navigation from Wix 2.0
- Font: _Nunito_

## Getting started

```
$ yarn install
```

## Rename project (optional)

### Install React Native Rename Globaly

```
$ yarn global add react-native-rename
```

### Rename the project

```
$ react-native-rename <newName>
```

## launch iOS

```
$ cd ios && pod install
$ react-native run-ios
```

###### If you have an Error at building app iOS (Mac's Xcode 10 users)

Go to Xcode, File -> Project Settings then change the Build System Default to Legacy Build System.

## launch Android

`$ yarn run android-build` (command to generate the necessary bundle for android)

## Libreries used

###### Flux architecture

- [Redux](https://redux.js.org/introduction)

###### Routing and navigation

- [React Native Navigtation from Wix V2](https://github.com/wix/react-native-navigation)

###### Version control

- [Pre Commit](https://github.com/pre-commit/pre-commit)

## Style guidelines

- https://eslint.org/
- https://github.com/airbnb/javascript
- https://github.com/airbnb/javascript/tree/master/react
- https://prettier.io/

:v: **Enjoy!**

TODO:

- Install react-native-vector-icons
- redux example (clean reducers on logout)
- redux-form example with material-text-field (validations with spanish/english configuration in config.js)
- login/logout example with asyncStorage example
- actions with await - no use cb
- defaultStyleCommonComponents in theme
- example of use modal with react-native-navigation
- example of use component didAppear with redux-form chageFieldValue
