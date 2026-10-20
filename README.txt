DAILY CHECK-IN TRACKER: HOSTING AND HOME-SCREEN SETUP

This folder contains a ready-to-deploy static web app:
- index.html: the form and history screen
- manifest.json: installable-app metadata
- service-worker.js: offline caching
- icon.svg: home-screen icon

IMPORTANT:
The tracker saves entries in browser storage on this device. Use Export CSV regularly.
It does not automatically sync with ChatGPT. Take a screenshot of the History table
or export CSV and share it with ChatGPT for analysis.

EASIEST HOSTING ROUTE: GitHub Pages
1. On your phone or computer, sign in to GitHub or create an account.
2. Create a new public repository named daily-checkin-tracker.
3. Upload all four files in this folder to the repository root. Keep index.html named exactly that.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for GitHub Pages to publish. The site URL will look like:
   https://YOUR-USERNAME.github.io/daily-checkin-tracker/
8. Open that URL in Chrome on Android. Use Chrome menu (⋮) > Add to Home screen
   or Install app if offered.
9. Open the new home-screen icon to use the tracker.

The URL above is a pattern, not your actual live URL. I cannot publish to your GitHub
account from this chat without access to an authorized hosting account.
