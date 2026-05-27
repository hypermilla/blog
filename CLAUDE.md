# hypermilla blog — Claude Context

> The **owned home base** for hypermilla (build-in-public). This file is thin on purpose:
> **build / visual / workflow conventions live in [`AGENTS.md`](./AGENTS.md)** (this repo is the
> Navfolio Astro template). **Planning, decisions, roadmap and status live in the brain vault** at
> `personal/projects/blog/index.md` — update that doc + its session log when decisions change.

## What this is

hypermilla's personal blog: long-form writing, build-in-public. Astro + Bun, deployed to
**Cloudflare Workers Static Assets**. Live at **hypermilla.com** (hypermilla.io planned as a later
secondary domain).

## Where things live

- **Build / run, visual language, code conventions** → [`AGENTS.md`](./AGENTS.md).
- **Deploy** → see [Deploy](#deploy) below and [`wrangler.jsonc`](./wrangler.jsonc).
- **Why / what / roadmap / post ideas / status** → brain vault `personal/projects/blog/index.md`.
- **Content** → `src/content/blog/` (Markdown/MDX); site config in `src/config/site.toml`.

## Principles (from the vault strategy)

- Ship at 80% — write first, build fancy later. Don't let blog-*building* block blog-*writing*.
- GEO the honest way — earn it, don't trick it. No agent manipulation / prompt injection.
- Agent-automatable: content is Markdown in the repo, predictable structure, CI deploy.

## Commands

Bun (not npm/pnpm/yarn). `bun install` · `bun run dev` · `bun run build` · `bun run preview`.
See `AGENTS.md` for full verification guidance.

> Bun must be the real runtime (`~/.bun/bin/bun`), not the `bun` npm-wrapper package.
> If `bun` is missing on a new machine: `curl -fsSL https://bun.sh/install | bash`.
> Don't add `bun` back to `package.json` dependencies — the npm wrapper's postinstall is
> what broke installs under pnpm/npm during initial setup.

## Deploy

**Cloudflare Workers Static Assets** (this CF account is on the new Workers-only UI — the legacy
Pages create flow isn't available). Auto-deploys on every push to `main`.

- Worker name: `blog`. Config: [`wrangler.jsonc`](./wrangler.jsonc) — assets-only, no `main` entry.
- Cloudflare build pipeline: `bun run build` → `dist/`, then `npx wrangler deploy` uploads.
- Build env vars (set in CF dashboard → project → Settings → Variables):
  - `SITE_URL=https://hypermilla.com`
  - `SITE_BASE=/`
  - `NODE_VERSION=22`
  - `BUN_VERSION=1.3.14`
- **Do not delete `wrangler.jsonc`.** Without it, `wrangler deploy` auto-runs `astro add cloudflare`,
  installs the SSR adapter, rewrites `astro.config.mjs`, and the static build fails with
  `No 'name' field provided in wrangler.jsonc`. The committed config is what keeps the deploy static.
- Custom domain wired in CF dashboard → Custom domains. `www.hypermilla.com` not yet attached.
