# LE3BA D ZEB ⚡🐍

A single-file cyberpunk neon snake game built with HTML5 Canvas + Web Audio API.

## Features

- **Neon Cyber UI** — animated gradient title, glassmorphism HUD, ambient light orbs
- **4 Power-up Types**:
  - 🔵 **Neon Core** — standard energy cell (+100 pts)
  - 🟡 **Quantum Glitch** — 2x score multiplier for 6s (+200 pts)
  - 🔴 **Supernova Blast** — mega explosion + shockwave (+300 pts)
  - 🟣 **Time Warp** — slow motion for 5s (+250 pts)
- **Creative Eat Effects**: Lightning arcs, particle supernovas, shockwave rings, spine luminescence pulse, screen shake, ambient color shift, floating score popups
- **Combo System** — streak multiplier with visual badge
- **Wall Wrap / Wall Kill** modes
- **Progressive Speed** scaling
- **Synthesized Audio** — 100% procedural Web Audio, no external files
- **Touch Support** — swipe gestures + virtual D-Pad
- **High Score** persistence via localStorage

## Play

Just open `index.html` in any browser — no build step, no dependencies.

```
http://localhost:8080
```

Or serve with:

```bash
node server.js
```

Then open on mobile: `http://<your-local-ip>:8080`

## Controls

| Key | Action |
|-----|--------|
| `↑ ↓ ← →` / `W A S D` | Move snake |
| `SPACE` / `P` | Pause |
| `M` | Toggle sound |
| Swipe | Mobile move |

---

**PRODUCED by AMINE · IDEA by Haytam**
