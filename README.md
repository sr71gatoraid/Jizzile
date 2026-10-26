# Jizzile

[Download the latest portable release](https://github.com/sr71gatoraid/Jizzile/releases/latest)

Current release: **0.21.3 - OCR, calibration and Air improvements**.

Faster HUD recognition, improved inventory and selected-weapon handling, calibration and capture recovery fixes, and more efficient native drawing. This release also includes the previously unpublished aircraft-engine range definitions.

Extract the complete portable folder and run Jizzile.exe. Existing users can use **Check for updates**. Preserve **Data**. Updating from 0.21.0 downloads approximately 3.8 MB of changed components.

This update includes matching aircraft-engine/event definition banks and a profile change. **War Thunder must exit before changed banks can be activated**; the update can be queued while the game is open. App-only updates retain their game-open workflow. Use **Install / verify mod** for the matching profile. Desktop dependencies are bundled. The external VR backend still requires SteamVR and a configured PC headset.

82 aircraft-engine events now advertise 10,000 rather than 3,000 units. This does not guarantee 10 km detection: the game controls which sound sources exist.

57 combined isolated suites plus scalar-fallback checks passed. Matched saved-pixel OCR measurements show about 49% lower focused processing time and 37% lower OCR-worker CPU use. These component measurements do not establish whole-game FPS or universal live accuracy. Unreadable or unusual HUD text can still withhold fresh readings; retained inventory is identified separately. Game/headset confirmation remains user testing.

Source capacity remains finite: 14 missile codes and eight aircraft-engine codes. Some unguided rockets share missile sound events; extreme bursts can briefly disturb distant measurements. Audio cannot establish seeker intent or guarantee countermeasure success.

This public repository distributes binaries, documentation and update manifests. Application source remains local.
