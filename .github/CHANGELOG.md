# Changelog

## [0.7.0](https://github.com/amanvr/test-release/compare/v0.7.0...v0.7.0) (2026-04-20)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* align manifest with last release and add versioning strategy ([00985a4](https://github.com/amanvr/test-release/commit/00985a4265bfa759db9c1d6fe41a76a5632e197e))
* align manifest with last release and add versioning strategy ([fd2cb9d](https://github.com/amanvr/test-release/commit/fd2cb9d882bc4c04d5879f8156552c63ac57888b))
* always create RC releases, remove auto-promotion ([#87](https://github.com/amanvr/test-release/issues/87)) ([bc11b8e](https://github.com/amanvr/test-release/commit/bc11b8eef386bfbf83980dd12d34a21ad1640564))
* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))
* auto-calculate RC version from tags ([#77](https://github.com/amanvr/test-release/issues/77)) ([bf3931c](https://github.com/amanvr/test-release/commit/bf3931c4d66d13f0271147eca9f9426ffa78d3a3))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* df ([#61](https://github.com/amanvr/test-release/issues/61)) ([7108756](https://github.com/amanvr/test-release/commit/7108756f39647117375ba920ce6aef519ee13fd1))
* e2e test 1 ([#66](https://github.com/amanvr/test-release/issues/66)) ([6a04ea8](https://github.com/amanvr/test-release/commit/6a04ea820097801da122d3627a4d051369d19852))
* e2e test 2 - should trigger stale detection ([#67](https://github.com/amanvr/test-release/issues/67)) ([fd57e28](https://github.com/amanvr/test-release/commit/fd57e283b91e0fe53768f6fa9beac88468bb71a1))
* extract base version from manifest for correct RC calculation ([#79](https://github.com/amanvr/test-release/issues/79)) ([e4f5160](https://github.com/amanvr/test-release/commit/e4f516092ab6b923cbd74443d77cbf8b2c67fe38))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final e2e test ([#75](https://github.com/amanvr/test-release/issues/75)) ([33d23ca](https://github.com/amanvr/test-release/commit/33d23ca672183d2a1ee917de302e37b82b25eb66))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* hello ([#76](https://github.com/amanvr/test-release/issues/76)) ([f0ba557](https://github.com/amanvr/test-release/commit/f0ba55730efae11ae2b926e287c172a8eca58712))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* remove separate cleanup PR, include in bootstrap instead ([d96bb7f](https://github.com/amanvr/test-release/commit/d96bb7f5074b34eccfa4bc2697476375b5ae0505))
* remove stale release-as from RC config ([#81](https://github.com/amanvr/test-release/issues/81)) ([6bcdb4f](https://github.com/amanvr/test-release/commit/6bcdb4f8d32163ec680e7a29d7b772035bbdabd0))
* remove versioning-strategy to let release-as take precedence ([#83](https://github.com/amanvr/test-release/issues/83)) ([c20c509](https://github.com/amanvr/test-release/commit/c20c5092460f149295fd7ad71e8c2124c35137fe))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set manifest to base version (0.7.0) for proper release-as handling ([#85](https://github.com/amanvr/test-release/issues/85)) ([c239714](https://github.com/amanvr/test-release/commit/c239714d147354a0299094ab974945eaa0ae2795))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* skip release-please when release-as version already has a tag ([8498600](https://github.com/amanvr/test-release/commit/84986008a3f5e853b44cb52fa144bbdcb718f3cc))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))
* test without cleanup PR ([#59](https://github.com/amanvr/test-release/issues/59)) ([f9796e4](https://github.com/amanvr/test-release/commit/f9796e4db9026e3a84b9be9086bae606c7612adb))
* verify new cycle works ([#55](https://github.com/amanvr/test-release/issues/55)) ([9f2b027](https://github.com/amanvr/test-release/commit/9f2b0273f476c9f1a7dad9006231caef543895b6))
* write release-as to config file instead of action input ([96ccab9](https://github.com/amanvr/test-release/commit/96ccab9f20130bf075b59403cafa6919e2df445e))
* write release-as to config file instead of action input ([754d48a](https://github.com/amanvr/test-release/commit/754d48a2b20acfdb52a689ac3eb6181e67430ed5))

## [0.7.0-rc.2](https://github.com/amanvr/test-release/compare/v0.7.0-rc.1...v0.7.0-rc.2) (2026-04-20)


### Bug Fixes

* align manifest with last release and add versioning strategy ([00985a4](https://github.com/amanvr/test-release/commit/00985a4265bfa759db9c1d6fe41a76a5632e197e))
* align manifest with last release and add versioning strategy ([fd2cb9d](https://github.com/amanvr/test-release/commit/fd2cb9d882bc4c04d5879f8156552c63ac57888b))
* always create RC releases, remove auto-promotion ([#87](https://github.com/amanvr/test-release/issues/87)) ([bc11b8e](https://github.com/amanvr/test-release/commit/bc11b8eef386bfbf83980dd12d34a21ad1640564))
* auto-calculate RC version from tags ([#77](https://github.com/amanvr/test-release/issues/77)) ([bf3931c](https://github.com/amanvr/test-release/commit/bf3931c4d66d13f0271147eca9f9426ffa78d3a3))
* extract base version from manifest for correct RC calculation ([#79](https://github.com/amanvr/test-release/issues/79)) ([e4f5160](https://github.com/amanvr/test-release/commit/e4f516092ab6b923cbd74443d77cbf8b2c67fe38))
* hello ([#76](https://github.com/amanvr/test-release/issues/76)) ([f0ba557](https://github.com/amanvr/test-release/commit/f0ba55730efae11ae2b926e287c172a8eca58712))
* remove stale release-as from RC config ([#81](https://github.com/amanvr/test-release/issues/81)) ([6bcdb4f](https://github.com/amanvr/test-release/commit/6bcdb4f8d32163ec680e7a29d7b772035bbdabd0))
* remove versioning-strategy to let release-as take precedence ([#83](https://github.com/amanvr/test-release/issues/83)) ([c20c509](https://github.com/amanvr/test-release/commit/c20c5092460f149295fd7ad71e8c2124c35137fe))
* set manifest to base version (0.7.0) for proper release-as handling ([#85](https://github.com/amanvr/test-release/issues/85)) ([c239714](https://github.com/amanvr/test-release/commit/c239714d147354a0299094ab974945eaa0ae2795))
* write release-as to config file instead of action input ([96ccab9](https://github.com/amanvr/test-release/commit/96ccab9f20130bf075b59403cafa6919e2df445e))
* write release-as to config file instead of action input ([754d48a](https://github.com/amanvr/test-release/commit/754d48a2b20acfdb52a689ac3eb6181e67430ed5))

## [0.7.0-rc.1](https://github.com/amanvr/test-release/compare/v0.7.0-rc.1...v0.7.0-rc.1) (2026-04-17)


### Bug Fixes

* auto-calculate RC version from tags ([#77](https://github.com/amanvr/test-release/issues/77)) ([bf3931c](https://github.com/amanvr/test-release/commit/bf3931c4d66d13f0271147eca9f9426ffa78d3a3))
* hello ([#76](https://github.com/amanvr/test-release/issues/76)) ([f0ba557](https://github.com/amanvr/test-release/commit/f0ba55730efae11ae2b926e287c172a8eca58712))

## [0.7.0-rc.1](https://github.com/amanvr/test-release/compare/v0.7.0-rc.0...v0.7.0-rc.1) (2026-04-16)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* df ([#61](https://github.com/amanvr/test-release/issues/61)) ([7108756](https://github.com/amanvr/test-release/commit/7108756f39647117375ba920ce6aef519ee13fd1))
* e2e test 1 ([#66](https://github.com/amanvr/test-release/issues/66)) ([6a04ea8](https://github.com/amanvr/test-release/commit/6a04ea820097801da122d3627a4d051369d19852))
* e2e test 2 - should trigger stale detection ([#67](https://github.com/amanvr/test-release/issues/67)) ([fd57e28](https://github.com/amanvr/test-release/commit/fd57e283b91e0fe53768f6fa9beac88468bb71a1))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final e2e test ([#75](https://github.com/amanvr/test-release/issues/75)) ([33d23ca](https://github.com/amanvr/test-release/commit/33d23ca672183d2a1ee917de302e37b82b25eb66))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* remove separate cleanup PR, include in bootstrap instead ([d96bb7f](https://github.com/amanvr/test-release/commit/d96bb7f5074b34eccfa4bc2697476375b5ae0505))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* skip release-please when release-as version already has a tag ([8498600](https://github.com/amanvr/test-release/commit/84986008a3f5e853b44cb52fa144bbdcb718f3cc))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))
* test without cleanup PR ([#59](https://github.com/amanvr/test-release/issues/59)) ([f9796e4](https://github.com/amanvr/test-release/commit/f9796e4db9026e3a84b9be9086bae606c7612adb))
* verify new cycle works ([#55](https://github.com/amanvr/test-release/issues/55)) ([9f2b027](https://github.com/amanvr/test-release/commit/9f2b0273f476c9f1a7dad9006231caef543895b6))

## [0.6.0](https://github.com/amanvr/test-release/compare/v0.6.0...v0.6.0) (2026-04-16)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* df ([#61](https://github.com/amanvr/test-release/issues/61)) ([7108756](https://github.com/amanvr/test-release/commit/7108756f39647117375ba920ce6aef519ee13fd1))
* e2e test 1 ([#66](https://github.com/amanvr/test-release/issues/66)) ([6a04ea8](https://github.com/amanvr/test-release/commit/6a04ea820097801da122d3627a4d051369d19852))
* e2e test 2 - should trigger stale detection ([#67](https://github.com/amanvr/test-release/issues/67)) ([fd57e28](https://github.com/amanvr/test-release/commit/fd57e283b91e0fe53768f6fa9beac88468bb71a1))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* remove separate cleanup PR, include in bootstrap instead ([d96bb7f](https://github.com/amanvr/test-release/commit/d96bb7f5074b34eccfa4bc2697476375b5ae0505))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* skip release-please when release-as version already has a tag ([8498600](https://github.com/amanvr/test-release/commit/84986008a3f5e853b44cb52fa144bbdcb718f3cc))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))
* test without cleanup PR ([#59](https://github.com/amanvr/test-release/issues/59)) ([f9796e4](https://github.com/amanvr/test-release/commit/f9796e4db9026e3a84b9be9086bae606c7612adb))
* verify new cycle works ([#55](https://github.com/amanvr/test-release/issues/55)) ([9f2b027](https://github.com/amanvr/test-release/commit/9f2b0273f476c9f1a7dad9006231caef543895b6))

## [0.6.0-rc.2](https://github.com/amanvr/test-release/compare/v0.6.0-rc.1...v0.6.0-rc.2) (2026-04-16)


### Bug Fixes

* e2e test 2 - should trigger stale detection ([#67](https://github.com/amanvr/test-release/issues/67)) ([fd57e28](https://github.com/amanvr/test-release/commit/fd57e283b91e0fe53768f6fa9beac88468bb71a1))

## [0.6.0-rc.1](https://github.com/amanvr/test-release/compare/v0.6.0-rc.0...v0.6.0-rc.1) (2026-04-16)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* df ([#61](https://github.com/amanvr/test-release/issues/61)) ([7108756](https://github.com/amanvr/test-release/commit/7108756f39647117375ba920ce6aef519ee13fd1))
* e2e test 1 ([#66](https://github.com/amanvr/test-release/issues/66)) ([6a04ea8](https://github.com/amanvr/test-release/commit/6a04ea820097801da122d3627a4d051369d19852))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* remove separate cleanup PR, include in bootstrap instead ([d96bb7f](https://github.com/amanvr/test-release/commit/d96bb7f5074b34eccfa4bc2697476375b5ae0505))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* skip release-please when release-as version already has a tag ([8498600](https://github.com/amanvr/test-release/commit/84986008a3f5e853b44cb52fa144bbdcb718f3cc))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))
* test without cleanup PR ([#59](https://github.com/amanvr/test-release/issues/59)) ([f9796e4](https://github.com/amanvr/test-release/commit/f9796e4db9026e3a84b9be9086bae606c7612adb))
* verify new cycle works ([#55](https://github.com/amanvr/test-release/issues/55)) ([9f2b027](https://github.com/amanvr/test-release/commit/9f2b0273f476c9f1a7dad9006231caef543895b6))

## [0.5.0-rc.2](https://github.com/amanvr/test-release/compare/v0.5.0-rc.2...v0.5.0-rc.2) (2026-04-16)


### Bug Fixes

* df ([#61](https://github.com/amanvr/test-release/issues/61)) ([7108756](https://github.com/amanvr/test-release/commit/7108756f39647117375ba920ce6aef519ee13fd1))

## [0.5.0-rc.2](https://github.com/amanvr/test-release/compare/v0.5.0-rc.1...v0.5.0-rc.2) (2026-04-16)


### Bug Fixes

* remove separate cleanup PR, include in bootstrap instead ([d96bb7f](https://github.com/amanvr/test-release/commit/d96bb7f5074b34eccfa4bc2697476375b5ae0505))
* test without cleanup PR ([#59](https://github.com/amanvr/test-release/issues/59)) ([f9796e4](https://github.com/amanvr/test-release/commit/f9796e4db9026e3a84b9be9086bae606c7612adb))

## [0.5.0-rc.1](https://github.com/amanvr/test-release/compare/v0.5.0-rc.1...v0.5.0-rc.1) (2026-04-16)


### Bug Fixes

* remove separate cleanup PR, include in bootstrap instead ([d96bb7f](https://github.com/amanvr/test-release/commit/d96bb7f5074b34eccfa4bc2697476375b5ae0505))

## [0.5.0-rc.1](https://github.com/amanvr/test-release/compare/v0.5.0-rc.0...v0.5.0-rc.1) (2026-04-16)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))
* verify new cycle works ([#55](https://github.com/amanvr/test-release/issues/55)) ([9f2b027](https://github.com/amanvr/test-release/commit/9f2b0273f476c9f1a7dad9006231caef543895b6))

## [0.4.1](https://github.com/amanvr/test-release/compare/v0.4.1...v0.4.1) (2026-04-16)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))

## [0.4.1-rc.2](https://github.com/amanvr/test-release/compare/v0.4.1-rc.1...v0.4.1-rc.2) (2026-04-16)


### Bug Fixes

* another test fix ([#47](https://github.com/amanvr/test-release/issues/47)) ([8aaba92](https://github.com/amanvr/test-release/commit/8aaba92fdef1c0987d01196f855cedd7355d23d8))

## [0.4.1-rc.1](https://github.com/amanvr/test-release/compare/v0.4.1-rc.0...v0.4.1-rc.1) (2026-04-16)


### Bug Fixes

* add set-next-rc-version workflow and cleanup job for proper RC versioning ([2f287d3](https://github.com/amanvr/test-release/commit/2f287d31337b2efa08f16577a3f5ac72dd2b9d57))
* add versioning-strategy input to release-please action for proper RC bumping ([3a1412e](https://github.com/amanvr/test-release/commit/3a1412ee0ee8ddcd677143c06f503b11f3598514))
* dewsfdfsd ([#38](https://github.com/amanvr/test-release/issues/38)) ([485b10a](https://github.com/amanvr/test-release/commit/485b10a92d7dd237fe0b3baaa1c594a33ddb61ce))
* test proper RC increment ([#44](https://github.com/amanvr/test-release/issues/44)) ([1b62a72](https://github.com/amanvr/test-release/commit/1b62a72da87e6ad90c7e84f563314244646c58e9))

## [0.4.1-rc.0](https://github.com/amanvr/test-release/compare/v0.4.0-rc.0...v0.4.1-rc.0) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* final test to verify new RC cycle ([#37](https://github.com/amanvr/test-release/issues/37)) ([da35ae5](https://github.com/amanvr/test-release/commit/da35ae5fd2f79e611cd71a46c0ba6db0dd850732))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))

## [0.3.1](https://github.com/amanvr/test-release/compare/v0.3.1...v0.3.1) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))

## [0.3.1-rc.0](https://github.com/amanvr/test-release/compare/v0.3.0-rc.0...v0.3.1-rc.0) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add bootstrap-next-rc-cycle job after stable releases ([4097ad4](https://github.com/amanvr/test-release/commit/4097ad4a2c47255ba9602ca62c263a78d02d5c49))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test new RC cycle after stable release ([#29](https://github.com/amanvr/test-release/issues/29)) ([e017d46](https://github.com/amanvr/test-release/commit/e017d46fc9d0fb5c0f742c74fb76f9af7c0bb55e))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))

## [0.2.2](https://github.com/amanvr/test-release/compare/v0.2.2...v0.2.2) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))
* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))

## [0.2.2-rc.0](https://github.com/amanvr/test-release/compare/v0.2.1-rc.0...v0.2.2-rc.0) (2026-04-15)


### Bug Fixes

* test RC increment ([#25](https://github.com/amanvr/test-release/issues/25)) ([c4a5ba9](https://github.com/amanvr/test-release/commit/c4a5ba9970821006fda93cbef05faf04cc0f90a8))

## [0.2.1-rc.0](https://github.com/amanvr/test-release/compare/v0.2.0-rc.0...v0.2.1-rc.0) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* promote workflow creates PR instead of direct commit ([1dfc58b](https://github.com/amanvr/test-release/commit/1dfc58b0f626c96bd64babbaead4f0514ec36296))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdfdfdsf ([#23](https://github.com/amanvr/test-release/issues/23)) ([83c9b5c](https://github.com/amanvr/test-release/commit/83c9b5c35760a8342b8f448c6b8083d272886a4d))
* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))

## [0.1.4-rc.1](https://github.com/amanvr/test-release/compare/v0.1.4-rc.0...v0.1.4-rc.1) (2026-04-15)


### Bug Fixes

* add versioning-strategy prerelease to only bump RC number ([ca8a6bb](https://github.com/amanvr/test-release/commit/ca8a6bb10c51e64890d8b476f928d69e4fb861ca))
* fdfsff ([#16](https://github.com/amanvr/test-release/issues/16)) ([0f26f73](https://github.com/amanvr/test-release/commit/0f26f733433683ddac25630294cf936feba427d2))
* implement release-as injection for proper RC version bumping ([4855be0](https://github.com/amanvr/test-release/commit/4855be0015d93d0b05f92b954b4e229b39ce89b1))
* set versioning-strategy action input for proper RC bumping ([8da67b2](https://github.com/amanvr/test-release/commit/8da67b2f52407a5d88c5f1eb0147a3d52e2ca952))

## [0.1.4-rc.0](https://github.com/amanvr/test-release/compare/v0.1.3-rc.0...v0.1.4-rc.0) (2026-04-15)


### Bug Fixes

* sdfsddffd ([#14](https://github.com/amanvr/test-release/issues/14)) ([42524c1](https://github.com/amanvr/test-release/commit/42524c1703e0a3a2a34b0e6df2bfc3f5992eb42e))

## [0.1.3-rc.0](https://github.com/amanvr/test-release/compare/v0.1.2-rc.0...v0.1.3-rc.0) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* sdgfsdf ([#10](https://github.com/amanvr/test-release/issues/10)) ([793a0bb](https://github.com/amanvr/test-release/commit/793a0bb27ca77dcb7e383b5d1f8d4417deb8ac95))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))

## [0.1.1](https://github.com/amanvr/test-release/compare/v0.1.1...v0.1.1) (2026-04-15)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* add release-as to stable config for 0.1.1 promotion ([8c15762](https://github.com/amanvr/test-release/commit/8c1576271c813d552ff83751a8051125639854d3))
* inject release-as into config file for stable promotion ([31c46f5](https://github.com/amanvr/test-release/commit/31c46f576ff754060f33ed2a54b93eecc72c7bb3))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))

## [0.1.1-rc.0](https://github.com/amanvr/test-release/compare/v0.1.0-rc.0...v0.1.1-rc.0) (2026-04-14)


### Features

* initial test-release project setup ([61b63c6](https://github.com/amanvr/test-release/commit/61b63c603033ecc727b044fb49f62a4a7097df6d))


### Bug Fixes

* add ([#1](https://github.com/amanvr/test-release/issues/1)) ([155fb68](https://github.com/amanvr/test-release/commit/155fb6880a0e9f6c8de86387e823fc2bb8935698))
* add prerelease config to package-specific settings ([2b02da1](https://github.com/amanvr/test-release/commit/2b02da1f9206c87905d5a089afb06c1ecba8e5f3))
* remove pyproject.toml from release-please extra-files ([2ce2ef2](https://github.com/amanvr/test-release/commit/2ce2ef2337babeb60bd1e45f2c265b32121ce314))
* tergg ([#3](https://github.com/amanvr/test-release/issues/3)) ([a35a3d3](https://github.com/amanvr/test-release/commit/a35a3d3db7a52b8c271abff3e134a7c90980ec29))

## Changelog

All notable changes to this project will be documented in this file.
