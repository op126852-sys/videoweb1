# videoweb1

Architecture firm landing page: full-bleed looping video hero + a Featured Projects section.

## Setup

1. Clone this repo.
2. Add your hero video file at `assets/hero-loop.mp4` (not committed here — see note below).
3. Open `index.html` in a browser, or deploy the folder as-is (static site, no build step).

## Note on the video file
The hero video wasn't pushed here automatically (binary files can't be streamed through this pipeline). Add it manually:
- Drag and drop `hero-loop.mp4` into the `assets/` folder via the GitHub web UI, or
- `git add assets/hero-loop.mp4 && git commit -m "add hero video" && git push` from your machine.
