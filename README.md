# Claudia Molinet Homes — Website V1.0

Production-ready static bilingual website for Claudia Molinet, REALTOR® (S.01829117) with Lisa Bond Real Estate.

## Structure

- `index.html`: complete one-page website and SEO metadata
- `404.html`: GitHub Pages fallback
- `assets/css/styles.css`: mobile-first responsive design
- `assets/js/app.js`: bilingual system, menu and contact form behavior
- `assets/images/`: official logos and web-optimized professional photographs
- `robots.txt`, `sitemap.xml`, `CNAME`: search and domain configuration

## Bilingual system

The first visit uses `navigator.languages` / `navigator.language`. Spanish devices see Spanish; all others see English. The ES/EN selector updates the page without reloading and stores the preference in `localStorage`.

## Deployment

The site uses only relative asset paths and is ready for GitHub Pages. Publish from the repository root on the `main` branch. `CNAME` is configured for `claudiamolinethomes.com`.

## Contact form

V1.0 prepares the visitor's message and opens their email application. A future release may connect the same form to Formspree, EmailJS or another approved endpoint without changing its visual structure.

## Maintenance

Update translations together in `assets/js/app.js`. Do not replace or modify official logos or Claudia's photographs. After content updates, confirm both languages, mobile navigation, external contact links and responsive layouts.

## Future versions

Planned architecture can expand to `/buy`, `/sell`, `/land`, `/manufactured-homes`, `/about`, `/testimonials`, `/resources` and `/contact`, plus MLS/IDX, Prospects CRM, verified testimonials, closing photos and lead resources.
