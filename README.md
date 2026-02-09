# Weight Converter PWA

A Progressive Web App for converting barbell weights into plate combinations.

## Features
- Calculate plate combinations for 45lb and 55lb barbells
- Shows total plates and per-side breakdown
- Visual representation with proportionally-sized circles
- Works offline after installation
- Installable on iPhone as a standalone app

## Deploy to GitHub Pages

### Step 1: Create Icons
1. Open `create-icons.html` in your browser
2. Download both `icon-192.png` and `icon-512.png`
3. Save them in this folder

### Step 2: Initialize Git Repository
```bash
git init
git add .
git commit -m "Initial commit"
```

### Step 3: Create GitHub Repository
1. Go to https://github.com/new
2. Name your repository (e.g., "weight-converter")
3. Don't initialize with README (we already have files)
4. Click "Create repository"

### Step 4: Push to GitHub
Replace `YOUR-USERNAME` and `YOUR-REPO` with your actual GitHub username and repository name:

```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git branch -M main
git push -u origin main
```

### Step 5: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Click "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Click "Save"
6. Wait 1-2 minutes for deployment

### Step 6: Access Your App
Your app will be available at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO/
```

## Install on iPhone

1. Open Safari on your iPhone
2. Go to your GitHub Pages URL
3. Tap the Share button (square with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Tap "Add"
6. The app icon will appear on your home screen

## Files Needed for GitHub Pages
- `index.html` - Main app file
- `manifest.json` - PWA manifest
- `service-worker.js` - Offline functionality
- `icon-192.png` - App icon (192x192)
- `icon-512.png` - App icon (512x512)

## Local Development
To test locally:
```bash
python -m http.server 8000
```
Then open http://localhost:8000 in your browser.

## Updating Your App
After making changes:
```bash
git add .
git commit -m "Description of changes"
git push
```
GitHub Pages will automatically update in 1-2 minutes.
