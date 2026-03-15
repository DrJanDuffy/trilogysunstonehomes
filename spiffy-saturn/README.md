# Astro with Tailwind

```sh
npm create astro@latest -- --template with-tailwindcss
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/with-tailwindcss)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/with-tailwindcss)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/with-tailwindcss/devcontainer.json)

Astro comes with [Tailwind](https://tailwindcss.com) support out of the box. This example showcases how to style your Astro project with Tailwind.

For complete setup instructions, please see our [Tailwind Integration Guide](https://docs.astro.build/en/guides/integrations-guide/tailwind).

## Deployment (Vercel)

The site is built as a static Astro site and deploys to [Vercel](https://vercel.com) with zero config (no adapter). Connect the repo in the Vercel dashboard and set the **Root Directory** to `spiffy-saturn` if the repo root is the workspace root. Non-www redirects to www via `vercel.json` (trilogysunstonehomes.com → https://www.trilogysunstonehomes.com).

## Google Search Console

The site is set up for Google Search Console: sitemap at `/sitemap-index.xml`, static `robots.txt` in `public/`, and optional verification via HTML meta tag. To verify ownership, set the env var `PUBLIC_GSC_VERIFICATION` to the code from GSC → Settings → Ownership verification → HTML tag (e.g. in Vercel project env or a `.env` file). Do not commit the real verification code.
