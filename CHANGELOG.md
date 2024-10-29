# Changelog

## [1.0.0](https://github.com/joeyparrish/shaka-streamer/compare/v0.5.1...v1.0.0) (2024-10-29)


### ⚠ BREAKING CHANGES

* Bump minimum Python version to 3.9

### Features

* Add config file with Apple's HLS recommendations ([#72](https://github.com/joeyparrish/shaka-streamer/issues/72)) ([01793a1](https://github.com/joeyparrish/shaka-streamer/commit/01793a1a21e2f736c0931f9d561ac1a337bca6d1)), closes [#70](https://github.com/joeyparrish/shaka-streamer/issues/70)
* Add OPUS mp4 support ([#143](https://github.com/joeyparrish/shaka-streamer/issues/143)) ([2f38022](https://github.com/joeyparrish/shaka-streamer/commit/2f38022a2708dfd29e5c6f51cd7a34c1f8478004))
* Add support for ac3 and ec3 ([#69](https://github.com/joeyparrish/shaka-streamer/issues/69)) ([e9d47be](https://github.com/joeyparrish/shaka-streamer/commit/e9d47beb87f7d1ae3a18a713258fbf9574bc6dfd)), closes [#37](https://github.com/joeyparrish/shaka-streamer/issues/37)
* Add support for HEVC video codec ([#74](https://github.com/joeyparrish/shaka-streamer/issues/74)) ([d154fc7](https://github.com/joeyparrish/shaka-streamer/commit/d154fc740426191756a47661427f665373c33c0e))
* Automatic frame rate reduction ([#77](https://github.com/joeyparrish/shaka-streamer/issues/77)) ([43e0ca8](https://github.com/joeyparrish/shaka-streamer/commit/43e0ca8683a12ed6c9d7e21b6b03caec71738e1e))
* Bump minimum Python version to 3.9 ([fda49ac](https://github.com/joeyparrish/shaka-streamer/commit/fda49acf8aa400b8cb9aec4226153769dba4622d))
* Channel count as an input feature ([#84](https://github.com/joeyparrish/shaka-streamer/issues/84)) ([5a5b53d](https://github.com/joeyparrish/shaka-streamer/commit/5a5b53d3d301925d984efac1a9a5a5d7ebf5379d)), closes [#38](https://github.com/joeyparrish/shaka-streamer/issues/38)
* **cloud:** Add cloud delete support ([#164](https://github.com/joeyparrish/shaka-streamer/issues/164)) ([aa1f4e7](https://github.com/joeyparrish/shaka-streamer/commit/aa1f4e793750573079a71bdacd11a64cf43d5730))
* **cloud:** Upload through HTTP proxy node ([#103](https://github.com/joeyparrish/shaka-streamer/issues/103)) ([20c2704](https://github.com/joeyparrish/shaka-streamer/commit/20c2704deacb402e39640408ac6157e94a5f78ba)), closes [#47](https://github.com/joeyparrish/shaka-streamer/issues/47)
* Expand binary platforms and hardware encoding ([#161](https://github.com/joeyparrish/shaka-streamer/issues/161)) ([0c4b529](https://github.com/joeyparrish/shaka-streamer/commit/0c4b529d56555ad249246cd2a8c5ea935ca9edbe))
* Webcam support for Windows and microphone support ([#95](https://github.com/joeyparrish/shaka-streamer/issues/95)) ([cde5803](https://github.com/joeyparrish/shaka-streamer/commit/cde5803d705fc3e055ece540614c2c548c5affee))
* Windows support ([#85](https://github.com/joeyparrish/shaka-streamer/issues/85)) ([9a7e0ec](https://github.com/joeyparrish/shaka-streamer/commit/9a7e0ec1d5e0b5c3b67b2df97c68c0e43e0d86b7)), closes [#8](https://github.com/joeyparrish/shaka-streamer/issues/8)


### Bug Fixes

* **cloud:** Avoid rate limit issues on live streams ([#162](https://github.com/joeyparrish/shaka-streamer/issues/162)) ([1231502](https://github.com/joeyparrish/shaka-streamer/commit/1231502c068e15c6e10b856520d5fc891a5bcc20))
* **cloud:** Fix write failures from Packager ([#167](https://github.com/joeyparrish/shaka-streamer/issues/167)) ([791e39f](https://github.com/joeyparrish/shaka-streamer/commit/791e39f0a9ecb12252eb6ed08155653f6614c5ab))
* **cloud:** Quiet the HTTP server log ([#163](https://github.com/joeyparrish/shaka-streamer/issues/163)) ([4170d21](https://github.com/joeyparrish/shaka-streamer/commit/4170d218dc834f9b174019287320de64e596e54c))
* **cloud:** Retry on all failures ([#165](https://github.com/joeyparrish/shaka-streamer/issues/165)) ([7bb46d4](https://github.com/joeyparrish/shaka-streamer/commit/7bb46d446ae645ab0fbe471bf59ff3091a87c6e7))
* **external command:** Create the new shell process in a new group ([#96](https://github.com/joeyparrish/shaka-streamer/issues/96)) ([19e8652](https://github.com/joeyparrish/shaka-streamer/commit/19e8652e3419940f80170ccdf041c355ef63f02b)), closes [#46](https://github.com/joeyparrish/shaka-streamer/issues/46)
* Fix cloud upload for S3 ([7afe61e](https://github.com/joeyparrish/shaka-streamer/commit/7afe61ed653b2396dfeca303ccf2afb090c24a29)), closes [#67](https://github.com/joeyparrish/shaka-streamer/issues/67)
* Fix frame-rate and resolution auto-detection edge case ([#129](https://github.com/joeyparrish/shaka-streamer/issues/129)) ([f42188e](https://github.com/joeyparrish/shaka-streamer/commit/f42188e9bb93af1e27116b42a759a8e49587f7a9)), closes [#127](https://github.com/joeyparrish/shaka-streamer/issues/127)
* Fix framerate autodetection edge case ([#128](https://github.com/joeyparrish/shaka-streamer/issues/128)) ([aacabdc](https://github.com/joeyparrish/shaka-streamer/commit/aacabdc9bb4b82331d49e91ca41abfbb889cb49e)), closes [#127](https://github.com/joeyparrish/shaka-streamer/issues/127)
* Fix framerate detection for mixed-framerate content ([#93](https://github.com/joeyparrish/shaka-streamer/issues/93)) ([79bcd58](https://github.com/joeyparrish/shaka-streamer/commit/79bcd5857665beb27c6375059fea25c8bcacb9e6)), closes [#90](https://github.com/joeyparrish/shaka-streamer/issues/90)
* Fix minimum required version of Packager ([3cb7cc6](https://github.com/joeyparrish/shaka-streamer/commit/3cb7cc6ff7a343c50806e3a63a54017dd39d67be)), closes [#18](https://github.com/joeyparrish/shaka-streamer/issues/18)
* Fix tests running from any directory ([#71](https://github.com/joeyparrish/shaka-streamer/issues/71)) ([10c8f46](https://github.com/joeyparrish/shaka-streamer/commit/10c8f46b19b9a2c38d7f5b99b6bc7ea4fd94ce61)), closes [#49](https://github.com/joeyparrish/shaka-streamer/issues/49)
* Fix typing of log_request ([#166](https://github.com/joeyparrish/shaka-streamer/issues/166)) ([c38d7e9](https://github.com/joeyparrish/shaka-streamer/commit/c38d7e9f4ba0962c5c9b186bc3ed13f6a747903e))
* Monkey-patch subprocess on Windows to find .CMD scripts ([96f140f](https://github.com/joeyparrish/shaka-streamer/commit/96f140f0c4061d859ece80ce11841b7e07c98113))
* **multiperiod:** Use posixpath for URLs and namespace DASH BaseURL ([#91](https://github.com/joeyparrish/shaka-streamer/issues/91)) ([282db9d](https://github.com/joeyparrish/shaka-streamer/commit/282db9d49b5bebc6ac019accacf1689011316f46))
* only use the first line of ffprobe's output ([#120](https://github.com/joeyparrish/shaka-streamer/issues/120)) ([4d7d077](https://github.com/joeyparrish/shaka-streamer/commit/4d7d077e270474f99a2c6851133e8b97b738e990)), closes [#119](https://github.com/joeyparrish/shaka-streamer/issues/119)
* Report clear error if an input track does not exist ([#94](https://github.com/joeyparrish/shaka-streamer/issues/94)) ([689b803](https://github.com/joeyparrish/shaka-streamer/commit/689b8030bbe0d007cb260977d03301401b66c17d)), closes [#89](https://github.com/joeyparrish/shaka-streamer/issues/89)
* Restrict WebM formats to DASH protocol ([#80](https://github.com/joeyparrish/shaka-streamer/issues/80)) ([696d4ea](https://github.com/joeyparrish/shaka-streamer/commit/696d4eac21d40178c3846c8ce4fc47ef9ab48584)), closes [#18](https://github.com/joeyparrish/shaka-streamer/issues/18)


### Performance Improvements

* Slight speed up of vp9 encoding ([#81](https://github.com/joeyparrish/shaka-streamer/issues/81)) ([349f8de](https://github.com/joeyparrish/shaka-streamer/commit/349f8de5e2905061c2f94195cb9a19521c8e410a))


### Documentation

* Auto-link to types in config format docs ([41994f3](https://github.com/joeyparrish/shaka-streamer/commit/41994f383e4dec7bc8fd4383b8b7aec3bfb182e3))
* Change the documentation theme ([f9f9645](https://github.com/joeyparrish/shaka-streamer/commit/f9f964550ca58c094fcc94ba5409404432578ebf))
* Fix missing members in generated docs ([7368e54](https://github.com/joeyparrish/shaka-streamer/commit/7368e5433a444f19425f7c4992eb7a608258ecfa))
* Refactor installation, prereq, and overview docs ([4a6b837](https://github.com/joeyparrish/shaka-streamer/commit/4a6b837ad93f187c0a8db515c2ac1ec7aafbf82c))
* Remove note about lack of Windows support ([ab4bfa5](https://github.com/joeyparrish/shaka-streamer/commit/ab4bfa5d74e5832d892abdeae0347e9fcfb20e6a))
* Update docs for shaka-streamer-binaries and multiperiod ([#92](https://github.com/joeyparrish/shaka-streamer/issues/92)) ([d8a8d2d](https://github.com/joeyparrish/shaka-streamer/commit/d8a8d2d985154a5a5a01d27cb34cf0b6712f4fcf)), closes [#60](https://github.com/joeyparrish/shaka-streamer/issues/60)

## [0.5.1](https://github.com/shaka-project/shaka-streamer/compare/v0.5.0...v0.5.1) (2021-10-14)

 - Require Shaka Packager v2.6.1+, to fix segfault in Linux binaries
   (https://github.com/shaka-project/shaka-packager/issues/996)


## [0.5.0](https://github.com/shaka-project/shaka-streamer/compare/v0.4.0...v0.5.0) (2021-10-01)

 - Command-line argument style changed (dashes instead of underscores)
 - Multi period support for DASH
   (https://github.com/shaka-project/shaka-streamer/issues/43)
   (https://github.com/shaka-project/shaka-streamer/pull/78)
   (https://github.com/shaka-project/shaka-streamer/pull/91)
 - Multi period support for HLS
   (https://github.com/shaka-project/shaka-streamer/issues/43)
   (https://github.com/shaka-project/shaka-streamer/pull/83)
   (https://github.com/shaka-project/shaka-streamer/pull/91)
 - LL-DASH support
   (https://github.com/shaka-project/shaka-streamer/pull/88)
 - Require Python 3.6+
 - Require Shaka Packager v2.6+
 - New shaka-streamer-binaries package for binary dependencies;
   add argument --use-system-binaries to use your system-installed deps instead
   (https://github.com/shaka-project/shaka-streamer/issues/60)
   (https://github.com/shaka-project/shaka-streamer/pull/87)
   (https://github.com/shaka-project/shaka-streamer/pull/92)
 - Fix framerate detection for mixed-framerate content
   (https://github.com/shaka-project/shaka-streamer/issues/90)
   (https://github.com/shaka-project/shaka-streamer/pull/93)
 - Fix cloud upload errors for S3
   (https://github.com/shaka-project/shaka-streamer/issues/67)
 - Report clear error if an input track does not exist
   (https://github.com/shaka-project/shaka-streamer/issues/89)
   (https://github.com/shaka-project/shaka-streamer/pull/94)
 - Fix orphaned subprocesses using CTRL-C
   (https://github.com/shaka-project/shaka-streamer/issues/46)
   (https://github.com/shaka-project/shaka-streamer/pull/96)
 - Add webcam and microphone support on Windows
   (https://github.com/shaka-project/shaka-streamer/pull/95)


## [0.4.0](https://github.com/shaka-project/shaka-streamer/compare/v0.3.0...v0.4.0) (2021-08-26)

 - Fix shutdown of cloud upload
 - Improve the formatting of minimum version errors
 - Fix several issues with Ubuntu 16.04 and Python 3.5
 - Add `--skip_deps_check` to bypass version checks on dependencies
 - Increase preserved segments outside of the availability window, improving HLS
   playback in Shaka Player
 - Require Shaka Packager v2.5+
 - Add AV1 support
   (https://github.com/shaka-project/shaka-streamer/issues/10)
 - Drop `raw_images` input type
   (https://github.com/shaka-project/shaka-streamer/issues/25)
 - Fix duplicate transcoder outputs with multiple audio languages
 - Fix resolution autodetection boundary cases
 - Add support for extracting text streams from multiplexed inputs
   (https://github.com/shaka-project/shaka-streamer/issues/53)
 - Improved type-checking and type annotations
 - Fix install commands in docs
   (https://github.com/shaka-project/shaka-streamer/issues/56)
 - Fix various test failures and test-runner bugs
 - Fix packaging failures with long-running content
   (https://github.com/shaka-project/shaka-streamer/issues/64)
 - Add raw-key support
   (https://github.com/shaka-project/shaka-streamer/issues/21)
   (https://github.com/shaka-project/shaka-streamer/pull/63)
 - Add support for ac3 and ec3
   (https://github.com/shaka-project/shaka-streamer/issues/37)
   (https://github.com/shaka-project/shaka-streamer/pull/69)
 - Fix running tests from any directory
   (https://github.com/shaka-project/shaka-streamer/issues/49)
   (https://github.com/shaka-project/shaka-streamer/pull/71)
 - Add config file with Apple's HLS recommendations
   (https://github.com/shaka-project/shaka-streamer/issues/70)
   (https://github.com/shaka-project/shaka-streamer/pull/72)
 - Add support for HEVC video codec
   (https://github.com/shaka-project/shaka-streamer/pull/74)
 - Restrict WebM formats to DASH, omit from HLS
   (https://github.com/shaka-project/shaka-streamer/issues/18)
   (https://github.com/shaka-project/shaka-streamer/pull/80)
 - Automatic frame rate reduction
   (https://github.com/shaka-project/shaka-streamer/pull/77)
 - Fix missing members in docs, auto-link to types in config docs
 - Change the documentation theme
 - Set channel count as an input feature, downmix as needed
   (https://github.com/shaka-project/shaka-streamer/issues/38)
   (https://github.com/shaka-project/shaka-streamer/pull/84)
 - Add Windows support
   (https://github.com/shaka-project/shaka-streamer/issues/8)
   (https://github.com/shaka-project/shaka-streamer/pull/85)
 - Add HTTP url output support
   (https://github.com/shaka-project/shaka-streamer/pull/82)
 - Fix accidental live-type DASH output in VOD mode


## [0.3.0](https://github.com/shaka-project/shaka-streamer/compare/v0.2.0...v0.3.0) (2019-10-18)

 - Added autodetection of frame rate, resolution, interlacing, track numbers
 - Added support for custom resolutions and bitrates
   (https://github.com/shaka-project/shaka-streamer/issues/5)
 - Added hardware encoding on macOS
   (https://github.com/shaka-project/shaka-streamer/issues/23)
 - Added support for NVENC-backed hardware encoding on Linux
 - Fixed several issues in the docs, including installation instructions
 - Complain if ffprobe is missing
   (https://github.com/shaka-project/shaka-streamer/issues/35)
 - Fix PyYAML deprecation warning and YAML loading vulnerability
   (https://github.com/shaka-project/shaka-streamer/issues/35)
 - Fixed resolution name (1440p vs 2k)
 - Updated default bitrates
 - Added definition of 8k resolution
 - Now rejects unsupported features in text inputs
   (https://github.com/shaka-project/shaka-streamer/issues/34)
 - Fixed cloud upload for VOD
   (https://github.com/shaka-project/shaka-streamer/issues/30)
 - Added webcam support on macOS
   (https://github.com/shaka-project/shaka-streamer/issues/29)
 - Make common errors easier to read
 - Fixed early shutdown and missing files
   (https://github.com/shaka-project/shaka-streamer/issues/32)
 - Added a check for gsutil and for cloud destination write access
 - Speed up VP9 software encoding
 - Fixed rounding errors in width in HLS playlist
   (https://github.com/shaka-project/shaka-streamer/issues/36)


## [0.2.0](https://github.com/shaka-project/shaka-streamer/compare/v0.1.0...v0.2.0) (2019-10-14)

 - Comprehensive docs now on GitHub Pages: https://shaka-project.github.io/shaka-streamer/
   (https://github.com/shaka-project/shaka-streamer/issues/22)
 - Fixed orphaned processes on shutdown
   (https://github.com/shaka-project/shaka-streamer/issues/20)
 - Improved cloud upload performance
   (https://github.com/shaka-project/shaka-streamer/issues/19)
 - Added a setting for debug logging
   (https://github.com/shaka-project/shaka-streamer/issues/12)
 - Fixed support for 6-channel audio
   (https://github.com/shaka-project/shaka-streamer/issues/6)
 - Added support for arbitrary FFmpeg filters
   (https://github.com/shaka-project/shaka-streamer/issues/4)
 - Added support for setting presentation delay
   (https://github.com/shaka-project/shaka-streamer/issues/3)
 - Added support for setting availability window
   (https://github.com/shaka-project/shaka-streamer/issues/2)
 - Added support for extracting a small time range for VOD
   (https://github.com/shaka-project/shaka-streamer/issues/1)
 - Added support for external commands that generate input streams
 - Added support for push to Amazon S3 (gsutil supports both GCS and S3)
 - Added a quiet mode
 - Added control over output paths
 - Fixed output filename consistency, issues with multiple languages
 - Fixed issues with mapping multiple inputs
 - Flattened pipeline config format


## 0.1.0 (2019-08-30)

The first public release of Shaka Streamer! :tada:

This initial release was the work of @vickymin13 and @prestontai. Many thanks
to both of them for their hard work and dedication! It has been wonderful
having them on the team.
