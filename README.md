# 🎹 Advanced Interactive Piano

A feature-rich, browser-based piano application built with **vanilla JavaScript**, **TailwindCSS**, and the powerful **Tone.js Web Audio** framework. This project showcases dynamic UI generation, advanced audio synthesis, and responsive user interaction—creating a fun and immersive musical tool.

## 🚀 [Live Demo](#)  
_(Replace this link with your actual deployment URL)_

---

## 📖 Description

Not just another virtual piano—this is an **interactive musical instrument** for the web. Designed with a clean, modern interface and built-in audio control, it supports both casual play and deep musical exploration.

You can play it using:
-🖱️ Mouse
-🤳 Touchscreen
-⌨️ Keyboard

---

## ✨ Features

- **🎼 Multi-Octave Keyboard**: Scrollable 4-octave range.
- **🎻 Multiple Instruments**:
  - Acoustic Piano (HQ samples)
  - Music Box
  - Harp
  - Violin
- **🎧 Reverb Toggle**: Add atmospheric space and depth.
- **🎹 Sustain Pedal**: Realistic sustain (disabled where inapplicable, e.g., Violin).
- **🧠 Multi-Input Support**:
  - Mouse clicks
  - Touch (mobile)
  - Computer keyboard (intuitive mappings)
- **📱 Mobile Friendly**: Responsive with rotate prompt for landscape mode.
- **🪄 Handcrafted UI**: Styled with TailwindCSS.

---

## 🛠️ Tech Stack

- **HTML5**: App structure
- **CSS3 + TailwindCSS**: Styling and responsive design
- **JavaScript (ES6+)**: Logic, state management, UI generation
- **Tone.js**: Audio synthesis, sampling, effects

---

## 🔍 How It Works

1. **Dynamic UI**: JavaScript builds the keyboard on load.
2. **Tone.js Audio Engine**:
   - `Tone.Sampler` for realistic instruments
   - `Tone.PolySynth` for synthesized tones
   - Routed through `Tone.Reverb` + master volume
3. **State Variables**: Track instrument, reverb, and sustain.
4. **Event Handling**:
   - Mouse/touch input for note triggering
   - Keyboard input mapping via `keydown`/`keyup`
   - Prevents retriggering via a `Set` of active keys

---

## 🧪 Development Notes

This project was a personal learning journey into:
- Web Audio APIs
- DOM manipulation
- UI/UX design principles  
AI tools (e.g., Gemini) were used as conceptual partners to refine Tone.js architecture and streamline routing logic.

---

## 💻 Run Locally

1. Clone/download this repo
2. Open `index.html` in your browser  
That’s it—start playing!

---

## 🛤️ Future Improvements

- [ ] 🎵 Add Metronome (adjustable BPM)
- [ ] 🎙️ Recording Feature (playback or download)
- [ ] 🎸 More Instruments (organ, guitar, drums)
- [ ] 📊 Audio Visualizer (note reaction display)

---

## 📜 License

Open-source under the [MIT License](http://docs.google.com/LICENSE)  
Feel free to fork, play, and remix! 🎶
