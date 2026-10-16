# Jizzile

<img src="https://github.com/sr71gatoraid/Jizzile/releases/download/v0.14.0/Jizzile-Icon.png" width="128" height="128" alt="Jizzile cartoon missile icon">

Portable Windows audio-based radar, desktop overlays and squad datalink. Built releases and incremental updates are public; source stays local.

[Download Jizzile 0.14.0](https://github.com/sr71gatoraid/Jizzile/releases/download/v0.14.0/Jizzile-0.14.0-Portable.zip) · [Latest release notes](https://github.com/sr71gatoraid/Jizzile/releases/latest)

## Run

Extract the entire portable folder, run `Jizzile.exe`, and install/verify the matching sound mod for your game folder. Existing users can use **Check for updates** in settings. Updates download changed files and preserve personal settings/calibrations. No separate .NET SDK, Python, Tesseract, FMOD Studio, audio-routing driver or GitHub account is required.

Look straight ahead and press **F8** to capture a new reference calibration when needed. Qualified saved layouts can return automatically; never-seen randomized layouts still need F8.

## Squad

Open **Settings > Setup > Open squad**. Set your callsign, create a squad, and copy its invitation for teammates. They paste it and Join. Membership reconnects automatically on startup. Sharing can be paused; Leave forgets local membership. Send the portable ZIP, **not your Data folder**, and keep the invitation private.

Green radar aircraft and green desktop squares identify linked members with fresh own-8111 telemetry on a matching map. You must join the same actual battle yourselves; the local API does not verify shared battle or game account identity. 3D squares require valid camera calibration. Latency compensation is bounded prediction, not exact 1:1 alignment. No VPN, port forwarding or player Cloudflare login is needed. The first hosted relay uses Cloudflare Free and its quotas apply. Squad markers are not yet in the native VR bridge.

## In 0.14.0

- Encrypted squad position sharing with measured timing, bounded queues, automatic reconnect and stale-contact hiding.
- Multiple saved reference layouts per airframe, strict matching and persistence recovery.
- Qualified HUD recognition of selected missile and separate flare/chaff stock; bundled OCR/model and versioned missile catalog.
- Experimental launch reach markers using robust target histories and independent calculation scheduling.
- Improved radar/overlay pacing, asynchronous input sampling and bounded hardware/software renderer recovery.
- Combined HUD, inventory, update and presentation fixes developed since the preceding public 0.12.6 release.

Existing missile/reference/aircraft tracking and countermeasure protection are preserved. Banks and codebooks remain compatible with 0.12.6. The deferred head-tracking experiment is not included and controls are unchanged.

## Scope

Range is decoded from diagnostic audio, not general loudness. Audio cannot prove missile intent or guarantee evasion; urgent close flybys can spend flares when direction is unreliable. A launch reach marker is an estimate, not a seeker lock or guaranteed hit. Aircraft course is estimated movement, not target body attitude. Height requires qualified reference and own attitude.

Fourteen missile signatures, three cockpit references and eight independent engine-source codes across 247 exterior engine events. Capacity is not a guaranteed unique-aircraft count; aircraft model/team are unknown and game sound-source creation can limit range. Acoustic aircraft markers are desktop-only. Physical-headset validation is not claimed.

35 isolated desktop suites and 7 relay runtime tests passed. Synthetic hosted testing measured about 25 ms RTT from the test computer; in-game alignment, geographic latency and actual game rendering performance require user validation. Read the bundled documentation and release notes for detailed limits.

Experimental software for the user's separate/offline diagnostic setup. All in-game tests belong to the user. Releases are published deliberately; this repository is not a live source mirror.
