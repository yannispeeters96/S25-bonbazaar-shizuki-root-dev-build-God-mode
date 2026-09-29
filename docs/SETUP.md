# Windows development setup

This repository is currently a starting point: it does not yet include an Electron `package.json`, application source, an Android Gradle project, or a Gradle wrapper. As a result, there are no project build or test commands to run yet.

## Prerequisites

- Git for Windows.
- A current Node.js LTS release, including npm, for the planned Electron app.
- Android Studio for the planned Android app. Install the Android SDK and platform tools through Android Studio's SDK Manager. Use the JDK bundled with Android Studio unless the eventual Gradle project specifies another supported version.

## Get the repository

In PowerShell, clone the repository and enter its directory:

```powershell
git clone https://github.com/yannispeeters96/S25-bonbazaar-shizuki-root-dev-build-God-mode.git
Set-Location S25-bonbazaar-shizuki-root-dev-build-God-mode
```

## Build and test status

The app has not been scaffolded, so commands such as `npm install`, `npm run`, or `.\gradlew.bat` are not available in this checkout. Once the relevant manifests, lockfiles, scripts, and Android Gradle wrapper are added, their documented commands should be used to install dependencies, build, and test each target.
