# Hybrid Train

A mobile-friendly, offline-capable personal strength + running tracker. Open `index.html` in a browser for a preview. To install on iPhone, host these files on an HTTPS site (e.g., GitHub Pages), open in Safari, then use Share → Add to Home Screen.

## Features
- 4 strength days plus optional 5th; set-by-set weight, rep and completion logging
- 3 runs weekly; distance, time, pace, RPE and notes
- 9-week race-aware progression, Dec 20 2026 10-mile race and Jan 15 2027 half marathon
- Weekly mileage charts, best lifts, estimated 1RMs, and workout history
- Browser localStorage persistence and JSON export/import
- Basic PWA manifest and offline service worker

## Important limitations
- No account/cloud sync, GPS tracking, Strava integration, push notifications or server backup.
- Progression is provisional because current weekly mileage, exact pace, injury status and race goal time are unknown.
- The half marathon is on a Friday, so the final long run must be the previous weekend.
- For security and reliability, export data frequently and avoid clearing browser data.
