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

Levels 1–5 stay open and gentle. From level 6 the challenge ramps: balls speed
up, the chain window shrinks, and **walls** appear (and later move) — they block
chains, so a single big pop no longer clears everything. Powerups counter all of
this, but each extra copy costs more, so you choose rather than buy everything.

## Features

- Smooth `requestAnimationFrame` loop with delta timing
- Glowing balls, particle bursts, score pop-ups
- Generated Web Audio sound effects (toggle with the 🔊 button)
- Responsive, retina-aware canvas
- Start / level-complete / game-over screens with live HUD
- Zero external dependencies — a single self-contained HTML file
