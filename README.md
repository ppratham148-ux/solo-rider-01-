# SOLO RIDER: THE THREE SANCTUMS — Cyber Hunter v2.0

## Deploy to your existing GitHub Pages repository
1. Extract this ZIP.
2. Open https://github.com/ppratham148-ux/solo-rider-01-
3. Replace `index.html`, `manifest.webmanifest`, `sw.js`, and `README.md` in the repository root.
4. Commit changes to `main`.
5. In Settings → Pages, choose Deploy from a branch, `main`, folder `/(root)`.
6. Wait for deployment, then open https://ppratham148-ux.github.io/solo-rider-01-/
7. On Android Chrome, open the site menu and choose Install app / Add to Home screen. Allow location access.
8. Export JSON backups regularly.

## Features
RPG ranks and XP, old campaign migration, foreground GPS, safety checklist and dialer shortcut, offline shell cache, photo/diary memories, Open-Meteo weather, synthesized UI audio, backup/restore.

## Important limitations
- Migration reads `soloRiderThreeSanctums_v1` only on the same browser profile and exact origin. It migrates XP and completed quests; it cannot read another browser/device's storage.
- GPS is foreground browser tracking. Android may suspend it when the screen locks; it is not reliable background tracking.
- Offline cache covers the app shell only. Weather, map tiles and external map content require internet.
- GPS distance is approximate, not turn-by-turn navigation. Use a navigation app for routing.
- SOS opens the dialer only. It does not auto-call or share location.
- Memories and progress are local to this browser. Clearing site data may erase them.
- Route distances are planning estimates. Verify roads, two-wheeler restrictions, temple hours, Ellora closure, accommodation and weather.
- Day 5 is a long ride. Stop overnight if fatigued. Safety outranks schedule.
