# Jizzile

<img src="https://github.com/sr71gatoraid/Jizzile/releases/download/v0.15.1/Jizzile-Icon.png" width="128" height="128" alt="Jizzile cartoon missile icon">

Portable Windows audio-based radar, desktop overlays and own-position squad datalink. Built releases and incremental updates are public; application source stays local.

[Download Jizzile 0.15.1](https://github.com/sr71gatoraid/Jizzile/releases/download/v0.15.1/Jizzile-0.15.1-Portable.zip) · [Latest release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

## Run

Extract the entire portable folder, run `Jizzile.exe`, and install/verify the matching sound mod for your game folder. Existing users can use **Check for updates** in settings. Updates download changed components and preserve personal settings/calibrations. No separate .NET SDK, Python, Tesseract, FMOD Studio, audio-routing driver or GitHub account is required.

Look straight ahead and press **F8** to capture a new reference calibration when needed. Qualified saved layouts can return automatically; never-seen randomized layouts still need F8.

## New in 0.15.1

- Faster HUD quantity recognition, using known rows and fresh confirmation through short unreadable gaps while retaining stricter zero/refill safeguards.
- Eight searchable dark settings pages, clearer grouping and independent radar visibility/appearance controls.
- An actual radar preview pinned above scrolling appearance controls.
- Production artwork for missile circles, aircraft markers, offscreen arrows, ranges and above/below altitude examples.
- Clearer control/category icons and cleaner Protection and squad dialog presentation.

Existing tracking, reference memory, HUD inventory, launch estimates, rendering recovery and countermeasure protection are preserved. Sound banks and codebooks remain compatible. The separate shared-unknown-aircraft candidate is not integrated into this release.

## Squad

Open **Settings > Squad > Manage squad**. Set a callsign, create a squad, and copy its invitation for teammates. They paste it and Join. Membership reconnects automatically on startup. Sharing can be paused; Leave forgets local membership. Send the portable ZIP, **not your Data folder**, and keep the invitation private.

Green radar aircraft and green desktop squares identify linked members with fresh own-8111 telemetry on a matching map. You must join the same actual battle yourselves; the local API does not verify shared battle or game account identity. 3D squares require valid camera calibration. Latency compensation is bounded prediction. No VPN, port forwarding or player Cloudflare login is needed. The hosted relay uses Cloudflare Free and its quotas apply. Squad markers are not in the native VR bridge.

## Scope

Range is decoded from diagnostic audio, not general loudness. Audio cannot prove missile intent or guarantee evasion; urgent close flybys can spend flares when direction is unreliable. A launch reach marker is an estimate, not a seeker lock or guaranteed hit. Aircraft course is estimated movement, not body attitude. Height requires qualified reference and own attitude.

Fourteen missile signatures, three cockpit references and eight independent engine-source codes across 247 exterior engine events. Capacity is not a guaranteed unique-aircraft count; aircraft model/team are unknown and game sound-source creation can limit range. Acoustic aircraft markers are desktop-only. Physical-headset validation is not claimed.

37 isolated desktop suites passed for this build. The relay is unchanged; its existing isolated tests and synthetic hosted evidence remain documented in prior releases. Game alignment, geographic latency, rendering performance and headset behavior require user validation.

Experimental software for the user's separate/offline diagnostic setup. All in-game tests belong to the user. Releases are published deliberately; this repository is not a live source mirror.
