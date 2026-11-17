# Our Springfield v0.3

This is a private, original isometric town-building web game prototype.

## What's new in v0.3
- Building income accumulates while the game is closed; tap Collect to receive it.
- Residents can be assigned timed tasks (1 minute, 1 hour, 4 hours, 8 hours, or 24 hours) and collect XP when complete.
- Select a placed building, move it to an open tile, and rotate it 90 degrees.
- Existing local town saves are retained where possible.

## Install/update
Upload all files in this folder to the existing GitHub Pages repository, replacing the previous versions. Open the same Pages link on iPhone and refresh. If the old version remains cached, close Safari and reopen the page.

## Important
This remains a front-end prototype. Town data is stored on each device. Online accounts, cloud saves, friend invitations, and visiting other towns still require a backend and are not included yet.


Version 0.4 update: landscape-first iPhone layout with a rotate-your-phone prompt in portrait, a wider town view, and a cached terrain layer to reduce repeated canvas drawing. Building placement hit detection is more forgiving, and the service worker cache has been versioned so updated files replace the older cached app.


## Version 0.6
The landscape town map now fills the entire screen behind the interface. The top balances and level/XP, quest panel, move/rotate controls, and bottom navigation remain visible as overlays. Build and other menus open over the town.
