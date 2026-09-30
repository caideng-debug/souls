# Ashen Vigil

Browser-playable medieval parry-combat vertical slice inspired by the supplied master prompt, using original/procedural assets.

## Run
`npm install && npm run dev`

Open the local Vite URL. Click the arena. RMB is guard/deflect; LMB attacks; Shift dodges; Space jumps; Q lock-on; F1 debug; F2 tuning; F3 training; R restart.

## Test
`npm run dev`, then open `/?test=1`. The page exposes `window.__game` and renders a compact automated test result in the document title/body dataset.

## Asset fallback
The environment could not complete npm/network downloads during build preparation, so this iteration follows the master prompt's procedural fallback. External CC0 assets can later be swapped into `public/assets` and wired through a manifest.
