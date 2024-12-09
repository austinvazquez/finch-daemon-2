# Changelog

## [0.12.0](https://github.com/austinvazquez/finch-daemon-2/compare/v0.11.0...v0.12.0) (2024-12-09)


### Build System or External Dependencies

* **deps:** bump github.com/containerd/go-cni from 1.1.9 to 1.1.10 ([#53](https://github.com/austinvazquez/finch-daemon-2/issues/53)) ([31583b0](https://github.com/austinvazquez/finch-daemon-2/commit/31583b0bd25dfdcf5c53ae78882b9df3ac36cc11))
* **deps:** bump github.com/containerd/nerdctl from 1.7.5 to 1.7.7 ([#66](https://github.com/austinvazquez/finch-daemon-2/issues/66)) ([80fdae9](https://github.com/austinvazquez/finch-daemon-2/commit/80fdae9e466a2df51f61f6f7ab22effe21f5913f))
* **deps:** Bump github.com/containernetworking/cni from 1.2.2 to 1.2.3 ([#87](https://github.com/austinvazquez/finch-daemon-2/issues/87)) ([46df1b6](https://github.com/austinvazquez/finch-daemon-2/commit/46df1b631d6d9cf77d1a34b1162c9ac0226e5ff6))
* **deps:** Bump github.com/coreos/go-iptables from 0.7.0 to 0.8.0 ([#106](https://github.com/austinvazquez/finch-daemon-2/issues/106)) ([9905569](https://github.com/austinvazquez/finch-daemon-2/commit/990556941eee136457e190de217e9e64249b54d1))
* **deps:** bump github.com/onsi/ginkgo/v2 from 2.17.1 to 2.20.2 ([#19](https://github.com/austinvazquez/finch-daemon-2/issues/19)) ([e282c25](https://github.com/austinvazquez/finch-daemon-2/commit/e282c253bfdd2bad7e97866e75598291892fb7fa))
* **deps:** bump github.com/onsi/gomega from 1.32.0 to 1.34.2 ([#18](https://github.com/austinvazquez/finch-daemon-2/issues/18)) ([ea72df3](https://github.com/austinvazquez/finch-daemon-2/commit/ea72df3f479e10ef0de0357a31a1686d626f5041))
* **deps:** bump github.com/runfinch/common-tests from 0.7.21 to 0.8.0 ([#64](https://github.com/austinvazquez/finch-daemon-2/issues/64)) ([df9f0ca](https://github.com/austinvazquez/finch-daemon-2/commit/df9f0cad2f1cc842a6c3033dc2d635008a2690df))
* **deps:** bump github.com/spf13/cobra from 1.8.0 to 1.8.1 ([#49](https://github.com/austinvazquez/finch-daemon-2/issues/49)) ([3eff666](https://github.com/austinvazquez/finch-daemon-2/commit/3eff666f81e4ea655b9d70e5fa7e8043283ec959))
* **deps:** Bump github.com/stretchr/testify from 1.9.0 to 1.10.0 ([#107](https://github.com/austinvazquez/finch-daemon-2/issues/107)) ([e5b9878](https://github.com/austinvazquez/finch-daemon-2/commit/e5b987880954c14b90a2f984a586b2b02eeec44c))
* **deps:** bump github.com/vishvananda/netlink from 1.2.1-beta.2 to 1.3.0 ([#50](https://github.com/austinvazquez/finch-daemon-2/issues/50)) ([e3cffc7](https://github.com/austinvazquez/finch-daemon-2/commit/e3cffc77ac28451c15d5c6a04ab63fd89c34fe4b))
* **deps:** Bump github.com/vishvananda/netns from 0.0.4 to 0.0.5 ([#112](https://github.com/austinvazquez/finch-daemon-2/issues/112)) ([40d3991](https://github.com/austinvazquez/finch-daemon-2/commit/40d3991864516be6816abbb788118aaaf6e29802))
* **deps:** Bump golang.org/x/net from 0.29.0 to 0.31.0 ([#93](https://github.com/austinvazquez/finch-daemon-2/issues/93)) ([dcffe39](https://github.com/austinvazquez/finch-daemon-2/commit/dcffe399140761198e2fec7de08005a7c56c5c3f))
* **deps:** Bump google.golang.org/protobuf from 1.35.1 to 1.35.2 ([#116](https://github.com/austinvazquez/finch-daemon-2/issues/116)) ([682d4cd](https://github.com/austinvazquez/finch-daemon-2/commit/682d4cddf09c19a254e5341d9c7842d4da3e2d3c))


### Features

* add container create options ([#27](https://github.com/austinvazquez/finch-daemon-2/issues/27)) ([504dcaf](https://github.com/austinvazquez/finch-daemon-2/commit/504dcaf9eff1316c9dd40db82a4ecce9b3e1796d))
* add distribution API ([#92](https://github.com/austinvazquez/finch-daemon-2/issues/92)) ([0e413d7](https://github.com/austinvazquez/finch-daemon-2/commit/0e413d7a3833f2b392921bf7131e80bf6b969fa0))
* Add Support for Extra Hosts ([#85](https://github.com/austinvazquez/finch-daemon-2/issues/85)) ([5722300](https://github.com/austinvazquez/finch-daemon-2/commit/5722300912f8a4cdcc4aa22bae6524ef79a9b7d1))
* Add support for nerdctl config and default variables ([#73](https://github.com/austinvazquez/finch-daemon-2/issues/73)) ([284c73f](https://github.com/austinvazquez/finch-daemon-2/commit/284c73ffc02ac5bd1712b92e06675474cb206c19))
* Add support for pidfile ([#90](https://github.com/austinvazquez/finch-daemon-2/issues/90)) ([55eacb5](https://github.com/austinvazquez/finch-daemon-2/commit/55eacb5f8ed302bf8aa2138a9b47b2c01970e28b))
* Add support for socket Activation ([#89](https://github.com/austinvazquez/finch-daemon-2/issues/89)) ([d185ad3](https://github.com/austinvazquez/finch-daemon-2/commit/d185ad3b2fc057fb7655ee0168d4ffea679df432))
* allow custom socket path ([#7](https://github.com/austinvazquez/finch-daemon-2/issues/7)) ([4c17545](https://github.com/austinvazquez/finch-daemon-2/commit/4c1754576d5beb3bd6b12e36893a588b2bb95825))
* implement container restart API ([#23](https://github.com/austinvazquez/finch-daemon-2/issues/23)) ([5d9b1e0](https://github.com/austinvazquez/finch-daemon-2/commit/5d9b1e0f4e1565fd374b0f0941f373a094dc749c))
* Implementation of enable_icc option ([#69](https://github.com/austinvazquez/finch-daemon-2/issues/69)) ([5fd2e3e](https://github.com/austinvazquez/finch-daemon-2/commit/5fd2e3ee7cf1f17f59c58028fd931bc9a9f51b38))
* Port 'implement container restart API' patch ([5d9b1e0](https://github.com/austinvazquez/finch-daemon-2/commit/5d9b1e0f4e1565fd374b0f0941f373a094dc749c))


### Bug Fixes

* Add arm64 build and release ([#99](https://github.com/austinvazquez/finch-daemon-2/issues/99)) ([9cc615a](https://github.com/austinvazquez/finch-daemon-2/commit/9cc615af4add118537441a7357f936fb02f7ef86))
* Add static binaries to release ([#63](https://github.com/austinvazquez/finch-daemon-2/issues/63)) ([57a0c44](https://github.com/austinvazquez/finch-daemon-2/commit/57a0c44d56bbf0addbf5b8c78a2baebac61141ab))
* bump minor for feat ([65fbf5a](https://github.com/austinvazquez/finch-daemon-2/commit/65fbf5afaeb175d5660ff13acc639ec3d72ac273))
* doc nits and parameter casing ([#57](https://github.com/austinvazquez/finch-daemon-2/issues/57)) ([e22c156](https://github.com/austinvazquez/finch-daemon-2/commit/e22c156cc8bcb97f25c6f41a14e833203e8798ce))
* filter unsupported enable_icc option ([#36](https://github.com/austinvazquez/finch-daemon-2/issues/36)) ([6c5e72d](https://github.com/austinvazquez/finch-daemon-2/commit/6c5e72d4e8c9f6a5be12bf38078798423d11064f))
* image load should close stream after copy ([#34](https://github.com/austinvazquez/finch-daemon-2/issues/34)) ([5ee657b](https://github.com/austinvazquez/finch-daemon-2/commit/5ee657b17de96c1d2302e9ee7490ccfdc64cd907))
* Make DOCKER_CONFIG available to buildctl ([#94](https://github.com/austinvazquez/finch-daemon-2/issues/94)) ([f5b426d](https://github.com/austinvazquez/finch-daemon-2/commit/f5b426d058c8700e4a4111143db131b4582287d8))
* Pidfile handling and socket docs ([#101](https://github.com/austinvazquez/finch-daemon-2/issues/101)) ([5c2e99f](https://github.com/austinvazquez/finch-daemon-2/commit/5c2e99f22388d184b2f7916432cac1173622143c))
* README changes re: systemd setup ([#59](https://github.com/austinvazquez/finch-daemon-2/issues/59)) ([2096ded](https://github.com/austinvazquez/finch-daemon-2/commit/2096ded2283a8582186be01eeee42a8c0ab6161d))
* Remove bump-patch-for-minor-pre-major ([#83](https://github.com/austinvazquez/finch-daemon-2/issues/83)) ([65fbf5a](https://github.com/austinvazquez/finch-daemon-2/commit/65fbf5afaeb175d5660ff13acc639ec3d72ac273))
* return an error if custom bridge name is not set successfully ([#100](https://github.com/austinvazquez/finch-daemon-2/issues/100)) ([0469999](https://github.com/austinvazquez/finch-daemon-2/commit/0469999c87b8659b149617cc99ab919e1a09b752))
* Set release version to 0.9.0 ([#56](https://github.com/austinvazquez/finch-daemon-2/issues/56)) ([024768a](https://github.com/austinvazquez/finch-daemon-2/commit/024768a6937ab2917870f9a3348dc0be114d3523))
* truncate image id on publish tag event ([#35](https://github.com/austinvazquez/finch-daemon-2/issues/35)) ([6aa5b7c](https://github.com/austinvazquez/finch-daemon-2/commit/6aa5b7ce76979682ad1cf2b49ac0237a74cac809))


### Reverts

* "feat: add distribution API ([#92](https://github.com/austinvazquez/finch-daemon-2/issues/92))" ([#110](https://github.com/austinvazquez/finch-daemon-2/issues/110)) ([2177f95](https://github.com/austinvazquez/finch-daemon-2/commit/2177f9553d2ecc80908d09729277a24ac355f8e2))
* "fix: Add arm64 build and release ([#99](https://github.com/austinvazquez/finch-daemon-2/issues/99))" ([#105](https://github.com/austinvazquez/finch-daemon-2/issues/105)) ([fb0dc0f](https://github.com/austinvazquez/finch-daemon-2/commit/fb0dc0fa6a4a4d6d0aba3567afffe3f4fe0e9291))

## [0.11.0](https://github.com/runfinch/finch-daemon/compare/v0.10.0...v0.11.0) (2024-11-27)


### Build System or External Dependencies

* **deps:** Bump github.com/containernetworking/cni from 1.2.2 to 1.2.3 ([#87](https://github.com/runfinch/finch-daemon/issues/87)) ([46df1b6](https://github.com/runfinch/finch-daemon/commit/46df1b631d6d9cf77d1a34b1162c9ac0226e5ff6))
* **deps:** Bump github.com/coreos/go-iptables from 0.7.0 to 0.8.0 ([#106](https://github.com/runfinch/finch-daemon/issues/106)) ([9905569](https://github.com/runfinch/finch-daemon/commit/990556941eee136457e190de217e9e64249b54d1))
* **deps:** Bump github.com/stretchr/testify from 1.9.0 to 1.10.0 ([#107](https://github.com/runfinch/finch-daemon/issues/107)) ([e5b9878](https://github.com/runfinch/finch-daemon/commit/e5b987880954c14b90a2f984a586b2b02eeec44c))
* **deps:** Bump golang.org/x/net from 0.29.0 to 0.31.0 ([#93](https://github.com/runfinch/finch-daemon/issues/93)) ([dcffe39](https://github.com/runfinch/finch-daemon/commit/dcffe399140761198e2fec7de08005a7c56c5c3f))
* **deps:** Bump github.com/containerd/containerd from 1.7.22 to 1.7.24 ([#102](https://github.com/runfinch/finch-daemon/issues/102)) ([0d6cd12](https://github.com/runfinch/finch-daemon/commit/0d6cd122af858ed4431ebf37a673ad933054c833))
* **deps:** Bump github.com/containerd/errdefs from 0.1.0 to 1.0.0 ([#102](https://github.com/runfinch/finch-daemon/issues/102)) ([0d6cd12](https://github.com/runfinch/finch-daemon/commit/0d6cd122af858ed4431ebf37a673ad933054c833))


### Features

* Implementation of enable_icc option ([#69](https://github.com/runfinch/finch-daemon/issues/69)) ([5fd2e3e](https://github.com/runfinch/finch-daemon/commit/5fd2e3ee7cf1f17f59c58028fd931bc9a9f51b38))


### Bug Fixes

* Make DOCKER_CONFIG available to buildctl ([#94](https://github.com/runfinch/finch-daemon/issues/94)) ([f5b426d](https://github.com/runfinch/finch-daemon/commit/f5b426d058c8700e4a4111143db131b4582287d8))
* Pidfile handling and socket docs ([#101](https://github.com/runfinch/finch-daemon/issues/101)) ([5c2e99f](https://github.com/runfinch/finch-daemon/commit/5c2e99f22388d184b2f7916432cac1173622143c))
* return an error if custom bridge name is not set successfully ([#100](https://github.com/runfinch/finch-daemon/issues/100)) ([0469999](https://github.com/runfinch/finch-daemon/commit/0469999c87b8659b149617cc99ab919e1a09b752))


## [0.10.0](https://github.com/runfinch/finch-daemon/compare/v0.9.0...v0.10.0) (2024-10-31)


### Build System or External Dependencies

* **deps:** bump github.com/containerd/nerdctl from 1.7.5 to 1.7.7 ([#66](https://github.com/runfinch/finch-daemon/issues/66)) ([80fdae9](https://github.com/runfinch/finch-daemon/commit/80fdae9e466a2df51f61f6f7ab22effe21f5913f))
* **deps:** bump github.com/runfinch/common-tests from 0.7.21 to 0.8.0 ([#64](https://github.com/runfinch/finch-daemon/issues/64)) ([df9f0ca](https://github.com/runfinch/finch-daemon/commit/df9f0cad2f1cc842a6c3033dc2d635008a2690df))


### Features

* Add Support for Extra Hosts ([#85](https://github.com/runfinch/finch-daemon/issues/85)) ([5722300](https://github.com/runfinch/finch-daemon/commit/5722300912f8a4cdcc4aa22bae6524ef79a9b7d1))
* Add support for nerdctl config and default variables ([#73](https://github.com/runfinch/finch-daemon/issues/73)) ([284c73f](https://github.com/runfinch/finch-daemon/commit/284c73ffc02ac5bd1712b92e06675474cb206c19))
* Add support for pidfile ([#90](https://github.com/runfinch/finch-daemon/issues/90)) ([55eacb5](https://github.com/runfinch/finch-daemon/commit/55eacb5f8ed302bf8aa2138a9b47b2c01970e28b))
* Add support for socket Activation ([#89](https://github.com/runfinch/finch-daemon/issues/89)) ([d185ad3](https://github.com/runfinch/finch-daemon/commit/d185ad3b2fc057fb7655ee0168d4ffea679df432))


### Bug Fixes

* Add static binaries to release ([#63](https://github.com/runfinch/finch-daemon/issues/63)) ([57a0c44](https://github.com/runfinch/finch-daemon/commit/57a0c44d56bbf0addbf5b8c78a2baebac61141ab))
* bump minor for feat ([65fbf5a](https://github.com/runfinch/finch-daemon/commit/65fbf5afaeb175d5660ff13acc639ec3d72ac273))
* Remove bump-patch-for-minor-pre-major ([#83](https://github.com/runfinch/finch-daemon/issues/83)) ([65fbf5a](https://github.com/runfinch/finch-daemon/commit/65fbf5afaeb175d5660ff13acc639ec3d72ac273))

## 0.9.0  Finch-Daemon Init

This is the first release of the Finch Daemon.
The Finch Daemon project is an open source container runtime engine that enables users to integrate software that uses Docker's RESTful APIs as a programmatic dependency.
