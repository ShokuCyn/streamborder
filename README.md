# Alive Stream Border

This repository now includes an animated browser-source border for Streamlabs:

- File: `alive-border.html`
- Resolution target: 1920x1080 (scales to window size)
- Style: slightly chunkier purple border based on `stream border.png`
- Animation: subtle breathing/flicker, scanline movement, occasional dead/hot/inverted pixels for a creepy glitch vibe

## Streamlabs setup

1. Add a **Browser Source**.
2. Point it to the local `alive-border.html` file.
3. Set Width = `1920`, Height = `1080`.
4. Enable shutdown/restart source when not visible if you want animation to reset per scene switch.

Tip: Keep this source above your gameplay/camera sources.
