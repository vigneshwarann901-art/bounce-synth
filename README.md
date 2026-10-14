# Bounce Synth

A musical physics puzzle and sandbox game built with HTML, CSS, Canvas, and the Web Audio API.

## Features

- Six puzzle levels plus a free sandbox studio
- Draw musical strings to bounce the orbs toward the portal
- Three string/instrument types: Synth Pluck, Super Bass, and Boost Bell
- Procedural audio using the Web Audio API
- Selectable musical scales and adjustable spawn tempo
- Undo, clear, erase, and mute controls
- Keyboard shortcuts: `1` Synth Pluck, `2` Super Bass, `3` Boost Bell, `4` or `E` Erase, `Ctrl+Z` Undo
- Canvas-based visuals with particle effects and animated portals

## Run locally

No build step is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Interact with the canvas to draw strings. Audio starts after your first interaction, as required by browser autoplay policies.

The page loads Tailwind CSS and Google Fonts from external CDNs, so an internet connection is needed for those styling resources. The game logic and sound synthesis are contained in `index.html`.

## Publish with GitHub Pages

1. Push these files to a GitHub repository.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.
5. Wait for GitHub Pages to publish the site. The URL will appear in the Pages settings.

## Controls

- **Left-drag:** Draw a musical string
- **Right-drag** or choose **Erase:** Remove strings
- **Sandbox:** Drag emitters and the portal to reposition them
- **Scale:** Change the musical note set
- **Tempo:** Adjust orb spawn rate (visible on wider screens)

## Technology

- HTML5
- CSS and Tailwind CSS CDN
- HTML Canvas 2D API
- Web Audio API
- Vanilla JavaScript

## Credits

Created with assistance from Google's Gemini. Game code and design should be reviewed by the project owner before public distribution.
