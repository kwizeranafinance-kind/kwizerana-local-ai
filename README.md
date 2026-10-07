# Kwizerana Local AI

Public static site for Kwizerana Sovereign AI, a private on-premise AI offer for
law, medical, and finance firms.

## Public Pages

- `index.html` - Sovereign home page
- `concierge/index.html` - planned Enclave Concierge service, linked from the homepage navigation and bind section
- `fit/index.html` - 60-second fit check
- `privacy.html` - privacy page
- `404.html` - branded not-found page
- `assets/` - shared images, CSS, and JavaScript

The site is zero-build and can run on any static host.

## Run Locally

```bash
python3 -m http.server 3000
```

Open `http://localhost:3000`.

## Deploy

GitHub Pages can serve this site directly from the `main` branch and repository
root.

Netlify and Vercel configs are also included for static hosting.

## Enclave Concierge integration

The Concierge page adapts the supplied HTML using existing logo assets and brand styles. Service navigation remains visible on mobile. The original homepage, `#bind` anchor and fit check remain in place.

Concierge is currently presented as upcoming. Prices and terms are proposed, not an active offer. The supplied Calendly booking route returned HTTP 404 during integration, so the new page routes availability links to an explicit booking-not-open section. Replace these with a verified booking destination when the service launches. The first-session guarantee is intentionally not advertised as active.

This is website integration only. It does not connect a model, provision a private workspace or deploy an Enclave runtime. Cloud-account workflows and local Sovereign deployments have different data boundaries.
