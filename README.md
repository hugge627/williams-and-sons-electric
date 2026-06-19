# San Jose Electricians — Website

Marketing website for **San Jose Electricians**, a licensed, 24/7 local electrical
service in San Jose, CA.

It's a single self-contained `index.html` — no build step, no dependencies.
Just open the file in a browser, or upload it to any static host.

## Features

- Multi-page experience (Home · Services · About · Reviews · Contact) via a
  lightweight client-side router — all in one file.
- Bright, construction-styled design (safety orange + steel) with smooth,
  reduced-motion-aware animations.
- Real customer reviews, business details, and an embedded map.
- `LocalBusiness` structured data (JSON-LD) + meta tags for local SEO.
- Responsive and accessible (keyboard focus states, alt text, ARIA labels).

## Local preview

Just double-click `index.html`. Or, on Windows, run the included static server:

```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1 -Port 8910
# then open http://localhost:8910/
```

## Before going live — fill these in

Search `index.html` for `TODO`:

- **CSLB license number** (FAQ + footer)
- **Email address** (currently a placeholder)
- **Years in business / founding year** (About copy)
- **Contact form backend** — the form currently shows a success message only.
  Wire it to a service (e.g. Formspree) or your own endpoint to receive submissions.
