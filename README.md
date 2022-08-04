# Android Studio SEC Fonts

As described in [this issue](https://github.com/OneUIProject/OneUI-Design-Library/issues/58), using one of our One UI libraries (both [sesl](https://github.com/OneUIProject/oneui-core) and the old [Design lib](https://github.com/OneUIProject/OneUI-Design-Library)) will cause issues with the [Android Studio Layout Editor](https://developer.android.com/studio/write/layout-editor). This happens because Samsung's text styles use a custom fontFamily which is not available on AOSP. This repository contains a font pack to replace the AOSP one included in Android Studio.

## Usage
Download the [repo](https://github.com/OneUIProject/android-studio-sec-fonts/archive/refs/heads/main.zip) archive and extract it, navigate to the `plugins/design-tools/resources/layoutlib/data` directory inside your Android Studio folder and replace the "fonts" folder with the one provided in this repo.

Before applying the new font pack we suggest you to make a backup of your current "fonts" folder, since this may break some components such as the Android Studio Updater.
