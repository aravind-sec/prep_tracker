VAPT INTERVIEW PREP CHECKLIST APP

FILES
- index.html: responsive app; no build step or dependencies.
- manifest.webmanifest and sw.js: install/offline support when hosted on HTTPS or localhost.

USE ON PC
1. Extract the ZIP.
2. Open index.html in a modern browser. Checklist, search, progress, notes, and export work locally.

USE ON MOBILE
1. Transfer the ZIP to your phone and extract it, or open the hosted version described below.
2. Opening index.html locally works in many mobile browsers, but install/offline PWA features require hosting on HTTPS or localhost.

INSTALL AS AN APP ON BOTH PC AND PHONE
1. Host the extracted folder on a static HTTPS host, such as GitHub Pages.
2. Open the HTTPS URL in Chrome or Edge on PC and use the browser's Install app option if offered.
3. On Android Chrome, open the URL, browser menu, then Install app / Add to Home screen.
4. On iPhone, open in Safari, Share, then Add to Home Screen.

PROGRESS / PRIVACY
- Progress and notes are saved in localStorage in each browser/device, not automatically synced.
- Use Export progress to download a JSON backup. Keep that file private if your notes contain sensitive information.
- Reset clears local progress and notes after confirmation.
- The app is static and has no analytics or external service calls.

Note: The web app is designed to be responsive on desktop and mobile. Cross-device sync would require a hosted backend or manually moving the exported JSON backup; this version uses local storage by design.
