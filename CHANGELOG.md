## [3.0.7](https://github.com/semantic-release-action/typescript/compare/v3.0.6...v3.0.7) (2023-07-13)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.7 ([a97ed9e](https://github.com/semantic-release-action/typescript/commit/a97ed9e539f7eb3962083df30ed8003209049bd6))

## [3.0.6](https://github.com/semantic-release-action/typescript/compare/v3.0.5...v3.0.6) (2023-06-18)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.5 ([5b8dc42](https://github.com/semantic-release-action/typescript/commit/5b8dc42bec7e1dce77b51db31eb2d18b327d4697))

## [3.0.5](https://github.com/semantic-release-action/typescript/compare/v3.0.4...v3.0.5) (2023-05-06)


### Bug Fixes

* **deps:** update dependency semantic-release to v21.0.2 ([f43d183](https://github.com/semantic-release-action/typescript/commit/f43d1836c138da85098b807afd02f3bfc77c8567))

## [3.0.4](https://github.com/semantic-release-action/typescript/compare/v3.0.3...v3.0.4) (2023-05-04)


### Bug Fixes

* thread release-node-version through to reusable action properly ([a908a08](https://github.com/semantic-release-action/typescript/commit/a908a087275c5127da819568fd862f4142192742))

## [3.0.3](https://github.com/semantic-release-action/typescript/compare/v3.0.2...v3.0.3) (2023-03-26)


### Bug Fixes

* remove redundant words from step name ([7e220b9](https://github.com/semantic-release-action/typescript/commit/7e220b9d37c9be5970f2cfc103b3457a66258e29))
* use consistent job name ([f03d69d](https://github.com/semantic-release-action/typescript/commit/f03d69d5de8c2c07910f562d4a757826dd992fff))

## [3.0.2](https://github.com/semantic-release-action/typescript/compare/v3.0.1...v3.0.2) (2023-03-25)


### Bug Fixes

* **deps:** update dependency semantic-release to v21 ([d97e282](https://github.com/semantic-release-action/typescript/commit/d97e282157f34cce823224075cfa3e93d0581fb1))

## [3.0.1](https://github.com/semantic-release-action/typescript/compare/v3.0.0...v3.0.1) (2023-03-25)


### Bug Fixes

* **deps:** update semantic-release monorepo ([e203a3e](https://github.com/semantic-release-action/typescript/commit/e203a3e23c90e17a0b7a818f8287144ab2ba272c))

# [3.0.0](https://github.com/semantic-release-action/typescript/compare/v2.0.6...v3.0.0) (2023-02-19)


* fix!: pass node-version properly to setup-node ([ba0fa52](https://github.com/semantic-release-action/typescript/commit/ba0fa52a891e09150378166a706de953073933ae))


### BREAKING CHANGES

* release workflow specifies test and release Node.js versions

The release.yml workflow now accepts two inputs specifying Node.js
version:

1. `test-node-versions`
2. `release-node-version`

The former specifies which Node.js versions will be used to run
the `build` and `test` npm scripts before invoking `semantic-release`,
and the latter specifies which Node.js version to use to invoke
`semantic-release`.

## [2.0.6](https://github.com/semantic-release-action/typescript/compare/v2.0.5...v2.0.6) (2023-02-07)


### Bug Fixes

* update node-version to match documentation ([87d72ed](https://github.com/semantic-release-action/typescript/commit/87d72edbf11b370ab4c5216ec5b66cb62b8a9dd0))

## [2.0.5](https://github.com/semantic-release-action/typescript/compare/v2.0.4...v2.0.5) (2023-02-07)


### Bug Fixes

* update allow-postinstall-scripts code to match documentation ([7bc9008](https://github.com/semantic-release-action/typescript/commit/7bc9008f70b46c3b8e9feb2da70a44171158d845))

## [2.0.4](https://github.com/semantic-release-action/typescript/compare/v2.0.3...v2.0.4) (2023-02-07)


### Bug Fixes

* remove unrelated environment variable ([6c12764](https://github.com/semantic-release-action/typescript/commit/6c12764c70f7058685d3663d6aebbf93435bd0de))

## [2.0.3](https://github.com/semantic-release-action/typescript/compare/v2.0.2...v2.0.3) (2023-02-07)


### Bug Fixes

* **deps:** update dependency semantic-release to v20.1.0 ([5423b5a](https://github.com/semantic-release-action/typescript/commit/5423b5a33b6b621c0c76b846d33230b46b1ee762))

## [2.0.2](https://github.com/semantic-release-action/typescript/compare/v2.0.1...v2.0.2) (2023-01-16)


### Bug Fixes

* treat action inputs as string ([13825af](https://github.com/semantic-release-action/typescript/commit/13825afc6b46638373b4eddb53f04affb2632047))

## [2.0.1](https://github.com/semantic-release-action/typescript/compare/v2.0.0...v2.0.1) (2023-01-16)


### Bug Fixes

* **deps:** upgrade self-reference to latest ([24d0bb1](https://github.com/semantic-release-action/typescript/commit/24d0bb13a7d93c93ac9b82f973f4ea36c04fc89d))

# [2.0.0](https://github.com/semantic-release-action/typescript/compare/v1.1.2...v2.0.0) (2023-01-16)


* fix!: negate logic of runtime flags controlling semantic-release ([7544b20](https://github.com/semantic-release-action/typescript/commit/7544b2089895af14d01326df360e506101bfc183))


### BREAKING CHANGES

* negate logic of runtime flags controlling semantic-release

## [1.1.2](https://github.com/semantic-release-action/typescript/compare/v1.1.1...v1.1.2) (2023-01-15)


### Bug Fixes

* only run tests if present ([45fa0e9](https://github.com/semantic-release-action/typescript/commit/45fa0e9a652c0d5bb6cda64dfda3e510bf3e68e7))

## [1.1.1](https://github.com/semantic-release-action/typescript/compare/v1.1.0...v1.1.1) (2023-01-14)


### Bug Fixes

* **ci:** invoke reusable workflow correctly ([b7e7be1](https://github.com/semantic-release-action/typescript/commit/b7e7be1b3df6e805c3084d60dcb2eb95fb4276a1))
* **ci:** update semantic-release-action/github-actions to v4 ([67ce158](https://github.com/semantic-release-action/typescript/commit/67ce158ef561194b1a5958dbfbf5c11422286ee5))

# [1.1.0](https://github.com/semantic-release-action/typescript/compare/v1.0.8...v1.1.0) (2023-01-14)


### Features

* add runtime flag to control semantic-release git ([9b1f384](https://github.com/semantic-release-action/typescript/commit/9b1f3846cd3879f4424a9c89f85a1c36d76fe7d5)), closes [#3](https://github.com/semantic-release-action/typescript/issues/3)

## [1.0.8](https://github.com/semantic-release-action/typescript/compare/v1.0.7...v1.0.8) (2023-01-14)


### Bug Fixes

* update project metadata ([5101277](https://github.com/semantic-release-action/typescript/commit/5101277f7120f1a25b76b5d0f25bc4fa4a779c63)), closes [#4](https://github.com/semantic-release-action/typescript/issues/4)

## [1.0.7](https://github.com/semantic-release-action/typescript/compare/v1.0.6...v1.0.7) (2023-01-14)


### Bug Fixes

* **deps:** migrate to semantic-release-action/github-actions ([86c03b6](https://github.com/semantic-release-action/typescript/commit/86c03b64248eae542967674db021255b4f686f6f))

## [1.0.6](https://github.com/semantic-release-action/typescript/compare/v1.0.5...v1.0.6) (2023-01-12)


### Bug Fixes

* **deps:** upgrade install-github-release-binary to v2 ([34dd4d4](https://github.com/semantic-release-action/typescript/commit/34dd4d48eb837555cc600a348e2588668594ed75))

## [1.0.5](https://github.com/semantic-release-action/typescript/compare/v1.0.4...v1.0.5) (2023-01-10)


### Bug Fixes

* add --if-present to all npm script invocations ([2e5ee30](https://github.com/semantic-release-action/typescript/commit/2e5ee30d31cc12f9e8e0b1a49f1b30eefb62506c))

## [1.0.4](https://github.com/semantic-release-action/typescript/compare/v1.0.3...v1.0.4) (2023-01-10)


### Bug Fixes

* use correct input name ([51a3e96](https://github.com/semantic-release-action/typescript/commit/51a3e9627dc2651e09a7493883dabe90c150b22c))

## [1.0.3](https://github.com/semantic-release-action/typescript/compare/v1.0.2...v1.0.3) (2023-01-10)


### Bug Fixes

* use a single node version for the release workflow ([cac9d3c](https://github.com/semantic-release-action/typescript/commit/cac9d3c3dcaead4a2995f7f483aa2ecae7300686))

## [1.0.2](https://github.com/semantic-release-action/typescript/compare/v1.0.1...v1.0.2) (2023-01-10)


### Bug Fixes

* always install host node_modules ([ca45c56](https://github.com/semantic-release-action/typescript/commit/ca45c56cd94148c6376fb49da7d788b7933325a1))

## [1.0.1](https://github.com/semantic-release-action/typescript/compare/v1.0.0...v1.0.1) (2023-01-10)


### Bug Fixes

* default flag to true ([0d96c29](https://github.com/semantic-release-action/typescript/commit/0d96c299d662d4153f336aaa25adfe438a480a32))

# 1.0.0 (2023-01-10)


### Features

* initial commit ([e53d4f7](https://github.com/semantic-release-action/typescript/commit/e53d4f77ff33fb63586da20def46a3f57275756f))
