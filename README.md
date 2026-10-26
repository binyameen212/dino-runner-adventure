# Dino Runner Adventure — source code

An independent modification of the Chromium T-Rex Runner, including custom game UI and Adventure-mode work.

## Scope of this repository

This repository publishes game source code while deliberately excluding the creator's private image/audio assets. The HTML points to a `private-assets/` directory that is not included here, so this repository is **not playable as cloned**. The owner can restore their private files locally without committing them.

## Licence

Chromium-derived code is covered by the BSD 3-Clause terms; see `LICENSE` and `THIRD_PARTY_NOTICES.md`. The original Chromium copyright notices in the source must remain. The licence does not grant rights to excluded private assets.

## Run locally (after restoring private assets)

1. Restore the excluded files into `private-assets/` using the same filenames.
2. Open `index.html` in a modern browser, or serve this folder with a local HTTP server, for example `python -m http.server 8000`.
3. Visit `http://localhost:8000`.

## Branding

This is an unofficial community project. It is not a Google product and is not endorsed by Google or the Chromium Authors.

## Limitations

The code has not been fully runtime-tested after asset references were externalized. Review all third-party components and notices before release.
