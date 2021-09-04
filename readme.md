# Flutter

## Introduction to Flutter

Flutter is Google's official UI toolkit for building beautiful, natively compiled applications for [mobile](https://flutter.dev/docs), [web](https://flutter.dev/web), [desktop](https://flutter.dev/desktop), and [embedded](https://flutter.dev/embedded) devices from a single codebase, which essentially means you can run your app on Windows, iOS and Web all from a single codebase and save up a lot of time and resources.

Flutter offers you:

- Fast Development
- Flexible and beautiful UI
- Native Performance

Here is a [video](https://www.youtube.com/watch?v=fq4N0hgOWzU) that gives an overview of flutter.

## Setup Flutter on your machine

### For Windows:

1.  Download the flutter SDK from [here](https://storage.googleapis.com/flutter_infra_release/releases/stable/windows/flutter_windows_2.2.3-stable.zip)
2.  **Important** Follow the steps listed [here](https://flutter.dev/docs/get-started/install/windows#update-your-path) to update your system path **Important**
3.  Download and install Android Studio from [here](https://developer.android.com/studio). You will be using Android Studio to create a virtual android machine (to test your apps on). It can also be used to code, but we recommend using [VS Code](https://code.visualstudio.com/) for that.
4.  Open your command prompt (cmd) and run `flutter doctor --android-licenses`
5.  Open your command prompt (cmd) and run `flutter doctor`, this should show an output like this:

```
Doctor summary (to see all details, run flutter doctor -v):
[√] Flutter (Channel stable, 2.2.3, on Microsoft Windows [Version 10.0.19041.630], locale en-IN)
[√] Android toolchain - develop for Android devices (Android SDK version 30.0.2)
[√] Chrome - develop for the web
[√] Android Studio (version 4.1.0)
[√] IntelliJ IDEA Community Edition (version 2021.1)
[√] VS Code (version 1.59.1)
[√] Connected device (2 available)
```

### For MacOS:

1.  Download the flutter SDK from [here](https://storage.googleapis.com/flutter_infra_release/releases/stable/macos/flutter_macos_2.2.3-stable.zip)
2.  Extract the zip file onto your system, or open terminal and:

```
cd ~/development
unzip ~/Downloads/flutter_macos_2.2.3-stable.zip
```

3. Add the flutter tool to your path:
   `` export PATH="$PATH:`pwd`/flutter/bin" ``
   Note: **Recommended** This command sets your `PATH` variable for the _current_ terminal window only. To permanently add Flutter to your path, see [Update your path](https://flutter.dev/docs/get-started/install/macos#update-your-path).

4. Install the latest version of **Xcode** from the [Mac App Store](https://apps.apple.com/us/app/xcode/id497799835)
5. Set up the iOS simulator `open -a Simulator`

### Creating your first flutter app

Congrats! You are now all setup to create you very first flutter app.
To create your first app, open terminal/cmd and run: `flutter create my_app`

1. A folder will get created, open this folder in android studio or VS Code
2. Click `Run`
3.
