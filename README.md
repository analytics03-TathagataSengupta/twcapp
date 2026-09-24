# Together We Can — Android app

A WebView wrapper for https://togetherwecan.alcoverealty.in

## Option A: build on GitHub (no installs)
1. Create a new GitHub repo and upload everything in this folder, including `.github/`.
2. Open the **Actions** tab. The "Build APK" job runs automatically, taking about 3-4 minutes.
3. Open the finished run, then download **TogetherWeCan-apk** under Artifacts. It's a zip containing `app-debug.apk`.

## Option B: Android Studio
Open this folder in Android Studio, let it sync, then choose **Build > Build APK(s)**.

## Change things
- URL / allowed domain: `START_URL` and `ALLOWED_HOST` in `MainActivity.java`
- App name: `res/values/strings.xml`
- Colour: `res/values/colors.xml`
