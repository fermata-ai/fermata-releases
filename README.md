# Fermata releases

Build artifacts for the Fermata desktop app. No source lives here.

Download the latest DMG from [Releases](https://github.com/fermata-ai/fermata-releases/releases/latest).

**First install.** The app is not signed by an Apple Developer ID yet, so macOS asks once. Open the DMG,
drag Fermata to Applications, and double-click it. When macOS says it cannot verify the app, choose
Done, open System Settings, go to Privacy & Security, scroll down, and press **Open Anyway**. That is
needed once. Every later version arrives through the in-app Update button, with no dialog.

**If it says the app "is damaged".** It is not. That message comes from a build before 0.2.1. Run this
once in Terminal, then open the app normally:

```
xattr -cr /Applications/Fermata.app
```
