# Waseer Agri Farm Android project

This is an Android WebView wrapper around the offline Waseer Agri Farm web app.

## Cloud build (no PC required)
1. Create a GitHub repository and upload all files/folders from this project ZIP.
2. Open the repository's **Actions** tab and enable Actions if prompted.
3. Choose **Build Waseer Agri Farm APK** and tap **Run workflow**.
4. When the workflow finishes, open the run, scroll to **Artifacts**, and download `Waseer-Agri-Farm-debug-apk`.
5. Extract the artifact ZIP and install the `.apk` on Android. If prompted, allow installing apps from that browser/file manager.

The output is a debug-signed APK suitable for personal installation/testing, not a Play Store release.

## App behavior
- The HTML app is bundled inside the APK, so the core app can open offline.
- Records are stored locally in WebView local storage on this device. Use the app's backup/export feature regularly.
- Uninstalling the app or clearing its app storage may delete local records.
