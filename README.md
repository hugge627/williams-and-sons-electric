# Williams & Sons Electric, LLC — Website

Marketing website for **Williams & Sons Electric, LLC**, a third-generation,
family-owned electrical company serving **Denver, Colorado since 1957**.

It's a single self-contained `index.html` — no build step, no dependencies.
Just open the file in a browser, or upload it to any static host.

## Features

- Multi-page experience (Home · Services · About · Our Work · Contact) via a
  lightweight client-side router — all in one file.
- Bright, construction-styled design (safety orange + steel) with smooth,
  reduced-motion-aware animations.
- Real company heritage, services, and notable projects.
- `LocalBusiness` structured data (JSON-LD) + meta tags for local SEO.
- Responsive and accessible (keyboard focus states, alt text, ARIA labels).

## Business details

- Phone: **(303) 762-9484** · 24/7 emergency service · free estimates
- Serving the Denver metro area & the Front Range, Colorado
- Owner & Master Electrician: Tim Williams · Colorado Contractor License #583
- Family-owned since 1957 (founded by Fred T. Williams)

## Local preview

Just double-click `index.html`. Or, on Windows, run the included static server:

```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1 -Port 8910
# then open http://localhost:8910/
```

## Before going live — fill these in

Search `index.html` for `TODO`:

- **Email address** (currently a placeholder)
- **Street address** (optional — currently shows service area only)
- **Contact form backend** — the form currently shows a success message only.
  Wire it to a service (e.g. Formspree) or your own endpoint to receive submissions.
