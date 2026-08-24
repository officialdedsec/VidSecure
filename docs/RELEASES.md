# Publishing free downloads (maintainer note)

This repo hosts **documentation and download links only** — the builds live on the
GitHub **Releases** page. To publish downloads:

1. Build the apps locally:
   - Windows: build `VidSecure-Setup.exe` with the Protector's "Build Setup Installer".
   - Android: build a signed APK/AAB in Android Studio (`Build ▸ Generate Signed Bundle/APK`).
2. On GitHub, go to **Releases → Draft a new release**.
3. Tag it (e.g. `v1.0.0`), give it a title, and **attach**:
   - `VidSecure-Setup.exe`
   - `VidSecure-Player.apk`
4. Publish. The README's download buttons point at `releases/latest`, so they will
   always link to your newest build automatically.

Optional: add screenshots to `assets/` and reference them in the README's Screenshots
section.
