# Maxion Education Website Template

A single-page static HTML template exported from Webflow — the **Maxion Education Website Template**.

## Stack

- Pure static HTML (single file: `template-maxion_webflow_io.html`)
- Styles and assets loaded from Webflow's CDN (`assets.website-files.com`)
- No backend, no build step, no dependencies

## How to run

The workflow `Start application` serves the file with Python's built-in HTTP server:

```
python3 -m http.server 5000
```

Open the preview at: `/template-maxion_webflow_io.html`

## Notes

- POST requests (e.g. form submissions) will return a 501 error from Python's static server — this is expected and doesn't affect browsing.
- All images, fonts, and CSS load from Webflow's CDN, so an internet connection is required.
