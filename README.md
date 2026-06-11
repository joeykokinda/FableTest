# NIGHTDIAL

A radio for the frequencies between frequencies.

Single-page interactive experience. The whole site is an analog tuner sweeping 87.0 to 108.0 MHz. Six living stations hide in the static:

| Freq | Station | What it does |
|------|---------|--------------|
| 88.3 | THE RAIN | Code rain that is afraid of your cursor. Click to scatter it. |
| 91.7 | BLOOM | Conway's Game of Life as a garden. Paint cells with your cursor. |
| 95.5 | COLLAPSE | Click to place singularities. They grow as they eat particles. |
| 99.1 | THE GHOST | An endless typewriter. Type and it answers. |
| 103.9 | FIRMAMENT | Click stars into the sky. Four nearby become a named constellation. |
| 107.7 | THE EYE | It follows your cursor. Move fast and it flinches. Click and it blinks. |

There is also something at the very bottom of the dial.

Scroll to tune, drag the dial, space to scan, arrows to fine-tune, M to mute. Discovered stations are marked on the dial and remembered in localStorage. WebAudio drones and tuning static throughout.

Zero dependencies, one `index.html`, vanilla Canvas 2D + WebAudio.
