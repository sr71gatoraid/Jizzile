# Jizzile

[Download the latest portable release](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Current release: **0.21.0 - Air reliability overhaul**.

Faster qualified calibration, automatic capture recovery, corrected roll transforms, newest-source priority under crowding, distant-threat confirmation and countermeasure salvos. External VR helper v5 improves centering and restart recovery.

Extract the complete portable folder and run Jizzile.exe. Existing users can use Check for updates and restart Jizzile. Preserve Data. Updating from 0.20.7 downloads approximately 5.1 MB of changed components.

This release includes three matching Air sound definition banks and an updated codebook. Sound-bank activation requires War Thunder to exit; app-only updates retain their game-open workflow. Use Install / verify mod for the matching profile. No additional dependency installation is needed for desktop use. The external VR backend requires SteamVR and a configured PC headset.

The measured analysis pipeline uses 32.4% less CPU time and 10.1% fewer allocations than 0.20.7 on matched audio. These component measurements do not establish whole-game FPS. Forty-six applicable isolated suites pass; thirteen display/audio-endpoint suites were blocked by the locked test session. Actual game/headset confirmation remains pending.

Source capacity remains finite: 14 missile codes and eight aircraft-engine codes. Some unguided rockets share missile sound events; extreme bursts can briefly disturb distant measurements. Audio cannot establish seeker intent or guarantee countermeasure success.

This public repository distributes binaries, documentation and update manifests. Application source remains local.
