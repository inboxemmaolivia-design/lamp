# The Reading Lamp — an interactive study

A single self-contained HTML file: a cinematic, physically-lit Three.js scene
of a standing lamp with a real Verlet-physics pull cord.

## Run it
Just open `index.html` in a modern browser (Chrome, Firefox, Safari, or Edge).
No build step, no dependencies to install — Three.js and GSAP load from CDN
at runtime, everything else (textures, environment lighting) is generated
procedurally in-browser.

## Interact
Click and drag the rope's handle downward to pull the switch. Pull far enough
and it triggers — the lamp lights up (or turns off) with a full cinematic
transition: bulb glow, point light, floor pool, wall warmth, and bloom.

## Structure
- `index.html` — the entire experience (HTML, CSS, and a single ES module
  script covering scene setup, lamp geometry, rope physics, the interaction
  state machine, the lighting/mechanical animation timeline, and
  post-processing).
