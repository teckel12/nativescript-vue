# NativeScript + Vue

## Installation

- Download/install [Node.js - LTS](https://nodejs.org/en/)
- Download/install [Java SDK - v8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- Download/install **as administrator** [Android Studio](https://developer.android.com/studio/index.html)
- The download & install will take a **long** time as it downloads the entire Internet
- Run Adroid Studio, from the `Configure` menu select `SDK Manager`
- Select Android v7.1.1 to install
- Set environment variable `JAVA_HOME` to `C:\Program Files\Java\jdk1.8.0_161`
- Set environment variable `ANDROID_HOME` to `C:\Users\<your name>\AppData\Local\Android\Sdk`
- Open a new command prompt and run `npm install -g nativescript`
- If you have any hard drive space left, download/install [NativeScript Sidekick](https://www.nativescript.org/nativescript-sidekick)
    - App Name: `NativeScript-Vue`
    - Project Folder: <path>
    - App ID: Auto
    - Project Type: NativeScript + JavaScript
    - Select: `Nagivation Drawer`
    - Click: `Create App`
- Add `NativeScript` extension to Visual Studio Code

 - tns build android --bundle
    - tns build ios --bundle
    - tns run android --bundle
    - tns run ios --bundle
