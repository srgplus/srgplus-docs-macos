# SRG+ Docs for Mac

The Mac app of SRG+ Docs, for download outside the App Store. The same app is on TestFlight for the Mac, the iPhone and the iPad.

**Download:** [SRG-Plus-Docs.dmg](https://github.com/srgplus/srgplus-docs-macos/releases/latest/download/SRG-Plus-Docs.dmg)

Open the DMG and drag SRG+ Docs to Applications. The app updates itself (Sparkle): it checks once a day, and
**SRG+ Docs › Check for Updates…** checks at once. It needs macOS 26 or later.

**Dev, for the studio's own testing.** These builds sign in with the SRG+ development accounts and work on the Docs
development server, not on real client documents.

This repository only hosts the releases (the DMG) and `appcast.xml`, the update feed the installed apps read
(GitHub Pages, `https://srgplus.github.io/srgplus-docs-macos/appcast.xml`). The app's code and the build script
(`apps/apple/scripts/mac-dmg.sh`) are in the private repository srgplus/srgplus-docs. Changes to `appcast.xml` go
through a pull request, never straight to `main`.
