# Nuxt 3 \ Nuxt Content Issue

Install packages then you can try if it works in dev mode.

```bash
yarn dev
```

It works.

## Issue scenario

1. Generate static site

```bash
yarn generate
```

2. Serve static site

```bash
npx http-server .output/public --port 8081 -P http://localhost:8081\?
```

3. Open http://localhost:8081

