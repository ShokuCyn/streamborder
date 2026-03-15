# Alive Stream Border

This repository includes an intentionally chaotic browser-source border for Streamlabs:

- File: `alive-border.html`
- Resolution target: 1920x1080 (scales to window size)
- Base look: chunkier purple frame inspired by `stream border.png`
- Mood: unstable CRT / glitch / creepypasta energy

## Effect highlights

- Motion stack: shaking bursts, slight rotation/skew warp pulses, micro-jitter, and breathing pulse
- Color abuse: randomized hue/saturation/brightness/contrast shifts and RGB ghost offsets
- CRT damage: rolling scanline, TV-line texture, vignette darkening, and wave-like distortion
- Artifact spam: dead/hot pixels, invert pixels, and larger dead/inverted chunk blocks
- Channel-dead interruptions: occasional old-TV color bars with NO SIGNAL flashes

## Streamlabs setup

1. Add a **Browser Source**.
2. Point it to local `alive-border.html`.
3. Set Width = `1920`, Height = `1080`.
4. Keep this source above gameplay/camera sources.
5. Optional: enable source restart on scene switch if you want glitch timing to reset.
