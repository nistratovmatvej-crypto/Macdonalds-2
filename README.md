# McDonald's 2026 — personal demo

A multi-page, offline-first website and Android WebView shell.

## Website
Open `index.html`. All pages share `styles.css` and `app.js`.

## Android
The `:app:assembleDebug` Gradle task packages the same static pages into an Android WebView app. The HTML/CSS/JS assets are bundled locally, so navigation and localStorage features work offline.

## Build APK
A GitHub Actions workflow builds a debug APK on every push to `main` and on manual dispatch. Download `McDonalds-2026-debug-apk` from the workflow run's Artifacts section.

## Notes
This is an unofficial personal demo. Brand marks are text approximations; menu pricing and nutrition values are illustrative. Location search, contact submission and app-store links are placeholders and are not connected to production services.
