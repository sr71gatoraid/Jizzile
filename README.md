# Jizzile

Portable War Thunder audio tracking, radar and desktop markers, with optional
squad datalink. Windows x64; no separate .NET/OCR installation for players.
This repository distributes compiled downloads only. Application source stays local.

## Download or update

Get the current portable from [Releases](https://github.com/sr71gatoraid/Jizzile/releases/latest).
Extract the complete folder and run **Jizzile.exe**. Keep its files together.
Use **Settings → Setup → Install or verify sound mod** with your actual game
folder, closing the game when installation is required. Existing users can use
**Settings → Setup → Check for updates**; only changed managed components download.
Personal Data, settings and calibrations are preserved.

## Squad aircraft sharing in0.16.0

Create or join under **Settings → Squad → Manage squad**. Share the invitation
privately with your teammates. Membership reconnects automatically. Update each
member to0.16.0 for aircraft sharing; old clients keep own-position sharing.
There is no VPN/Tailscale or extra player dependency to install.

- **Green aircraft:** a linked member's own telemetry position.
- **Solid cyan aircraft:** your locally detected aircraft.
- **Hollow cyan aircraft with a link cue:** unknown aircraft observed by a squad member.

**Share aircraft contacts** and **Shared aircraft on radar** default on, within
overall squad sharing. Sender observations require a qualified audio reference
and own telemetry; receivers use their own position/heading without requiring
a camera reference for this radar layer. Reports retain measurement age, expire
when stale, and use bounded velocity prediction only when qualified.

The relay negotiates encrypted aircraft packets without breaking older clients
and reserves capacity for own-position traffic. Shared aircraft stay on the
radar: they do not add desktop3D/VR/offscreen aircraft, drive countermeasures,
or feed missile risk/launch estimates. Allegiance remains unknown. Multiple
emitters/observers can report the same plane; reports are not automatically fused.
Same-map invited membership does not confirm the same battle.

## Gameplay interface

The compact radar automatically listens when one game process is found. Radar
and desktop markers can run together. The scope uses2/5/10/20km or1/3/6/12mi
rings with whole-number labels, aircraft motion/altitude, missile risk colors,
speed arrows, trails and estimated reach explosions when data qualifies.

Eight searchable dark settings pages include actual marker/altitude examples,
a pinned scope preview, appearance sliders, independent radar visibility,
CM key/inventory, HUD reading, squad, setup/updates, VR and advanced tools.

- **F8:** look forward/hold steady to center the audio reference.
- **CM button:** arm/disarm the configured countermeasure key.
- **Ctrl+Alt+F10:** disarm for the current listening session.
- **Ctrl+Alt+F9:** toggle desktop markers.
- **F11 / fullscreen button:** fullscreen; Esc restores window bounds.

Set the correct CM key in Protection. Automatic protection still depends on
fresh qualified data, focus/input gates and finite stock. Separate HUD flare/
chaff counts reconcile estimates; weak/missing OCR does not prove zero stock.
Missile identity persists within a qualified flight/loadout. Exact HUD names
and a readable supported English layout remain necessary.

## Limits and data

Audio-derived positions, heading, range, risk and launch reach are estimates.
An explosion means estimated nominal reach, not seeker lock, team identity or
a guaranteed hit. Synthetic test timing/position error does not prove game
accuracy or evasion. Each local aircraft code represents an engine emitter,
not necessarily a distinct aircraft; local acoustic capacity stays unchanged.

Desktop markers require suitable windowed/borderless play and matching current
horizontal FOV. Optional VR targets Meta Link/OpenXR with DX11/DX12; aircraft/
squad markers are not implemented in that VR layer. Physical headset alignment
remains unverified here. All in-game/headset testing remains the user's.

The portable includes sound banks, codebooks, OCR runtime/models, catalog,
licenses and optional VR components. Save HUD sample writes locally only when
clicked. Detailed audio recording is off by default and uses disk space.
Do not distribute your personal **Data** directory or private squad invitation.
