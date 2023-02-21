# remix-cf-pages-template-hmr

A template to try out Remix's new dev server + HMR on Cloudflare Pages

## Getting started

**Install dependencies:**

```sh
yarn i
```

You must use yarn at the moment or configure overrides for conflicts on @cloudflare/workers-types.

**Start in development mode with HMR:**

```sh
yarn dev
```

Visit http://localhost:3000/

## Deployment

- Point a new Cloudflare Pages project at your repository
- Configure the build command to be `yarn build`
- Configure the build output directory to be `public`
