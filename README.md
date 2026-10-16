# Jizzile

Portable Windows audio-based radar and overlay. This repository distributes built releases and incremental updates; source code is kept local.

[Download the latest portable build](https://github.com/sr71gatoraid/Jizzile/releases/latest/download/Jizzile-0.12.2-Portable.zip) Â· [Release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Extract the entire folder, run `Jizzile.exe`, and install/verify the matching sound mod. Existing users can use **Settings > Advanced > Check for updates**. Updates download changed files and preserve settings and compatible calibrations. No separate .NET installation or audio-routing driver is needed.

## Version0.12.2

- Offscreen aircraft arrows with a border safe zone, rear-facing cue, and optional range labels.
- Existing blue square markers for visible aircraft and blue aircraft symbols on the radar.
- Broad aircraft preview across247 exterior engine events with eight independent engine-source codes.
- Fourteen missile signatures and three cockpit references. No sound-bank changes in this release.

Aircraft detection was confirmed working by the user on0.12.1. The new indicators passed isolated geometry, GPU/fallback, refresh, input-transparency and regression checks; user game validation of the new feature is pending.

Capacity counts engine sources rather than guaranteed unique aircraft. Game sound-event creation limits coverage and range; aircraft identity/team remain unknown. Aircraft markers are desktop-only. Read the bundled `AIRCRAFT-PREVIEW.txt` and `AIRCRAFT-COVERAGE.json` for details. Physical-headset validation is not claimed.

This remains experimental software for the user's separate/offline diagnostic setup. Releases are published deliberately; GitHub is not a live mirror of local work.
