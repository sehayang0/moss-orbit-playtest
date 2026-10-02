# Moss & Orbit mobile test export

<!-- forest-orbit-pages-v1: exported game only -->

This repository contains the exported Godot Web game and its publishing workflow.
The original development repository, device saves, signing keys, and local tools
are not included. The downloadable game package still contains the game's runtime
resources; this is not a promise of protection against extraction.

Enable Settings > Pages > Source > GitHub Actions once, then publish this repository's
`main` branch. The workflow uploads only `site/`. Use its reported Pages URL, keeping
the account, repository name, protocol, and path stable for later releases.

`site/build-info.json` identifies the source commit and game package. The deployment
manifest records file sizes and SHA-256 hashes; the workflow verifies them before
uploading. No external analytics or save upload service is included.

Game progress belongs to this browser and origin. Export a save from the old address
and import it here before continuing. Reload to update; do not clear site data.

This repository does not grant a license to the game's original art or game code.
Third-party notices are included in the game.
