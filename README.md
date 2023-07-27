# Instagram Clone

This is an instagram clone the practice css. I may integrate a backend, but we'll see how it goes. This can also be build using Tauri so that it can be run as a native application.

## Tauri Build

```
npm run tauri build
```

As a note for myself or anyone else, to make nuxt work with tauri, you must modify the following file `nuxt.config.ts` and add the following: ` ssr: false`

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install

# pnpm
pnpm install

# yarn
yarn install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

# pnpm
pnpm run dev

# yarn
yarn dev
```

## Production

Build the application for production:

```bash
# npm
npm run build

# pnpm
pnpm run build

# yarn
yarn build
```

Locally preview production build:

```bash
# npm
npm run preview

# pnpm
pnpm run preview

# yarn
yarn preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
