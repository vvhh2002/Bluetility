fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew cask install fastlane`

# Available Actions
## Mac
### mac prepare_minor_version
```
fastlane mac prepare_minor_version
```

### mac prepare_bugfix_version
```
fastlane mac prepare_bugfix_version
```

### mac build_release
```
fastlane mac build_release
```
Increments the build number, builds, and notarizes the Release configuration of the app.

----

This README.md is auto-generated and will be re-generated every time [fastlane](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
