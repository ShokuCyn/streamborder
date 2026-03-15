# Alive Stream Border

This repository includes a creepy animated browser-source border for Streamlabs:

- File: `alive-border.html`
- Resolution target: 1920x1080 (scales to window size)
- Base look: chunkier purple frame inspired by `stream border.png`
- Mood: unstable CRT / glitch / creepypasta energy (dialed back from full-chaos mode)

## Effect highlights

- Motion stack: occasional shake bursts, slight rotation/skew warp pulses, breathing pulse, and constant micro-jitter on X/Y position
- Color drift: randomized hue/saturation/brightness/contrast shifts and RGB ghost offsets
- Texture style: no scanline/striped line overlays; uses soft noise and jagged block-edge treatment instead
- Extra glitch motion: faster artifact bursts with subtle frame-coordinate jitter updates
- Artifacts: dead/hot pixels, invert pixels, and medium dead/inverted chunk blocks

## Streamlabs setup

1. Add a **Browser Source**.
2. Point it to local `alive-border.html`.
3. Set Width = `1920`, Height = `1080`.
4. Keep this source above gameplay/camera sources.
5. Optional: enable source restart on scene switch if you want glitch timing to reset.
