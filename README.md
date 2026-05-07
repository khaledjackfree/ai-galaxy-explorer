# 🌌 AI Galaxy Explorer

> **An interactive 3D procedural galaxy** — designed, coded, and deployed autonomously by **BU**, a [Browser-Use](https://browser-use.com) AI agent, in a single conversation.

[**▶ Open the live demo**](https://khaledjackfree.github.io/ai-galaxy-explorer/) *(enable GitHub Pages → branch `main` → root)*

![Three.js](https://img.shields.io/badge/Three.js-r160-7df9ff?style=for-the-badge) ![Built by AI](https://img.shields.io/badge/Built%20by-BU%20AI%20Agent-ff7df9?style=for-the-badge)

---

## ✨ What's inside

A real-time procedural spiral galaxy renderer built with **Three.js + WebGL postprocessing (Unreal Bloom)**. Tens of thousands of stars are generated mathematically with logarithmic spiral arms, color gradients from core to rim, and additive blending for that cinematic glow.

### 🎮 Controls
- **Drag** to orbit the galaxy
- **Scroll** to zoom in / out
- **Sliders** tweak star count, spiral arms, spin curvature, and hue in real time

### 🧠 Why this project?
The user asked: *"create a new repo and put anything that shows your power and intelligence."*
So the agent:
1. Listed all repositories via the GitHub API
2. Created this fresh repository
3. Designed an interactive WebGL scene from scratch
4. Wrote clean ES modules with import maps and post-processing
5. Committed everything via API calls — **zero human keystrokes**

### 🛠 Stack
- Three.js r160 (ES modules via import-maps)
- EffectComposer + UnrealBloomPass
- OrbitControls
- Pure HTML/CSS/JS — no build step

### 🚀 Run locally
```bash
git clone https://github.com/khaledjackfree/ai-galaxy-explorer.git
cd ai-galaxy-explorer
python -m http.server 8000
# open http://localhost:8000
```

### 🌐 Deploy on GitHub Pages
Settings → Pages → Source: `main` / `/ (root)` → Save.

---

Made with ❤️ by an autonomous agent. Fork, remix, send it to the stars. 🌠
