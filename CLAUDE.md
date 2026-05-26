# hypermilla blog — Claude Context

> The **owned home base** for hypermilla (build-in-public). This file is thin on purpose:
> **build / visual / workflow conventions live in [`AGENTS.md`](./AGENTS.md)** (this repo is the
> Navfolio Astro template). **Planning, decisions, roadmap and status live in the brain vault** at
> `personal/projects/blog/index.md` — update that doc + its session log when decisions change.

## What this is

hypermilla's personal blog: long-form writing, build-in-public. Astro + Bun, deployed to
**Cloudflare Pages**. Live at **hypermilla.com** (hypermilla.io planned as a later secondary domain).

## Where things live

- **How to build / run / deploy, visual language, code conventions** → [`AGENTS.md`](./AGENTS.md).
- **Why / what / roadmap / post ideas / status** → brain vault `personal/projects/blog/index.md`.
- **Content** → `src/content/blog/` (Markdown/MDX); site config in `src/config/site.toml`.

## Principles (from the vault strategy)

- Ship at 80% — write first, build fancy later. Don't let blog-*building* block blog-*writing*.
- GEO the honest way — earn it, don't trick it. No agent manipulation / prompt injection.
- Agent-automatable: content is Markdown in the repo, predictable structure, CI deploy.

## Commands

Bun (not npm/pnpm/yarn). `bun install` · `bun run dev` · `bun run build` · `bun run preview`.
See `AGENTS.md` for full verification guidance.
