# Jizzile

<img src="https://github.com/sr71gatoraid/Jizzile/releases/download/v0.12.3/Jizzile-Icon.png" width="128" height="128" alt="Jizzile cartoon missile icon">

Portable Windows audio-based radar and overlay. This repository distributes built releases and incremental updates; source code is kept local.

[Download the latest portable build](https://github.com/sr71gatoraid/Jizzile/releases/latest/download/Jizzile-0.12.3-Portable.zip) · [Release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Extract the entire folder, run `Jizzile.exe`, and install/verify the matching sound mod. Existing users can use **Settings > Advanced > Check for updates**. Updates download changed files and preserve settings and compatible calibrations. No separate .NET installation or audio-routing driver is needed.

## Version 0.12.3

- New cartoon missile application icon, embedded in the executable and included as `Jizzile.ico` for shortcuts.
- [Transparent PNG](https://github.com/sr71gatoraid/Jizzile/releases/download/v0.12.3/Jizzile-Icon.png) and [Windows ICO](https://github.com/sr71gatoraid/Jizzile/releases/download/v0.12.3/Jizzile-Icon.ico) are separate downloads too.
- Branding only: sound banks, tracking, overlays, calibration and countermeasure logic retain the 0.12.2 implementation.

The application includes offscreen aircraft arrows with a border safe zone, a rear-facing cue and optional range labels; blue squares for visible aircraft and aircraft symbols on the radar. Aircraft encoding covers 247 exterior engine events using eight independent engine-source codes, alongside fourteen missile signatures and three cockpit references.

Aircraft detection was confirmed working by the user on 0.12.1. Offscreen indicators passed isolated geometry, GPU/fallback, refresh, input-transparency and regression checks in 0.12.2; user game validation of those arrows remains pending. Icon resources and focused standalone checks passed for 0.12.3.

Capacity counts engine sources rather than guaranteed unique aircraft. Game sound-event creation limits coverage and range; aircraft identity/team remain unknown. Aircraft markers are desktop-only. Read the bundled `AIRCRAFT-PREVIEW.txt` and `AIRCRAFT-COVERAGE.json` for details. Physical-headset validation is not claimed.

This remains experimental software for the user's separate/offline diagnostic setup. Releases are published deliberately; GitHub is not a live mirror of local work.
