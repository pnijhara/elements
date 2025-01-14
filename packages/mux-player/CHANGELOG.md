# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [0.1.0-beta.9](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.8...@mux-elements/mux-player@0.1.0-beta.9) (2022-05-03)

### Bug Fixes

- custom video events handling ([#203](https://github.com/muxinc/elements/issues/203)) ([a909f89](https://github.com/muxinc/elements/commit/a909f89a69ee0d4b67e9d9371ac0f80984016181))
- keep .hls but have it log a warning saying to use .\_hls ([11e6c10](https://github.com/muxinc/elements/commit/11e6c102a7e238bc8104c52ae9b94e7e3c2c7e19))
- keep mux-player#video for backward compatibility ([ddf3c6e](https://github.com/muxinc/elements/commit/ddf3c6eccb0011a42774133ec0a646d84d463f53))
- playback core should handle seek to live on first play ([805070a](https://github.com/muxinc/elements/commit/805070a7a4cb7158180710ecf85bf54bdb1f9280))
- prevent dialog from focus if outside player ([#196](https://github.com/muxinc/elements/issues/196)) ([6c73219](https://github.com/muxinc/elements/commit/6c732198b08f11162f7ee8c4345344b4c050a60f))

### Features

- add errorTranslator prop & muxVideo.error property ([#195](https://github.com/muxinc/elements/issues/195)) ([3afc2f0](https://github.com/muxinc/elements/commit/3afc2f0af75a5ad8ef00257a4ebc34882ff8c9ab))
- add media-theme-mux as a replaceable element ([#175](https://github.com/muxinc/elements/issues/175)) ([ee3c186](https://github.com/muxinc/elements/commit/ee3c186433c198a27304577e012b899c1aee44d4))
- rename .video to .media for consistency with media-chrome ([52c3a1d](https://github.com/muxinc/elements/commit/52c3a1ddef275256d2adc4cc200cb47b1c3023c3))
- rename hls to \_hls ([2d53bc2](https://github.com/muxinc/elements/commit/2d53bc2517840d65a8fd5e2bb2d979ce8b491116))

# [0.1.0-beta.8](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.7...@mux-elements/mux-player@0.1.0-beta.8) (2022-04-22)

### Bug Fixes

- point pkgjson#browser at mjs build for webpack 4 ([#191](https://github.com/muxinc/elements/issues/191)) ([a73a495](https://github.com/muxinc/elements/commit/a73a4951052bfc77cc24667b9bc0a05efbcbb355))

# [0.1.0-beta.7](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.6...@mux-elements/mux-player@0.1.0-beta.7) (2022-04-18)

### Bug Fixes

- make mux-player size based on video element ([#185](https://github.com/muxinc/elements/issues/185)) ([e4af9a8](https://github.com/muxinc/elements/commit/e4af9a885720f172837eb20ea49dc96bf66a77be))
- make mux-video errors more uniform, fix async ([#183](https://github.com/muxinc/elements/issues/183)) ([0ea4dc3](https://github.com/muxinc/elements/commit/0ea4dc3beafc7d8a6c5078087d14f3f4bac5dda7))

# [0.1.0-beta.6](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.5...@mux-elements/mux-player@0.1.0-beta.6) (2022-04-13)

### Bug Fixes

- get polyfill from playback core in mux-player ([ec053f9](https://github.com/muxinc/elements/commit/ec053f90f6b7e3ccf0dd6bdd9034cbe8ead0d593))

# [0.1.0-beta.5](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.4...@mux-elements/mux-player@0.1.0-beta.5) (2022-04-12)

### Bug Fixes

- clear some state on playbackId change ([#174](https://github.com/muxinc/elements/issues/174)) ([af0738e](https://github.com/muxinc/elements/commit/af0738ea5ae5a75861f75fc2ae3809ada735f3e2))
- **mux-player:** adding test for metadata attrs. ([a460566](https://github.com/muxinc/elements/commit/a4605661fabb33a178bb3244b1411c63bf1e1148))
- **mux-player:** metadata fields should be set based on 'external'/attr values in mux-player. ([bd474b6](https://github.com/muxinc/elements/commit/bd474b658931afb0ea9f3f1585ba3142d22bd503))
- prevent non-fatal error events propagating ([#179](https://github.com/muxinc/elements/issues/179)) ([2103800](https://github.com/muxinc/elements/commit/2103800b1026653703a67432a9bf80cb2ce5c7ac))

# [0.1.0-beta.4](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.3...@mux-elements/mux-player@0.1.0-beta.4) (2022-04-08)

### Bug Fixes

- child custom element mux-video upgraded after mux-player ([#171](https://github.com/muxinc/elements/issues/171)) ([9db8037](https://github.com/muxinc/elements/commit/9db8037f379132307727941f82a736d55e76b4e5))
- primary color should be also used for the text color on controls ([d44da1b](https://github.com/muxinc/elements/commit/d44da1b7e4a11ddf8274a09acf306747a5af42ce))

### Features

- **mux-player:** Add more seek to live behavior tests. Add event for inLiveWindow change. ([f334328](https://github.com/muxinc/elements/commit/f3343289a29b0c19856addf41fd0c5c1b2081c6a))
- **mux-player:** Don't use disabled to toggle seek to live btn functionality. ([14f1f1c](https://github.com/muxinc/elements/commit/14f1f1c7ecd43416363eb43583622ea5732c9072))
- **mux-player:** Seek to live button impl with live edge window detection and play on seek/seek on play behavior. ([77c8c5f](https://github.com/muxinc/elements/commit/77c8c5f05c2b22553efc6e627b0b148dded19a42))
- **mux-player:** use aria-disabled instead of non-standard attr. Add consts/code comments. fix css var. ([8c73f60](https://github.com/muxinc/elements/commit/8c73f602c6745a731f7fafdfdd8567b90db2ccad))
- **player:** Add inLiveWindow getter to player. Start tests for seek to live button behaviors. ([8217a4e](https://github.com/muxinc/elements/commit/8217a4ee4c9e61b570fa506f2b476a570dd78f61))

# [0.1.0-beta.3](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.2...@mux-elements/mux-player@0.1.0-beta.3) (2022-04-01)

### Bug Fixes

- devLog links to GH base URL ([022f69f](https://github.com/muxinc/elements/commit/022f69fca5624399e67ea9bb5ce1b2b2929979d6))
- **mux-player:** Make sure internal state monitoring setup happens after relevant elements exist. ([43e9566](https://github.com/muxinc/elements/commit/43e956678b7e1b8da3e95144b7d9f6f3d2cb99d5))

# [0.1.0-beta.2](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.1...@mux-elements/mux-player@0.1.0-beta.2) (2022-04-01)

### Bug Fixes

- **mux-player:** temp fix conditional render bug ([73534dc](https://github.com/muxinc/elements/commit/73534dc476d901e916734044834c71130a6de73e))

### Features

- **mux-player:** new iteration on error handling ([a89af8a](https://github.com/muxinc/elements/commit/a89af8a0b9400f2e0836e67b813d996636f044c1))

### Reverts

- Revert "Publish" ([42fc528](https://github.com/muxinc/elements/commit/42fc528216346ff52d967cec5392a1191f74a1c0))

# [0.1.0-beta.1](https://github.com/muxinc/elements/compare/@mux-elements/mux-player@0.1.0-beta.0...@mux-elements/mux-player@0.1.0-beta.1) (2022-03-28)

### Bug Fixes

- add patched template-parts fork ([b200e9f](https://github.com/muxinc/elements/commit/b200e9fcdff9cf5757ec646c8833e742e329afa0))
- **mux-player:** Add support for event handlers to template parts processing. ([704d2e3](https://github.com/muxinc/elements/commit/704d2e34dacdb68316ead85a2dd494475de72732))
- **mux-player:** don't fire the closed event twice per close on the dialog WC. ([0231b1a](https://github.com/muxinc/elements/commit/0231b1a950fe6eb476ce8bcd3ce4d49cee97e0c9))
- **mux-player:** Use onclose event handler in template. Clear errors onclose. ([1eca0ef](https://github.com/muxinc/elements/commit/1eca0efb32b74f82c67be4f9ac0f3bc5dfbf7839))
- prettier format all elements files ([741d607](https://github.com/muxinc/elements/commit/741d607521ca9578cfad9f0a9216a6565b4c56a1))
- update media-chrome to 0.5.4 ([21e7884](https://github.com/muxinc/elements/commit/21e78840768bad8eeb24d39fa97fcd8cf6ab266a))

### Features

- add beaconCollectionDomain option to replace beaconDomain ([a44b699](https://github.com/muxinc/elements/commit/a44b699ae3138590b9d953f693f95971694658df))
- Improve error handling / messaging ([#132](https://github.com/muxinc/elements/issues/132)) ([b1f2dd0](https://github.com/muxinc/elements/commit/b1f2dd0f44ceb75a93f8cf758d6e4258e1366ed5))
- **mux-player:** move captions up when controls are showing ([e8d9842](https://github.com/muxinc/elements/commit/e8d9842f5b343fd11965c4fbda96323a6e173e63))
