# Jizzile

<img src="https://github.com/sr71gatoraid/Jizzile/releases/download/v0.12.4/Jizzile-Icon.png" width="128" height="128" alt="Jizzile cartoon missile icon">

Portable Windows audio-based radar and overlay. This repository distributes built releases and incremental updates; source code is kept local.

[Download the latest portable build](https://github.com/sr71gatoraid/Jizzile/releases/latest/download/Jizzile-0.12.4-Portable.zip) · [Release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Extract the entire folder, run `Jizzile.exe`, and install/verify the matching sound mod. Existing users can use **Settings > Advanced > Check for updates**. Updates download changed files and preserve settings and compatible calibrations. No separate .NET installation or audio-routing driver is needed.

## Version 0.12.4

- Clear swept-wing aircraft icons. Filled radar planes point along estimated ground movement; hollow planes mean course is unknown.
- Stalkless up/down chevrons with relative height in metres, or feet when miles are selected.
- Tighter 24-pixel offscreen aircraft-arrow safe zone, including the GPU and fallback renderers.
- Separate, confidence-gated aircraft histories preserve existing missile/reference/CM behavior. Sound banks and codebooks are unchanged.

Reliable relative height needs reference correction and synchronized player attitude; ground course also needs valid own world positions. New or noisy sources may need time to establish direction. Course shows movement, not directly measured airframe attitude.

The application includes blue squares for visible aircraft, offscreen arrows with a rear-facing cue and optional ranges, nonlinear radar, fourteen missile signatures and three cockpit references. Aircraft encoding covers 247 exterior engine events using eight independent engine-source codes.

Aircraft detection was confirmed working by the user on 0.12.1. Later features have isolated geometry, GPU/fallback, timing and regression evidence; they do not have a new user in-game confirmation recorded yet. For 0.12.4, sixteen standalone suites passed; the install-audit suite was skipped while the game was running, retaining the guard. Decoded aircraft and missile/reference outputs match 0.12.3 on the comparison fixture.

Capacity counts engine sources rather than guaranteed unique aircraft. Game sound-event creation limits coverage and range; aircraft identity/team remain unknown. Aircraft markers are desktop-only. Read bundled `AIRCRAFT-PREVIEW.txt` and `AIRCRAFT-COVERAGE.json` for details. Physical-headset validation is not claimed.

This remains experimental software for the user's separate/offline diagnostic setup. Releases are published deliberately; GitHub is not a live mirror of local work.
