# Refarium releases

Official Windows installers and signed updater metadata for Refarium.

This public repository contains release artifacts only. The Refarium source
code is maintained separately and is not published here.

## Download

Use the [latest published release](../../releases/latest) to download the
Windows NSIS installer.

Refarium also reads `latest.json` from the latest release to discover updates.
Updater bundles are signed, and the installed app verifies that signature before
installation.

## Repository contents

- Windows NSIS installers
- signed Tauri updater bundles and `.sig` files
- `latest.json` updater metadata
- release notes

No source code, signing keys, debug symbols, user data, or diagnostics belong in
this repository.
