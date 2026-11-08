# Abhinav AI English

A mobile-friendly starter English practice app for children.

## Included
- Beginner lessons: greetings, daily life, school, and questions
- English speech playback using the phone/browser voice
- Speech recognition where supported by the browser
- Hindi meanings for common starter phrases
- PWA manifest and basic offline cache

## Try it
Open `index.html` in a browser. For install/offline support, publish over HTTPS (for example, GitHub Pages).

## Important limitations
This is a web/PWA prototype, **not an Android APK**. Voice recognition depends on browser/device support and microphone permission. The app requests an English (India) voice but the phone chooses the available voice; a male voice cannot be guaranteed. Hindi meanings are a small built-in phrase list, not full AI translation. No API keys or personal data are included.

## Publish with GitHub Pages
In the repository, open Settings → Pages → Deploy from a branch → choose `main` and `/(root)` → Save. GitHub Pages will provide a website address after deployment.

## Next Android step
To distribute an APK, this web app needs to be packaged with an Android wrapper (such as Capacitor), built and tested with Android tooling, and signed. Play Store publication also requires a developer account and store review.
