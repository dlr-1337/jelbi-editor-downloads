# Jelbi Editor downloads

Public installation page for Jelbi Editor. The Android project remains private.

- Stable page: https://dlr-1337.github.io/jelbi-editor-downloads/
- Version: **1.4** (`versionCode 5`)
- Minimum: **Android 8.0 / API 26**
- APK: https://github.com/dlr-1337/jelbi-editor-downloads/releases/download/v1.4/Jelbi-Editor-1.4.apk
- Checksum: https://github.com/dlr-1337/jelbi-editor-downloads/releases/download/v1.4/Jelbi-Editor-1.4.apk.sha256

The app works offline. The page and APK download need an internet connection.

## Publishing

Publish this directory as the root of the public `dlr-1337/jelbi-editor-downloads` repository. Enable GitHub Pages from the `main` branch root. `.nojekyll` makes this a plain static page; there is no build step.

Create release `v1.4` with `RELEASE-NOTES.md`, `Jelbi-Editor-1.4.apk` and `Jelbi-Editor-1.4.apk.sha256`. Generate the checksum against the final signed APK and upload those same bytes. Confirm the APK certificate matches the distributed 1.3 APK before publishing an update. Test the page and release downloads without signing in.

`install-qr.png` and `install-qr.svg` point to the stable page, so the printed QR remains useful when a later release changes the download.

This repository contains only the installation page, QR images and public release information. Do not add Android source, keys, credentials or client photos. Keep APKs and checksums in Releases.

## Updates and installation warnings

Install over the existing app using the same package and signing certificate. Do not uninstall first: uninstalling removes the private history and draft.

The installation page distinguishes personal phones from company-managed phones. An “Action not allowed / Contact your IT admin” block requires the company’s authorized distribution process; a public link or QR does not grant approval.

The Play Protect warning saying it has not seen apps from this developer before matches Google’s **Uncommon** category. Keep Play Protect enabled, stop on a block and report the exact message and environment. Do not describe a classification as a proven false positive or recommend “Install anyway”. Browser download warnings, source-install permission and Play Protect classifications are separate prompts.

Release updated on 19 October 2026. The public APK is version 1.4/build 5, SHA-256 `b1b9a15de21e2e12241e72dacba428478fc69a5f96d1368d7baea54a532af1b7`, certificate SHA-256 `94536cb805b64eeb9fe79977645281f6e04d14109faddcf1e0d113e069464a2a`. This update corrects the support contact and app branding. Historical scans and the classification-review submission for version 1.3 apply to that older APK hash, not automatically to 1.4.

Camera field of view and installation warnings require validation on the affected physical phones; emulators do not establish either outcome.
