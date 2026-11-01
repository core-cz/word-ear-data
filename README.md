# word-ear-data

Public data assets for the Word Ear Training project (单词磨耳朵).

This repo exists because the main website repo is private, so its GitHub
Pages stopped serving. The ESP32 device reads its data from here instead:

- `data/manifest.json` — default book index (junior / 1317 words / 66 pages)
- `data/books/` — all books: kids, junior, senior, cet4, cet6, toefl, ielts
- `data/pages/` — legacy junior pages (kept for the current firmware)
- `data/lessons.json` — lesson catalogue
- `audio/us/` — word pronunciation MP3s (US accent, the device default)
- `images/` — images the site/device may call (e.g. donation QR)

The website itself lives on Cloudflare Pages (earx.pages.dev); this repo is
data only, not a runnable site. Paths are identical to the old public repo,
only the repo name (and therefore the Pages base URL) changed.
