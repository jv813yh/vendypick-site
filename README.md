# VendyPick — Official Website & Privacy Policy

![VendyPick — Tap. Pick. Dare.](feature-graphic.png)

This repository hosts the official website and privacy policy for **VendyPick**, a family-safe local multiplayer *finger-picker* party game for Android. The page is a single, self-contained `index.html` served through **GitHub Pages** — no build step, no dependencies, and no third-party requests.

**Tap. Pick. Dare.**

## About VendyPick

VendyPick turns any gathering into a game. Everyone puts a finger on the screen, the app randomly picks one player, and that player gets a quick Truth-or-Dare style prompt. One phone, passed around the group — that's the whole setup.

- **2–10 players** on a single device
- **Configurable rounds** (3, 5, 7 or 10) and **lives** (1–3)
- **Five worlds** of questions — Party, Safe, Know, Action, Deep — with dozens of categories you can switch on and off
- **8 languages**, each with its own hand-localized question bank: English, Slovak, German, Spanish, Polish, Czech, French, Italian
- **Star scoring** — a round is worth 0, 1 or 2 stars; 0 stars costs a life
- **The Joker** — once per game from round 2, a player can spend a life to make sure they get picked
- **Plays fully offline, on-device** — no account, no ads, no tracking

## Privacy

VendyPick is built privacy-first. There is no account, no sign-up, and no personal data collection. Player names and gameplay never leave the device. The app contains no advertising or analytics SDKs, and it doesn't need an internet connection to play. This website itself loads no third-party resources.

The full privacy policy is published on the site (`index.html`) and is intended to be used as the privacy-policy URL in the Google Play Console.

## Repository Contents

| File | Purpose |
|------|---------|
| `index.html` | Complete website and privacy policy in a single file |
| `feature-graphic.png` | Neon banner (1024×500) shown lower down as the closing visual |
| `screenshots/dare.jpg` | Round result (Dare + scoring) used in "Every round, a new challenge" |
| `screenshots/menu.jpg` | Setup screen used in "Set up in seconds" |
| `screenshots/lang.jpg` | Language selection used in "Play in your language" |
| `README.md` | This documentation |

The hero contains a small **interactive "pick a player" demo** (three glowing spots + a button that runs a random-pick roulette). It is plain inline JavaScript — no libraries, no build step, and it respects `prefers-reduced-motion`.

**When the app goes live on Google Play:** in the `#download` section, replace the placeholder `<span class="gp-btn is-soon">…</span>` with `<a class="gp-btn" href="STORE_URL_HERE">…</a>` (keep the same inner markup) and change the "Coming soon to" line to "Get it on". An HTML comment in that section marks the exact spot.

> The page loads no third-party resources — every image is same-origin (`feature-graphic.png` and the three screenshots in `screenshots/`) and all CSS/JS is inline. Keep those files next to `index.html` when you deploy.

## Editing

`index.html` is plain HTML with inline CSS — open it in any editor and change the copy directly. There is nothing to build or install; commit the file and GitHub Pages serves it.

## Contact

vendeljozko@gmail.com

© 2026 VendyPick. All rights reserved.
