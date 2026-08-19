# Shot Tracker — Football Coach Tool

A Progressive Web App (PWA) for football coaches to track goal attempts and scored goals on a half-pitch map, with distance-to-goal measurements.

## Features

- 🔵 **Goal Attempt** marker — blue circle with distance to goal
- 🔴 **Goal** marker — red circle with distance to goal
- 📊 **Live stats** — attempt count, goal count, conversion rate
- 💾 **Save** — exports the pitch as a PNG image
- 🔄 **Reset** — clears all markers
- 📱 **Touch & mouse** support (mobile friendly)
- ✈️ **Offline** — works without internet after first load (PWA)

## Deploy to GitHub Pages

### Option A — GitHub Actions (automatic)

1. Create a new GitHub repository (e.g. `shot-tracker`)
2. Push all files to the `main` branch
3. Go to **Settings → Pages**
4. Set source to **"GitHub Actions"**
5. The workflow in `.github/workflows/deploy.yml` will auto-deploy on every push
6. Your app will be live at: `https://YOUR_USERNAME.github.io/shot-tracker/`

### Option B — Manual (gh-pages branch)

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/shot-tracker.git
git push -u origin main

# Then in GitHub Settings → Pages → set source to main branch / root
```

## Local development

Just open `index.html` in any browser. No build step needed.
