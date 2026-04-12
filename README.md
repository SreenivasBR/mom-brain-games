# 🌸 Brain Games

A simple, mobile-friendly brain games app built with love — designed for elderly users to stay entertained and keep their minds sharp.

## Games included

- **Word Puzzle** — Read a clue and tap letter tiles to spell the answer
- **Memory Match** — Flip cards to find matching emoji pairs
- **Picture Quiz** — Look at a picture and pick the correct answer from four options

## Design goals

- Large text and big touch targets, easy for older hands and eyes
- No logins, no ads, no distractions — just games
- Works on any phone or tablet browser, no app install needed
- Gentle encouragement whether the answer is right or wrong

## Tech stack

Plain HTML, CSS, and JavaScript — no frameworks, no dependencies, no build step needed.

## Getting started locally

```bash
git clone https://github.com/YOUR_USERNAME/mom-brain-games.git
cd mom-brain-games
open index.html   # or just double-click the file
```

## Deploying to Digital Ocean App Platform

1. Push this repo to GitHub
2. Go to [cloud.digitalocean.com/apps](https://cloud.digitalocean.com/apps) and click **Create App**
3. Connect your GitHub repo
4. Digital Ocean will auto-detect it as a **Static Site**
5. Set output directory to `/` and deploy

Live in ~2 minutes. Static site hosting on DO App Platform is free.

## Adding to phone home screen

On iPhone: open the app URL in Safari → tap the Share icon → **Add to Home Screen**

On Android: open in Chrome → tap the three-dot menu → **Add to Home Screen**

This gives it an app-like feel with no browser chrome.

## Customising

All game content lives in `index.html` as simple JavaScript arrays — `wordData`, `memEmojis`, and `picData`. You can swap in new words, pictures, or clues without touching anything else.

## Built with

Made with [Claude](https://claude.ai) by Anthropic.
