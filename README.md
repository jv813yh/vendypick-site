# VendyPick — Official Website & Privacy Policy

This repository hosts the official website and Privacy Policy for **VendyPick**, a family-safe local multiplayer finger picker party game for Android. The page is a single, self-contained `index.html` served through **GitHub Pages**, and its public URL is used as the Privacy Policy link in the Google Play Console.

**Tap. Pick. Dare.**

## About VendyPick

VendyPick turns any get-together into a game. Players place fingers on assigned spots, the app randomly picks one player, and the group gets a quick Truth or Dare style prompt.

- 2–10 players in one game
- Configurable rounds (3, 5, 7 or 10) and lives (1–3)
- Question categories: Party, Safe, Know, Action, Deep
- Star scoring — 0 stars costs a life, 1–2 stars are added
- Multiple languages (English, Slovak, and more)
- Plays fully offline, on-device — no account, no ads, no tracking

## What's in this repo

| File | Purpose |
|------|---------|
| `index.html` | The entire website and Privacy Policy in one self-contained file (HTML + CSS + a small vanilla JS animation). No frameworks, no external requests, no cookies, no analytics. |
| `README.md` | This file. |

## Deploy with GitHub Pages

1. Create a public repository and add `index.html` at the **root**.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose the `main` branch and the `/ (root)` folder, then **Save**.
5. Wait a minute, then open the published URL:

   ```
   https://<your-username>.github.io/<repository-name>/
   ```

That URL is what you paste into the **Privacy Policy** field in the Google Play Console.

## Editing the page

A few values you may want to update over time:

- **Contact email** — set to `vendeljozko@gmail.com`. Appears in the Privacy Policy and Support sections.
- **Effective date** — set in the Privacy Policy section (currently `June 13, 2026`). Update it whenever the policy changes.
- **App icon** — the hero has a placeholder labelled "VendyPick App Icon". Replace it with your real icon if you'd like.

All of these are plain text inside `index.html`, so you can edit them directly in the GitHub web editor and commit the change.

## Privacy summary

VendyPick is built to respect privacy by default:

- No account registration required.
- No personal information collected.
- No advertising or analytics SDKs.
- No user tracking, and no selling or sharing of data.
- Gameplay and any player names stay on the device and are never sent to a server.

The full policy is in the **Privacy Policy** section of the page.

## Tech notes

- Single file, no build step, no dependencies.
- Responsive for mobile and desktop.
- Accessible: semantic HTML, keyboard focus styles, and `prefers-reduced-motion` support.
- Safe system fonts only — no external font or asset requests.

## Contact

For support or privacy questions: **vendeljozko@gmail.com**

---

© 2026 VendyPick. All rights reserved.
