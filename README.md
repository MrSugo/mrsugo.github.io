# Edoardo Fabbro — portfolio

A personal site you fly: a first-person 1980s spaceship cockpit built with three.js (WebGL), in a single `index.html`.

- **Work** keys (centre console): Experience, Contacts, CV
- **Personal** keys (left wing): Writing, Books, Films, Photos
- Left wing: colour palette and cabin light; right wing: volume, track selector and thrust lever

## Run locally
Any static server works, for example `python3 -m http.server 8000`, then open http://localhost:8000.

## Files
- `index.html` — the whole site (scene, content, audio)
- `cv.pdf` — one-page CV
- `icons/` — holo icons for the personal sections
- `photos/` — photos shown in the Photos section

Content (sections, books, films, captions) lives in the `SECTIONS` array near the top of `index.html`.
