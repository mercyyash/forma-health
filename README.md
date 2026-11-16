# FORMA Health Lite

A simple, offline-first personal health tracker built as a web app.

## Run locally
Open `index.html` in a modern browser. Data is saved in that browser's localStorage.

## Make it installable / convert to APK
For PWA installation and PWA-to-APK tools, host this folder on an HTTPS static host first (for example GitHub Pages). Then submit the HTTPS URL to PWABuilder or use an Android WebView wrapper.

## Current capabilities
- Personal profile and editable daily calorie target
- 7-day starter meal plan
- Manual food and nutrition logging
- Activity logging with estimated calorie burn
- Weight history and export
- Offline built-in fitness guidance

## Important limitations
- The Coach is an offline rule-based helper, NOT a live generative AI model.
- Health Connect is not included in this lightweight web version.
- Calorie and nutrition values are estimates, not medical measurements.
- Data is stored locally in the browser on this device. Export it before clearing browser data.
- Do not enter medical emergencies or rely on this app for diagnosis.
