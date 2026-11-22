# Live Subtitles → English

A phone web app that listens through the microphone and shows live English subtitles for speech in German, Spanish, Catalan or Italian.

- Works on Android (Chrome) and iPhone (Safari)
- Add it to your home screen and it opens like a normal app
- Large, adjustable subtitles, the original words shown underneath, a history you can copy, and the screen stays on while it listens
- No server and no account. Speech recognition is done by the phone's browser. Translation runs on the device when the browser supports it, and otherwise uses the free MyMemory service.

## Put it on GitHub (free hosting)

1. On github.com, create a new public repository, for example `live-subtitles`.
2. Click **Add file → Upload files** and upload every file in this folder: `index.html`, `manifest.webmanifest`, `icon.svg`, `icon-180.png`, `icon-512.png` and `README.md`. Then click **Commit changes**.
3. Open **Settings → Pages**. Under **Branch**, pick `main` and `/ (root)`, then click **Save**.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/live-subtitles/`.

The microphone only works over HTTPS, and GitHub Pages provides that automatically.

## Install it on your phone

- **iPhone:** open the link in Safari, tap **Share → Add to Home Screen**.
- **Android:** open the link in Chrome, tap **⋮ → Add to Home screen** (or **Install app**).

The first time you tap **Start listening**, allow microphone access.

## Using it

1. Tap the language being spoken.
2. Tap **Start listening** and hold the phone near the speaker, TV or person talking.
3. English subtitles appear as each sentence finishes. While someone is still talking, the original words show in grey.

Use **A− / A+** (or Settings) to change the subtitle size. **History** keeps what was said on this phone, with buttons to copy it.

## Limits to know

- It listens through the microphone. A web page can't capture sound from other apps the way Earwig does on iPhone. A video playing out loud on the same phone or on a nearby TV or laptop works fine. Headphones won't work, because the microphone can't hear them.
- It needs an internet connection. Most phones send the audio to Google (Android) or Apple (iPhone) to recognise the speech.
- Translation limit: the free online translator allows about 5,000 characters a day. Add an email address in Settings to raise that to about 50,000. In desktop Chrome, translation runs on the device with no limit.
- Catalan recognition depends on the phone. If it's missing, check that Catalan is enabled for dictation or voice typing in the phone's keyboard settings.
