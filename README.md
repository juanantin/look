# You Look You Buy

Single-page, non-scrolling landing site for the "You Look You Buy" meme on Robinhood Chain.

## Before going live

Open `index.html` and update the remaining placeholder:

1. **Chart link** — replace `PASTE_PAIR_ADDRESS_HERE` in the DexScreener `href` with the real pair address once the token is live.

The contract address is already set on the CA button (`data-ca` attribute and visible label).

## Run locally

Any static file server works, e.g.:

```
python3 -m http.server 8000
```

Then open http://localhost:8000
