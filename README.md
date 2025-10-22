# shadturbo — Turborepo starter with shadcn/ui

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FMontekkundan%2Fshadturbo&env=NEXT_PUBLIC_WEB_URL&envDescription=Your%20website%20URL&envLink=https%3A%2F%2Fgithub.com%2FMontekkundan%2Fshadturbo%2Fblob%2Fmain%2Fapps%2Fweb%2F.env.example&project-name=shadturbo&repository-name=shadturbo&demo-title=shadturbo&demo-description=Minimal%20starter%20repo%20that%20includes%20a%20Next.js%20app%20and%20a%20shadcn%20design%20system.&demo-url=https%3A%2F%2Fshadturbo.vercel.app&demo-image=https%3A%2F%2Fshadturbo.vercel.app%2Fapi%2Fog)

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
