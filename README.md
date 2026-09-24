# Together We Can — Android app

A WebView wrapper for https://togetherwecan.alcoverealty.in

## Build the APK (GitHub)
1. Add the 4 secrets from GITHUB-SECRETS.txt under Settings > Secrets and variables > Actions.
   These are kept separately and are NOT in this zip.
2. Push or upload these files to `main`, keeping everything at the top level of the repo.
3. Open Actions > Build APK > the latest run > Artifacts > **TogetherWeCan-release**.
   `TogetherWeCan.apk` is inside.

Every build is signed with the same key, so new versions install over old ones.

## Change things
- URL / allowed domain: `START_URL` and `ALLOWED_HOST` in `MainActivity.java`
- App name: `res/values/strings.xml`
- Colour: `res/values/colors.xml`
