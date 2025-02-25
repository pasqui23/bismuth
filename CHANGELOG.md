<!--
  SPDX-FileCopyrightText: none
  SPDX-License-Identifier: MIT
-->

# Changelog

## [2.1.0](https://www.github.com/Bismuth-Forge/bismuth/compare/v2.0.1...v2.1.0) (2021-11-09)


### Features

* add a shortcut for the reverse rotation action ([a027e54](https://www.github.com/Bismuth-Forge/bismuth/commit/a027e5467f870e6f8b6b046d4d8e3477ea6dca8d))
* make script installation directory global ([b82e0b2](https://www.github.com/Bismuth-Forge/bismuth/commit/b82e0b270698539a510a617c3736d60d1450359f))

### [2.0.1](https://www.github.com/Bismuth-Forge/bismuth/compare/v2.0.0...v2.0.1) (2021-11-08)


### Bug Fixes

* do not ignore second windows when resize ([165008b](https://www.github.com/Bismuth-Forge/bismuth/commit/165008b9ac755bf312096ea45ac2ef303fb42e3a))
* prevent broken tiling, by not including empty stings into rules ([9a5cbe4](https://www.github.com/Bismuth-Forge/bismuth/commit/9a5cbe498cfc32e7ae1612cabce0e173e9e55c28))

## [2.0.0](https://www.github.com/Bismuth-Forge/bismuth/compare/v1.1.0...v2.0.0) (2021-11-03)


### ⚠ BREAKING CHANGES

* remove old config button from KWin scripts page. This is no longer needed, as the user should use KCM.
* removed adjust layout options. These options should be always enabled by default, because this is how all tiling window managers work: mouse resize always has feedback and resizing always affects the layout.

### Features

* add KCM for Bismuth configuration ([1c410cf](https://www.github.com/Bismuth-Forge/bismuth/commit/1c410cf1c759d707596a42214489dbe36bd52278))
* introduce tray item, that lets you toggle floating mode ([ba689c5](https://www.github.com/Bismuth-Forge/bismuth/commit/ba689c5ff099c3263384395cfaa737a14e158b90))
* make layouts togglable ([8ebffbe](https://www.github.com/Bismuth-Forge/bismuth/commit/8ebffbe639efcf1cfec5addad29e2777d1bbd5d2))
* reload script after applying configuraton ([e73cbce](https://www.github.com/Bismuth-Forge/bismuth/commit/e73cbce4c8af5ab308634972409b4f7f87e95085))

### Bug Fixes

* correctly destroy callbacks after script unload ([aad9860](https://www.github.com/Bismuth-Forge/bismuth/commit/aad986096273bc9d66ef7098c1c32b725a120902))

## [1.1.0](https://www.github.com/gikari/bismuth/compare/v1.0.2...v1.1.0) (2021-10-23)


### Features

* :lipstick: make the popup more consistent with the Plasma OSDs ([8d6a374](https://www.github.com/gikari/bismuth/commit/8d6a3747e640c4bd418e361b342f1cb0745a3ff0))
* use better layout notifications ([8c013ac](https://www.github.com/gikari/bismuth/commit/8c013ac7bc8d293c81c1f14f03c2147d47d43703))


### Bug Fixes

* :ambulance: add executable flag to installation script ([360588a](https://www.github.com/gikari/bismuth/commit/360588ad216d364a81d518e020e5fe37b6365ccc))
* improve popup geometry update ([1f02e47](https://www.github.com/gikari/bismuth/commit/1f02e47a37fa0771f10e31e6e7f2e5d2cb9419db))
* **popup:** fix errors in popup.qml ([2862e56](https://www.github.com/gikari/bismuth/commit/2862e56194fc37308224caf5fe826c76a59e088c))

### [1.0.2](https://www.github.com/gikari/bismuth/compare/v1.0.1...v1.0.2) (2021-10-22)


### Bug Fixes

* :bug: add Conky to default ignore list ([d989261](https://www.github.com/gikari/bismuth/commit/d989261d82ed75781b59322402beb6c3916d09ce))
* :bug: correctly import Tile Layout Krohnkite shortcut ([04f11f9](https://www.github.com/gikari/bismuth/commit/04f11f98c31ce63adb6c09a06da95377b01defba))
* :bug: do not tile utility windows on wayland ([935a338](https://www.github.com/gikari/bismuth/commit/935a33820b20ab4c4b68dd797b62a64947cb9e0c))
* :bug: prevent KWin freeze in various scenarious ([34d24a4](https://www.github.com/gikari/bismuth/commit/34d24a4cb6494ea5bf29305462a1243ab143dc0c))
* :bug: put shaded windows to float state to avoid layout breakage ([aa05369](https://www.github.com/gikari/bismuth/commit/aa053694aac927184ee17fdbe39b9f8a550b129c))
* ignore ksmserver (logoug screen) ([caf7d08](https://www.github.com/gikari/bismuth/commit/caf7d080d94776defbb4e2dfe9cf0e5ff7f00a31))
* no crashes in closing transients -- might fix others too; ref [#110](https://www.github.com/gikari/bismuth/issues/110), [#109](https://www.github.com/gikari/bismuth/issues/109) ([502f812](https://www.github.com/gikari/bismuth/commit/502f8120815ce4a6b1d40ac1e79e046b0fc59624))
* prevent crash with Monocle and monocleMinimizeRest when closing transient dialogs; ref [#110](https://www.github.com/gikari/bismuth/issues/110) ([49ac131](https://www.github.com/gikari/bismuth/commit/49ac131044f5202069f2202dea5ca0cd16a5257b))

### [1.0.1](https://www.github.com/gikari/bismuth/compare/v1.0.0...v1.0.1) (2021-10-02)


### Bug Fixes

* :ambulance: restore configuration dialog ([2be1673](https://www.github.com/gikari/bismuth/commit/2be1673c41eafef2666a6265335b39159f916903))
* :memo: provide more feedback after installation ([cf59968](https://www.github.com/gikari/bismuth/commit/cf59968dcaf3cf2df92541897824886b9d0fd4d5))

## [1.0.0](https://www.github.com/gikari/bismuth/compare/v1.0.0-beta...v1.0.0) (2021-10-02)

Initial release.
