# CineVoz

CineVoz is a web and Android media application built with React, Vite and Capacitor.

## Project structure
- `src/` — React application and UI
- `public/` — web assets
- `android/` — native Android application
- `worker/` — optional backend worker
- `docs/` — project documentation

## Development
```bash
npm install
npm run dev
npm run build
npx cap sync android
```

Open the `android/` folder in Android Studio to build the Android app.

## Android identity
- Display name: CineVoz
- Application ID: `com.cinevoz.app`

## Security and content
The original repository's signing keystore was intentionally excluded. Create and protect your own release signing key. Never commit private keystores, passwords, API tokens or production credentials.

Review third-party services and content-provider integrations before enabling them in a public release. Only use media that you own, are licensed to distribute, or that is in the public domain.
