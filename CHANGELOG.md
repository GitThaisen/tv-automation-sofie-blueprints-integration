# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="0.11.0"></a>
# [0.11.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.10.0...0.11.0) (2019-01-16)


### Features

* **migrations:** Add show style runtime arguments to migrations ([b9d055b](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/b9d055b))



<a name="0.10.0"></a>
# [0.10.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.9.0...0.10.0) (2019-01-11)


### Bug Fixes

* Tidy todos ([1744867](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/1744867))


### Features

* Add classes arrays to SegmentLine ([0911caf](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/0911caf))
* add ConfigRef function, to be able to reference config values, instead of using the values directly (can be used for usernames & passwords in metadata message flow) ([efa467e](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/efa467e))



<a name="0.9.0"></a>
# [0.9.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.8.0...0.9.0) (2019-01-08)


### Bug Fixes

* add AsRunLogEventContent ([11a2cf0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/11a2cf0))


### Features

* add mediaFlowId to VTContent ([8e505b4](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/8e505b4))
* asRunEventContext: add getSegmentLineItem & getSegmentLineItem ([bc1e58c](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/bc1e58c))



<a name="0.8.0"></a>
# [0.8.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.7.0...0.8.0) (2018-12-11)


### Bug Fixes

* add missing enum export ([2e74bc0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/2e74bc0))


### Features

* add asRunEvent methods ([92772c4](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/92772c4))



<a name="0.7.0"></a>
# [0.7.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.6.2...0.7.0) (2018-12-10)


### Bug Fixes

* AsRunLogEvent: add _id ([27f8db0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/27f8db0))


### Features

* **migrations:** Expose method to get the full variant id ([1e59893](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/1e59893))



<a name="0.6.2"></a>
## [0.6.2](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.6.1...0.6.2) (2018-12-03)


### Bug Fixes

* SegmentLineContext typings ([f98765c](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/f98765c))



<a name="0.6.1"></a>
## [0.6.1](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.6.0...0.6.1) (2018-11-30)


### Bug Fixes

* fixed IMessageBlueprintSegmentLine and removed Pure interfaces because they are stupid. ([0fb1f3e](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/0fb1f3e))



<a name="0.6.0"></a>
# [0.6.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.7...0.6.0) (2018-11-30)


### Bug Fixes

* bug in iterateDeeplyAsync ([7b2e5b5](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/7b2e5b5))
* case sensitive import paths ([ca94cdb](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/ca94cdb))
* **migrations:** Blueprints specify variant id, to make it possible to update one later on ([d4ad8a4](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/d4ad8a4))
* linter error ([16cec3a](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/16cec3a))
* onTakes should have SegmentLineContextPure ([14eb7b2](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/14eb7b2))
* update tsr-types ([41a4583](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/41a4583))


### Features

* **migrations:** Add playout-device migration methods to studio migration context ([6e1ecb0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/6e1ecb0))
* fixed API for eventCallbacks, and split interfaces into "Pure" (which doesn't contain the UI-centric NotesContext) and normal ([ddfa0ab](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/ddfa0ab))
* renamed & reworked API ([fc51f11](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/fc51f11))



<a name="0.5.7"></a>
## [0.5.7](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.6...0.5.7) (2018-11-28)


### Bug Fixes

* missing dependencies ([6be0633](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/6be0633))



<a name="0.5.6"></a>
## [0.5.6](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.5...0.5.6) (2018-11-26)



<a name="0.5.5"></a>
## [0.5.5](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.4...0.5.5) (2018-11-23)


### Bug Fixes

* migration interface typing tweaks ([e2f9666](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/e2f9666))



<a name="0.5.4"></a>
## [0.5.4](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.3...0.5.4) (2018-11-23)


### Bug Fixes

* add missing ConfigItemValue types ([2ab6e33](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/2ab6e33))



<a name="0.5.3"></a>
## [0.5.3](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.2...0.5.3) (2018-11-22)


### Bug Fixes

* config default value type ([11caa0e](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/11caa0e))
* proper enum exports & fixed tests ([ac7e82a](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/ac7e82a))



<a name="0.5.2"></a>
## [0.5.2](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.1...0.5.2) (2018-11-22)


### Bug Fixes

* mos-connection typings: add full classes for data types. (They are needed downstream in Core..) ([eb57f04](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/eb57f04))



<a name="0.5.1"></a>
## [0.5.1](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.5.0...0.5.1) (2018-11-22)


### Bug Fixes

* export mos typings ([0edff3f](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/0edff3f))



<a name="0.5.0"></a>
# [0.5.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.4.1...0.5.0) (2018-11-22)


### Bug Fixes

* migration interfaces touchups ([aa8257b](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/aa8257b))
* removed dependency mos-connection and replaced with internal copy ([c2963ba](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/c2963ba))
* removed dependency of superfly-timeline and replaced with types from TSR-types ([480408e](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/480408e))
* tighten type of configItem ([57ff2c1](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/57ff2c1))
* type ref ([ed000c6](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/ed000c6))
* update dependencies ([e26fd9b](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/e26fd9b))
* update TSR-types dependency ([b6bfcab](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/b6bfcab))
* update typedoc dep ([0c0c508](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/0c0c508))


### Features

* **migrations:** Add context to migration validate and migrate functions. ([93b555e](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/93b555e))
* **migrations:** Add types for blueprint based migrations ([0d0d99b](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/0d0d99b))



<a name="0.4.1"></a>
## [0.4.1](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.4.0...0.4.1) (2018-11-21)


### Bug Fixes

* **runningOrder:** Correct types of transisition duration properties on SegmentLine ([b0aec50](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/b0aec50))



<a name="0.4.0"></a>
# [0.4.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.3.1...0.4.0) (2018-11-20)


### Bug Fixes

* Change types of transition timings on segmentline ([0a7ba6b](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/0a7ba6b))
* reverting splitting configManifest ([cf9a68b](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/cf9a68b))


### Features

* split configs into studio-configs & show-configs ([2d95741](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/2d95741))



<a name="0.3.1"></a>
## [0.3.1](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.3.0...0.3.1) (2018-11-19)


### Bug Fixes

* **config:** Missing export in index.ts ([5e70d2d](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/5e70d2d))



<a name="0.3.0"></a>
# [0.3.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.2.0...0.3.0) (2018-11-19)


### Features

* Add config manifests ([4bfd30a](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/4bfd30a))
* Add minimum core version field ([3817ce3](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/3817ce3))



<a name="0.2.0"></a>
# [0.2.0](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.1.5...0.2.0) (2018-11-15)


### Features

* Add blueprint runtime arguments ([1676711](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/1676711))



<a name="0.1.5"></a>
## [0.1.5](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/0.1.4...0.1.5) (2018-11-08)


### Bug Fixes

* attempt to fix npm package not including dist files ([744b2b6](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/744b2b6))



<a name="0.1.4"></a>
## [0.1.4](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/v0.1.3...v0.1.4) (2018-11-08)


### Bug Fixes

* prevent infinite release loop ([a2dd894](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/a2dd894))



<a name="0.1.3"></a>
## [0.1.3](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/v0.1.2...v0.1.3) (2018-11-08)



<a name="0.1.2"></a>
## [0.1.2](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/v0.1.1...v0.1.2) (2018-11-08)



<a name="0.1.1"></a>
## [0.1.1](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/compare/v0.1.0...v0.1.1) (2018-11-08)



<a name="0.1.0"></a>
# 0.1.0 (2018-11-08)


### Bug Fixes

* add index.ts ([200af13](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/200af13))
* Add missing iterateDeeplyAsync ([4ab0127](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/4ab0127))
* added devDependencies ([8d9ad46](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/8d9ad46))
* build ([8f825af](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/8f825af))
* enum used before declaration ([6dce53e](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/6dce53e))
* Loosen typings to reduce polluting core with unnecessary types ([e1ec803](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/e1ec803))
* Remove getHash as it leaves a require in the built blob ([dba6e77](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/dba6e77))
* Update to release supertimeline ([b25e920](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/b25e920))


### Features

* added scripts and tests stub. also preparing for CI ([bedfeb3](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/bedfeb3))
* Simplify some typings ([9a2c2eb](https://github.com/nrkno/tv-automation-sofie-blueprints-integration/commit/9a2c2eb))