# [![Flutter logo][]][flutter.dev]

Flutter is Google's mobile app SDK for crafting high-quality native interfaces on iOS and Android in record time. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Get the Flutter SDK

1.  Download the following installation bundle to get the latest stable release of the [Flutter SDK]:
    For other release channels, and older builds, see the [SDK archive] page.
2.  Extract the zip file and place the contained **flutter** in the desired installation location for the Flutter SDK (for           example, `C:\src\flutter;` do not install Flutter in a directory like `C:\Program Files\` that requires elevated privileges).
3.  Locate the file **`flutter_console.bat`** inside the flutter directory. Start it by double-clicking.

You are now ready to run Flutter commands in the **`Flutter Console!`**

        flutter --version
        flutter doctor
More Detail [Get the Flutter SDK]

## Android setup

### Install Android Studio
1.  Download and install [Android Studio].
2.  Start Android Studio, and go through the ‘Android Studio Setup Wizard’. This installs the latest Android SDK, Android SDK Platform-Tools, and Android SDK Build-Tools, which are required by Flutter when developing for Android.

### Android Simulators

1.  Download components
    Android Studio > Tools > SDK Manager > System Settings > Android SDK
    and download all the required components
2. Create Android simulator
    **Tools > AVD Manager** and click on "**Create Virtual Device....**"
3.  Open Android simulators
    Tools > AVD Manager and click on appropriate AVD and play to launch.
    OR
    To list out all the emulators available - **EMulator -list-avds**
    To open specific emulator- **Emulator-avd [devicename]**

**Note -** Enviornmental setup needed for the android SDK location

## Create the app
1. Open the IDE and select **Start a new Flutter project**.
2. Select **Flutter Application** as the project type. Then click **Next**.
3. Verify the Flutter SDK path specifies the SDK’s location (select **Install SDK**… if the text field is blank).
4. Enter a project name (for example, myapp). Then click **Next**.
5. Click **Finish**.
6. Wait for Android Studio to install the SDK and create the project.

## Run the app

1.  Locate the main Android Studio toolbar:
[![Build Status](https://flutter.dev/assets/tools/android-studio/main-toolbar-857fe8c36d38020e27b502ec643ea8b1716edbe150cc6e39e3560f8fb7bda5b2.png)](https://flutter.dev/docs/get-started/test-drive?tab=androidstudio)
2.  In the **target selector**, select an Android device for running the app. If none are listed as available, select **Tools> Android > AVD Manager** and create one there. For details, see [Managing AVDs].
3.  Click the run icon in the toolbar, or invoke the menu item **Run > Run**.

    After the app build completes, you’ll see the starter app on your device.
[![](https://flutter.dev/assets/get-started/ios/starter-app-5e284e57b8dce587ea1dfdac7da616e6ec9dc263a409a9a8f99cf836340f47b8.png)]



[Flutter logo]: https://flutter.dev/assets/flutter-lockup-4cb0ee072ab312e59784d9fbf4fb7ad42688a7fdaea1270ccf6bbf4f34b7e03f.svg
[flutter.dev]: https://flutter.dev
[Flutter SDK]: <https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.7.8+hotfix.4-stable.zip>
[SDK archive]: <https://flutter.dev/docs/development/tools/sdk/archive>
[Get the Flutter SDK]:<https://flutter.dev/docs/get-started/install/windows#get-the-flutter-sdk>
[Android Studio]:<https://developer.android.com/studio>
[Managing AVDs]:<https://developer.android.com/studio/run/managing-avds>
