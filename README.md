# RoadGuardian for Android

This repository distributes signed Android APKs. It does not contain the application source code, server configuration, or signing keys.

Download the APK from the repository's **Releases** page. Pre-releases are evaluation builds, not validated stable releases.

## Current candidate

- GitHub release: `v1.0.0-rc.1`
- Android version: `1.0.0` (version code `1`)
- Minimum Android version: Android 7.0 (API 24)
- API: `https://api-rg.baysiva.app`

Read the release notes before installation. Android may require permission to install apps from the browser or file manager used for the download.

Updates must retain the same application ID and signing key. This APK cannot update a development installation signed with a debug key. Do not uninstall an existing installation without considering its local data.

## Verification

Download the APK and `SHA256SUMS` into the same directory, then run:

```sh
sha256sum --check SHA256SUMS
```

The signing certificate SHA-256 fingerprint is:

```text
e58023d3cedbe904f57598beeda206b1820529f9f9461db2a872e387507228ac
```