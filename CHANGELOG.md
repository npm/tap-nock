# Changelog

## [2.0.2](https://github.com/npm/tap-nock/compare/v2.0.1...v2.0.2) (2023-12-07)

### Chores

* [`adfc1d3`](https://github.com/npm/tap-nock/commit/adfc1d3da312a1cf3b7fb663eab75157d07eae92) [#64](https://github.com/npm/tap-nock/pull/64) postinstall for dependabot template-oss PR (@lukekarrys)
* [`0704390`](https://github.com/npm/tap-nock/commit/07043900f0fa1cc784882a37da4aab366a69fe51) [#64](https://github.com/npm/tap-nock/pull/64) bump @npmcli/template-oss from 4.21.1 to 4.21.3 (@dependabot[bot])
* [`552e737`](https://github.com/npm/tap-nock/commit/552e73730f82cdf5a0fa40d5d80964f5c7026ec2) [#61](https://github.com/npm/tap-nock/pull/61) postinstall for dependabot template-oss PR (@lukekarrys)
* [`b014a06`](https://github.com/npm/tap-nock/commit/b014a06f185926314fd7fae6465cf1716eda7d39) [#61](https://github.com/npm/tap-nock/pull/61) bump @npmcli/template-oss from 4.19.0 to 4.21.1 (@dependabot[bot])
* [`df581af`](https://github.com/npm/tap-nock/commit/df581af8e1685c200eed8633ccc1a947ac154718) [#43](https://github.com/npm/tap-nock/pull/43) postinstall for dependabot template-oss PR (@lukekarrys)
* [`4938013`](https://github.com/npm/tap-nock/commit/49380137f2a763c27c96bf62d83db0066c159f7d) [#43](https://github.com/npm/tap-nock/pull/43) bump @npmcli/template-oss from 4.17.0 to 4.19.0 (@dependabot[bot])
* [`ffb9c46`](https://github.com/npm/tap-nock/commit/ffb9c464d8b4bb6804b3114b79f520912e5841b4) [#41](https://github.com/npm/tap-nock/pull/41) postinstall for dependabot template-oss PR (@lukekarrys)
* [`2f0b205`](https://github.com/npm/tap-nock/commit/2f0b20547f181471009afc9776a7350acbbfcd5a) [#41](https://github.com/npm/tap-nock/pull/41) bump @npmcli/template-oss from 4.15.1 to 4.17.0 (@dependabot[bot])
* [`23b1ac2`](https://github.com/npm/tap-nock/commit/23b1ac2f33905f4cbbeea0fa501e4476f46d810d) [#40](https://github.com/npm/tap-nock/pull/40) postinstall for dependabot template-oss PR (@lukekarrys)
* [`80f9841`](https://github.com/npm/tap-nock/commit/80f984119422611ae701a093b90b4be6b4a19ef5) [#40](https://github.com/npm/tap-nock/pull/40) bump @npmcli/template-oss from 4.12.0 to 4.15.1 (@dependabot[bot])
* [`63ffab8`](https://github.com/npm/tap-nock/commit/63ffab833ce55a81df1f6be835e005fc513b1193) [#39](https://github.com/npm/tap-nock/pull/39) postinstall for dependabot template-oss PR (@lukekarrys)
* [`c164f3f`](https://github.com/npm/tap-nock/commit/c164f3fb78e5312d86efa1a89c8e3e9bd10faa21) [#39](https://github.com/npm/tap-nock/pull/39) bump @npmcli/template-oss from 4.11.4 to 4.12.0 (@dependabot[bot])
* [`565ae2e`](https://github.com/npm/tap-nock/commit/565ae2eb9acdac6b76183bebafe7783ce3257761) [#38](https://github.com/npm/tap-nock/pull/38) postinstall for dependabot template-oss PR (@lukekarrys)
* [`02a2022`](https://github.com/npm/tap-nock/commit/02a202262e379da8de4a32506f97dbc99fc97bcc) [#38](https://github.com/npm/tap-nock/pull/38) bump @npmcli/template-oss from 4.11.3 to 4.11.4 (@dependabot[bot])

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
