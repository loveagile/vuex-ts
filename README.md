<p align="center">
  <a href="https://rxjs.dev">
    <img src="https://rxjs.dev/assets/images/logos/Rx_Logo_S.png" height="50">
  </a>
  <a href="#readme">
    <img src="https://rx-ts.github.io/assets/heart.svg" height="50">
  </a>
  <a href="https://vuejs.org">
    <img src="https://vuejs.org/images/logo.png"  height="50">
  </a>
</p>

[![GitHub Actions](https://github.com/rx-ts/eslint/workflows/CI/badge.svg)](https://github.com/rx-ts/eslint/actions/workflows/ci.yml)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/rx-ts/vue.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/rx-ts/vue/context:javascript)
[![type-coverage](https://img.shields.io/badge/dynamic/json.svg?label=type-coverage&prefix=%E2%89%A5&suffix=%&query=$.typeCoverage.atLeast&uri=https%3A%2F%2Fraw.githubusercontent.com%2Frx-ts%2Fvue%2Fmaster%2Fpackage.json)](https://github.com/plantain-00/type-coverage)
[![GitHub release](https://img.shields.io/github/release/rx-ts/vue)](https://github.com/rx-ts/vue/releases)

[![Conventional Commits](https://img.shields.io/badge/conventional%20commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![Renovate enabled](https://img.shields.io/badge/renovate-enabled-brightgreen.svg)](https://renovatebot.com/)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
[![Code Style: Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![changesets](https://img.shields.io/badge/maintained%20with-changesets-176de3.svg)](https://github.com/atlassian/changesets)

> Make [Vue][] greater with [RxTS][].

## TOC <!-- omit in toc -->

- [Homepage](#homepage)
- [Packages](#packages)
- [Install](#install)
- [Sponsors](#sponsors)
- [Backers](#backers)
- [Changelog](#changelog)
- [License](#license)

## Homepage

<a href="https://vue-rx.now.sh" target="_blank">vue-rx</a>

## Packages

This repository is a monorepo managed by [Changesets][] what means we actually publish several packages to npm from same codebase, including:

| Package                               | Description                                               | Version                                                                                                                                                                                                            |
| ------------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [`vue-qrcode`](/packages/vue-qrcode/) | 🤳 A Vue component for QR code generation with [qrcode][] | [![npm](https://img.shields.io/npm/v/vue-qrcode.svg)](https://www.npmjs.com/package/vue-qrcode) [![View changelog](https://img.shields.io/badge/changelog-explore-brightgreen)](https://changelogs.xyz/vue-qrcode) |
| [`vue-qrious`](/packages/vue-qrious/) | 🤳 A Vue component for QR code generation with [qrious][] | [![npm](https://img.shields.io/npm/v/vue-qrious.svg)](https://www.npmjs.com/package/vue-qrious) [![View changelog](https://img.shields.io/badge/changelog-explore-brightgreen)](https://changelogs.xyz/vue-qrious) |

## Install

```shell
# yarn
yarn add vue-{qrcode,qrious}

# npm
npm i vue-{qrcode,qrious}
```

## Sponsors

| 1stG                                                                                                                               | RxTS                                                                                                                               | UnTS                                                                                                                               |
| ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| [![1stG Open Collective backers and sponsors](https://opencollective.com/1stG/organizations.svg)](https://opencollective.com/1stG) | [![RxTS Open Collective backers and sponsors](https://opencollective.com/rxts/organizations.svg)](https://opencollective.com/rxts) | [![UnTS Open Collective backers and sponsors](https://opencollective.com/unts/organizations.svg)](https://opencollective.com/unts) |

## Backers

[![Backers](https://raw.githubusercontent.com/1stG/static/master/sponsors.svg)](https://github.com/sponsors/JounQin)

| 1stG                                                                                                                             | RxTS                                                                                                                             | UnTS                                                                                                                             |
| -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [![1stG Open Collective backers and sponsors](https://opencollective.com/1stG/individuals.svg)](https://opencollective.com/1stG) | [![RxTS Open Collective backers and sponsors](https://opencollective.com/rxts/individuals.svg)](https://opencollective.com/rxts) | [![UnTS Open Collective backers and sponsors](https://opencollective.com/unts/individuals.svg)](https://opencollective.com/unts) |

## Changelog

Detailed changes for each release are documented in [CHANGELOG.md](./CHANGELOG.md).

## License

[MIT][] © [JounQin][]@[1stG.me][]

[1stg.me]: https://www.1stg.me
[changesets]: https://GitHub.com/atlassian/changesets
[rxts]: https://rxjs.dev
[vue]: https://vuejs.org
[jounqin]: https://GitHub.com/JounQin
[mit]: http://opensource.org/licenses/MIT
[qrcode]: https://github.com/soldair/node-qrcode
[qrious]: https://github.com/neocotic/qrious
