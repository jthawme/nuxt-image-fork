# HEY

This is a fork, to fix the fingerprinting of static files. This package should in fact use the contents of the file to create the `[hash]` part of static filename.

I couldn't work out the best way to report back this change to the main module as they are preparing for a new release, so it exists here, for you to:

## Install

```
yarn add jthawme-nuxt-image // or npm install jthawme-nuxt-image
```

With nuxt 2 you also have to add this package to the `transpile` property in `nuxt.config.js`

```
...
build: {
  // other config etc.
  transpile: ["jthawme-nuxt-image"]
},
```

---

[![@nuxt/image](./docs/public/cover.jpg "Nuxt Image")](https://image.nuxtjs.org)

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Checks][checks-src]][checks-href]
[![Codecov][codecov-src]][codecov-href]

- [📖 &nbsp;Read Documentation](https://image.nuxtjs.org)
- [▶️ &nbsp;Play online](https://githubbox.com/nuxt/image/tree/main/example)

### Contributing

1. Clone this repository
2. Install dependencies using `yarn install`
3. Start development server using `yarn dev`

## 📑 License

Copyright (c) Nuxt Team

<!-- Badges -->

[npm-version-src]: https://flat.badgen.net/npm/v/@nuxt/image
[npm-version-href]: https://npmjs.com/package/@nuxt/image
[npm-downloads-src]: https://flat.badgen.net/npm/dm/@nuxt/image
[npm-downloads-href]: https://npmjs.com/package/@nuxt/image
[checks-src]: https://flat.badgen.net/github/checks/nuxt/image/master
[checks-href]: https://github.com/nuxt/image/actions
[codecov-src]: https://flat.badgen.net/codecov/c/github/nuxt/image
[codecov-href]: https://codecov.io/gh/nuxt/image
[license-src]: https://img.shields.io/npm/l/@nuxt/image.svg
[license-href]: https://github.com/nuxt/image/blob/main/LICENSE
