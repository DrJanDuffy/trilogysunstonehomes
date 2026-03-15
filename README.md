# Trilogy Sunstone Homes

Static site for Trilogy Sunstone (Las Vegas 55+ community). Built with Astro, deployed on Vercel.

## Structure

- **spiffy-saturn/** – Astro app (pages, components, layouts). Build output: `spiffy-saturn/dist`.
- **tasks/** – Planning and lessons: [tasks/README.md](tasks/README.md).

## Build and deploy

From repo root (Vercel uses this):

```bash
cd spiffy-saturn && npm install && npm run build
```

Output directory: `spiffy-saturn/dist`. Root [vercel.json](vercel.json) configures build, redirects (non-www → www), and headers.

## Tasks workflow

See [tasks/README.md](tasks/README.md) for how to use `tasks/to-do.md` and `tasks/lessons.md`.
