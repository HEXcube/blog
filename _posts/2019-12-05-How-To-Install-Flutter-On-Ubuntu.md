---
layout: post
title: How to install Flutter on Ubuntu
---

The easiest method to install Flutter or Dart on Ubuntu is to use the officially recommended [Ubuntu Make snap](https://github.com/ubuntu/ubuntu-make). No need to download Flutter as zip, try to [manually install it](https://flutter.dev/docs/get-started/install/linux), add PPAs or fiddle with PATHs. Ubuntu Make'll automatically download the latest Flutter SDK, install it along with all the necessary dependencies and setup the correct PATH variables.

Step 1: Install Ubuntu Make snap
-------------
Run this command:

    snap install --classic ubuntu-make

Step 2: Install Flutter SDK
-------------
Run this command:

    umake dart flutter-sdk

Step 3: Install Android Studio
-------------
Install Android Studio to supply Flutter's Android platform dependencies. [How to install Android Studio on Ubuntu?](https://askubuntu.com/questions/634082/how-to-install-android-studio-on-ubuntu/941222#941222)

Step 4: Install an editor
-------------
To enable Flutter support in Android Studio, IntelliJ or Visual Studio Code follow [this guide](https://flutter.dev/docs/get-started/editor?tab=vscode).
