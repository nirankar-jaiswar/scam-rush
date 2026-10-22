# Scam Rush — Catch the Phish!

A lightweight, single-file browser game that puts you in the role of a digital scam detective. Sort 12 fictional New Zealand-inspired SMS and email messages as **SCAM** or **SAFE** before the 60-second timer runs out. Earn points, build streaks, and protect your three lives.

Messages feature familiar scenarios involving Inland Revenue, NZ Post, NZTA, bank alerts, and family emergencies. Scam examples use reserved `example.com` domains and have no clickable links. All game HTML, CSS, and JavaScript are contained in `index.html`; there are no external libraries, services, or other game assets.

## How to play

- Select **Start Game**, then classify each message with the **SCAM** or **SAFE** buttons.
- Press **S** for SCAM or **L** for SAFE. Press **Enter** to start or restart.
- Correct answers earn 100 points. Consecutive correct answers add a streak bonus.
- An incorrect answer costs one of your three lives. The round ends after 12 messages, when time runs out, or when all lives are lost.
- Your high score is saved in your browser's local storage.

## Run locally

1. Download or clone this repository.
2. Open `index.html` directly in Chrome or another modern browser.

No installation, build step, server, or internet connection is required to play locally.

## GitHub Pages

The GitHub Actions workflow in `.github/workflows/pages.yml` validates the inline game script on pull requests and publishes `index.html` to GitHub Pages when changes are pushed to `main`. A manual run is also available from the repository's **Actions** tab when run on `main`. After the first successful deployment, the public game is available at:

<https://nirankar-jaiswar.github.io/scam-rush/>

## Safety note

This is a training game, not official security advice. When a real message is unexpected or urgent, contact the organisation or person using contact details you find independently.
