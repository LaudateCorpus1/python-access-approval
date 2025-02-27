# Changelog

### [1.4.1](https://www.github.com/googleapis/python-access-approval/compare/v1.4.0...v1.4.1) (2021-11-01)


### Bug Fixes

* **deps:** drop packaging dependency ([d6e1bd6](https://www.github.com/googleapis/python-access-approval/commit/d6e1bd63bdf6b8881659eb41c1a9e15968c3dfee))
* **deps:** require google-api-core >= 1.28.0 ([d6e1bd6](https://www.github.com/googleapis/python-access-approval/commit/d6e1bd63bdf6b8881659eb41c1a9e15968c3dfee))
* fix extras_require typo in setup.py ([d6e1bd6](https://www.github.com/googleapis/python-access-approval/commit/d6e1bd63bdf6b8881659eb41c1a9e15968c3dfee))


### Documentation

* list oneofs in docstring ([d6e1bd6](https://www.github.com/googleapis/python-access-approval/commit/d6e1bd63bdf6b8881659eb41c1a9e15968c3dfee))

## [1.4.0](https://www.github.com/googleapis/python-access-approval/compare/v1.3.5...v1.4.0) (2021-10-11)


### Features

* add context manager support in client ([#126](https://www.github.com/googleapis/python-access-approval/issues/126)) ([372628b](https://www.github.com/googleapis/python-access-approval/commit/372628b04734c8a15a0ed0ada374120a4ce024db))
* add trove classifier for python 3.9 and python 3.10 ([#129](https://www.github.com/googleapis/python-access-approval/issues/129)) ([2bb4981](https://www.github.com/googleapis/python-access-approval/commit/2bb4981fc62bfbf918e0c215e97f1edb47dcc045))

### [1.3.5](https://www.github.com/googleapis/python-access-approval/compare/v1.3.4...v1.3.5) (2021-09-30)


### Bug Fixes

* improper types in pagers generation ([a73b1e0](https://www.github.com/googleapis/python-access-approval/commit/a73b1e0bc466b6edc6355423180b4cf44d64e55a))

### [1.3.4](https://www.github.com/googleapis/python-access-approval/compare/v1.3.3...v1.3.4) (2021-09-24)


### Bug Fixes

* add 'dict' annotation type to 'request' ([0585562](https://www.github.com/googleapis/python-access-approval/commit/0585562b62c7c7fe81eacc8124ab4f85484ee879))

### [1.3.3](https://www.github.com/googleapis/python-access-approval/compare/v1.3.2...v1.3.3) (2021-07-27)


### Bug Fixes

* enable self signed jwt for grpc ([#102](https://www.github.com/googleapis/python-access-approval/issues/102)) ([a7a1fc2](https://www.github.com/googleapis/python-access-approval/commit/a7a1fc248176131331526a331f121d369a872f2a))


### Documentation

* add Samples section to CONTRIBUTING.rst ([#98](https://www.github.com/googleapis/python-access-approval/issues/98)) ([4fda4f9](https://www.github.com/googleapis/python-access-approval/commit/4fda4f97b3cf12043fe69d3bde7d8f0057c428e0))


### Miscellaneous Chores

* release as 1.3.3 ([#103](https://www.github.com/googleapis/python-access-approval/issues/103)) ([0b964c6](https://www.github.com/googleapis/python-access-approval/commit/0b964c60b8306d53e364a4431be55bebf1c48b48))

### [1.3.2](https://www.github.com/googleapis/python-access-approval/compare/v1.3.1...v1.3.2) (2021-07-20)


### Bug Fixes

* **deps:** pin 'google-{api,cloud}-core', 'google-auth' to allow 2.x versions ([#97](https://www.github.com/googleapis/python-access-approval/issues/97)) ([9400ffe](https://www.github.com/googleapis/python-access-approval/commit/9400ffeffb89458f738961ef0ef4729141f37ee8))

### [1.3.1](https://www.github.com/googleapis/python-access-approval/compare/v1.3.0...v1.3.1) (2021-06-30)


### Bug Fixes

* disable always_use_jwt_access ([e4e04a0](https://www.github.com/googleapis/python-access-approval/commit/e4e04a02ba3c58a6451356ea75cfd0b0146ec956))
* disable always_use_jwt_access ([#93](https://www.github.com/googleapis/python-access-approval/issues/93)) ([e4e04a0](https://www.github.com/googleapis/python-access-approval/commit/e4e04a02ba3c58a6451356ea75cfd0b0146ec956))

## [1.3.0](https://www.github.com/googleapis/python-access-approval/compare/v1.2.0...v1.3.0) (2021-06-23)


### Features

* add `always_use_jwt_access` ([#88](https://www.github.com/googleapis/python-access-approval/issues/88)) ([73dce43](https://www.github.com/googleapis/python-access-approval/commit/73dce43cddf1f013ae54e83d9c53fb42f129223b))


### Documentation

* omit mention of Python 2.7 in 'CONTRIBUTING.rst' ([#1127](https://www.github.com/googleapis/python-access-approval/issues/1127)) ([#83](https://www.github.com/googleapis/python-access-approval/issues/83)) ([8c56c88](https://www.github.com/googleapis/python-access-approval/commit/8c56c88e0ba6ceec08cb6dae2094bdca1f7365dc)), closes [#1126](https://www.github.com/googleapis/python-access-approval/issues/1126)

## [1.2.0](https://www.github.com/googleapis/python-access-approval/compare/v1.1.1...v1.2.0) (2021-05-28)


### Features

* add `from_service_account_info` ([8f6833a](https://www.github.com/googleapis/python-access-approval/commit/8f6833aa95e7610576fba4500857a4143de7d1d7))
* support self-signed JWT flow for service accounts ([e761cff](https://www.github.com/googleapis/python-access-approval/commit/e761cfffccd416a4552ccdece2a6d6f1ae84cad8))


### Bug Fixes

* add async client to %name_%version/init.py ([e761cff](https://www.github.com/googleapis/python-access-approval/commit/e761cfffccd416a4552ccdece2a6d6f1ae84cad8))
* **deps:** add packaging requirement ([#78](https://www.github.com/googleapis/python-access-approval/issues/78)) ([fd1417b](https://www.github.com/googleapis/python-access-approval/commit/fd1417b61019150963c83b4594fd86e2fb304355))
* use correct retry deadlines ([#57](https://www.github.com/googleapis/python-access-approval/issues/57)) ([8f6833a](https://www.github.com/googleapis/python-access-approval/commit/8f6833aa95e7610576fba4500857a4143de7d1d7))

### [1.1.1](https://www.github.com/googleapis/python-access-approval/compare/v1.1.0...v1.1.1) (2021-02-12)


### Bug Fixes

* remove client recv msg limit and add enums to `types/__init__.py` ([#40](https://www.github.com/googleapis/python-access-approval/issues/40)) ([2333089](https://www.github.com/googleapis/python-access-approval/commit/2333089890db28aacf2c8386d7d7e78008f04812))

## [1.1.0](https://www.github.com/googleapis/python-access-approval/compare/v1.0.0...v1.1.0) (2020-11-16)


### Features

* add common resource helpers, expose client transport ([#33](https://www.github.com/googleapis/python-access-approval/issues/33)) ([2c07916](https://www.github.com/googleapis/python-access-approval/commit/2c0791682d0ca4f62f3649c5e408176346adc7a1))

## [1.0.0](https://www.github.com/googleapis/python-access-approval/compare/v0.2.0...v1.0.0) (2020-08-05)


### ⚠ BREAKING CHANGES

* migrate to use microgen (#23)

### Features

* migrate to use microgen ([#23](https://www.github.com/googleapis/python-access-approval/issues/23)) ([537de3d](https://www.github.com/googleapis/python-access-approval/commit/537de3d317f3a7c1d3c6734e07e8544f18cdd0ed))

## [0.2.0](https://www.github.com/googleapis/python-access-approval/compare/v0.1.0...v0.2.0) (2020-05-13)


### Bug Fixes

* update readme ([#11](https://www.github.com/googleapis/python-access-approval/issues/11)) ([4315c46](https://www.github.com/googleapis/python-access-approval/commit/4315c46ab73493f10ca8b963252a05b6159c0f63))

## 0.1.0 (2020-02-10)


### Features

* generate v1 ([88003fe](https://www.github.com/googleapis/python-access-approval/commit/88003fe05150ee653ba9a8ba072058b35d3f3c49))
