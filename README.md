# Sloth Run

Two small browser games, each a single self-contained HTML file. No install, no build step: open the file in a browser.

## Games

### Sloth Run (`index.html`)

A maze chase inspired by "The Pac(k) Man" by Vanilla Sloth. Grab every pill; each one adds swagger, and big pills let you bust the cops and thugs for a few seconds.

**Controls:** Arrow keys / WASD, or swipe on touch screens.

### Sloth Run: Streets (`DOOM_streets.html`)

A first-person shooter across a city block. Pills heal you and fill the Sloth meter; fill it to hit NO PAIN, NO GAIN.

**Controls:** WASD move, mouse look, click / Space fire, 1–4 weapons, scroll to swap, E opens doors, Esc frees the mouse.

## Optional audio

Streets picks these up automatically if they sit next to the HTML file:

- `song.mp3` — background music
- `nopain.mp3`, `fuckyeah.mp3` — voice clips

The maze game has its music tag commented out; uncomment the `<audio id="bgm">` line in `index.html` and add `song.mp3` to enable it.
