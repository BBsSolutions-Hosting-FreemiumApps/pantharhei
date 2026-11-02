# Pantha Rhei — static site clone

A 1-to-1 static rebuild of https://pantharheiart.wordpress.com/, intended as a clean
starting point for conversion into editable pages (e.g. via Novamira + Claude Code).

## Structure

- `index.html` — homepage (Art Upcycling, techniques, B2B, quote, CTA)
- `pantha-rhei.html` — "Pantha Rhei" page (about / circular fashion)
- `catalogues.html` — Catalogues page (Discover. Explore. Download. + ordering info)
- `privacy.html` — placeholder (the original site's privacy link returns a 404)
- `b2b.html` — B2B page (regenerative collaborations, collaboration process, FAQs)
- `css/style.css` — shared stylesheet

## Notes for CMS conversion

- Each section of a page is a standalone `<section>` element, so content blocks map
  one-to-one to CMS page sections.
- Text content is taken verbatim (English) from the original site.
- Catalogue items are headings only; on the original they are image/PDF download blocks
  (catalogue PDFs, price list, Telegram QR code). Add those assets here before or after
  migration.
- No JavaScript, no build step. Open any HTML file directly in a browser.
