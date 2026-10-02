# DinoServer 1.2.19 publication handoff

Prepared for Thylacine from the verified timer and branding fixes on 2 October 2026.

## Files

- **DinoServer-Windows-v1.2.19.zip** — clean Windows portable installation. Extract the whole ZIP and run DinoServer.exe inside DinoServer. No saves or caches are included; install caches through Cache Delivery.
- **DinoServer-Update-v1.2.19.zip** and its **.sha256** — existing updater format for an installed DinoServer. This ZIP is not a standalone installation.
- **Android-Controller/JPB-Controller-v0.8.23.apk** — optional signed controller with the timer fixes; preserve existing app data. It is not the game APK.
- **SHA256SUMS.txt**, **RELEASE-NOTES.md**, and **VERIFICATION.json** — checksums, release notes, and packaging evidence.

## Publishing

The GitHub handoff repository is public, with a draft v1.2.19 release. Publish the draft when ready, or copy the Windows ZIP to the established Windows downloads release and the update ZIP plus matching checksum to the established updater release. Keep the maintainer handoff ZIP separate from the automatic updater payload.

The application still uses its existing updater feed. Creating this repository does not redirect clients or change the stable release. The version remains 1.2.19, so a client already on 1.2.19 will not see a newer version automatically.

Back up existing saves and settings; close the game and stop DinoServer before updating. Keep the full EXE, server and docs layout. The separate game APK is not included. Fresh device gameplay checks remain pending; see KNOWN-ISSUES.md in the Windows package.
