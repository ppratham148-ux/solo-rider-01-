# SOLO RIDER: THE THREE SANCTUMS — Cyber Hunter 3.0

## Project Overview
SOLO RIDER is a travel adventure campaign with an RPG-inspired Hunter Gateway, campaign progression, XP, ranks, and offline app-shell support.

## Gateway Features
- Create New Journey
- Extreme Expedition
- Continue Existing Campaign
- Hunter Profile with live campaign XP, rank, and quest progress
- Return to Gateway without resetting campaign progress

## Existing Campaign
Campaign: THE THREE SANCTUMS
Route: Vashi → Trimbakeshwar → Bhimashankar → Grishneshwar → Vashi
Campaign dates: 3–7 December 2026
Total quests: 21

The existing campaign save system is preserved.

## Deploy to GitHub Pages
1. Open https://github.com/ppratham148-ux/solo-rider-01-
2. Upload or replace all five project files in the repository root:
   - index.html
   - gateway-preview.html
   - manifest.webmanifest
   - sw.js
   - README.md
3. Commit the changes to the main branch.
4. In Settings → Pages, select Deploy from a branch, branch main, folder /(root).
5. Wait for deployment.
6. Open https://ppratham148-ux.github.io/solo-rider-01-/
7. On Android Chrome, use Install app / Add to Home screen.
8. Export JSON backups regularly.

## Offline Support
- Service Worker cache: solo-rider-cyber-v3
- Cached app shell: index.html, gateway-preview.html, and manifest.webmanifest.
- Campaign progress is stored locally in browser storage.
- Weather, external map tiles, and other external services require internet.

## Campaign Features
RPG ranks and XP, legacy save migration, foreground GPS tracking, safety checklist, dialer shortcut, photo and diary memories, Open-Meteo weather, synthesized UI audio, JSON backup and restore.

## Important Limitations
- Migration reads soloRiderThreeSanctums_v1 only on the same browser profile and exact origin. It migrates XP and completed quests; it cannot read another browser or device's storage.
- GPS is foreground browser tracking. Android may suspend it when the screen locks; it is not reliable background tracking.
- GPS distance is approximate, not turn-by-turn navigation. Use a navigation app for routing.
- SOS opens the dialer only. It does not automatically call or share location.
- Memories and progress are local to this browser. Clearing site data may erase them.
- Route distances are planning estimates. Verify roads, two-wheeler restrictions, temple hours, Ellora closure, accommodation, and weather.
- Day 5 is a long ride. Stop overnight if fatigued. Safety outranks schedule.
