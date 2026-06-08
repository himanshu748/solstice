# SOLSTICE — The Longest Day

A short, atmospheric platformer where **your light is your only resource**. Built for the [DEV June Solstice Game Jam](https://dev.to/challenges/june-game-jam-2026-06-03).

**▶ Play:** https://hyperagent.com/s/A_Xul17aTbCIAsAcvG8A-w

On the eve of the solstice the sun is failing. Carry the last ember of daylight across four levels — **Dusk → Twilight → Deep Night → The Turning** — and rekindle the dawn. Your light lets you see, slowly drains, and is spent in a **Sunburst** to bloom platforms, light beacons, and push back the dark.

## Controls
- **Move:** ← → or A D
- **Jump:** Space or W
- **Sunburst:** J or Shift
- **Pause:** P · **Restart:** R · **Mute:** M
- **Mobile:** on-screen buttons — play in landscape

## Tech
One self-contained `index.html` — HTML5 Canvas 2D + vanilla JavaScript. No engine, no libraries, no build step. Real-time 2D lighting via canvas compositing, fixed-timestep platformer physics (coyote time, jump buffering, variable jump height), and fully synthesized Web Audio. Open it in any browser, or just *View Source*.
