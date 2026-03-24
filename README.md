# FinOps Service Landing Page

Static landing page for an async Google Cloud Platform cost audit offer.

## Files

- `index.html`: landing page markup and content
- `styles.css`: visual system, layout, and responsive styles
- `.gitignore`: ignored local/dev artifacts for simple static site work

## Local preview

Run a local static server from the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/index.html
```

## What the page includes

- Hero section with primary CTA
- Scope and deliverables
- Focus areas and exclusions
- Async process overview
- Sample findings output
- Fit criteria
- FAQ
- Final CTA

## Notes

- The final CTA currently uses `mailto:hello@example.com` as a placeholder.
- The page is a plain HTML/CSS implementation, so it can be deployed to any static hosting provider.
