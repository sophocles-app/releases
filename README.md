# Sophocles Releases

This repository hosts the public releases of **Sophocles**, a local-first screenwriting
and rehearsal app.

Sophocles is not open source, and **this repository does not contain its source code.**
It exists so that installers and update manifests are publicly downloadable.

## Downloads

Get the latest version from the [Releases page](../../releases/latest), or from
[sophocles.app](https://sophocles.app).

| Platform | File |
| --- | --- |
| macOS (Apple Silicon) | `Sophocles_<version>_aarch64.dmg` |
| Windows (x64) | `Sophocles_<version>_x64-setup.exe` |

The `.app.tar.gz` and `.sig` files are used by the in-app updater. You do not need to
download them manually.

## Manifests

- `stable/latest.json` — the update feed the desktop app checks for new versions.
- `stable/downloads.json` — current download URLs per platform, used by the website.

Both are written automatically when a release is published. **Do not edit them by hand** —
the next release will overwrite your changes.

## Versioning

Sophocles uses a single version number across every platform, so desktop 0.4.0 and
mobile 0.4.0 are the same release.

Not every version ships on every platform. If a version is missing for your platform,
there was simply no update for it — the previous version is still current there.

## Issues

This repository does not accept issues. For bugs, questions, or feedback about
Sophocles, see [sophocles.app](https://sophocles.app).
