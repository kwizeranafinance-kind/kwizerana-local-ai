# Kwizerana Local AI

Public static site for Kwizerana Sovereign AI, a private on-premise AI offer for
law, medical, and finance firms.

## Public Pages

- `index.html` - home page
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
