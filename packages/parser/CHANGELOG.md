# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.15.0 (2025-03-17)


### Bug Fixes

* add a negative lookahead for subtitles in language parsing ([35a6d7a](https://github.com/raiyn27/AIOStreams/commit/35a6d7aaee48e7fbf792ad46fcd5222adf010db2))
* adjust hdr regex ([fdda8c6](https://github.com/raiyn27/AIOStreams/commit/fdda8c6db3ee428f6b90e763809fdd91a5e1a65e))
* don't match UHD for bluray ([7798669](https://github.com/raiyn27/AIOStreams/commit/7798669937e0e9a862e7b2f9a72d0ab76f72d77f))
* enhance regex for DD and 5.1/7.1 combinations ([c1b9632](https://github.com/raiyn27/AIOStreams/commit/c1b96324246d497fbcac9bfd73fbf61f77cfb9e0))
* fix 7.1 and 5.1 regex ([794eb11](https://github.com/raiyn27/AIOStreams/commit/794eb111156d1b047ed7bd94a3f34f0325408d95)), closes [#58](https://github.com/raiyn27/AIOStreams/issues/58)
* improve regex ([ea1217f](https://github.com/raiyn27/AIOStreams/commit/ea1217fde7322a05640366b7874db110b0213f9d))
* **parser:** correctly escape characters ([f1a2ef1](https://github.com/raiyn27/AIOStreams/commit/f1a2ef14835a828875e2d546007bc1472f924ea7))
* **parser:** improve regex for DTS and DTS-HD to avoid matching all 3 DTS tags with DTS-HD MA ([705772c](https://github.com/raiyn27/AIOStreams/commit/705772c1aa6730afa69ca4a24963c6a48b2712b8))
* **parser:** remove `ma` from dts-hd regex which caused no matches due to typo ([ea33d7c](https://github.com/raiyn27/AIOStreams/commit/ea33d7c12ad6ef2450031d2c51c2c5f24267f914))
* **parser:** update SCR regex to match HDSCR and DV regex to match dovi ([d3a55b0](https://github.com/raiyn27/AIOStreams/commit/d3a55b00b2d81fef16d0db0727af594e6b46606c))
* remove AC3 and E-AC3 from audio tags and combine with DD and DD+ ([d6503d4](https://github.com/raiyn27/AIOStreams/commit/d6503d428388e169e4ff8b77981a1df0abbc8c29))
* update AI regex ([8b2e2fc](https://github.com/raiyn27/AIOStreams/commit/8b2e2fc9c99dbc48b105b518a668b29473637588))
* update regex patterns for H-OU and H-SBS to improve matching accuracy ([4b7daab](https://github.com/raiyn27/AIOStreams/commit/4b7daab27ea3fe3906a8423346115f16f1a6b747))
* update Spanish regex to include 'esp' as a valid abbreviation ([f620cea](https://github.com/raiyn27/AIOStreams/commit/f620cea389e023e5836a09e7d1e93d87ecff197e))


### Features

* add 10bit, e-ac3, flac, xvid, divx filters ([092e37e](https://github.com/raiyn27/AIOStreams/commit/092e37e388778263c8c6baa07d2c81bb3321e797))
* add 3D encodes ([dcff999](https://github.com/raiyn27/AIOStreams/commit/dcff99931a2515619a96ea3d8031baf5050d3add))
* add 3D visual tag ([57db4db](https://github.com/raiyn27/AIOStreams/commit/57db4dbb21ce2442431aa5748d9a572169eb63dd))
* add av1 encode filter ([53d730c](https://github.com/raiyn27/AIOStreams/commit/53d730cf16be40b0af36e933c87b7bcecc794e63))
* add easynews and easynews+ addons ([2ddac6b](https://github.com/raiyn27/AIOStreams/commit/2ddac6b0715330bd79ee40ef2b12e0328a121b9d))
* add latino language ([e13ff56](https://github.com/raiyn27/AIOStreams/commit/e13ff560d60488c31bd6a34e7f0f491909a1447f))
* add more languages ([0da1165](https://github.com/raiyn27/AIOStreams/commit/0da11652f90050f35d137b48297efc214c3f2abe))
* add regex for dubbed ([5c41642](https://github.com/raiyn27/AIOStreams/commit/5c41642d86f1a8d669bf97ed1c7673576259f0ed))
* add SDR visual tag ([1855b3b](https://github.com/raiyn27/AIOStreams/commit/1855b3bf94e342f566ef813e16e5f213e0ccadb9)), closes [#88](https://github.com/raiyn27/AIOStreams/issues/88)
* combine hevc/x265 and avc/x264 regex ([c1a36ef](https://github.com/raiyn27/AIOStreams/commit/c1a36ef8d3bb918a711513dca6bc1b35101bfcfc))
* improve duration parser ([cd0f456](https://github.com/raiyn27/AIOStreams/commit/cd0f45634efde545658bc13a6fbe991b482d9daa))
* **parser:** add regex for DTS-HD MA ([75ba6d5](https://github.com/raiyn27/AIOStreams/commit/75ba6d57f3a475500bf200fbad1d9dccd328cb06))
* **parser:** allow brackets ([ba88b3d](https://github.com/raiyn27/AIOStreams/commit/ba88b3da105f989d3d259047c7b221376cfb9cba))
* **parser:** allow spaces and other characters between true and hd ([737aefb](https://github.com/raiyn27/AIOStreams/commit/737aefb4ea650e9559df4adf62c80bd625565d75))
* **parser:** allow UHD in place of bluray ([6c5f091](https://github.com/raiyn27/AIOStreams/commit/6c5f09104ff98bdc616e7d83d6784f6f9e077b2f))
* **parser:** make rip in predvdrip optional for TS regex ([0e9f553](https://github.com/raiyn27/AIOStreams/commit/0e9f5538a08de0ffb70d3db17a7daf353ccac316))
* **parser:** return 'Unknown' when unable to match for single pattern tests ([3f58f86](https://github.com/raiyn27/AIOStreams/commit/3f58f861db5938fb95bee76980d2f04fa949c90b))
* update parser ([6352ca4](https://github.com/raiyn27/AIOStreams/commit/6352ca40daee9b00e0fd50298aaaa852edfeaacb))
