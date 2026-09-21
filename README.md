# naseq-media

Public media for the Naseq website: the hero films. No code, no secrets, nothing private — everything here is meant to be seen on the public site.

Served through the jsDelivr CDN, e.g. `https://cdn.jsdelivr.net/gh/Rashid-aq/naseq-media@main/hero/coffee-matcha-1080.mp4`.
jsDelivr caches `@main` for up to a day; to make a replaced file show at once, reference a commit hash instead of `@main`.

| file | what | length | size |
|---|---|---|---|
| `hero/coffee-matcha-1080.mp4` | clip 1, the coffee and matcha station, from the 6 s mark of the master | 2.0 s | 0.8 MB |
| `hero/coffee-matcha-720.mp4` | the same at 720p, for phones | 2.0 s | 0.3 MB |

Masters with audio stay in the founders' Drive.


## `scroll/` — the scroll film

The same clips encoded for scrubbing (a keyframe every 6 frames, no B-frames, silent), so any scroll position seeks in one short decode, plus first-frame posters.

| file | size |
|---|---|
| `scroll/coffee-matcha-poster.jpg` | 0.2 MB |
| `scroll/coffee-matcha-scrub-1080.mp4` | 5.9 MB |
| `scroll/coffee-matcha-scrub-720.mp4` | 3.2 MB |
| `scroll/wedding-organised-poster.jpg` | 0.2 MB |
| `scroll/wedding-organised-scrub-1080.mp4` | 14.7 MB |
| `scroll/wedding-organised-scrub-720.mp4` | 7.7 MB |
