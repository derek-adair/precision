# Precision

Precision is a [Ghost](https://github.com/TryGhost/Ghost) theme aimed at simple brochure sites.  Forked from [Wave](https://github.com/TryGhost/Wave).

* hide/enable search.
* Nav will always have a bold Contact Button.


# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/wave.zip`, which you can then upload to your site.

```bash
yarn zip
```

## Copyright & License

Copyright (c) 2013-2022 Ghost Foundation - Released under the [MIT license](LICENSE).
