# package-starter

A template repo to help build a new npm package. Includes a minimal monorepo with two workspaces:

- `package`: single-file package with index.mjs
- `demo`: basic astro app that consumes `package`

## Commands

```shell
pnpm i
```

```shell
pnpm run dev
```

```shell
pnpm run build
```

### TODO

- Support TypeScript for authoring package files
  - Should have commands: `dev` (fast transpile) and `build` (generate types)
