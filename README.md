# Jizzile

Portable audio-derived radar and missile-overlay toolkit for offline War Thunder testing.

## Download

Download **Jizzile-0.10.0-Portable.zip** from [Releases](https://github.com/sr71gatoraid/Jizzile/releases/latest), extract the complete folder, and open **Jizzile.exe**. Keep its bundled files together. No compiler, .NET installation or GitHub login is required on recipient PCs.

The source is maintained locally; this repository distributes binaries and update manifests only.

## Updates

In Jizzile, open **Settings → Advanced → Check for updates**, then **Install update**. Close War Thunder before installing. Only changed files are downloaded, including sound banks when needed. Personal settings and calibration memories in `Data` are preserved. Open Jizzile after the completion message.

## Version 0.10.0

- Jizzile branding and simplified settings.
- Smooth nonlinear scope with 2 / 5 / 10 / 20 km rings, or exact 1 / 3 / 6 / 12 mile rings. No radius selector or decimal scope labels.
- Improved 3D threat validation: descending intercepts, overhead passes, missing elevation, stale/invalid data, and early-response precedence.
- Incremental compressed downloads, SHA-256 verification, staging, rollback and interrupted-update recovery.
- Desktop and optional Quest Link/OpenXR presentation. Physical-headset alignment remains unvalidated; start with the bundled standalone headset test.

Read `README.txt` and `VR/README.txt` in the portable for setup, calibration, countermeasure settings and limitations. Risk colors are geometric estimates, not hit probabilities. No model-specific remaining missile range is inferred from unidentified audio signatures.
