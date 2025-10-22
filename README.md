# shadturbo — Turborepo starter with shadcn/ui

Minimal starter repo that includes a Next.js app and a shadcn design system.

Quick start (bun)

```sh
bunx create-turbo@latest --example https://github.com/Montekkundan/shadturbo myproject
cd myproject
bun install
bunx turbo dev --filter=web
```

Add components to the design system:

```sh
# from repo root
bun ui add <component-name>
```

Useful links

- https://ui.shadcn.com/docs
- https://turbo.build/docs

That's it the README is intentionally small. If you want a longer quickstart or CI notes, tell me what to include [@montekkundan](https://x.com/montekkundan).
