## NativeInsomia
This Mendix widget utilizes the @sayem314/react-native-keep-awake library to prevent the device screen from going to sleep while your app is running. This is beneficial for scenarios where you require the app to stay visible for extended periods without user interaction, such as during navigation or video playback.

## Usage
![ins](https://github.com/aerborne/mendix-native-insomnia/assets/28711216/08a2e72d-9756-46e0-a5c2-11d92d7c2754)



## Development and contribution

1. Install NPM package dependencies by using: `npm install`. If you use NPM v7.x.x, which can be checked by executing `npm -v`, execute: `npm install --legacy-peer-deps`.
1. Run `npm start` to watch for code changes. On every change:
    - the widget will be bundled;
    - the bundle will be included in a `dist` folder in the root directory of the project;
    - the bundle will be included in the `deployment` and `widgets` folder of the Mendix test project.
      
Karl A Baldelomar - Rapid App Werks
