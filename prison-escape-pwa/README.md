# Prison Escape - Mobile PWA

A stealth game where you escape prison by avoiding guards and their flashlights.

## Features

- **5 progressively challenging levels**
- **Touch controls** - Virtual joystick + action buttons
- **Sprint mechanic** - Burst of speed (use wisely!)
- **Shadow-casting lights** - Guards' flashlights respect walls
- **Instant detection** - Stay out of the light!
- **Works offline** - Play anywhere after first load
- **Installable** - Add to your home screen like a native app

## How to Install on Your Phone

### Option 1: Host Locally (for testing)

1. Put all files in a folder on your computer
2. Run a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   ```
3. Open your phone browser to `http://YOUR_COMPUTER_IP:8000`
4. The install prompt should appear, or use "Add to Home Screen" in browser menu

### Option 2: Deploy to the Web

Upload all files to any static hosting service:

- **GitHub Pages** (free)
- **Netlify** (free)
- **Vercel** (free)
- **Firebase Hosting** (free tier)
- Any web server

#### GitHub Pages Quick Deploy:
1. Create a new GitHub repository
2. Upload all 5 files to the repo
3. Go to Settings → Pages → Deploy from branch (main)
4. Your PWA will be live at `https://USERNAME.github.io/REPO_NAME`

### Option 3: iPhone/iPad (Safari)
1. Open the hosted URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"

### Option 4: Android (Chrome)
1. Open the hosted URL in Chrome
2. You'll see an "Install" banner, or tap the menu (⋮)
3. Tap "Install app" or "Add to Home screen"

## Files Included

- `index.html` - The complete game
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline play
- `icon-192.png` - App icon (192x192)
- `icon-512.png` - App icon (512x512)

## Controls

**Touch (Mobile):**
- Left joystick: Move
- SPRINT button: Speed burst
- ↻ button: Restart level

**Keyboard (Desktop):**
- WASD / Arrow Keys: Move
- E: Sprint
- R: Restart level

## Game Tips

- Stay OUT of the yellow flashlight beams
- Detection is instant if you're in the light
- Sprint through dark areas only
- Walls block guard vision - use them!
- Reach the green EXIT door

## Requirements

- HTTPS is required for PWA features (or localhost for testing)
- Modern browser (Chrome, Safari, Firefox, Edge)

## Troubleshooting

**Install prompt not showing?**
- Make sure you're using HTTPS
- Clear browser cache and reload
- Check that all files are in the same directory

**Game not loading offline?**
- Open the game online first to cache it
- Wait a few seconds for service worker to install
- Close and reopen the app

Enjoy your escape!
