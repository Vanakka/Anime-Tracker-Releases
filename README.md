# Anime Tracker — releases

This repository holds the **release files** of Anime Tracker, a Windows desktop app for keeping track of the anime and manga you watch and read. It contains installers, their signature files and the update manifest, and nothing else. The app's source code is private.

## Installing

1. Open the [latest release](https://github.com/Vanakka/Anime-Tracker-Releases/releases/latest) and download `AnimeTracker_<version>_x64-setup.exe`.
2. Run it. The installer is not signed with a Windows certificate, so SmartScreen shows a warning the first time: choose **More info**, then **Run anyway**. It installs for the current user only and needs no administrator rights.
3. Each release's notes list the installer's SHA-256 so you can check a download before running it.

## Updating

Once installed, the app checks this repository for a newer release and offers to install it; nothing installs without your click. Updates downloaded by the app are verified against a signing key built into the app before they run. A file you download from this page by hand is **not** checked by the app, which is why the SHA-256 is published with every release.

## What the files are

- `AnimeTracker_<version>_x64-setup.exe` — the installer.
- `AnimeTracker_<version>_x64-setup.exe.sig` — its signature, read by the app's updater.
- `latest.json` — the update manifest the installed app reads.

## Contact

Questions and suggestions: [@Vanakka on X](https://x.com/Vanakka). All rights reserved.
