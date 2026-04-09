# GeneCode-Explorer

Interactive middle-school lesson: DNA structure, bases, pairing, codons, proteins — flashcards, 3D helix, missions, and quiz. Open **`index.html`** in a browser (or use a local server so the 3D viewer can load scripts).

## Live site (GitHub Pages)

1. **Repo → Settings → Pages**
2. **Build and deployment** → **Source**: **GitHub Actions** (not “Deploy from branch”).
3. Push to `main` runs [`.github/workflows/deploy-pages.yml`](.github/workflows/deploy-pages.yml). When the workflow finishes, the site is at:

**https://leighrobbins-hub.github.io/GeneCode-Explorer/**

If you see 404, wait a minute after the first successful run, or confirm Pages source is **GitHub Actions**.
