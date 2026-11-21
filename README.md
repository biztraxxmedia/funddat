# FundDat

Unlisted crew tracker for local business deals. Not a client-facing site.

Live: https://biztraxxmedia.github.io/funddat/

The page asks search engines not to index it (`noindex`), but the repo is public, so treat it as visible if someone has the link.

## Edit

All deal data lives in the JavaScript arrays at the top of the `<script>` in `index.html` (`NEXT_UP`, `BUSINESSES`, `IDEAS`).

To add a photo, drop a compressed image in `assets/img/` and add an `images` entry on that business:

```js
images: [
  { src: "assets/img/example.jpg", thumb: "assets/img/example-thumb.jpg", alt: "...", caption: "..." }
]
```

Tap a thumbnail to open the in-page lightbox.
