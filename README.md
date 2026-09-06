**TESDA APEX -- App Releases**

Official Android APK releases for TESDA APEX, the mobile companion app to TESDA Catanduanes' scholarship and training management system. Supports both TESDA Staff and TVI (training institution) sign-in modes in one app.

This repository holds nothing but the compiled APK for each release. The app's source code lives in a private repository -- this repo is public only so the release files themselves can be downloaded directly, without requiring a GitHub account or login.

Download

Grab the latest version from the Releases page -- download the app-release.apk file attached to the newest release and install it on your Android phone.

Installing / updating
Download app-release.apk from the latest release using your phone's browser.
If this is your first time installing an app from outside the Play Store, Android will ask you to allow installs from your browser -- allow it once when prompted.
Open the downloaded file and tap Install.
Open the app, sign in, and (first time only) set a 4-digit PIN.

Once installed, the app can check for and download future updates itself from More/Settings -> Check for updates -- you generally won't need to come back to this page except for a first install.

⚠️ Coming from v1.0.17 or earlier? Starting with v1.0.18, releases are signed with a proper release key instead of a shared debug certificate. Android will refuse to install this version directly over an older one because of that change. Uninstall the old app first, then install the new APK fresh. You'll need to sign in and set your PIN again, same as on a new device -- every release after v1.0.18 will go back to updating in place normally.

Version numbers

Releases are tagged vX.Y.Z, matching the app's own versionName+versionCode (e.g. v1.0.19 is 1.0.19+20 inside the app). The build number after the + always increases, which is what the app's own "Check for updates" uses to decide whether a newer version is available -- always update to the highest-numbered release here.

Each release's notes describe exactly what changed in that version and any versions bundled since the last one you might have installed -- check the Releases page for full changelogs.

Who this is for

Built specifically for TESDA Catanduanes staff and partner Training Institutions (TVIs). If you're not sure whether you should have this app, ask your TESDA Provincial Office contact.

Support

Found a bug or something not working right? Let your TESDA Catanduanes contact know directly -- this repository doesn't monitor Issues.
