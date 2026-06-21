[README.md](https://github.com/user-attachments/files/29172717/README.md)
# 南山 · The Architecture of the Held Space

An integrated single-file work in two books — *South Mountain* and *Sage · Sovereign · Servant* — with a full back-matter apparatus, a scrollytelling overture and coda, and a live interactive layer.

## Deploy to GitHub Pages

1. Create (or open) the repo whose Pages URL matches the canonical link in the file:
   `https://markdownham88-crypto.github.io/held-space/`
   → repo name **`held-space`** under the user/org **`markdownham88-crypto`**.
2. Put these two files in the repo root:
   - **`index.html`** — the entire work (self-contained: all images embedded as data-URIs; only web-fonts load from Google's CDN, degrading gracefully to system serifs if blocked).
   - **`held-space-card.jpg`** — the 1200×630 social/Open-Graph card (so LinkedIn / Twitter / iMessage previews unfurl).
3. In **Settings → Pages**, set the source to the `main` branch, root (`/`).
4. Wait for the green check; the work goes live at the canonical URL above.

That's all — no build step, no dependencies. If you host it under a different repo slug, update the three URLs in the `<head>` (`canonical`, `og:url`, `og:image`) accordingly.

## Notes
- `held-space-architecture.html` is an identical working-name copy.
- The page honours `prefers-reduced-motion` (the overture, coda, Peng-flight and cadence pulse fall back to static states).
- In-page search, the live glossary tooltips, the 三家 diagnostic, the constellation, the motif threads, Trade Fours, the Yijing oracle, the cadence pulse and the valence palette are all pure client-side JS — nothing phones home.
