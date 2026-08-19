<div align="center">
  <img src="frames/storm.jpg" alt="Uchiha Itachi" width="100%" style="border-radius: 8px; margin-bottom: 20px;">
</div>

# Uchiha Itachi — 写輪眼 (Cinematic Web Experience)

A highly interactive, visually striking tribute to Uchiha Itachi from Naruto. This project is a premium front-end experience built from scratch using raw WebGL, HTML5 Canvas, and scroll-driven choreography. 

It aims to capture the dark, atmospheric essence of Itachi's character through immersive visual effects and dynamic user interactions.

## 🌟 Features

- **Scroll-Scrubbed Canvas (Act I):** High-performance scroll-driven video playback (image sequence scrubbing) with synchronized typographic phase reveals.
- **Mouse-Tracked Eyes (Act II):** The Mangekyō Sharingan tracks your cursor across the screen using a mapped Gaze Lookup Table (LUT).
- **WebGL Ghost Cursor (Act III):** A custom WebGL shader (port of fluid smoke/fbm algorithms) that creates a trailing, additive blood-red "ghost" cursor which interacts with the Jutsu cards.
- **Procedural Amaterasu (Canvas):** A highly optimized, procedural black flame engine (Amaterasu) that burns endlessly at the bottom of the screen using stacked radial gradients and phase animation.
- **Dynamic Storm & Synthesized Thunder:** Procedurally generated lightning bolts via SVG paths and a custom Web Audio API synthesizer that generates thunder sounds (sub-bass rumbles and high-pass cracks) without any audio files.
- **Premium Typography & Aesthetics:** Curated Japanese and English typography (Shippori Mincho, Zen Kaku Gothic New, Cinzel) combined with glassmorphism, film grain, and cinematic vignettes.

## 🛠️ Technology Stack

- **Core:** HTML5, Vanilla JavaScript (ES6+)
- **Styling:** CSS3 (Custom Properties, Grid, Flexbox, Animations)
- **Graphics & Shaders:** Raw WebGL, HTML5 `<canvas>`, SVG
- **Audio:** Web Audio API (Procedural sound synthesis)
- **Zero Dependencies:** No external libraries or frameworks were used.

## 🚀 Getting Started

Simply open `index.html` in any modern web browser. Since the project uses ES6 modules and fetches local image frames for the canvas scrubbing, you may need to serve it via a local development server to bypass CORS restrictions for the images:

```bash
# If using Node.js/npm:
npx serve .

# Or using Python 3:
python -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser.

## 📂 Project Structure

- `index.html` — The core markup and SVG definitions.
- `style.css` — All layout, typography, animations, and responsive breakpoints.
- `main.js` — The logic engine driving the WebGL cursor, canvas animations, scroll syncing, and audio generation.
- `frames/` — Image sequences used for the scroll-scrubbing (Act I) and eye-tracking (Act II).

## 📜 License

This project is created as a fan-made tribute. All character rights belong to Masashi Kishimoto and Shueisha.
