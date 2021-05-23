# react-native-app-nativepack


HMR does not work without hermes.
Reproduce:
- npm install
- npm start
- npm run android

change some code.

[Console] Loading HMR update chunk failed: [TypeError: null is not an object (evaluating 'this["webpackHotUpdatemyapp"]')] 
