# improved-barnacle
This repository is based on my practice using react-native real estate application

### Getting Started
1. ``npx create-expo-app@latest``
2. ``react_native_restate``
3. Reset the project ``npm run reset-project``

### Setting up routes
#### File based routing
File structure
* app
  * _layout.tsx
  * sign-in.tsx
  * (root)
    *  (tabs)
        * explore.tsx
        * index.tsx
        * profile.tsx        
    *  properties
        * [id].tsx

## Setting up theme using NativeWind using expo
### Installation with Expo
1. Install Nativewind
You will need to install nativewind and its peer dependencies tailwindcss, react-native-reanimated and react-native-safe-area-context.   
 
  ``` npm install nativewind react-native-reanimated react-native-safe-area-context ```
  ``` npm install --dev tailwindcss@^3.4.17 prettier-plugin-tailwindcss@^0.5.11 babel-preset-expo ```

  
   
