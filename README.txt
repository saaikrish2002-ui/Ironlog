IRONLOG - standalone workout tracker

CONTENTS
- index.html: the app
- manifest.webmanifest: installable web app metadata
- sw.js: offline app shell cache
- icon.svg: app icon

RUN LOCALLY
Open index.html in a modern browser. Core logging works locally. For install prompts and offline service-worker support, serve the folder over HTTPS or localhost.

PUBLISH AS A WEBSITE
1. Create a GitHub account if you do not have one.
2. Create a new public repository named ironlog.
3. Upload all four app files (index.html, manifest.webmanifest, sw.js, icon.svg) to the repository root.
4. In repository Settings > Pages, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish. Your site URL will be shown in Settings > Pages.
6. Open that HTTPS URL on your phone and laptop.

INSTALL ON ANDROID
Open the published HTTPS site in Chrome > menu (three dots) > Install app or Add to Home screen.

DATA & PRIVACY
Workout data is stored in localStorage in the browser on the device. It is not uploaded to a server by this app. Phone and laptop data remain separate. Export JSON from History & backup before clearing browser data or changing devices. Import the JSON backup on another device to transfer history.

IMPORTANT
This package is prepared for deployment, but it has not been published to a public URL. The owner must upload it to a hosting provider. Do not use private/shared devices for sensitive records.
