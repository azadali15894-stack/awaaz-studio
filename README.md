# 🎵 Awaaz Studio — Synced Lyrics & Audio Visualizer

An all-in-one, browser-native studio to create cinematic audio-reactive visualizer and synced lyrics videos without installing Python, MoviePy, or heavy editing suites.

Built with **HTML5 Canvas**, **Web Audio API**, **Anime.js**, and **MediaRecorder API**.

---

## ✨ Features

- **Audio-Reactive Visualizers**: 5 built-in responsive themes (Romantic Bokeh, Melancholic Rain, Cyberpunk Pulse, Bass Reactor, and Synthwave Grid) that pulse to bass and frequency bands in real time.
- **Custom Media Backgrounds**: Upload your own cinematic images (AI art, wallpapers) or motion loop videos.
- **Precision Synced Lyrics**: Full timestamp-based syncing `[mm:ss]` with smooth line-by-line animations and active cue highlights.
- **Fancy & Aesthetic Unicode Typography**: 1-click styling including Gothic/Fraktur (𝕿𝖞𝖕𝖊), Cursive Script (𝓣𝔂𝓹𝓮), Tiny Superscript (ᵀʸᵖᵉ), Double-Struck (𝕋𝕪𝕡𝕖), Typewriter, and Bubble letters.
- **Flexible Layout Engine**: 9-point grid alignment, vertical/horizontal offset sliders, text stroke/outlines, glowing shadows, and high-contrast backdrops.
- **Direct Video Export**: Built-in 1-click screen & audio recorder exporting directly to downloadable `.webm` / `.mp4` video files.
- **Mobile PWA Ready**: Fully responsive. Can be added to the mobile home screen as a standalone web app.

---

## 🚀 Live Demo

Check out the live web application here:  
👉 `https://<your-github-username>.github.io/<your-repo-name>/`

---

## 🛠️ How to Use

1. **Load Audio**: Use the built-in ambient demo audio or upload your own `.mp3` / `.wav` song.
2. **Add Lyrics**: Click **Edit Lyrics** and paste your lyrics with timestamps (e.g., `[00:12] Your first lyric line`).
3. **Style & Position**:
   - Choose a visualizer theme or upload a custom image/video background.
   - Adjust font family, aesthetic Unicode style, size, color, stroke, and screen position.
4. **Record Video**:
   - Hit **Record Video** and play the track.
   - The visualizer, custom background, and synced typography render synchronously.
   - Click **Stop Recording** to automatically download your final video.

---

## 💻 Tech Stack

- **Frontend**: Vanilla JavaScript, HTML5, Modern CSS
- **Animation**: [Anime.js](https://animejs.com/)
- **Audio Analysis**: Web Audio API (`AudioContext`, `AnalyserNode`)
- **Video Capture**: Canvas Capture Stream + MediaRecorder API
- **Fonts**: Google Fonts & Unicode Math Alphabets

---

## 📄 License

This project is licensed under the MIT License — feel free to use, modify, and build upon it.
