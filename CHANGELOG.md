# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.0.1](https://github.com/aspect-dev/json-dts-generator/compare/v2.0.0...v2.0.1) (2021-10-01)


### Bug Fixes

* export a const and not a type so that dts matches what typescript expects when it imports a json file ([2ecee05](https://github.com/aspect-dev/json-dts-generator/commit/2ecee05945d2830aa2afe725b1190e25954e57c3))

## [2.0.0](https://github.com/aspect-dev/json-dts-generator/compare/v1.0.0...v2.0.0) (2021-10-01)


### Features

* switch to input_file and output_file ([94615e7](https://github.com/aspect-dev/json-dts-generator/commit/94615e75ff83625d3e8fba99df8c11765b19c22b))

## 1.0.0 (2020-07-07)


### Features

* Add contexts to generated type aliases ([f82e977](https://github.com/Asha20/json-dts-generator/commit/f82e977829b05581fac8d6358be322daab77369f))
* Allow multiple contexts per type alias ([7347f68](https://github.com/Asha20/json-dts-generator/commit/7347f687cb02354aa7e5073f2ebd776c616d66bb))
* Display warning about `unknown[]` arrays ([0e1824b](https://github.com/Asha20/json-dts-generator/commit/0e1824bd51e778717c3f5c8c1f88a41f006f0a80))
* Generate DTS files from JSON files ([7ad41f5](https://github.com/Asha20/json-dts-generator/commit/7ad41f5eb9758e832c88ffbfa24413cb732a48e4))
* Introduce unique types ([0b735d2](https://github.com/Asha20/json-dts-generator/commit/0b735d266de3d9a2e60de3dbe82e2e1fc7dad8cb))
* Process subfolders & mirror them in output ([ed80b71](https://github.com/Asha20/json-dts-generator/commit/ed80b7148933efdf6909e89b6ec2dd83545ce436))


### Bug Fixes

* Arrays not working as a top-level type ([8055298](https://github.com/Asha20/json-dts-generator/commit/805529895dcdaee36874ee859dd8038258cd7807))
* Move code belonging inside main() into main() ([6a413fa](https://github.com/Asha20/json-dts-generator/commit/6a413fa04035714662483b73564b3ede6a02d5cf))
* Non-identifier properties no longer broken ([637acfc](https://github.com/Asha20/json-dts-generator/commit/637acfc405e494ddc146008624648160f47b183f))
