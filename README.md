# ✨ Awesome Hand Gestures

A curated catalog of browser-based hand-tracking AR experiences powered by **MediaPipe Hands**. No installs required — just open in your browser and use your webcam.

## 🎮 Experiences

| Experience | Description | Gestures |
|---|---|---|
| 🍥 **Ninja Mode** | Naruto Rasengan & Sasuke Chidori effects | Open palm triggers jutsu |
| ✨ **Doctor Strange Shields** | Rotating magic circle mandalas | 6 gestures: open, fist, peace, thumbs up, point, rock |
| 🔮 **Neon Aura AR** | Cyberpunk particles, lightning arcs, matrix rain, audio synth | Pinch, open hand, fist + 5 color themes |
| 🧨 **Magic Draw** | Draw glowing trails, tap fingers for sparkles, or pinch for fireworks | Pinch, index point, finger tap |

## 🚀 How to Use

1. Open `index.html` in your browser (or use a local server)
2. Pick an experience from the catalog
3. Allow camera access
4. Use your hands!

## 📁 Project Structure

```
├── index.html              # Landing page catalog
├── assets/                 # Shared media assets
│   ├── naruto.mp4
│   ├── sasuke.mp4
│   └── magic_circle_*.png
├── naruto/
│   └── naruto.html         # Ninja Mode experience
├── docter-strange/
│   └── magic-shield.html   # Doctor Strange experience
├── neon-aura/
│   └── neon-aura.html      # Neon Aura AR experience
└── magic-draw/
    └── magic-draw.html     # Magic Draw & Fireworks experience
```

## ⚡ Performance

- Uses `modelComplexity: 0` (Lite) for smooth 60fps on mobile
- Particle systems are capped to prevent frame drops
- Camera resolution adapts to portrait/landscape automatically

## 🛠 Tech Stack

- **MediaPipe Hands** — Real-time hand landmark detection
- **Web Audio API** — Reactive audio synthesis (Neon Aura)
- **Canvas 2D** — All visual effects rendered via HTML5 Canvas
- **Zero dependencies** — Pure HTML/CSS/JS, no build tools needed

## 📝 License

MIT