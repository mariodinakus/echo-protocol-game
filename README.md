# ECHO — Time Loop Protocol

**Playable 2D time-loop action puzzle game** with 10 levels. Runs on desktop and mobile in a modern browser.

## How to play
- **WASD / arrows** — Move
- **Q** — Record your current movement and rewind, leaving behind an echo that repeats that trajectory
- **Shift** — Dash
- **P** or **Space** — Pause
- **R** — Restart
- On mobile use the on-screen D-pad, DASH and CREATE ECHO buttons.

In the first chamber stand on the glowing pressure pad and press Q. Your echo will replay your actions and keep the gate open while you pass through to the goal.

## Deployment (Vercel)
This repository is a self-contained **static HTML5 game**, with no dependencies, server, API key, or compilation.
1. Visit https://vercel.com/new
2. Import `mariodinakus/echo-protocol-game` from GitHub.
3. Choose **Other** as framework, `./` as root, and **leave build and output directory empty**.
4. Deploy. Subsequent commits to `main` will deploy automatically when Git integration is connected.

## Local development
Open `index.html` in your browser. This version bundles the game, styles and logic into one file; no build step is required.

## Notes
- Save data and sound preference are stored **only in the user's local browser**.
- This is **single-player**. It does not promise multiplayer or a cloud account.
- Original game code and artwork, copyright 2026. All rights reserved.
