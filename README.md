# dashboard

Primary Pea · SSA women's nutrition dashboard (Women in Data 2026 Datathon). Live at https://primary-pea.github.io/dashboard/ .

- `docs/` is the site (deployed by `.github/workflows/pages.yml` on every push to `main`; Settings → Pages → Source: GitHub Actions).
- `docs/data/` holds the precomputed results the page reads (written from the scaffold's `results/`, scaffold v2.0, data version `afe63e46c26b`); nothing is computed on a server.
- All links and asset paths are relative: the site lives under `/dashboard/`, not at the root.

Preview locally: `python3 -m http.server 8765 --directory docs` then open http://localhost:8765/ .
