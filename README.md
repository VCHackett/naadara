# NAADARA v1.0
### The world's first open cymatics laboratory

**[▶ Launch Naadara](https://naadara.org)** · [Wiki](https://github.com/VCHackett/naadara/wiki) · [Discord](https://discord.gg/XUAyvZCUdj) · Free · No signup · No download · Runs in your browser

---

Naadara is a real-time cymatics and frequency laboratory built entirely in the browser. Watch sound become geometry. Explore 23 categories of frequencies from the Solfeggio scale to the full Periodic Table of Elements. Generate binaural beats, design tones with a full synth engine, position audio in 3D space with HRTF, route your microphone into a live resonance field, and record everything.

Built by a musician with Synesthesia — Naadara gives everyone a window into what it feels like to see sound.

---

## Features

- **Chladni Field** — Real-time spring-mesh resonance simulation. Nodal lines form standing wave patterns at any frequency
- **23-Category Frequency Library** — Solfeggio, Chakras, Brainwave & Entrainment, Schumann, Planetary, Sacred Geometry, Pythagorean, DNA, Rife, Vedic, Buddhist, Norse, Sufi, Shamanic, Gregorian, Kabbalah, Chinese Five Elements, Bioacoustic, Cymatics Nodes, Musical Harmonics, Alchemical, Sacred Geometry, and the full **Periodic Table of Elements** (atomic chromatic scale: f(Z) = 16 Hz × 2^((Z−1)/12))
- **Binaural Beats** — Per-track L/R frequency offset with sweep mode for brainwave entrainment
- **HRTF 3D Spatial Audio** — Full head-related transfer function positioning with X/Z pad and elevation axis
- **Synth Engine** — Per-track ADSR envelope, biquad filter (LP/HP/BP/Notch), LFO modulation, detune, portamento
- **Display Modes** — Chladni · Lissajous (with 9 geometric shape presets) · Spectrum · Waveform
- **Input Field** — Route live microphone audio through HPF → Drive → LPF → Reverb into the Chladni field
- **Output Calibration** *(Experimental)* — Mic pitch detection with auto-tune for real-world frequency verification
- **Recording & Export** — Live Audio (WebM/Opus) · Video (WebM/VP9 60fps) · A+V combined · Offline WAV · Visualizer video export (HD/FHD)
- **432 Hz Tuning** — Offline pitch shift of any loaded audio file from 440 Hz to 432 Hz
- **10 UI Themes** — Cave · Ocean · Forest · Glacier · Dusk · Sand · River · Meadow · Bamboo · Stone
- **Saved Sessions** — Full state persistence to localStorage
- **WebGL Rendering** — GPU-accelerated Chladni field with multi-tap smoothing, bloom, persistence, and palette system

---

## How to Use

Just open [naadara.org](https://naadara.org) in any modern browser. No installation, no account, no cost.

For the best experience:
- Use **headphones** — required for binaural beats and HRTF 3D spatial audio
- Use **Chrome or Edge** for full WebGL + recording support
- Allow **microphone access** if using Input Field or Output Calibration

---

## Contributing

Naadara is open source and welcomes contributions of all kinds — new frequency entries, bug fixes, feature ideas, UI improvements, documentation, translations.

See **[CONTRIBUTING.md](CONTRIBUTING.md)** for the full guide.

Not a developer? Open an [Issue](https://github.com/VCHackett/naadara/issues) or start a [Discussion](https://github.com/VCHackett/naadara/discussions) — frequency knowledge, research links, and ideas are just as valuable as code.

---

## Tech Stack

Single-file HTML application — no framework, no build step, no dependencies except the Google Fonts CDN.

- **Web Audio API** — oscillators, binaural routing, HRTF PannerNode, OfflineAudioContext, MediaRecorder
- **WebGL** — GPU fragment shader for Chladni field rendering
- **Canvas 2D** — Lissajous, Spectrum, Waveform oscilloscope
- **JavaScript** — Spring-mesh physics simulation at 200×200 resolution (40,000 cells)
- **localStorage** — Session persistence, theme, disclaimer state

---

## Running Locally

No build process needed. Just open the file:

```bash
git clone https://github.com/VCHackett/naadara.git
cd naadara
# Open index.html in your browser
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

Or serve it locally for microphone/recording features (some browsers require HTTPS or localhost):

```bash
python3 -m http.server 8080
# Then open http://localhost:8080
```

---

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START -->
**V.C. Hackett** — Creator & maintainer
<!-- ALL-CONTRIBUTORS-LIST:END -->

Want to see your name here? Check out [CONTRIBUTING.md](CONTRIBUTING.md).

---

## Licence

**MIT Licence** — free to use, study, modify, and share. Your name stays on it. See [LICENSE](LICENSE) for full text.

---

## About the Creator

Built by **V.C. Hackett** — musician, father of two, lifetime conspiracy enthusiast, and Synesthete. I visualise sound as geometry and colour. Naadara is my attempt to share that experience with everyone.

[naadara.org](https://naadara.org) · [Instagram](https://instagram.com/VCHackett) · [YouTube](https://youtube.com/@VCHackett) · [Twitch](https://twitch.tv/VCHackett)
