# Alive Stream Border

This repository includes an animated browser-source border for Streamlabs:

- File: `alive-border.html`
- Resolution target: 1920x1080 (scales to window size)
- Style: chunkier purple frame based on `stream border.png`
- Vibe: creepy / glitchy and always moving

## Effect highlights

- Subtle living motion: pulse, flicker, and micro-jitter
- Periodic warp/skew pulses so the border briefly bends instead of staying a perfect rectangle
- CRT flavor: rolling scanline, faint TV lines, vignette, and slight RGB ghost shift
- Glitch artifacts: dead pixels, hot pixels, invert pixels, and larger dead/inverted chunk blocks

## Streamlabs setup

1. Add a **Browser Source**.
2. Point it to the local `alive-border.html` file.
3. Set Width = `1920`, Height = `1080`.
4. Keep this source above your gameplay/camera sources.
5. Optional: enable source restart on scene switch if you want glitch timing to reset.
