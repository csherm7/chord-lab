# Chord Lab 🎸🎹

A guitar & piano chord practice tool. Hit the random button, study the voicing.

**Live site:** `https://yourusername.github.io/chord-lab/`

## Features

- Random major/minor chord generator
- Piano keyboard diagram (chord tones + scale tones)
- Guitar chord box with note labels
- Full-neck scale map (frets 0–12, all 6 strings)
- Chord variations: 7th, maj7, sus2, sus4, add9, 6th, aug (major keys) / m7, m9, dim, dim7, sus2, sus4, m6 (minor keys)
- Mini piano + guitar chord diagram for every variation
- Works offline (PWA — installable on phone/desktop)

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Source: **Deploy from branch**, branch: `main`, folder: `/ (root)`
4. Visit `https://yourusername.github.io/chord-lab/`

## Icons (optional)

For a proper PWA icon, add `icon-192.png` and `icon-512.png` to the root folder.  
Simple approach: use a tool like [favicon.io](https://favicon.io) to generate them.

## Local development

No build step needed — just open `index.html` in a browser.  
For service worker to work locally, serve with a local server:

```bash
npx serve .
# or
python3 -m http.server 8080
```
