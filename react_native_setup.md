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

### Environment Path Variables Setup

This step is not difficult at all but many mess up at this step because this can differ from OS to OS. For example, in WIndows, you need to add Environment Path Variables from the **"User Accounts"** in **Control Panel** but in case of MacOS and Linux, it's slightly different. In fact, this step for Linux even varies from distro to distro depending on what shell you use. I, myselef use `fish` shell instead of Linux's default `bash` shell and hence, it was a bit different from me. But remember, this is not difficult at all and takes just a few minutes. So search this step for the operating system you're using.

You need to setup environment variables and path for `Android SDK`, `Virtual Emulator`, and `Platform Tools`.

### Watchman Installation

Watchman is not mandatory to install but is recommended for better performance, compatibility, and development experience. So you can install it with the help of their [official documentation](https://facebook.github.io/watchman/docs/install#buildinstall "Watchman Installation Guide").

### Use JDK11

I already mentioned above that jdk11 is necessary to run React Native and Android Studio properly but sometimes there might be more than two jdk in your machine and jdk11 might not have been selected. This can be a headache, so ensure that jdk11 is selected and in use no matter if other versions are installed too. Now again, you need to search this for the OS you're using as the method varies from OS to OS. In my case, I am using Arch linux, so I used this tutorial to select JDK11 for use.

### Conclusion

With this, your React Native and Android Studio environment is hopefully properly set up. Now you should be able to properly run React Native projects on your machine, but wait, there are still a few things you need to know before you start creating and developing React Native apps. So you must read my another React Native guide to officially start creating and developing React Native apps.
