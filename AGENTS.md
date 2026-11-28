# AGENTS.md — Live Subtitles

Instructions for any AI coding agent (Claude, Antigravity, Codex, Copilot…) working in this repo.

## What this project is
A phone web app (similar to Earwig) that listens through the microphone and shows live translated subtitles. Languages in any direction: English, French, German, Spanish, Catalan, Italian, Chinese (Mandarin). The owner's main use: German, Spanish, Catalan and Italian → English.

## Setup
- **One page, no build step:** `index.html` (all the code), `manifest.webmanifest`, icons.
- Hosted free on **GitHub Pages** from `main` / root. A push to `main` updates the live app.
- Works on Android (Chrome) and iPhone (Safari), and can be added to the home screen.
- No server and no account. Speech recognition is done by the phone's browser. Translation runs on the device when the browser supports it, otherwise Google's free web translator, with MyMemory (free) as a backup.

## Project rules
- **Speed first:** subtitles should appear while the person is still talking (grey), then settle into white.
- Large, readable subtitles. Keep the A−/A+ size controls, the original words underneath, History and copy.
- Keep it free and serverless. Don't add a paid speech or translation API without asking the owner.
- Known limit: a web page can't capture sound from other apps; it hears only through the microphone.
- Test on both a real iPhone (Safari) and a real Android phone (Chrome), over HTTPS.

## Rules for all of Daniel's projects (the same in every repo)
- **Free only.** Use free plans and free services. Ask the owner before adding anything paid.
- **No secrets in the repo.** API keys, passwords and tokens go in Cloudflare or GitHub secrets.
- **Keep the owner's private email address out** of the code and the website.
- **Don't break links.** Keep existing URLs, page titles and sitemaps working (Google ranking).
- **`main` is live.** In most repos a push to `main` publishes the site or builds a new app release. Only push work that builds and has been checked.
- **Explain changes simply.** Give a short, plain-language summary of what changed and how to check it.
- **Keep this file current** when the setup changes. Claude reads it through `CLAUDE.md`. Antigravity, Codex and Copilot read `AGENTS.md` directly.
