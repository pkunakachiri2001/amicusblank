# AMICUS_IPR_BLANK

Minimal standalone Capacitor Android project for **Amicus IPR**.

## Behavior
- Opens to a blank white screen.
- Shows tiny text in the center: Android version.
- Uses the same app name and Android launcher icons as the original project.

## Local build steps
1. `npm install`
2. `npm run cap:sync`
3. Open Android Studio with `npm run android`
4. Build APK from Android Studio (`Build > Build Bundle(s) / APK(s) > Build APK(s)`).

## GitHub Actions
Push this folder to its own repository. You can then run your Android build workflow to generate and download the APK artifact.

If you want side-by-side install with the original app, change `appId` in `capacitor.config.json` and `applicationId` in `android/app/build.gradle`.
