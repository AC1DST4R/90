# A-90 Simulator

A standalone web-based **A-90 / A-90B simulator** inspired by the entities and mechanics from *DOORS*.

## Features

### A-90

- Spawn A-90 manually with a button.
- Uses the A-90 warning background.
- Randomly flashes between:
  - A-90
  - STOP sign
- Red static and glitch effects.
- `warning.mp3` plays during the warning.
- Mouse movement is detected while A-90 is active.
- Moving during A-90 results in an immediate jumpscare.
- A-90 remains active for the duration of the warning audio.
- Uses `JUMPSCARE.webp` when caught.
- The jumpscare shakes and glitches on screen.
- Jumpscare remains visible for the entire duration of `fail.mp3`.

### A-90B

- Spawn A-90B manually.
- Generates **5–10 random rounds**.
- Each round randomly selects:
  - `HALT.`
  - `PROCEED.`
- Displays the corresponding image.
- Keeps the original colors of the HALT/PROCEED images.
- Uses a typewriter-style font for the `HALT.` / `PROCEED.` text.
- Glitch and flash effects during instructions.
- Plays the corresponding audio:
  - `HALT.ogg`
  - `PROCEED.ogg`
- Includes a 1-second grace period after each instruction.
- Displays A-90B after the instruction.
- **HALT:** Stay completely still.
- **PROCEED:** Move your mouse.
- Moving during HALT results in an `ATTACK.webp` jumpscare.
- Failing to move during PROCEED results in an `ATTACK.webp` jumpscare.
- Jumpscare shakes and glitches like the HALT/PROCEED warnings.
- Jumpscare remains visible for the entire duration of `fail.mp3`.

## Controls

| Button | Action |
|---|---|
| `SPAWN A-90` | Starts an A-90 warning |
| `SPAWN A-90B` | Starts an A-90B sequence |
| `Mouse movement` | Used for A-90 and A-90B mechanics |
