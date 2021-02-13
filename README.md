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

```shell script
[00:07:33]: Package Name (com.krausefx.app): com.prongbang.fastlane101
```

### Output

```
android-fastlane-101
├── Gemfile
├── Gemfile.lock
├── app
|   ├── ...
│   └── build.gradle
├── build.gradle
├── fastlane
│   ├── Appfile
│   └── Fastfile
└── ...
```

- `Gemfile`             - Define your dependency on fastlane
- `Gemfile.lock`        - Define Version Control
- `fastlane/Appfile`    - Defines configuration information that is global to your app
- `fastlane/Fastfile`   - Defines the "lanes" that drive the behavior of fastlane
- `fastlane/Pluginfile` - Define your plugin on fastlane
  
### Add Firebase App Distribution

```shell script
fastlane add_plugin firebase_app_distribution
```
