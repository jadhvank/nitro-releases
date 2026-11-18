# Nitro downloads

Nitro (formerly Model Dial) is a native macOS menu bar app for model and effort profiles in Codex
and Claude Code. It supports direct shortcuts, previous/next navigation, and
routing to the focused app. The RPM menu-bar dashboard provides quick profile selection.

**[Download the latest release](https://github.com/jadhvank/model-dial-releases/releases/latest)**

Requires an Apple silicon Mac and macOS 13 or later.

The app can check, download, install and relaunch updates using Sparkle. Open
**Settings → General → Updates** or choose **Check for Updates** from the menu bar.
The update feed and archives are signed with Ed25519, and the app is signed with
Developer ID. The private signing key is never included in a release.

Apple notarization has not been performed for the initial release. This is a
separate step from Developer ID and Sparkle signing.

This repository contains distribution metadata and release assets only. App
source is maintained separately in a private repository. GitHub's generated
source archives for this repository do not contain the app source.

Sparkle: https://sparkle-project.org/ (MIT; license included in the app bundle).
