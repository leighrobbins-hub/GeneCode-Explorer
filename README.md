# Gene Code Explorer + Nexus Academy

Static learning games (life science, math, ELA) and the Nexus meta-hub.

**Live site:** [https://leighrobbins-hub.github.io/GeneCode-Explorer/](https://leighrobbins-hub.github.io/GeneCode-Explorer/)

**Entry points**

- `index.html` — quick entry (redirects to Lesson 1); use **`hub.html`** for the full course picker
- `nexus.html` — Nexus Academy (all three games)
- `hub.html` — Gene Code Explorer chapters

**Regenerate math/ELA unit HTML** (after editing `scripts/generate-realm-units.py`):

```bash
python3 scripts/generate-realm-units.py
```

**Deploy:** GitHub Actions publishes this repo to GitHub Pages on every push to `main` (see `.github/workflows/deploy-pages.yml`).
