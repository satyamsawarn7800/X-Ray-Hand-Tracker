# ✋ Neon Aura AR: Advanced Hand Tracking

A real-time, webcam-based hand tracking experience that runs entirely in the browser. Your hands become glowing neon trails, particles and shockwaves, powered by **MediaPipe Hands** and the HTML5 Canvas API. No install, no backend.

## ✨ Features
- Real-time tracking of up to **two hands** with fingertip trails and glowing skeleton
- **Gesture detection**: Pinch (shockwave burst), Open Hand, Fist, and palms-together power surge
- **5 colour themes**: Rainbow, Cyberpunk, Lava, Ocean, Galaxy
- Live HUD showing hands detected, FPS, current gesture and finger spread %
- Particle system, reactive background and audio feedback
- Mirrored glassmorphism UI

## 🚀 Live Demo
Enable GitHub Pages and open:
`https://<your-username>.github.io/<repo-name>/`

> The camera needs **HTTPS** (GitHub Pages provides it) or `localhost`.

## 🛠 Run Locally
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
python -m http.server 8000
```
Open `http://localhost:8000` and click **Enter Experience**. Allow camera access.

## 🎮 Controls
| Gesture | Effect |
|---|---|
| Move hands | Neon trails follow fingertips |
| Pinch (thumb + index) | Shockwave burst |
| Open hand / Fist | Updates gesture + spread in HUD |
| Palms together | Ambient particle surge |
| Theme buttons (bottom) | Switch colour theme |

## 🧰 Tech Stack
HTML5 · CSS3 · JavaScript · Canvas API · Web Audio API · MediaPipe Hands

## 🔒 Privacy
All processing happens locally in your browser. Video is never uploaded or stored.

## 👤 Author
**Satyam Kumar**: B.Tech CSE, Lovely Professional University

## 📄 License
MIT
