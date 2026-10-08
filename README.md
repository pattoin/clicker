# OncehLab — Clicker Rings

Static landing page. No build step.

```
index.html     the whole page (HTML + CSS + JS)
images/        product photos
vercel.json    clean URLs + image caching
```

## Deploy

1. Create a GitHub repo and push this folder's contents to the root.
2. In Vercel: Add New → Project → import the repo.
3. Framework Preset: **Other**. Leave build command and output directory empty. Deploy.

Preview locally: `npx serve .` or open `index.html`.

## Editing

- Replace the three dashed "Out in the world" frames with `<img>` tags pointing at new files in `images/`.
- The reserve form currently only shows a confirmation message. To collect emails, point it at a form service (Formspree, Tally, Buttondown) or a Vercel serverless function.
