# ForgePod

**Run a Commander (EDH) tournament from one browser tab — fully offline.**

ForgePod is a single, self-contained web app for running Swiss-pod EDH/cEDH events at your local game store. No install, no accounts, no internet required. Everything is saved on the device you run it on.

👉 **Live app:** _(your GitHub Pages URL, e.g. https://your-username.github.io/forgepod-app/)_

---

## What it does

- **Create events** and add players — with **Scryfall commander autocomplete** (including partner `//` pairs) and one-tap re-add of returning regulars.
- **Real Swiss pairing** — 4- and 3-player pods, byes only when unavoidable, avoids repeat pod-mates.
- **Run rounds** — tap a winner, declare a full-pod draw, undo, swap players between pods, and a **fullscreen pop-out timer** for a projector.
- **Live standings** — proper cEDH scoring (Win 5 / Draw 1 / Bye 5) and the full tie-breaker chain, with a tap-to-open *"why am I ranked here?"* explanation and a Top-N cut line.
- **Finals** — cut to Top N, then finalize to lock the event.
- **Community profiles** — lifetime and per-commander win/loss records across every event.
- **Export** standings to clipboard or CSV, and **Present** a live standings board on a second monitor.

## How to use it

1. Open the app (the link above).
2. **New event** → add players → **Start Tournament**.
3. Enter results each round → **Pair next round** → **Cut to Top N** → **Finalize**.
4. Check the **Community** tab for player history.

That's it. Your data lives in this browser, on this device.

## Good to know

- **Single device.** Data is stored in your browser's local storage — it is **not** synced between people or machines. Run the event from one laptop. (The multi-device "players join from their phones over store WiFi" experience is a separate, server-based version.)
- **Offline-first.** After the page loads once, it works with the internet off. (Commander autocomplete is the only online feature; without internet you just type commander names by hand.)
- **Clearing your browser data will erase your events.** Use the CSV export to keep a record.

## Feedback

This is an early release being tested at real events. Found a bug or have a request? **[Send feedback (Google Form)](https://forms.gle/GhFNkUJMNtLFW4Tv7)** — no account needed. There's also a **Feedback** link in the app's top bar. Pairings, scoring edge cases, and TO workflow notes are especially welcome.

## Updating

The whole app is the single `index.html` file. To update, replace it with a new build and GitHub Pages redeploys automatically.

---

_ForgePod v1.0 — built for the LGS scene._
