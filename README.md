beautiful-data-space
- jupyter svetegraph one pager project
pythond data
github pages
jupyter notebook export

infra/
    .github/workflows/deploy.yml    # CI/CD for auto-build & deploy
    docker/                         # optional reproducible env for notebooks
beautiful-data-space/
    notebooks/                      # raw Jupyter notebooks
    data/                           # CSV/JSON or small datasets
    src/                            # SvelteKit source
        routes/+page.svelte         # main one-pager
        lib/components/             # charts, tables, etc.
    static/                         # static assets (favicon, logo)
    scripts/                        # Python -> JSON export scripts