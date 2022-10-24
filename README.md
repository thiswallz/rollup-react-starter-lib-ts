# rollup-react-starter-lib-ts

[![npm package][npm-badge]][npm]

<image width="100px" src="https://rollupjs.org/logo.svg" />

Template to create your own Typescript React library with Rollup.

- Rollup v3 :tada:
- Compatible with  new and old React versions, generates ESM/CJS files.

## Build & Publish

You can use this template and
change the name under package.json.

Build

```
npm run build
```

Build & Watch

```
npm run build:watch
```

Publish (public library)

Be sure you are either logged in under `npm login` or you have a token (check https://docs.npmjs.com/creating-and-viewing-access-tokens).

```
npm run publish --access=public
```

## For local testing

cd your-lib-folder/

```
npm link 
```

cd your-app/

```
npm link name-of-your-lib
```

[npm-badge]: https://img.shields.io/npm/v/rollup-react-starter-lib-ts.svg
[npm]: https://www.npmjs.org/package/rollup-react-starter-lib-ts
