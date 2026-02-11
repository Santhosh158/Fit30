# Fit30 — 30-Day Fat Loss Tracker PWA

A premium, evidence-based fat loss tracker designed for South Asian women. Features daily coaching, meal plans with recipes, gym workouts with exercise explanations, and progress tracking.

## Deploy to GitHub Pages

1. Create a new GitHub repo (e.g., `fit30`)
2. Upload these 2 files to the repo root:
   - `index.html`
   - `sw.js`
3. Go to **Settings → Pages → Source** → select `main` branch → Save
4. Wait ~2 minutes, then visit `https://yourusername.github.io/fit30/`

## Install on iPhone

1. Open the URL in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (square with arrow)
3. Tap **"Add to Home Screen"**
4. It will appear as a native app icon called "Fit30"

## Features

- 📋 **Daily coaching** — unique briefing, do's/don'ts, and meal explanations for each of 30 days
- 🍽️ **32 Indian recipes** — with calories, protein, ingredients, instructions, and *why* each was chosen
- 🏋️ **3 gym routines** (A/B/C) — with exercise explanations, knee modifications, weekly progression
- 📊 **Progress tracking** — weight, waist, hips, 30-day streak grid, weekly notes
- 🎓 **12 science deep-dives** — calorie science, protein, hidden calories, sleep, menstrual cycle, plateaus, and more
- 🔒 **Works offline** — service worker caches the app for offline use
- 💾 **Data persists** — all progress saved in localStorage

## Tech

- Pure HTML/CSS/JS — no React, no build tools, no dependencies
- PWA with inline manifest (blob URL) + companion service worker
- Dark glassmorphic UI inspired by Nike Training Club, Hevy, Fitbod
- iOS-optimized with safe-area-inset support, black-translucent status bar
