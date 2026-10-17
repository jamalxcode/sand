# Sand Digger

A desert digging arcade game. Play it at **https://sand.sala.company**.

Dig through the dunes as a Bedouin kid, sling the uromastyx lizards (three hits knock one out), and dig under clay pots to drop them on the lizards. Drop two pots and a golden dallah appears for bonus points.

## Controls

| | Desktop | Phone |
|---|---|---|
| Move | Arrows / WASD | D-pad |
| Sling | Space / Z / X | SLING button |
| Pause | P / Esc | |
| Mute | M | Sound button |

## Tech

One static `index.html` with no build step and no dependencies: canvas 2D graphics, Web Audio sound (an original walking tune in a Hijaz scale), and the best score saved in the browser. Deployed to GitHub Pages by `.github/workflows/pages.yml` on every push to `main`.

Add `#debug` to the URL to expose `window.__sd` for testing.
