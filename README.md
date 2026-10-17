# Jelbi Editor downloads

Public installation page for Jelbi Editor. The Android project remains private.

- Stable page: https://dlr-1337.github.io/jelbi-editor-downloads/
- Version: **1.3** (`versionCode 4`)
- Minimum: **Android 8.0 / API 26**
- APK: https://github.com/dlr-1337/jelbi-editor-downloads/releases/download/v1.3/Jelbi-Editor-1.3.apk
- Checksum: https://github.com/dlr-1337/jelbi-editor-downloads/releases/download/v1.3/Jelbi-Editor-1.3.apk.sha256

The app works offline. The page and APK download need an internet connection.

## Publishing

Publish this directory as the root of the public `dlr-1337/jelbi-editor-downloads` repository. Enable GitHub Pages from the `main` branch root. `.nojekyll` makes this a plain static page; there is no build step.

Create release `v1.3` with `RELEASE-NOTES.md`, `Jelbi-Editor-1.3.apk` and `Jelbi-Editor-1.3.apk.sha256`. Generate the checksum against the final signed APK and upload those same bytes. Confirm the APK certificate matches the distributed 1.2 APK before publishing an update. Test the page and release downloads without signing in.

`install-qr.png` and `install-qr.svg` point to the stable page, so the printed QR remains useful when a later release changes the download.

This repository contains only the installation page, QR images and public release information. Do not add Android source, keys, credentials or client photos. Keep APKs and checksums in Releases.

## Updates and installation warnings

Install over the existing app using the same package and signing certificate. Do not uninstall first: uninstalling removes the private history and draft.

The installation page distinguishes personal phones from company-managed phones. An “Action not allowed / Contact your IT admin” block requires the company’s authorized distribution process; a public link or QR does not grant approval.

The Play Protect warning saying it has not seen apps from this developer before matches Google’s **Uncommon** category. Keep Play Protect enabled, stop on a block and report the exact message and environment. Do not describe a classification as a proven false positive or recommend “Install anyway”. Browser download warnings, source-install permission and Play Protect classifications are separate prompts.

Guidance updated on 17 October 2026. The public APK remains version 1.3/build 4, SHA-256 `e59a97a11554d8d5970c3fe554a8dba5bf6015ab80b0527ae72ad50fa810f22c`, certificate SHA-256 `94536cb805b64eeb9fe79977645281f6e04d14109faddcf1e0d113e069464a2a`. No application changes or new signing key were needed for this documentation update.

Camera field of view and installation warnings require validation on the affected physical phones; emulators do not establish either outcome.
