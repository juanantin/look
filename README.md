# You Look You Buy

Single-page, non-scrolling landing site for the "You Look You Buy" meme on Robinhood Chain.

## Before going live

Open `index.html` and update two placeholders:

1. **Chart link** — replace `PASTE_PAIR_ADDRESS_HERE` in the DexScreener `href` with the real pair address once the token is live.
2. **Contract address** — replace `TBA` (both the button's `data-ca` attribute and its visible label) with the real CA.

## Run locally

Any static file server works, e.g.:

```
python3 -m http.server 8000
```

Then open http://localhost:8000
