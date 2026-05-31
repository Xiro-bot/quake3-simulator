# quake3-simulator

Browser-based strafe-jump trainer with VQ3 / CPM physics, a first-person view, two race-bots executing fixed L/R patterns, mouse model ported from Q3's `cl_mouseAccelStyle 0`, and a real 30 000-ups race track.

Play it: **https://xiro-bot.github.io/quake3-simulator/**

Self-contained single HTML file. No build step, no dependencies.

## Controls

- **Click** the canvas to capture your mouse
- **W / A / S / D** move (W+D or W+A to strafe)
- **Space** (hold) — jump, auto-hop while held
- **Right-click** — also jumps
- **V** — cycle camera through you → bot1 → bot2 → you
- **R** — reset the race
- **Esc** — release mouse

Bot1 alternates strafe key every jump (A,D,A,D…). Bot2 alternates every 2 jumps (A,A,D,D…). Watch their forward speeds diverge.

Physics dropdown toggles between vanilla **VQ3** and **CPM** (CPMA-style, with airstop / strafeaccel / aircontrol).
