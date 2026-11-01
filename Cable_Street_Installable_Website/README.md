# Cable Street — installable website (PWA)

This folder contains the ready-to-host app. Upload **all files together** to a static HTTPS host, maintaining the folder structure. The hosting URL is the shareable link for your guild.

- `index.html`: complete app with 12 chapters and 11 heroes
- `manifest.webmanifest`: home-screen app name, colors and icons
- `sw.js`: service worker for offline access
- `icons/`: install icons

## Install on a phone
Android Chrome: open hosted site, then browser menu → Install app (or use the Install Cable Street button when visible).
iPhone Safari: open hosted site, Share → Add to Home Screen.

## Daily stories
The home page cycles through **existing** chapters daily, beginning November 1, 2026. It does not generate new stories or send notifications. Publishing additional chapters requires updating `index.html` and redeploying.

## Important
PWA installation and offline reading require hosting over HTTPS (or localhost for testing). Opening the HTML file from a local file path does not enable those capabilities.
The work is an unofficial Warcraft fan project.
