# Tuckit website

The public pages of Tuckit – Block Puzzle, served by GitHub Pages at https://and-games-studio.github.io/tuckit/

- `index.html`: home page.
- `privacy/`: privacy policy (linked from the Play Store listing, AdMob's consent message and the game).
- `terms/`: terms of service.
- `delete/`: how to delete the data the game keeps (the Play Console data safety form links it).

Plain HTML and CSS, no build step, in the game's light room and bright pieces. The font is the game's, Baloo 2 (SIL Open Font License 1.1, in `fonts/` with its licence), served from here, so the site makes no requests to other servers. `images/icon.png` is the app icon (256 px, from the game's `Store/art`).

The privacy policy, the terms and the deletion page describe what the Android build will do: AdMob's rewarded videos (a video for an extra hint) and nothing else online. When the build changes, they change with it.
