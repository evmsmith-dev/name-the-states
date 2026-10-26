# Name the States

A map quiz for the 50 US states and their capitals. It installs as an app on phones and computers and works offline.

## Put it on GitHub Pages

1. On github.com, create a new **public** repository, for example `name-the-states`.
2. On the empty repository page, click **uploading an existing file**.
3. Click **choose your files**, select **all 15 files** (Ctrl+A on Windows, Cmd+A on Mac), and click **Open**. Then click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, and click **Save**.
5. After a minute or two the page shows your link: `https://YOUR-USERNAME.github.io/name-the-states/`

## Install it

- **iPhone / iPad (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap **⋮**, then **Install app** (or **Add to Home screen**).
- **Computer (Chrome or Edge):** click the install icon at the right end of the address bar.

## Updating

Upload the changed `index.html` to the same repository, replacing the old one. Every new `index.html` carries its own version stamp.

When someone opens the app, or switches back to it, it checks for a new version at most once an hour. If there is one, a banner says **A new version is ready**, and tapping **Update** loads it. GitHub can take up to about 10 minutes after an upload before the new file is visible.

## Files

| File | Purpose |
|---|---|
| `index.html` | The game |
| `manifest.webmanifest` | App name, colors and icons for installing |
| `sw.js` | Offline support |
| `icon*.png`, `icon.svg`, `apple-touch-icon.png`, `favicon-32.png` | App icons for iPhone, Android and browsers |
| `*.woff2` | The game's fonts, stored locally so it works offline |
