# PNPM workspace monorepo

## What's inside?

PNPM workspace repository structured as `apps` and `packages` folder. It contains

- a [Remix](https://remix.run) application in the `apps/my-remix-app` folder
- a React library compiled with TypeScript in the `packages/shared-ui` folder.
- Remix app imports the `shared-ui` library

## How to run it

Make sure you are in the example folder.

Install all packages via

```bash
> pnpm install
```

Serve the Remix application by running it's `dev` npm script defined in the `apps/my-remix-app/package.json`. We can do that with pnpm using

```bash
>  pnpm --filter my-remix-app dev
```
