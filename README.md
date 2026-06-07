Pop'em All! — Chain Reaction
============================

A fast, juicy chain-reaction popping game. **One click** sets off the chain:
each ball you pop expands and pops every ball it touches. Build big chains,
hit the level target, and climb through endless levels.

## Play

Open `index.html` in any modern browser — that's it. No build step, no
dependencies, works on desktop and mobile (click or tap).

## How it works

- You get **one** pop per level. Drop it where the most balls will cluster.
- Popped balls expand, hold, then shrink — anything they touch pops too.
- Clear at least the **target** number of balls to advance.
- Longer chains score more; clearing extra balls and higher levels add bonuses.
- Your **best score** is saved locally between sessions.

## Special balls

As you climb, the field mixes in special balls (telegraphed by colour/markers):

- 🟠 **Bomb** — pops with a much bigger blast and bonus points; great chain fuel.
- ⬜ **Stone** — slow, and a chain *dead-end*: it pops but won't trigger others.
- 🟢 **Runner** — fast, and flees from your pops. Hard to catch.
- 🟣 **Splitter** — bursts into two fresh balls that rejoin the reaction.

## Scaling difficulty

From level 3, **walls** appear — drawn from a library of partially-randomized
layouts (splits, crosses, pillars, serpentine lanes, diagonals, open boxes,
pinwheels) that grows more varied and elaborate as you climb, with some bars
oscillating. Walls block chains **and explosions** — a pop can't reach (or even
render) past a wall, so a single big blast no longer clears everything. From
level 6 balls also speed up and the chain window shrinks. Powerups counter all
of this, but each extra copy costs more, so you choose rather than buy everything.

## Features

- Smooth `requestAnimationFrame` loop with delta timing
- Glowing balls, particle bursts, score pop-ups
- Harmonic Web Audio sound: each ball's **colour maps to a note** in a C-major
  pentatonic scale, so chains play in harmony — warm plucked voices with stereo
  panning and reverb, and a signature tone per special ball (toggle with 🔊)
- Responsive, retina-aware canvas
- Start / level-complete / game-over screens with live HUD
- Zero external dependencies — a single self-contained HTML file
