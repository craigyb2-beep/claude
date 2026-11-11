# Pinball load queue

Things to load on the pinball machine. Added from the "Pinball machine queue"
session; handed off to the pinball PC's Claude session ("Pinball table library
cleanup") when back at the machine.

## How the handoff works

- In the queue session, say "hand off" — the pending items get sent as a
  message to the pinball PC's session, then moved to **Sent** below.
- Or, at the machine, tell that session to read this file from
  `craigyb2-beep/claude` → `pinball/QUEUE.md`.

## Pending

_(nothing yet)_

<!-- Item format:
- [ ] Name — type (table / ROM / backglass / DMD / PUP pack / mod) — source link or notes
-->

## Sent

Handed off 2026-11-11 to "Pinball table library cleanup":

- [x] **Time Machine (Data East 1988)** v2.4.2 by RobbyKingpin — VPX table
  - https://vpuniverse.com/files/file/24756-time-machine-data-east-1988/
  - Update (if already installed): baked textures for sidewalls, blades, plastics, decals, metals, wires, ramps, playfield shadows; new VR room (tribute to Rawd)
  - Check for ROM (`tmach_a4` or similar, Data East) and backglass/DMD if not already present
- [x] **Gravity Falls** (original theme) by Rulo12mayo — **Future Pinball** table (FizX physics), not VPX
  - https://pinballnirvana.com/forums/resources/gravity-falls.8863/
  - Pinball Nirvana downloads usually need a site login
  - Needs Future Pinball + BAM/FizX set up on the cabinet; check the frontend can launch FP tables
- [x] **World Poker Tour (Stern 2006)** v2.4.1 by RobbyKingpin — VPX table
  - https://vpuniverse.com/files/file/26237-world-poker-tour-stern-2006/
  - Update (if already installed): baked textures for sidewalls, blades, backpanel, plastics, decals, metals, wires, ramps, playfield shadows
  - Check for Stern SAM ROM (`wpt_1400` or similar — screenshot shows V14.0) and backglass/DMD if not already present
- [x] **Freddy - A Nightmare on Elm Street (Gottlieb 1994)** by RobbyKingpin — VPX table (new release)
  - https://vpuniverse.com/files/file/32879-freddy-a-nightmare-on-elm-street-gottlieb-1994/
  - Has an optional random "Freddy" scare mode (sounds + animation), **off by default** — 5 settings: Off / Every 60s / Every 60s with Lightning / At Random / At Random with Lightning. Set in the table options.
  - Check for Gottlieb System 3 ROM (`freddy` or similar) and backglass/DMD if not already present
- [x] **X-Files (Sega 1997) Hanibal 4k LED Edition MW MOD 1.0** by MachWon — VPX table (mod of Hanibal/JPSalas/Sliderpoint version)
  - https://vpuniverse.com/files/file/32630-x-files-sega-1997-hanibal-4k-led-edition-mw-mod-10/
  - nFozzy physics, Fleep sounds, reworked lighting/Alien tube, ball-stuck + left ramp fixes; 4 side blade choices in F12 menu; Rubberizer off by default
  - If an older X-Files is installed, decide whether this replaces it in the frontend
  - Check for Sega/Data East ROM (`xfiles` or similar) and backglass/DMD if not already present
