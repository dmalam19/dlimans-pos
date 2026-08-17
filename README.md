# Dlimans POS — Android Project

This project packages the completed offline Dlimans POS HTML app inside an Android WebView.

## Build in AndroidIDE
1. Extract this ZIP.
2. Open the extracted `DlimansPOS` folder in AndroidIDE.
3. Let Gradle sync/download the Android Gradle Plugin and dependencies.
4. Run the app for a debug APK.
5. For a release APK, use AndroidIDE's Generate/Build Signed APK option and create/select your release keystore.

## Important
- The POS data remains local/offline through the app's WebView storage.
- The HTML file is `app/src/main/assets/index.html`.
- Product images/file selection is supported by the included WebChromeClient file chooser.
- The current HTML/PWA Bluetooth BLE implementation is not automatically converted into a native Android Bluetooth printer bridge by this wrapper. A native Bluetooth bridge can be added separately if direct Classic Bluetooth/SPP printing is required.
