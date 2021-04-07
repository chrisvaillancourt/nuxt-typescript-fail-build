# nuxt-typescript-fail-build

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## Build Errors

This project simultaneously builds and reports errors during local development. Running `npm run build` results with `FATAL Nuxt build error` due to TypeScript errors reported by ESLint (see `~/components/TsSFC.vue`).

It would be ideal if there was an option to allow production builds with TypeScript errors.
