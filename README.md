# La Luna Malabo

Restaurant web presence for La Luna in Malabo.

## Build

```bash
npm ci
npm run lint
npm run build
```

## Deployment

Static site deployment uses Render with:

- Build command: `npm ci && npm run build`
- Publish directory: `dist`
- Rewrite: `/*` to `/index.html`
