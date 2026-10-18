# Comet Volley

A one-thumb space breaker. Drag to aim, let go, and a volley of comets bounces through a belt of numbered crystals that grows stronger every round.

**Play:** https://tiago4k.github.io/comet-volley/

## Play offline on iPhone

1. Open the link above in Safari while online.
2. Tap Share → **Add to Home Screen**.
3. Open it once from the home-screen icon while still online. The title screen shows "Saved on this phone · plays offline" once it's cached.

After that it launches from the icon with no connection, and runs save between launches.

## How to play

- Drag anywhere to aim, release to launch.
- Fly through gold rings to gain another comet.
- Numbers are hits left. Keep crystals off the bottom line.
- Blue arrows fire lasers across a row or column; red-ringed crystals explode.
- A mothership arrives every 10 rounds, along with a new sector of sky.
- Second wind clears the bottom three rows, once per run.

## Files

- `index.html` – the whole game (canvas, physics, sound, menus)
- `sw.js` – service worker that caches everything for offline play
- `manifest.webmanifest`, icons – home-screen app setup
