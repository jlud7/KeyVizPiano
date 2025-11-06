# Zelda Piano Visualizer

An interactive piano visualizer featuring The Legend of Zelda title theme by Koji Kondo.

## Features

- 🎹 Interactive 3-octave piano (C3-C6)
- 🎵 Falling note visualization
- 🎮 Playback controls with seek functionality
- ⚡ Variable speed control (0.5x-2x)
- 📱 Touch-screen compatible
- 🎼 Web Audio API for real-time sound generation

## Quick Start

### Live Demo

Visit the live demo at: [Your Vercel URL will appear here after deployment]

### Local Development

Simply open `index.html` in your web browser, or run a local server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve
```

Then open `http://localhost:8000` in your browser.

## Deployment

### Deploy to Vercel

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

### Deploy to Netlify

1. Install Netlify CLI:
   ```bash
   npm i -g netlify-cli
   ```

2. Deploy:
   ```bash
   netlify deploy
   ```

### GitHub Pages

1. Push to GitHub
2. Go to Settings > Pages
3. Select branch and root directory
4. Your site will be live at `https://[username].github.io/[repo-name]`

## How to Use

1. Click **Play** to start the Zelda theme visualization
2. Click **Stop** to pause
3. Use the **seek bar** to jump to any part of the song
4. Adjust **speed** to play faster or slower
5. Click on **piano keys** to play notes manually

## Technical Details

- Pure HTML/CSS/JavaScript
- No dependencies or build process required
- Uses Web Audio API for sound synthesis
- Responsive design with gradient backgrounds

## Credits

Music: The Legend of Zelda Title Theme by Koji Kondo
