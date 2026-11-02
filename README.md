# Liman Engineering Android app

This project packages the existing Liman Engineering website in a native Android
WebView app using Capacitor. The website and its online features still require
an internet connection.

## Build the APK using GitHub Actions

1. Download and extract this ZIP.
2. Sign in to GitHub and create a new **private** repository named
   `liman-engineering-android`.
3. Upload the extracted files and folders to the repository's main branch.
   Make sure the `.github/workflows/build-android.yml` file is included.
4. Open the repository's **Actions** tab.
5. Select **Build Liman Engineering APK**.
6. Press **Run workflow** and wait for the build to finish.
7. Open the completed workflow run. Under **Artifacts**, download
   `Liman-Engineering-APK`.
8. Extract the downloaded artifact ZIP. It contains `app-debug.apk`.
9. Transfer `app-debug.apk` to your Android phone and tap it to install.

## Important

- This produces an installable debug APK for personal testing.
- It is not yet a Google Play Store release. Play Store publishing requires a
  properly signed release build, store listing, and Google's review.
- Keep the GitHub repository private because it contains your app project.
- Do not share passwords, signing keys, or private account credentials.
