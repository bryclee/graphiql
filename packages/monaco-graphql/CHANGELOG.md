# Change Log

## 0.6.5

### Patch Changes

- [`989fca69`](https://github.com/graphql/graphiql/commit/989fca693385aa408bcfe18cde34934a5aea5dce) [#2070](https://github.com/graphql/graphiql/pull/2070) Thanks [@acao](https://github.com/acao)! - Fix a bug with variable completion with duplicate `$` across the ecosytem. Introduce more `triggerCharacters` across monaco and the LSP server for autocompletion in far more cases

- Updated dependencies [[`df57cd25`](https://github.com/graphql/graphiql/commit/df57cd2556302d6aa5dd140e7bee3f7bdab4deb1)]:
  - graphql-language-service@3.2.5

## 0.6.4

### Patch Changes

- Updated dependencies []:
  - graphql-language-service@3.2.4
  - graphql-language-service-utils@2.6.3

## 0.6.3

### Patch Changes

- Updated dependencies [[`bdd57312`](https://github.com/graphql/graphiql/commit/bdd573129844168749aba0aaa20e31b9da81aacf)]:
  - graphql-language-service@3.2.3
  - graphql-language-service-utils@2.6.2

## 0.6.2

### Patch Changes

- [`858907d2`](https://github.com/graphql/graphiql/commit/858907d2106742a65ec52eb017f2e91268cc37bf) [#2045](https://github.com/graphql/graphiql/pull/2045) Thanks [@acao](https://github.com/acao)! - fix graphql-js peer dependencies - [#2044](https://github.com/graphql/graphiql/pull/2044)

- Updated dependencies [[`858907d2`](https://github.com/graphql/graphiql/commit/858907d2106742a65ec52eb017f2e91268cc37bf)]:
  - graphql-language-service@3.2.2
  - graphql-language-service-utils@2.6.1

## 0.6.1

### Patch Changes

- [`9a6ed03f`](https://github.com/graphql/graphiql/commit/9a6ed03fbe4de9652ff5d81a8f584234995dd2ce) [#2013](https://github.com/graphql/graphiql/pull/2013) Thanks [@PabloSzx](https://github.com/PabloSzx)! - Update utils

- Updated dependencies [[`9a6ed03f`](https://github.com/graphql/graphiql/commit/9a6ed03fbe4de9652ff5d81a8f584234995dd2ce), [`9a6ed03f`](https://github.com/graphql/graphiql/commit/9a6ed03fbe4de9652ff5d81a8f584234995dd2ce)]:
  - graphql-language-service-utils@2.6.0
  - graphql-language-service@3.2.1

## 0.6.0

### Minor Changes

- [`716cf786`](https://github.com/graphql/graphiql/commit/716cf786aea6af42ea637ca3c56ae6c6ebc17c7a) [#2010](https://github.com/graphql/graphiql/pull/2010) Thanks [@acao](https://github.com/acao)! - upgrade to `graphql@16.0.0-experimental-stream-defer.5`. thanks @saihaj!

### Patch Changes

- Updated dependencies [[`716cf786`](https://github.com/graphql/graphiql/commit/716cf786aea6af42ea637ca3c56ae6c6ebc17c7a)]:
  - graphql-language-service@3.2.0

## 0.5.1

### Patch Changes

- [`0e2c1a02`](https://github.com/graphql/graphiql/commit/0e2c1a020cc2761155f7c9467d3ed4cb45941aeb) [#1979](https://github.com/graphql/graphiql/pull/1979) Thanks [@iahu](https://github.com/iahu)! - fix: export `monaco-graphql` esm with esm modules, also fix issues with worker manager, resolves #1706 & #1791

* [`75dbb0b1`](https://github.com/graphql/graphiql/commit/75dbb0b18e2102d271a5cfe78faf54fe22e83ac8) [#1777](https://github.com/graphql/graphiql/pull/1777) Thanks [@dwwoelfel](https://github.com/dwwoelfel)! - adopt block string parsing for variables in language parser

* Updated dependencies [[`0e2c1a02`](https://github.com/graphql/graphiql/commit/0e2c1a020cc2761155f7c9467d3ed4cb45941aeb), [`75dbb0b1`](https://github.com/graphql/graphiql/commit/75dbb0b18e2102d271a5cfe78faf54fe22e83ac8)]:
  - graphql-language-service@3.1.6

## 0.5.0

### Minor Changes

- [`fec37c6b`](https://github.com/graphql/graphiql/commit/fec37c6b2953e177bea99d4cbf993c9b253198ba) [#1952](https://github.com/graphql/graphiql/pull/1952) Thanks [@Nishchit14](https://github.com/Nishchit14)! - devDependancy and peerDependancy of monaco-graphql has been upgraded for monaco-editor. monaco-graphql is now supporting latest version of monaco-editor which is v0.27.0

### Patch Changes

- Updated dependencies [[`2fd5bf72`](https://github.com/graphql/graphiql/commit/2fd5bf7239edb78339e5ac7211f09c245e47c3bb)]:
  - graphql-language-service@3.1.5

## 0.4.4

### Patch Changes

- [`5b8a057d`](https://github.com/graphql/graphiql/commit/5b8a057dd64ebecc391be32176a2403bb9d9ff92) [#1838](https://github.com/graphql/graphiql/pull/1838) Thanks [@acao](https://github.com/acao)! - Set all cross-runtime build targets to es6

## 0.4.3

### Patch Changes

- [`6869ce77`](https://github.com/graphql/graphiql/commit/6869ce7767050787db5f1017abf82fa5a52fc97a) [#1816](https://github.com/graphql/graphiql/pull/1816) Thanks [@acao](https://github.com/acao)! - improve peer resolutions for graphql 14 & 15. `14.5.0` minimum is for built-in typescript types, and another method only available in `14.4.0`

## [0.4.2](https://github.com/graphql/graphiql/compare/monaco-graphql@0.4.1...monaco-graphql@0.4.2) (2021-01-07)

**Note:** Version bump only for package monaco-graphql

## [0.4.1](https://github.com/graphql/graphiql/compare/monaco-graphql@0.4.0...monaco-graphql@0.4.1) (2021-01-07)

**Note:** Version bump only for package monaco-graphql

# [0.4.0](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.5...monaco-graphql@0.4.0) (2021-01-07)

### Features

- implied or external fragments, for [#612](https://github.com/graphql/graphiql/issues/612) ([#1750](https://github.com/graphql/graphiql/issues/1750)) ([cfed265](https://github.com/graphql/graphiql/commit/cfed265e3cf31875b39ea517781a217fcdfcadc2))

## [0.3.5](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.4...monaco-graphql@0.3.5) (2021-01-03)

**Note:** Version bump only for package monaco-graphql

## [0.3.4](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.3...monaco-graphql@0.3.4) (2020-12-28)

**Note:** Version bump only for package monaco-graphql

## [0.3.3](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.2...monaco-graphql@0.3.3) (2020-12-08)

### Bug Fixes

- GraphQLAPI.setSchemaConfig README example ([#1726](https://github.com/graphql/graphiql/issues/1726)) ([01a1ff7](https://github.com/graphql/graphiql/commit/01a1ff74b0568229318339f9b026d99c117bd218))

## [0.3.2](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.1...monaco-graphql@0.3.2) (2020-11-28)

**Note:** Version bump only for package monaco-graphql

## [0.3.1](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.1-alpha.3...monaco-graphql@0.3.1) (2020-09-18)

**Note:** Version bump only for package monaco-graphql

## [0.3.1-alpha.3](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.1-alpha.2...monaco-graphql@0.3.1-alpha.3) (2020-09-11)

**Note:** Version bump only for package monaco-graphql

## [0.3.1-alpha.2](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.1-alpha.1...monaco-graphql@0.3.1-alpha.2) (2020-08-22)

### Bug Fixes

- improve setSchema & schema loading, allow primitive schema ([#1648](https://github.com/graphql/graphiql/issues/1648)) ([975f29e](https://github.com/graphql/graphiql/commit/975f29ed6e21c7354c42ed778dfd1b52287f70c6))

## [0.3.1-alpha.1](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.1-alpha.0...monaco-graphql@0.3.1-alpha.1) (2020-08-12)

**Note:** Version bump only for package monaco-graphql

## [0.3.1-alpha.0](https://github.com/graphql/graphiql/compare/monaco-graphql@0.3.0...monaco-graphql@0.3.1-alpha.0) (2020-08-10)

**Note:** Version bump only for package monaco-graphql

# [0.3.0](https://github.com/graphql/graphiql/compare/monaco-graphql@0.2.0...monaco-graphql@0.3.0) (2020-08-06)

### Features

- [RFC] GraphiQL rewrite for monaco editor, react context and redesign, i18n ([#1523](https://github.com/graphql/graphiql/issues/1523)) ([ad730cd](https://github.com/graphql/graphiql/commit/ad730cdc2e3cb7216d821a01725c60475989ee20))

# [0.2.0](https://github.com/graphql/graphiql/compare/monaco-graphql@0.1.4...monaco-graphql@0.2.0) (2020-06-11)

### Features

- standalone monaco API ([#1575](https://github.com/graphql/graphiql/issues/1575)) ([954aa3d](https://github.com/graphql/graphiql/commit/954aa3d7159fd26bba9650824e0f668e417ca64f))

## [0.1.4](https://github.com/graphql/graphiql/compare/monaco-graphql@0.1.3...monaco-graphql@0.1.4) (2020-06-04)

**Note:** Version bump only for package monaco-graphql

## [0.1.3](https://github.com/graphql/graphiql/compare/monaco-graphql@0.1.2...monaco-graphql@0.1.3) (2020-06-04)

### Bug Fixes

- cleanup cache entry from lerna publish ([4a26218](https://github.com/graphql/graphiql/commit/4a2621808a1aea8b30d5d27b8d86a60bf2b44b01))

## [0.1.2](https://github.com/graphql/graphiql/compare/monaco-graphql@0.1.1...monaco-graphql@0.1.2) (2020-05-28)

**Note:** Version bump only for package monaco-graphql

## [0.1.1](https://github.com/graphql/graphiql/compare/monaco-graphql@0.1.0...monaco-graphql@0.1.1) (2020-05-19)

**Note:** Version bump only for package monaco-graphql

# 0.1.0 (2020-05-17)

### Features

- Monaco Mode - Phase 2 - Mode & Worker ([#1459](https://github.com/graphql/graphiql/issues/1459)) ([bc95fb4](https://github.com/graphql/graphiql/commit/bc95fb46459a4437ff9471ff43c98e1c5c50f51e))
- monaco-graphql docs, api, improvements ([#1521](https://github.com/graphql/graphiql/issues/1521)) ([c79158c](https://github.com/graphql/graphiql/commit/c79158c72e976ab286e7ec3fded7f3e2d24e50d0))
