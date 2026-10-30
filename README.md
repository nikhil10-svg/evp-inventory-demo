# EVP customer inventory (demo)

Practice repo with DUMMY data only. Every customer, ID and contact here is fictional.

## Structure
- `data/customers/*.json` – one file per customer
- `data/manifest.json` – list of customer files the dashboard loads (add new files here)
- `index.html` – the dashboard, published with GitHub Pages

## Add a customer
1. Copy an existing file in `data/customers/`, rename it, change the values.
2. Add its path to `data/manifest.json`.
3. Commit. The live dashboard updates about a minute later.

## Run locally
Opening index.html by double-click won't load the JSON (browsers block it). Instead run:
`python -m http.server 8000` in this folder and open http://localhost:8000
