# Setting up React Native and Android Studio

A short guide to setup environment for React Native and Android Studio for mobile app development

> It is always best to follow the [original documentation](https://reactnative.dev/docs/environment-setup?guide=native&os=linux "Official documentation for setting up React Native environment") because they are regularly updated and maintained. This is created for my own quick reference to setting up React Native in the future which also covers some possible errors one can face along the way.

### Required Dependencies

> **Note:** For Linux, you can directly install respective dependencies from your package manager. For other machines such as Windows or Mac, you can manually download and install from below provided official websites.

1. **[Node](https://nodejs.org/en/download "Download Node.js for your machine")** (version 16 or newer)
2. **[Java Development Kit](https://adoptium.net/temurin/releases/?version=11 "Download OpenJDK11 for your machine")** (OpenJDK version 11 is recommended, others can cause issues)
3. **[Android Studio](https://developer.android.com/studio "Download Android Studio for your machine")** (latest stable release))
4. **[React Native CLI](https://reactnative.dev/ "React Native Official Site")** (doesn't have to be installed manually, will be automatically installed at runtime while running your React Native app)

### Android Studio Environment Setup

> If you are new to Android Studio and haven't used it before, I recommend you referring to original documenttion as it contains detailed steps on what to do. This is just for a quick reference.

- Make sure to select `Android SDK`, `Android SDK Platform`, and `Android Virtual Device` while installing Android Studio.
- Install `Android 13 (Tiramisu)` SDK (recommended) from the SDK Manager in Android Studio Configuration. While doing this, make sure to tick check the "**Show Package Details"** option in "SDK Platforms" tab and then ensure that `Android SDK Platform 33` and `Intel x86 Atom_64 System Image` or `Google APIs Intel x86 Atom System Image` is selected. also, make sure to select version `33.0.0` in "SDk Tools" tab. Finally click "**Apply"** to download and install Android SDK and related build tools.
- You cna also create a `Virtual Android Emulator` from the Virtual Device Manager in Android Studio Configuration to run and test the React Native app you've created, but read this article till end where I'll be sharing some important tips related to this.
