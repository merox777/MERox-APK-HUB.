# MERox APK HUB — Android wrapper

This project builds an installable Android app that opens the current MERox APK HUB website in a WebView.

## Build
Push these files to the `main` branch of your GitHub repository. GitHub Actions will build a debug APK.
Open the repository's **Actions** tab, select **Build MERox APK**, open the successful run, and download the `MERox-APK-HUB-debug` artifact.

## Important
This is an Android wrapper around the website at https://celadon-cat-22af51.netlify.app.
The website currently contains a demo upload interface; it does not securely authenticate an owner or upload APK files to permanent server storage. Those backend features must be implemented separately before public APK hosting is real.
