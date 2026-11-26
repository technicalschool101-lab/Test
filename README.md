# Toon Rig Studio Android build candidate
This packages the existing V11 browser studio with Capacitor 6. It does not complete the remaining AI reconstruction, automatic speech recognition or professional mocap modules. Android WebView rendering, file imports and downloads, audio and video recording require device testing. The debug APK is not a Play Store release.

Create a private GitHub repository, upload all files including .github/workflows/android.yml, and run Actions > Build Android APK > Run workflow (or push to main). Download the artifact ZIP and extract app-debug.apk. The runner downloads dependencies; the app bundles Three.js locally. No Termux server should be needed after installation. If the workflow fails, inspect its logs. 
