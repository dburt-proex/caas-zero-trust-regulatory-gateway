# CaaS Zero-Trust Regulatory Gateway

A single-page static dashboard prototype for a **CaaS Zero-Trust Regulatory Gateway**.

The interface simulates:

- hyperscale edge node telemetry
- regulatory lag monitoring
- energy draw status
- mycelial consensus logging
- grid stress and supply-chain shock events
- supply-chain fracture index visualization through Chart.js

## Repository Structure

```text
.
├── index.html
├── README.md
├── LICENSE
├── .gitignore
├── package.json
├── netlify.toml
└── .github/
    └── workflows/
        └── pages.yml
```

## Run Locally

This is a static HTML prototype. You can open `index.html` directly in a browser.

For a local dev server:

```bash
npm install
npm run dev
```

Then open the local URL printed in your terminal.

## Deploy

### GitHub Pages

This repo includes a GitHub Actions workflow at `.github/workflows/pages.yml`.

1. Go to **Settings → Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push to `main`.

### Netlify

This repo includes `netlify.toml` for simple static publishing.

## Notes

The dashboard currently uses CDN-loaded dependencies:

- Tailwind CSS CDN
- Chart.js CDN
- Google Fonts

No backend is required.

## License

MIT © 2026 Drew Burt
