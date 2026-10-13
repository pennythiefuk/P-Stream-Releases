# P-Stream Releases

Official public release repository and plugin update manifest for **P-Stream Android**.

## Install the beta app (Android)

You'll need an Android phone or tablet on **Android 7.0 or newer**. P-Stream isn't on the Play Store, so you install it from a file instead. Android calls this "sideloading". It only takes a couple of minutes.

### 1. Download the app
1. On your phone, open the **[Releases page](https://github.com/pennythiefuk/P-Stream-Releases/releases)**.
2. The newest version is at the top. Under **Assets**, tap the file ending in **`.apk`**, for example `P-Stream-v1.8.0-beta.apk`.
3. If your browser warns that "this type of file can harm your device", tap **Download anyway**. This is the standard warning for any app that doesn't come from the Play Store.

### 2. Open the file
1. When the download finishes, tap **Open** in the pop-up. You can also find the file in your **Files** or **Downloads** app.
2. The first time you install an app this way, Android blocks it and says the browser isn't allowed to install unknown apps. Tap **Settings**, turn on **Allow from this source**, then press **Back**.
   - You only need to do this once. You can turn it off again after installing if you like.
3. Tap **Install**.

### 3. If Play Protect pops up
Google Play Protect may say the app is from an "unknown developer" or offer to scan it. Tap **More details**, then **Install anyway**. If it offers to scan, you can let it scan first; it will still let you install.

### 4. Done
Open **P-Stream** from your app drawer.

### Updating
You don't need to repeat these steps. In the app, go to **Settings**, then **Check for App Update**. It downloads and installs new beta versions for you.

### Good to know
- The first time you open it, it needs an internet connection to download its sources.
- The beta installs **alongside** the regular P-Stream app, so it doesn't replace it and you can keep both.
- Only download P-Stream from this page. Copies from anywhere else could be modified.
- **"App not installed" error?** Make sure you have a little free space, and that the download finished. If you're installing an older beta over a newer one, uninstall the beta first.

## Quick Links
- **Streaming Plugin (app v1.7.7+)**: [plugin-release.js](https://raw.githubusercontent.com/pennythiefuk/P-Stream-Releases/main/plugin-release.js) — readable source; signed, signature in `manifest.json`
- **Plugin Update Manifest**: [manifest.json](https://raw.githubusercontent.com/pennythiefuk/P-Stream-Releases/main/manifest.json)

## How It Works
The P-Stream Android app checks `manifest.json` on this repository to automatically discover and update the streaming provider plugin.
