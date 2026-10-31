# TruthLens Android starter

A mobile-first starter app branded **TruthLens**, developed by **NETHA MANOJ**. Includes image, video and text input screens and an About / Developer Details section.

## Important
This is a front-end prototype, not yet a working AI detector. No detection model/API is connected, so it intentionally does not invent AI/real labels or confidence scores. A genuine detector needs a suitable model or API behind a secure backend. Results should be presented as probabilistic signals, not proof.

## Preview locally
Install Node.js, open a terminal in this folder, then run:

```bash
npm install
npm run start
```

## Build an Android APK
You need a computer with Node.js and Android Studio:

```bash
npm install
npm run build
npx cap add android
npx cap sync android
npx cap open android
```

In Android Studio choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**. If the `android` folder already exists, use `npm run android:sync` instead of `npx cap add android`.

Before publishing, connect and test a real detection service, add a privacy policy, explain file uploads/retention, and comply with Google Play and AdMob policies. Never embed private API keys in the app.
