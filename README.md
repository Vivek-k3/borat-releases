# Borat releases

Builds of **Borat**, a personal desktop agent for macOS (Apple Silicon). The source is private; this repository only holds releases.

## Install

1. Download `Borat-<version>-arm64.dmg` from the [latest release](https://github.com/later-stuff/borat-releases/releases/latest).
2. Open it and drag **Borat** to **Applications**.
3. The first time, right-click Borat → **Open**. Builds are signed with Borat's own certificate, not an Apple Developer ID, so macOS asks once.

## Updates

Borat checks this repository and installs updates itself: **Settings → Updates → Install and restart**, or the **Update** chip in the sidebar. It verifies each download against the release's `borat-update.json` (SHA-512) and the signing certificate before replacing the app.

Each release's notes are that version's section of Borat's changelog.
