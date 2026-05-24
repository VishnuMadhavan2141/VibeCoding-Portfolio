# Selected work

A small portfolio of interface explorations and tools.
Live site: **https://vishnumadhavan2141.github.io/VibeCoding-Portfolio/**

## Projects

- **[REWIND](projects/rewind/index.html)** — Turns your screenshots of movie recommendations into a shelf of VHS tapes you can flip through.
- **[Movie Bookmarker](projects/movie-bookmarker/index.html)** — A draggable 2D plane of real movie posters with shared-element hero transitions into each title.
- **[WhatsApp Event Extractor](projects/whatsapp-extractor/index.html)** — Node + Claude API tool that turns messy chat messages from community groups into structured event JSON.

## Running locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.

## Adding a new project

1. Drop the project folder into `projects/<slug>/`.
2. Capture a screenshot at 1280×800 and save it as `thumbnails/<slug>.png`.
3. Duplicate one card block in `index.html`, update the `href`, `<img src>`, title, and description.
4. Commit and push — GitHub Pages auto-deploys.
