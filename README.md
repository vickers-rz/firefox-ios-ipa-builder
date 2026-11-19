# Firefox iOS 160.1 IPA Builder

Build unsigned Firefox for iOS from Mozilla's official `firefox-v160.1` tag with GitHub Actions on the `xcode-27` macOS runner.

## Goal
- Physical device arm64 app for iPhone 14 (iOS 17.7)
- Reproducible unsigned `.ipa` and SHA-256 checksum
- No Apple ID, certificates, private files, or signing keys in GitHub
- LiveContainer compatibility is **not guaranteed**; test separately

## Build
Use **Actions → Build Firefox iOS 160.1 unsigned IPA → Run workflow**. Download the artifact after a successful run. The artifact ZIP contains the IPA and checksum.

Official source: https://github.com/mozilla-mobile/firefox-ios/tree/firefox-v160.1

Local workspace: `~/Documents/iOS_APP/apps/FirefoxIOS`.
