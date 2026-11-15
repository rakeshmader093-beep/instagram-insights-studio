INSTAGRAM INSIGHTS STUDIO - ANDROID PROJECT

This is an Android WebView shell project. It opens the Cloudflare-hosted
starter dashboard in an Android app window.

IMPORTANT:
- This project does NOT yet implement Instagram OAuth or Meta Graph API.
- The current hosted dashboard is a starter UI only; it does not load real
  Instagram insights until the required Meta developer app, permissions,
  backend and review/setup are completed.
- Editing metrics in the starter dashboard is only a local preview.
- Never put Instagram passwords, app secrets, or access tokens in this app.

BUILD APK USING A PHONE:
1. Create/sign in to GitHub in your browser.
2. Create a new repository.
3. Upload the CONTENTS of this ZIP (not the ZIP itself) to the repository.
4. Open the repository's Actions tab.
5. Run "Build Android APK" (or wait for the first push build).
6. Open the completed workflow run and download the
   "insights-studio-debug-apk" artifact.
7. Extract the artifact ZIP; install app-debug.apk on your Android phone.

The GitHub Actions workflow builds the APK in the cloud, so Android SDK
installation on Termux is not required.

If the Cloudflare URL does not open in Chrome, fix the hosted dashboard
deployment before using the app.
