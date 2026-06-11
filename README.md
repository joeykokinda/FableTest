# NIGHTDIAL

A radio for the frequencies between frequencies.

Single-page interactive experience. The whole site is an analog tuner sweeping 87.0 to 108.0 MHz. Eleven living stations hide in the static:

| Freq | Station | What it does |
|-------|---------|--------------|
| 88.3 | THE RAIN | Code rain that is afraid of your cursor. Click to scatter it. Words fall in it sometimes. |
| 89.9 | EMBER | Your cursor burns. Paint fire in the air, click to detonate, wind follows your hand. |
| 91.7 | BLOOM | Conway's Game of Life as a garden. Paint cells, plant a glider gun with G, reseed with R. |
| 93.3 | SWARM | Creatures that evolve based on how you move. Gentle hands tame them. Click to feed. |
| 95.5 | COLLAPSE | Click to place singularities. They grow as they eat, and they merge. |
| 97.3 | MIRROR | Phantoms replay your cursor from 3 and 7 seconds ago. One of them sometimes is not you. |
| 99.1 | THE GHOST | An endless typewriter. Type and it answers. It knows which stations you have found. |
| 101.1 | NUMBERS | A numbers station that speaks. Press digits and it repeats you. Write the groups down. |
| 103.9 | FIRMAMENT | Click stars into the sky. Four nearby become a named constellation, under the aurora. |
| 105.3 | UNDERTOW | A deep sea. Jellyfish follow your light. Click sends a sonar ping. Something big is down there. |
| 107.7 | THE EYE | It follows. It dilates when you approach. Watch long enough and others open. |

There is something at the very bottom of the dial. And when you have found all eleven, listen to the numbers again: they change, the ghost starts giving directions, and a thirteenth station opens in the exact middle of the dial.

Scroll to tune, drag the dial, space to scan, arrows to fine-tune, M to mute. Discovered stations are marked on the dial and remembered in localStorage. Idle for 45 seconds and the radio starts tuning itself. Frequencies deep-link via URL hash (`#99.1`). WebAudio drones, speech synthesis, sonar pings, heartbeats, and tuning static throughout.

Zero dependencies, one `index.html`, vanilla Canvas 2D + WebAudio.
