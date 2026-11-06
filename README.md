# Cleanroom Reference (APK build project)

1. Create a free GitHub account and a new empty repository (name it anything).
2. Upload every file and folder from this project to the repository, including the hidden .github folder, on the main branch.
3. Open the repository's Actions tab. The "Build APK" workflow starts by itself (or click Run workflow).
4. When it finishes (about 5 minutes), open the run and download the artifact "cleanroom-reference-apk". Unzip it to get app-debug.apk.
5. Copy app-debug.apk to your phone, allow installs from unknown sources, and tap the file to install.

To change the app, edit www/index.html and push again.
