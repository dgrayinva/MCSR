# House Radio Recycler (`MCSR`)

A lightweight, single-page web app hosted on GitHub Pages that randomly rotates through my favorite house music radio shows on SoundCloud without repeating a show until the full rotation cycle is complete.

**Live App:** https://dgrayinva.github.io/MCSR/

## Features

- **No-Repeat Cycle Rotation:** Randomly selects an enabled radio show and tracks cycle progress (`0 / 7 heard this cycle`) so every show plays once before repeating.
- **Direct SoundCloud App Handoff:** Opens directly into the native SoundCloud mobile app on iOS/Android or a new browser tab on desktop.
- **In-Progress Session Memory:** Keeps an active 1–2 hour show pinned at the top across browser restarts until marked finished.
- **Pin Exact Episode Links:** Paste a direct episode Share link to override the main feed and jump straight back into an unfinished episode.
- **Persistent Checkmarks & Episode Log:** Displays green checkmarks (`✓`) and a running `Heard:` history of episode numbers or dates for each show.
- **Custom Pool Management:** Toggle shows in and out of rotation with checkboxes, or add new SoundCloud profile/playlist URLs anytime.

## Default Radio Shows Included

1. **Black Legend** — *The Legendary Radio Show*
2. **Defected Records** — *Defected Radio Show*
3. **Motive Records** — *Motive Radio Show*
4. **Ricardo Torres** — *The NDYD Radio Show*
5. **Wh0 Plays Sessions**
6. **HouseBound Radio Show**
7. **Moulton Music** — *Moulton Radio*

## How It Works

- Built as a zero-dependency, single-file `index.html` app (HTML, CSS, and vanilla JavaScript).
- Uses browser `localStorage` to save show preferences, cycle state, pinned links, and episode notes locally on your device—no backend server, database, or SoundCloud API keys required.

## Recommended Mobile Setup

1. Open https://dgrayinva.github.io/MCSR/ in your mobile browser (avoid Private/Incognito tabs so `localStorage` persists).
2. Add the page to your phone's **Home Screen** for quick one-tap access before driving or listening.
3. *(Optional)* In the SoundCloud mobile app, go to **Settings → Basic Settings** and turn **Autoplay related tracks** off so playback stops cleanly at the end of a radio show.

