# Changelog

[npm history][1]

[1]: https://www.npmjs.com/package/google-proto-files?activeTab=versions

### [1.1.2](https://www.github.com/googleapis/nodejs-proto-files/compare/v1.1.1...v1.1.2) (2020-01-03)


### Bug Fixes

* **deps:** pin TypeScript below 3.7.0 ([cce5185](https://www.github.com/googleapis/nodejs-proto-files/commit/cce51858b5bae0ad30193766b03ad2dc631694bf))

### [1.1.1](https://www.github.com/googleapis/nodejs-proto-files/compare/v1.1.0...v1.1.1) (2019-11-14)


### Bug Fixes

* **docs:** add jsdoc-region-tag plugin ([#230](https://www.github.com/googleapis/nodejs-proto-files/issues/230)) ([8d25cd1](https://www.github.com/googleapis/nodejs-proto-files/commit/8d25cd12afeef9cfc37a5835f849225e4a5b5066))

## [1.1.0](https://www.github.com/googleapis/nodejs-proto-files/compare/v1.0.3...v1.1.0) (2019-08-23)


### Features

* include google/protobuf/compiler ([#213](https://www.github.com/googleapis/nodejs-proto-files/issues/213)) ([79ce071](https://www.github.com/googleapis/nodejs-proto-files/commit/79ce071))

### [1.0.3](https://www.github.com/googleapis/nodejs-proto-files/compare/v1.0.2...v1.0.3) (2019-06-26)


### Bug Fixes

* **docs:** link to reference docs section on googleapis.dev ([#206](https://www.github.com/googleapis/nodejs-proto-files/issues/206)) ([e25f29f](https://www.github.com/googleapis/nodejs-proto-files/commit/e25f29f))

### [1.0.2](https://www.github.com/googleapis/nodejs-proto-files/compare/v1.0.1...v1.0.2) (2019-06-14)


### Bug Fixes

* **docs:** move to new client docs URL ([#203](https://www.github.com/googleapis/nodejs-proto-files/issues/203)) ([324bbad](https://www.github.com/googleapis/nodejs-proto-files/commit/324bbad))

### [1.0.1](https://www.github.com/googleapis/nodejs-proto-files/compare/v1.0.0...v1.0.1) (2019-05-20)


### Bug Fixes

* **deps:** update dependency walkdir to ^0.4.0 ([#187](https://www.github.com/googleapis/nodejs-proto-files/issues/187)) ([48682cd](https://www.github.com/googleapis/nodejs-proto-files/commit/48682cd))

## [1.0.0](https://www.github.com/googleapis/nodejs-proto-files/compare/v0.20.0...v1.0.0) (2019-05-03)


### Bug Fixes

* **deps:** update dependency @google-cloud/promisify to v1 ([#179](https://www.github.com/googleapis/nodejs-proto-files/issues/179)) ([9a819f9](https://www.github.com/googleapis/nodejs-proto-files/commit/9a819f9))


### Build System

* upgrade engines field to >=8.10.0 ([#175](https://www.github.com/googleapis/nodejs-proto-files/issues/175)) ([e856a14](https://www.github.com/googleapis/nodejs-proto-files/commit/e856a14))


### Miscellaneous Chores

* **deps:** update dependency gts to v1 ([#173](https://www.github.com/googleapis/nodejs-proto-files/issues/173)) ([3ef1e72](https://www.github.com/googleapis/nodejs-proto-files/commit/3ef1e72))


### BREAKING CHANGES

* **deps:** this will ship async/await with the generated code.
* upgrade engines field to >=8.10.0 (#175)

## v0.20.0

03-15-2019 11:15 PDT

This release includes updated proto files from 
[googleapis/googleapis](https://github.com/googleapis/googleapis).

### Internal / Testing Changes

- build: use per-repo npm publish token ([#162](https://github.com/googleapis/nodejs-proto-files/pull/162))

## v0.19.0

03-13-2019 14:17 PDT

### Implementation Changes

- refactor: removed async module dependency ([#120](https://github.com/googleapis/nodejs-proto-files/pull/120))

### New Features

- Now the package includes new common proto file, `google/api/resource.proto`.

### Dependencies

- chore(deps): update dependency @google-cloud/nodejs-repo-tools to v3 ([#111](https://github.com/googleapis/nodejs-proto-files/pull/111))
- chore(deps): update dependency gts to ^0.9.0 ([#113](https://github.com/googleapis/nodejs-proto-files/pull/113))
- fix: Pin @types/sinon to last compatible version ([#116](https://github.com/googleapis/nodejs-proto-files/pull/116))
- chore(deps): update dependency @types/sinon to v5.0.7 ([#117](https://github.com/googleapis/nodejs-proto-files/pull/117))
- chore(deps): update dependency typescript to ~3.2.0 ([#119](https://github.com/googleapis/nodejs-proto-files/pull/119))
- chore(deps): update dependency @types/sinon to v7 ([#137](https://github.com/googleapis/nodejs-proto-files/pull/137))
- chore(deps): update dependency eslint-config-prettier to v4 ([#141](https://github.com/googleapis/nodejs-proto-files/pull/141))
- fix(deps): update dependency walkdir to v0.1.0 ([#143](https://github.com/googleapis/nodejs-proto-files/pull/143))
- fix(deps): update dependency walkdir to v0.2.0 ([#145](https://github.com/googleapis/nodejs-proto-files/pull/145))
- fix(deps): update dependency walkdir to ^0.3.0 ([#148](https://github.com/googleapis/nodejs-proto-files/pull/148))
- fix(deps): update dependency @google-cloud/promisify to ^0.4.0 ([#153](https://github.com/googleapis/nodejs-proto-files/pull/153))


### Documentation

- docs: update readme badges ([#123](https://github.com/googleapis/nodejs-proto-files/pull/123))
- docs: add lint/fix example to contributing guide ([#144](https://github.com/googleapis/nodejs-proto-files/pull/144))
- docs: update contributing path in README ([#147](https://github.com/googleapis/nodejs-proto-files/pull/147))
- docs: update links in contrib guide ([#155](https://github.com/googleapis/nodejs-proto-files/pull/155))

### Internal / Testing Changes

- chore: update eslintignore config ([#112](https://github.com/googleapis/nodejs-proto-files/pull/112))
- fix(build): fix system key decryption ([#121](https://github.com/googleapis/nodejs-proto-files/pull/121))
- chore: update license file ([#125](https://github.com/googleapis/nodejs-proto-files/pull/125))
- chore: nyc ignore build/test by default ([#127](https://github.com/googleapis/nodejs-proto-files/pull/127))
- chore: always nyc report before calling codecov ([#128](https://github.com/googleapis/nodejs-proto-files/pull/128))
- build: add Kokoro configs for autorelease ([#131](https://github.com/googleapis/nodejs-proto-files/pull/131))
- fix(build): fix Kokoro release script ([#132](https://github.com/googleapis/nodejs-proto-files/pull/132))
- chore: fix publish.sh permission +x ([#133](https://github.com/googleapis/nodejs-proto-files/pull/133))
- chore: update nyc and eslint configs ([#135](https://github.com/googleapis/nodejs-proto-files/pull/135))
- chore(build): inject yoshi automation key ([#136](https://github.com/googleapis/nodejs-proto-files/pull/136))
- build: check for 404s on all docs ([#139](https://github.com/googleapis/nodejs-proto-files/pull/139))
- build: ignore googleapis.com in doc link check ([#140](https://github.com/googleapis/nodejs-proto-files/pull/140))
- build: test using @grpc/grpc-js in CI ([#150](https://github.com/googleapis/nodejs-proto-files/pull/150))
- build: create docs test npm scripts ([#151](https://github.com/googleapis/nodejs-proto-files/pull/151))
- build: use linkinator for docs test ([#152](https://github.com/googleapis/nodejs-proto-files/pull/152))
- build: exclude CONTRIBUTING.md from synthing ([#154](https://github.com/googleapis/nodejs-proto-files/pull/154))
- build: use node10 to run samples-test, system-test etc ([#158](https://github.com/googleapis/nodejs-proto-files/pull/158))
- build: Add docuploader credentials to node publish jobs ([#159](https://github.com/googleapis/nodejs-proto-files/pull/159))

## v0.18.0

11-09-2018 15:34 PST

This is a minor service release, with a few internal changes.

- refactor: use `walkdir` instead of `globby` ([#109](https://github.com/googleapis/nodejs-proto-files/pull/109))
- chore: drop contributors from multiple places ([#108](https://github.com/googleapis/nodejs-proto-files/pull/108))
- chore: use latest npm on Windows ([#107](https://github.com/googleapis/nodejs-proto-files/pull/107))
- refactor: convert to typescript ([#106](https://github.com/googleapis/nodejs-proto-files/pull/106))
- refactor: use a src/ directory ([#105](https://github.com/googleapis/nodejs-proto-files/pull/105))
- chore: update CircleCI config ([#104](https://github.com/googleapis/nodejs-proto-files/pull/104))
- chore: include build in eslintignore ([#101](https://github.com/googleapis/nodejs-proto-files/pull/101))
- chore(deps): update dependency eslint-plugin-node to v8 ([#97](https://github.com/googleapis/nodejs-proto-files/pull/97))
- chore: update issue templates ([#96](https://github.com/googleapis/nodejs-proto-files/pull/96))
- chore: remove old issue template ([#94](https://github.com/googleapis/nodejs-proto-files/pull/94))
- build: run tests on node11 ([#93](https://github.com/googleapis/nodejs-proto-files/pull/93))
- chores(build): do not collect sponge.xml from windows builds ([#92](https://github.com/googleapis/nodejs-proto-files/pull/92))
- chores(build): run codecov on continuous builds ([#91](https://github.com/googleapis/nodejs-proto-files/pull/91))
- chore: update new issue template ([#90](https://github.com/googleapis/nodejs-proto-files/pull/90))
- build: fix codecov uploading on Kokoro ([#86](https://github.com/googleapis/nodejs-proto-files/pull/86))
- build: automate library with synth.py ([#85](https://github.com/googleapis/nodejs-proto-files/pull/85))
- chore(deps): update dependency sinon to v7 ([#84](https://github.com/googleapis/nodejs-proto-files/pull/84))

## v0.17.0

### Breaking changes
- fix: drop support for node.js 4.x and 9.x ([#57](https://github.com/googleapis/nodejs-proto-files/pull/57))

### Fixes
- fix: update linking for samples ([#50](https://github.com/googleapis/nodejs-proto-files/pull/50))

### Internal / Testing Changes
- chore(deps): update dependency eslint-plugin-prettier to v3 ([#81](https://github.com/googleapis/nodejs-proto-files/pull/81))
- test: remove appveyor config ([#80](https://github.com/googleapis/nodejs-proto-files/pull/80))
- Enable prefer-const in the eslint config ([#79](https://github.com/googleapis/nodejs-proto-files/pull/79))
- Enable no-var in eslint ([#78](https://github.com/googleapis/nodejs-proto-files/pull/78))
- Update CI and fix tests ([#77](https://github.com/googleapis/nodejs-proto-files/pull/77))
- Retry npm install in CI ([#76](https://github.com/googleapis/nodejs-proto-files/pull/76))
- chore(deps): update dependency nyc to v13 ([#75](https://github.com/googleapis/nodejs-proto-files/pull/75))
- chore(deps): update dependency eslint-config-prettier to v3 ([#74](https://github.com/googleapis/nodejs-proto-files/pull/74))
- chore: ignore package-lock.json ([#73](https://github.com/googleapis/nodejs-proto-files/pull/73))
- chore(deps): lock file maintenance ([#72](https://github.com/googleapis/nodejs-proto-files/pull/72))
- chore: use let and const ([#71](https://github.com/googleapis/nodejs-proto-files/pull/71))
- chore: update renovate config ([#69](https://github.com/googleapis/nodejs-proto-files/pull/69))
- remove that whitespace ([#68](https://github.com/googleapis/nodejs-proto-files/pull/68))
- chore(deps): lock file maintenance ([#67](https://github.com/googleapis/nodejs-proto-files/pull/67))
- chore: move mocha options to mocha.opts ([#66](https://github.com/googleapis/nodejs-proto-files/pull/66))
- chore(deps): update dependency eslint-plugin-node to v7 ([#62](https://github.com/googleapis/nodejs-proto-files/pull/62))
- chore(deps): lock file maintenance ([#65](https://github.com/googleapis/nodejs-proto-files/pull/65))
- chore(deps): lock file maintenance ([#61](https://github.com/googleapis/nodejs-proto-files/pull/61))
- chore(deps): lock file maintenance ([#60](https://github.com/googleapis/nodejs-proto-files/pull/60))
- chore(deps): lock file maintenance ([#59](https://github.com/googleapis/nodejs-proto-files/pull/59))
- chore(deps): lock file maintenance ([#58](https://github.com/googleapis/nodejs-proto-files/pull/58))
- fix: remove unused packages ([#56](https://github.com/googleapis/nodejs-proto-files/pull/56))
- chore(deps): lock file maintenance ([#55](https://github.com/googleapis/nodejs-proto-files/pull/55))
- chore(deps): lock file maintenance ([#54](https://github.com/googleapis/nodejs-proto-files/pull/54))
- chore(deps): lock file maintenance ([#53](https://github.com/googleapis/nodejs-proto-files/pull/53))
- chore(deps): lock file maintenance ([#52](https://github.com/googleapis/nodejs-proto-files/pull/52))
- Configure Renovate ([#48](https://github.com/googleapis/nodejs-proto-files/pull/48))
- chore(package): update eslint to version 5.0.0 ([#49](https://github.com/googleapis/nodejs-proto-files/pull/49))
- refactor: drop repo-tool as an exec wrapper ([#51](https://github.com/googleapis/nodejs-proto-files/pull/51))
