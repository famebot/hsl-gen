# [0.6.0](https://github.com/famebot/hsl-gen/compare/v0.5.1...v0.6.0) (2023-04-09)



## [0.5.1](https://github.com/famebot/hsl-gen/compare/v0.5.0...v0.5.1) (2023-04-09)



# [0.5.0](https://github.com/famebot/hsl-gen/compare/v0.4.0...v0.5.0) (2023-04-09)


### Features

* xlight, midrange, lowmid, swatch palette ([5b628a8](https://github.com/famebot/hsl-gen/commit/5b628a87ca4ee25cdaae49ee76592ce7ea6c6f3e))


### BREAKING CHANGES

* Deprecated huehslactive, huehslhover, huehslmuted,
darkhuehslactive, darkhuehslhover, and darkhuehslmuted

🎲 All mixing values now randomly generated 👾

- General reordering and organization of `src/index.js`
- mega update to `examples/browser-umd/index.html`
  - now shows swatch palette and supports copying values

New raw mixing values

- `xlight`: 84-92
- `midrange`: 48-64
- `lowmid`: 28-36

Usage

- `midrange` used for `analhslmid` and `comphslmid` lightness

DEPRECATED color scheme values

Goodbye

- `huehslactive`
- `huehslhover`
- `huehslmuted`
- `darkhuehslactive`
- `darkhuehslhover`
- `darkhuehslmuted`

Hello `huehslxlight` and `darkhuehsllowmid`

`huehslxlight`

Replaces `huehslactive` and `huehslhover`

- `xlight` for lightness
- `midrange` for saturation?

`darkhuehsllowmid`

Replaces `darkhuehslactive` and `darkhuehslhover`

- lowmid for lightness



# [0.4.0](https://github.com/famebot/hsl-gen/compare/v0.3.5...v0.4.0) (2023-04-06)


### Bug Fixes

* use darker instead of darkness for (anal|comp)hsltext ([19ea482](https://github.com/famebot/hsl-gen/commit/19ea482bc5884b376d160d5766d54bc473c50f69))



## [0.3.5](https://github.com/famebot/hsl-gen/compare/v0.3.4...v0.3.5) (2023-04-06)


### Features

* add analhsltext and comphsltext using darkness ([9177436](https://github.com/famebot/hsl-gen/commit/91774367d894ddb0303ceecfb95be77c12237017))



## [0.3.4](https://github.com/famebot/hsl-gen/compare/v0.3.3...v0.3.4) (2023-04-05)


### Features

* use fn instead of reloading page in UMD example ([e9c423c](https://github.com/famebot/hsl-gen/commit/e9c423c247c618f98543432847aad903a7564645))



## [0.3.3](https://github.com/famebot/hsl-gen/compare/v0.3.2...v0.3.3) (2023-04-03)


### Bug Fixes

* UMD color contrast ([112ede0](https://github.com/famebot/hsl-gen/commit/112ede0ff56e3feb66d407d978d61e1b02113241))



## [0.3.2](https://github.com/famebot/hsl-gen/compare/v0.3.1...v0.3.2) (2023-04-03)


### Bug Fixes

* use `latest` everywhere; UMD color contrast; devtools links ([30ce0fa](https://github.com/famebot/hsl-gen/commit/30ce0fa80bcfeacbecd841bebc13be49662f8a6f))



## [0.3.1](https://github.com/famebot/hsl-gen/compare/v0.3.0...v0.3.1) (2023-04-03)


### Features

* use raw hue in UMD example ([2541ce1](https://github.com/famebot/hsl-gen/commit/2541ce1ef7b272e8579b559954846d848bef93a7))



# [0.3.0](https://github.com/famebot/hsl-gen/compare/v0.2.2...v0.3.0) (2023-04-03)


### Features

* add raw values to returned object to expand customization possibilities ([c9b9b23](https://github.com/famebot/hsl-gen/commit/c9b9b2382db0b233e7ffb3e9e6f9f6f939bc512d))



## [0.2.2](https://github.com/famebot/hsl-gen/compare/v0.2.1...v0.2.2) (2023-04-01)


### Features

* add noop build script for umd example hosting ([8c54b52](https://github.com/famebot/hsl-gen/commit/8c54b5272c2703c86f2c98ff6ea1e4d4cbee92fe))



## [0.2.1](https://github.com/famebot/hsl-gen/compare/v0.2.0...v0.2.1) (2023-03-24)


### Bug Fixes

* standardize on `hslGen` not `HSLgen` for UMD compat ([b2b1f17](https://github.com/famebot/hsl-gen/commit/b2b1f17f5b51a5569013c2696300fb92ca5924cb))



# [0.2.0](https://github.com/famebot/hsl-gen/compare/v0.1.3...v0.2.0) (2023-03-24)


### Features

* provide CLS and UMD bundles via Microbundle ([5a39ee6](https://github.com/famebot/hsl-gen/commit/5a39ee6c83c1c2d2d5944e14376adef7008eabca))



## [0.1.3](https://github.com/famebot/hsl-gen/compare/v0.1.2...v0.1.3) (2023-03-17)



## [0.1.2](https://github.com/famebot/hsl-gen/compare/v0.1.1...v0.1.2) (2023-03-17)



## [0.1.1](https://github.com/famebot/hsl-gen/compare/v0.1.0...v0.1.1) (2023-03-17)



# [0.1.0](https://github.com/famebot/hsl-gen/compare/v0.0.9...v0.1.0) (2023-03-17)



## [0.0.9](https://github.com/famebot/hsl-gen/compare/v0.0.8...v0.0.9) (2023-03-17)


### Bug Fixes

* correct devDeps ([e6dedf2](https://github.com/famebot/hsl-gen/commit/e6dedf24fa82f46624ac374f376d10ce03e54f2c))



## [0.0.8](https://github.com/famebot/hsl-gen/compare/v0.0.7...v0.0.8) (2023-03-15)



## 0.0.7 (2023-03-15)


### Features

* init ([8aec25c](https://github.com/famebot/hsl-gen/commit/8aec25cb5335f3293346f29359826916eb61f2d6))



