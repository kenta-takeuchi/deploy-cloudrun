# Changelog

## [0.10.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.9.0...v0.10.0) (2022-05-02)


### Features

* allow for multi line flags ([#320](https://www.github.com/google-github-actions/deploy-cloudrun/issues/320)) ([c5ec47b](https://www.github.com/google-github-actions/deploy-cloudrun/commit/c5ec47bd62298b802bfff30783b634810a057e5b))


### Bug Fixes

* migrate to actions-utils parseFlags ([#332](https://www.github.com/google-github-actions/deploy-cloudrun/issues/332)) ([a695629](https://www.github.com/google-github-actions/deploy-cloudrun/commit/a6956293801f1f9078b3c25be42db7ad46b1d83d))

## [0.9.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.8.0...v0.9.0) (2022-03-08)


### ⚠ BREAKING CHANGES

* require Node 16 (#315)
* switch to nodejs 16 (#295)

### Features

* added gcloud_component flag to force alpha or beta ([#294](https://www.github.com/google-github-actions/deploy-cloudrun/issues/294)) ([08e594e](https://www.github.com/google-github-actions/deploy-cloudrun/commit/08e594ea50dd3b8b1f9e6f13179f1f5b18d5144a))


### Bug Fixes

* switch to actions-utils for multi-line KV parsing ([#312](https://www.github.com/google-github-actions/deploy-cloudrun/issues/312)) ([1cd5368](https://www.github.com/google-github-actions/deploy-cloudrun/commit/1cd5368e199e5944edfc7c9d953516a5f1642e78))


### Miscellaneous Chores

* require Node 16 ([#315](https://www.github.com/google-github-actions/deploy-cloudrun/issues/315)) ([20d7967](https://www.github.com/google-github-actions/deploy-cloudrun/commit/20d79677d49bd483b53e2e6755cde241ce76a85c))
* switch to nodejs 16 ([#295](https://www.github.com/google-github-actions/deploy-cloudrun/issues/295)) ([7c8e7d0](https://www.github.com/google-github-actions/deploy-cloudrun/commit/7c8e7d0b8066be63d8254cfdd7524186c8175b9e))

## [0.8.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.7.0...v0.8.0) (2022-01-31)


### Features

* add `timeout` option for setting execution timeouts ([#291](https://www.github.com/google-github-actions/deploy-cloudrun/issues/291)) ([30692e4](https://www.github.com/google-github-actions/deploy-cloudrun/commit/30692e449d09cf9b29e0be80a0d3d7cf7409a397))
* allow for multi line secrets ([#224](https://www.github.com/google-github-actions/deploy-cloudrun/issues/224)) ([5cab4a9](https://www.github.com/google-github-actions/deploy-cloudrun/commit/5cab4a99aad37f2049c16809f2372ee1bcfbd674))
* Enable machine parsable output with --format json ([#283](https://www.github.com/google-github-actions/deploy-cloudrun/issues/283)) ([50aa77a](https://www.github.com/google-github-actions/deploy-cloudrun/commit/50aa77a4cc04bc953904f3b82fce54dcdab435a5))
* support single quote flags ([#289](https://www.github.com/google-github-actions/deploy-cloudrun/issues/289)) ([dd45811](https://www.github.com/google-github-actions/deploy-cloudrun/commit/dd458116fa3a920fce433f28697629c5b163a9dc))

## [0.7.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.6.0...v0.7.0) (2021-12-15)


### Features

* add WIF support ([#254](https://www.github.com/google-github-actions/deploy-cloudrun/issues/254)) ([1a42a1c](https://www.github.com/google-github-actions/deploy-cloudrun/commit/1a42a1c5d9f8c28a15a9c2baec5767873fed11c7))
* update all dependencies ([#262](https://www.github.com/google-github-actions/deploy-cloudrun/issues/262)) ([ab7ecb7](https://www.github.com/google-github-actions/deploy-cloudrun/commit/ab7ecb7bee7cfa1c5d9d05d4a511e9ec9a99a117))
* use library for setup-cloud-sdk ([#232](https://www.github.com/google-github-actions/deploy-cloudrun/issues/232)) ([d419653](https://www.github.com/google-github-actions/deploy-cloudrun/commit/d419653e9e7540752f657d4ae8ce1c992a9454e7))

## [0.6.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.5.0...v0.6.0) (2021-05-27)


### Features

* Add Secrets Manger integration support ([#64](https://www.github.com/google-github-actions/deploy-cloudrun/issues/64)) ([4a9b191](https://www.github.com/google-github-actions/deploy-cloudrun/commit/4a9b1916d11796934ce70d155a9fa30b282bb935))


### Bug Fixes

* **deps:** update dependency fs to v0.0.2 ([#54](https://www.github.com/google-github-actions/deploy-cloudrun/issues/54)) ([3e6a16a](https://www.github.com/google-github-actions/deploy-cloudrun/commit/3e6a16a292c034e56bf24da5e45c59e232ab0639))
* **deps:** update dependency googleapis to v73 ([#57](https://www.github.com/google-github-actions/deploy-cloudrun/issues/57)) ([759fbb9](https://www.github.com/google-github-actions/deploy-cloudrun/commit/759fbb9f9ada824d9782018bf16acd8bcfb0d544))
* Update to PR target ([#68](https://www.github.com/google-github-actions/deploy-cloudrun/issues/68)) ([02b3b48](https://www.github.com/google-github-actions/deploy-cloudrun/commit/02b3b48476414e852806d64d4d8684f1a0894484))

## [0.5.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.4.0...v0.5.0) (2021-04-05)


### Features

* Add source deploys and traffic updates ([#45](https://www.github.com/google-github-actions/deploy-cloudrun/issues/45)) ([09c010d](https://www.github.com/google-github-actions/deploy-cloudrun/commit/09c010da2e395d281a1aa052c124e25499a90d01))

## [0.4.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.3.0...v0.4.0) (2021-02-11)


### Features

* **deps:** update dependencies ([#27](https://www.github.com/google-github-actions/deploy-cloudrun/issues/27)) ([0751aed](https://www.github.com/google-github-actions/deploy-cloudrun/commit/0751aed08ff283f784c4716030a75195098edaa8))


### Bug Fixes

* **testing:** run IT tests cleanup only when needed ([#37](https://www.github.com/google-github-actions/deploy-cloudrun/issues/37)) ([9de5186](https://www.github.com/google-github-actions/deploy-cloudrun/commit/9de5186fe826371613a003a2c22ae38be0994d22))
* update merging of services ([#30](https://www.github.com/google-github-actions/deploy-cloudrun/issues/30)) ([7d88f7a](https://www.github.com/google-github-actions/deploy-cloudrun/commit/7d88f7a4c9f15186916068e190b0de7eaf8a792e))
* Update service polling ([#31](https://www.github.com/google-github-actions/deploy-cloudrun/issues/31)) ([75b3108](https://www.github.com/google-github-actions/deploy-cloudrun/commit/75b31080b36d9abc33f5e2bdf6133aaa59103b78))

## [0.3.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.2.0...v0.3.0) (2021-01-27)


### Features

* add example workflows ([#18](https://www.github.com/google-github-actions/deploy-cloudrun/issues/18)) ([5652d4b](https://www.github.com/google-github-actions/deploy-cloudrun/commit/5652d4b5c6b4ce9faf3dd378b0ce708e3c5166d1))


### Bug Fixes

* Fix typo ([#14](https://www.github.com/google-github-actions/deploy-cloudrun/issues/14)) ([a668135](https://www.github.com/google-github-actions/deploy-cloudrun/commit/a66813593867a8bc0060864533692e5c2040ef4a))
* force update revision name ([#24](https://www.github.com/google-github-actions/deploy-cloudrun/issues/24)) ([cf303b9](https://www.github.com/google-github-actions/deploy-cloudrun/commit/cf303b9cfd946264794af73a25c0b058a00a1ced))

## [0.2.0](https://www.github.com/google-github-actions/deploy-cloudrun/compare/v0.1.0...v0.2.0) (2020-11-17)


### ⚠ BREAKING CHANGES

* transfer Cloud Run action (#1)

### Features

* add wait ([#7](https://www.github.com/google-github-actions/deploy-cloudrun/issues/7)) ([af80197](https://www.github.com/google-github-actions/deploy-cloudrun/commit/af80197d45a57e58031c68188979f7fcb2e63b82))
* transfer Cloud Run action ([#1](https://www.github.com/google-github-actions/deploy-cloudrun/issues/1)) ([6928ef0](https://www.github.com/google-github-actions/deploy-cloudrun/commit/6928ef0afe589614373c7d6ccc6f1dd4b149f96f))
* Update action desc ([#8](https://www.github.com/google-github-actions/deploy-cloudrun/issues/8)) ([b062ab9](https://www.github.com/google-github-actions/deploy-cloudrun/commit/b062ab9147fffb51a9c0f4f63090ccb37b884280))
