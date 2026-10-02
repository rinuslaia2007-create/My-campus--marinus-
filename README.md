# MyCampus — Marinus Laia

Android app source built around a local-first student dashboard.

## Included
- 9 IBBI Manajemen courses
- Course detail pages with per-course materials
- Add/remove schedule entries
- Tasks and deadlines
- Materials metadata and links
- 6 switchable themes: Ocean IBBI, Sakura Tokyo, Kyoto Zen, Seoul Dream, Shanghai Red, Tokyo Night
- Emoji/illustration accents and subtle animations
- LocalStorage persistence for personal data
- Mobile-first responsive UI

## Build as Android APK
Requires Node.js, Android Studio/SDK, and a Java JDK.

1. `npm install`
2. `npx cap add android`
3. `npx cap sync android`
4. Open the generated `android` folder in Android Studio.
5. Build > Build APK(s).

The web UI can also be opened directly from `www/index.html` for preview.
