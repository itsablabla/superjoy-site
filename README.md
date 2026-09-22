# Superjoy marketing site

Static marketing site for Superjoy, built from the brand system in `superjoy-figma-design.html`.

## Local preview

Open `index.html` in a browser, or:

```bash
docker build -t superjoy-site .
docker run --rm -p 8080:80 superjoy-site
```

## Deploy

Deployed on Coolify Cloud project **Superjoy** (server `srv1931315`) via Dockerfile + nginx.
