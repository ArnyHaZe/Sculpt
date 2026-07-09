# Sculpt — 24-Week Fitness Tracker

A private, phone-friendly fitness tracker built as a single-page HTML app and hosted with GitHub Pages.

This tracker is designed for a 24-week fitness journey with structured workouts, progress logging, weekly check-ins, rewards, and a mobile-first interface.

## Live app

Once GitHub Pages is enabled, the app should be available at:

https://ArnyHaZe.github.io/Sculpt/

If you later rename the repository to lowercase `sculpt`, the link will become:

https://ArnyHaZe.github.io/sculpt/

## What it includes

- 24-week training structure
- Lower / Upper / Lower workout rotation
- Set logging for weight, reps, RIR, and notes
- Rest timer
- Weekly check-ins
- Progress tracking
- Milestone rewards
- Mobile-first layout
- Local browser storage, so progress stays on the device being used

## How to use

Open the GitHub Pages link on a phone and use the app directly in the browser.

For the best experience on iPhone:

1. Open the live app in Safari.
2. Tap the Share button.
3. Tap **Add to Home Screen**.
4. Launch Sculpt from the new home-screen icon.

## Important note about saved progress

The app currently saves progress in the browser's local storage. That means progress is stored on the same phone/browser where she uses the app.

Avoid clearing Safari/browser data unless the app later gets an export or backup feature.

## GitHub Pages setup

To publish the app:

1. Go to the repository's **Settings** tab.
2. Open **Pages** in the left sidebar.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Branch: **main**.
5. Folder: **/(root)**.
6. Click **Save**.

After a short delay, GitHub will show the live site URL.

## Files

- `index.html` — the complete Sculpt fitness tracker app
- `README.md` — project documentation
- `manifest.json` — optional web app metadata for future installable/PWA support
- `.gitignore` — keeps local system files out of the repo

## Future upgrade ideas

- Export/import backup button
- App icon and splash screen
- Offline caching with a service worker
- Optional passcode screen
- Personalized name/welcome message
- Cloud sync later if needed
