# 🌙 Lofi Desk — Study With the Vibe
**VishwaNova 2026 · National Level Weboreel AI Hackathon**

> It's 2 AM. There's rain on the window. The lamp is warm. Your notes are open. This is where you do your best work. A fully interactive lo-fi study environment, no downloads required.

## ✨ Features
- 🖥️ **CSS Illustrated Desk Scene:** The entire desk scene — lamp, monitor, plant, notebook, coffee cup, rain-streaked window — is drawn purely in CSS using `div` shapes, `border-radius`, `clip-path`, and layered `box-shadow`. The lamp flickers realistically via a randomized opacity keyframe.
- 🌧️ **Animated Rain Window:** The window pane features streaking rain drawn on Canvas using randomized line velocities, creating a parallax rain depth effect with a fog `filter: blur()` overlay.
- ☕ **Steam Physics:** The coffee cup emits rising steam particles generated on Canvas — each particle drifts with a sine-wave horizontal wobble and fades via `globalAlpha`.
- 🎵 **Lo-Fi Audio Engine:** Three layered ambient tracks (rain, vinyl crackle, ambient hum) play simultaneously via Web Audio API, each independently volume-controlled. A fake vinyl record spins on the desk — clicking it changes the "track".
- 📝 **Sticky Note System:** Click anywhere on the desk to drop a sticky note. Type freely — notes persist in `localStorage`. Drag them to rearrange. Right-click to delete with a crumple animation.
- ⏰ **Pomodoro Timer:** A glowing digital clock on the monitor runs a configurable Pomodoro session tracker — work/break cycles animate the desk lamp color from warm white to cool blue.

## 🛠️ Tech Stack
- **HTML5** — Canvas for rain + steam particles, `localStorage` for sticky note persistence.
- **Vanilla CSS3** — Full scene illustration via CSS shapes, lamp flicker keyframes, glassmorphism note cards.
- **Vanilla JavaScript** — Particle systems, Pomodoro state machine, drag-and-drop note engine.
- **Web Audio API** — Multi-layer ambient audio mixer, `GainNode` per track volume control.

## 📸 Try It Out
Double-click `index.html` in any modern browser. Put on headphones. Get to work.

---
Built with ❤️ for VishwaNova 2026
