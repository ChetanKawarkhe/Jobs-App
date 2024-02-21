# Expo Router Example

Use [`expo-router`](https://docs.expo.dev/router/introduction/) to build native navigation using files in the `app/` directory.

## 🚀 How to use

```sh
npx create-expo-app -e with-router
```
### if not able to run project in expo go.  This will globally install expo cli. 
```sh
  npm install -g expo-cli
```

## Then expo-cli start --tunnel. to run the application on phone.
```sh
  expo-cli start --tunnel
```

## 📝 Notes

- [Expo Router: Docs](https://docs.expo.dev/router/introduction/)

## TouchableOpacity
  - interactive element that fades in opacity when pressed. We can use TouchableOpacity component.
## ActivityIndicator
  - used to show spinner or loading.
## Flatlist component
  - it is used to render a long list of items that needs to be scrolled efficiently.
  - it is like map function in react.
    - extra features:
      - optimized scroll performance.
      - item seperation.
  - Flatlist:-
    - for larger lists with smooth scrolling.
  - map function
    - for smaller lists.
## ScrollView
  - it is like a box that can hold multiple components and views providing a scrolling container for them.
  - similar as html ```css overflow: scroll ```  
  - allows us to easily navigate through large list of items or large amount of content in app.
## SafeAreaView
  - This ensures that the app content is displayed within the visible area, making your app more accessible. 
  - renders app content without being covered by the device's hardware like notch/camera etc.

# packages
  ### expo-font
    - custom fonts.
  ### axios
    - api requests.
  ### react-native-env
    - allows us to work with enviornment variables.
  