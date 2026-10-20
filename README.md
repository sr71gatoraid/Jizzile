# Jizzile

[Download the latest portable release](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Current release: **0.20.6 — Calibration and live-game updates**.

Fixes a reproduced cockpit-reference handoff failure that could block ground calibration. Capture is strictly process-only by default, and clean references tolerate loud game mixes. Includes the squadmate duplicate-filter repair.

Extract the full portable folder and run `Jizzile.exe`. Existing users can use **Check for updates**. Preserve `Data`.

This release changes one engine definition bank, so exit War Thunder once to install and activate it. After installing 0.20.6, app-only updates can leave War Thunder running; sound-bank updates queue until game exit. No virtual audio cable or extra runtime installation is needed on supported Windows process-loopback systems.

Native and isolated checks pass; live game/headset tests remain with users. The reported VR marker-visibility issue remains unresolved. Squad markers require fresh qualified coordinates in the same battle. Public lobbies are discoverable; callsigns are not verified identities.

This public repository distributes binaries and update manifests. Application source remains local.
