# Dlimans POS — GitHub APK Build

1. Create a GitHub repository, e.g. `dlimans-pos`.
2. Upload all files in this project, keeping `.github/workflows/build-apk.yml`.
3. Open the repository's Actions tab.
4. Select **Build Dlimans POS APK**.
5. Press **Run workflow**.
6. When the run finishes, open it and download **Dlimans-POS-debug-APK**.
7. Extract the artifact and install `app-debug.apk` on Android.

This produces a debug APK for testing. A signed release APK can be added afterward using a GitHub Secrets-based keystore workflow.
