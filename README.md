# SOLO RIDER: THE THREE SANCTUMS

## Included
- Installable PWA shell
- OpenStreetMap / Leaflet map
- Foreground GPS recording with route polyline
- Distance estimate, campaign quest checklist, XP and ranks
- Photo evidence and final report saved locally
- JSON journey export
- Background/visibility interruption warning

## Important GPS limitation
This is a website/PWA. Android browsers do not guarantee continuous geolocation while the page is backgrounded or the screen is locked. The service worker included here does **not** provide background GPS. For dependable screen-off tracking, build a native Android companion using a foreground location service (persistent notification) and Android location permissions. Do not rely on this PWA alone for safety-critical tracking.

## Deploy (easy path: GitHub Pages)
1. Extract the ZIP.
2. Create a GitHub repository, for example `solo-rider`.
3. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to the repository root.
4. In repository Settings → Pages, deploy from the `main` branch and `/ (root)`.
5. Open the generated HTTPS URL on your Android phone in Chrome.
6. Allow location permission. Use Chrome menu → Add to Home screen / Install app.
7. Start GPS only while parked. During the ride, mount the phone securely and do not touch it.

Alternative: upload the three files to Netlify or Vercel as a static site. HTTPS is required for geolocation.

## Local test
From a computer with Python installed, run in this folder:
`python -m http.server 8000`
Then open `http://localhost:8000`. For phone testing, localhost on your PC is not the phone; deploy to HTTPS instead.

## Data and privacy
Quest progress, GPS points, report and photos are stored in the browser's localStorage on that device. No server/account sync is configured. Export the JSON regularly. Clearing browser data can erase the campaign record. Photo data can make local storage fill up; use small images.

## Accuracy and route safety
The route waypoints are approximate planning markers, not turn-by-turn navigation or confirmed road access. Use a navigation app for actual directions. Verify temple and heritage opening times before travel. Do not ride at night in ghats, speed for XP, or continue when tired. Day 5 is a long return; stop overnight if fatigued.

## Rank thresholds
E: 0–299 | D: 300–599 | C: 600–899 | B: 900–1199 | A: 1200–1499 | S: 1500+
