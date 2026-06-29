# Flappy Dunk

A single-file HTML5 canvas basketball game built for TikTok Live streaming.

## Play

Open `index.html` in any modern browser — no build step, no dependencies.

## Controls

- **Space / ↑ / click** — flap the ball
- **Esc** — pause / resume
- **Ctrl + M** — open the options menu

### Stream controls (configurable in the options menu)

- **Boosts** — four configurable point boosts (two forward `+`, two backward `−`) with custom amounts and rebindable keys
- **2× Points** — 15-second double-points window (default `D`)
- **Reset** — 60-second countdown that freezes the game and resets the score (default `R`)
- **Save** — cancels an active reset (default `S`)
- **World Record** — manually set the on-screen world record value

## Features

- Full-screen 3D hoops with pass-through illusion
- Moving hoops (vertical and diagonal paths)
- Combo / streak multipliers — only clean center passes keep a streak alive
- Death only on ceiling contact; floor/miss costs points instead of ending the run
- Draggable, resizable HUD pills (Score, Personal Best, World Record)
- Synthesized audio via the Web Audio API
