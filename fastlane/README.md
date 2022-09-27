fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios sync_development_certificates

```sh
[bundle exec] fastlane ios sync_development_certificates
```

Sync development certificates

### ios sync_store_certificates

```sh
[bundle exec] fastlane ios sync_store_certificates
```

Sync store certificates

### ios build_ipa

```sh
[bundle exec] fastlane ios build_ipa
```

Create ipa

### ios test

```sh
[bundle exec] fastlane ios test
```

Runs all the tests

### ios screenshot

```sh
[bundle exec] fastlane ios screenshot
```

Take screenshots

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Upload to TestFlight

### ios upload

```sh
[bundle exec] fastlane ios upload
```

Upload to App Store

### ios release_app

```sh
[bundle exec] fastlane ios release_app
```

Sumbit app to App Store

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
