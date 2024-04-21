# Changelog

## [2.0.2](https://github.com/npm/tap-nock/compare/v2.0.1...v2.0.2) (2024-04-21)

### Chores

* [`2c2e3b0`](https://github.com/npm/tap-nock/commit/2c2e3b09ab8f0ec7ecc04221dcd522fe1bf120ac) [#68](https://github.com/npm/tap-nock/pull/68) postinstall for dependabot template-oss PR (@lukekarrys)
* [`69c6040`](https://github.com/npm/tap-nock/commit/69c60407068bb7a5b7e7a568b06b1365216d70d1) [#68](https://github.com/npm/tap-nock/pull/68) bump @npmcli/template-oss from 4.21.3 to 4.21.4 (@dependabot[bot])

## [2.0.1](https://github.com/npm/tap-nock/compare/v2.0.0...v2.0.1) (2023-02-07)

### Bug Fixes

* [`78fd1bf`](https://github.com/npm/tap-nock/commit/78fd1bf0cf2aed488335362567e9b5fac98787f6) [#36](https://github.com/npm/tap-nock/pull/36) replace mkdirp with fs.mkdir (#36) (@lukekarrys)

## [2.0.0](https://github.com/npm/tap-nock/compare/v1.0.0...v2.0.0) (2022-10-14)

### ⚠️ BREAKING CHANGES

* `@npmcli/tap-nock` is now compatible with the following semver range for node: `^14.17.0 || ^16.13.0 || >=18.0.0`

### Features

* [`47acde6`](https://github.com/npm/tap-nock/commit/47acde630164a8e5e5fbde8b94187d2f69e5130e) [#14](https://github.com/npm/tap-nock/pull/14) postinstall for dependabot template-oss PR (@lukekarrys)

## 1.0.0 (2022-05-03)


### Features

* add transforms for snapshots ([2f5faea](https://github.com/npm/tap-nock/commit/2f5faea30037ce2d88b81e7d190a0dbdfdd96c10))
* allow snapshots and nocks to co-exist ([61a49cc](https://github.com/npm/tap-nock/commit/61a49cc3f6bf363274c8be4acac4745b74562196))


### Bug Fixes

* only writeSnapshot if we are actually recording ([c3b744e](https://github.com/npm/tap-nock/commit/c3b744efeb500b1b5f82b0515e87da45f2f88305))
