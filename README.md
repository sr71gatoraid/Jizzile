# Jizzile

Portable Windows audio-based radar and overlay. This repository distributes built releases and incremental updates; source code is kept local.

[Download the latest portable build](https://github.com/sr71gatoraid/Jizzile/releases/latest/download/Jizzile-0.12.1-Portable.zip) Â· [Release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Extract the entire portable folder, run `Jizzile.exe`, and install/verify its matching sound mod. Existing users can use **Settings > Advanced > Check for updates**. Close the game before installing changed banks. The updater downloads changed files and preserves personal settings and compatible calibrations. No separate .NET installation or audio-routing driver is required.

## Version 0.12.1

Hotfix for missing aircraft markers: the aircraft calibration tone now routes directly from its source rather than through a receiver branch that can multiply its level. Aircraft signal levels have more quantization margin. Collision rejection remains enabled. This responds to the user's 0.12.0 logs; live-game retesting of the hotfix remains pending.


- Broad aircraft preview across 247 exterior engine events, replacing the single J85/F-5 host.
- Eight independent aircraft-source codes; blue radar symbols and blue square desktop markers.
- Fourteen missile signatures and all three existing references retained.
- Native routing, collision handling, camera/source motion, lifecycle, performance and app regressions checked in standalone fixtures.

Aircraft capacity counts engine sources, not guaranteed unique airframes. Extra emitters wait for a free code; aircraft identity and team are unknown. Game-controlled event creation and missing host definitions can prevent detection. Aircraft markers are desktop-only. Read the bundled `AIRCRAFT-PREVIEW.txt` and `AIRCRAFT-COVERAGE.json` for coverage and measurement limitations. In-game and physical-headset validation are not claimed.

This remains experimental software for the user's separate/offline diagnostic setup. Updates are published deliberately; the repository is not a live mirror of local work.
