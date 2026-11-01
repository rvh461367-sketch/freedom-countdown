THE FREEDOM COUNTDOWN — prototype 1.0

Files:
- index.html: app screen and layout
- app.js: countdown and milestone logic
- manifest.webmanifest: installable PWA metadata
- sw.js: offline cache
- icon.svg: app icon

Initial settings:
- Starting count: 892
- First working day: 1 April 2027
- Work cycle: 5 work days, then 4 rest days
- Annual leave: 1–28 October, 2027–2031
- Target: 8 January 2032

IMPORTANT:
This is a prototype. It is designed to be hosted over HTTPS (for example, a free static hosting service) before installing on Android. After the first successful load, the service worker caches the app for offline use. Data is stored locally in the browser on your phone.

To install on Android after hosting:
1. Open the app's HTTPS address in Chrome.
2. Open Chrome's menu.
3. Choose "Install app" or "Add to Home screen".
4. Launch it from the new home-screen icon.

The app does not need an account, paid API, or subscription. Keep a copy of this folder as a backup.
