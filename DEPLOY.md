# Deploy Portfolio Tracker to GitHub Pages

## Quick Setup (5 minutes)

### Step 1: Create a GitHub Repository
Go to https://github.com/new and create a new repo called `portfolio-tracker` (public).

### Step 2: Push this folder to GitHub
Open Terminal and run:

```bash
cd ~/Desktop/"Portfolio History"/portfolio-pwa
git init
git add .
git commit -m "Initial portfolio tracker PWA"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio-tracker.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** > **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch, **/ (root)** folder
5. Click **Save**

Your app will be live at: `https://YOUR_USERNAME.github.io/portfolio-tracker/`

## Install on Your Devices

### Mac:
1. Open the URL in Chrome
2. Click the install icon in the address bar (or Menu > "Install Portfolio Tracker...")
3. It will appear in your Applications and Dock

### iPhone:
1. Open the URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"
5. The app will appear on your home screen with its own icon

## Updating Data
To update your portfolio data, edit `index.html` and push changes:
```bash
cd ~/Desktop/"Portfolio History"/portfolio-pwa
git add . && git commit -m "Update portfolio data" && git push
```
