# Fastlane 101

## Fastlane for Android (macOS)
   
### 1. Install Homebrew
   
```shell script
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
   
### 2. Install Fastlane
   
```shell script
brew install fastlane
````

## Setting up fastlane

### Navigate your terminal to your project's directory and run

```shell script
fastlane init
```

### Enter your package

Output

```shell script
➜  fastlane101 git:(master) ✗ fastlane init
[✔] 🚀 
[✔] Looking for iOS and Android projects in current directory...
[00:07:33]: Created new folder './fastlane'.
[00:07:33]: Detected an Android project in the current directory...
[00:07:33]: -----------------------------
[00:07:33]: --- Welcome to fastlane 🚀 ---
[00:07:33]: -----------------------------
[00:07:33]: fastlane can help you with all kinds of automation for your mobile app
[00:07:33]: We recommend automating one task first, and then gradually automating more over time
[00:07:33]: 
[00:07:33]: To avoid re-entering your package name and issuer every time you run fastlane, we'll store those in a so-called Appfile.
[00:07:33]: Package Name (com.krausefx.app): com.prongbang.fastlane101
```

