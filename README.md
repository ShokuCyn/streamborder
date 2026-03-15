# Alive Stream Border

This repository includes a creepy animated browser-source border for Streamlabs:

- File: `alive-border.html`
- Resolution target: 1920x1080 (scales to window size)
- Base look: chunkier purple frame inspired by `stream border.png`
- Mood: unstable CRT / glitch / creepypasta energy with periodic chaos bursts

## Effect highlights

- Motion stack: shake bursts, rotation/skew warp pulses, breathing pulse, chaos surges, and constant micro-jitter on X/Y position
- Color drift: slower/smoother hue/saturation/brightness/contrast shifts with occasional jumpy spikes
- Border depth: thicker, more 3D ring lighting and inner/outer glow shaping
- Subtle Windows 95 flavor: beveled edge lighting and retro corner accent bars layered into the frame
- Texture style: no scanline/striped line overlays; uses soft noise with organic glitch texture
- Donut behavior: floating border donuts grow/shrink, merge into larger donuts, and sometimes split back out into smaller moving donuts
- Artifacts: dead/hot pixels, invert pixels, and medium dead/inverted chunk blocks

## Streamlabs setup

1. Add a **Browser Source**.
2. Point it to local `alive-border.html`.
3. Set Width = `1920`, Height = `1080`.
4. Keep this source above gameplay/camera sources.
5. Optional: enable source restart on scene switch if you want glitch timing to reset.
