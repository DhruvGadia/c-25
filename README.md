# Crumpled Balls — Physics Demo

A small interactive browser project showing a paper ball being launched toward a dustbin. It uses **Matter.js** for physics and **p5.js** to draw the scene.

## What it does

- Simulates a paper ball as a dynamic physics body
- Creates a ground and barriers around the bin
- Displays paper and dustbin images
- Applies a force to the paper ball when the up-arrow key is pressed

## How to run

1. Download or clone this repository.
2. Open the project folder.
3. Start a simple local web server:

   ```bash
   python -m http.server 8000
   ```

4. Open **http://localhost:8000/** in your browser.

Python is required only for this example local server. The project includes the JavaScript libraries it references; no npm installation or build step is required.

## Controls

**Up arrow** — Apply an upward/rightward force to the paper ball.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Loads the project scripts |
| `sketch.js` | Sets up and draws the physics simulation |
| `ground.js` | Defines the static ground and bin barriers |
| `matter.js` | Bundled physics library |
| `p5.js` | Bundled drawing library |
| `paper.png`, `dustbin.png` | Scene images |

## Notes

The canvas is fixed at 1600 × 700 and is not designed as a responsive mobile layout. This is a learning/demo project rather than a complete game with scoring or multiple levels.
