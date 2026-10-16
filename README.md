# Jizzile

<img src="https://github.com/sr71gatoraid/Jizzile/releases/download/v0.12.6/Jizzile-Icon.png" width="128" height="128" alt="Jizzile cartoon missile icon">

Portable Windows audio-based radar and overlay. Built releases and incremental updates are public; source stays local.

[Download the latest portable build](https://github.com/sr71gatoraid/Jizzile/releases/latest/download/Jizzile-0.12.6-Portable.zip) · [Release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Extract the entire folder, run `Jizzile.exe`, and install/verify the matching sound mod. Existing users: **Settings > Advanced > Check for updates** after closing the game. Updates download changed files and preserve settings/calibrations. No separate .NET installation or audio-routing driver is needed.

## Version0.12.6

- **Display > Aircraft:** altitude Off, Height + chevron, or Chevron stacks. The head sits nearest the plane; stack mode uses1–3 heads for increasing separation, with a100m level band.
- Recent qualified aircraft course persists up to2seconds through brief disruptions, slightly dimmed. Reuse, new flight and expiry still discard stale headings. Current valid contact data is required.
- Independent audio-range approach protection from0.12.5 is retained, including outgoing-range veto and trusted passing exclusions. Banks/codebooks and core decoder/missile/reference/CM algorithms are unchanged in0.12.6.

Range is decoded from audio, not general loudness. It cannot prove missile intent or guarantee evasion; close urgent flybys can spend flares when direction is unreliable. Read bundled `RANGE-PRIORITY-CM.txt`. Aircraft course is estimated movement, not target body attitude. Height requires valid reference/own attitude; missing height is omitted. See `AIRCRAFT-PREVIEW.txt` for complete limits.

Fourteen missile signatures, three cockpit references and eight independent engine-source codes across247 exterior engine events. Capacity is not guaranteed unique-aircraft count; model/team are unknown, game source creation limits range, and aircraft markers are desktop-only. Physical-headset validation is not claimed.

Experimental software for the user's separate/offline diagnostic setup. All in-game testing belongs to the user. Releases are published deliberately; the repository is not a live source mirror.
