# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.15.0 (2025-03-17)


### Bug Fixes

* add deprecated option type so removed options are still encrypted ([12f6b3d](https://github.com/raiyn27/AIOStreams/commit/12f6b3d59b4923676d0f6c97d2febf8ed51ce320))
* **addon:** allow any IDs ([ccbd649](https://github.com/raiyn27/AIOStreams/commit/ccbd649bc8d173edb7fb30c67cc9c30b32cd9e8e))
* extract entire string for usenet age rather than just the number ([007059c](https://github.com/raiyn27/AIOStreams/commit/007059c42a0f1155e3efa1aa7f59ff6ca62a597b))
* load config into sortable fields in correct order ([d423eed](https://github.com/raiyn27/AIOStreams/commit/d423eed60ef812258df139d35f8480c3dbae2ad6))


### Features

* add `addon` sort criterion ([aa74c37](https://github.com/raiyn27/AIOStreams/commit/aa74c370a2c9c86e641ea6cd77ce538c324e64ae))
* add `Stream Types` section for fltering/sorting by type ([a1d8971](https://github.com/raiyn27/AIOStreams/commit/a1d897191e88f30f3afdc067aa68b7e9e588ae2d))
* add comet and improve method of getting choosable addons ([4e5714d](https://github.com/raiyn27/AIOStreams/commit/4e5714db4465aec50aef4afca7d18965032dc324))
* add easynews and easynews+ addons ([2ddac6b](https://github.com/raiyn27/AIOStreams/commit/2ddac6b0715330bd79ee40ef2b12e0328a121b9d))
* add keyword filters and some refactors ([63133d0](https://github.com/raiyn27/AIOStreams/commit/63133d00c1b8ea72438ba0af5b9e3e96831cc92a))
* add option to move addon name to stream description ([0bd8db6](https://github.com/raiyn27/AIOStreams/commit/0bd8db6cfcf462de4ac86d1983d111931d1eec0e))
* add optional API key validation and input to configuration ([#99](https://github.com/raiyn27/AIOStreams/issues/99)) ([54ce738](https://github.com/raiyn27/AIOStreams/commit/54ce73814b5d26ed5151bb97baa412ee51055afd))
* add Orion Stremio addon support and use defined secret attribute for credential inputs rather than looking for URLs only ([bd672f1](https://github.com/raiyn27/AIOStreams/commit/bd672f13e5ede511c00d437ea2f9385087249848))
* add personal stream identification to formatters and wrappers ([f32ef8b](https://github.com/raiyn27/AIOStreams/commit/f32ef8b4ab29f5edc5e5885ee88cd836b16f33e1))
* add prioritisedLanguages and excludedLanguages option. ([15218b2](https://github.com/raiyn27/AIOStreams/commit/15218b2f3f172eaae449609ef6c758cebd7b5630))
* **addon:** support a custom formatter ([b0f27c8](https://github.com/raiyn27/AIOStreams/commit/b0f27c8b5547fbf1d40f4e1216a6b59da9746af5))
* **addon:** support encode and audioTag filter and sort criteria ([9f3e441](https://github.com/raiyn27/AIOStreams/commit/9f3e441fe36125eeb2e3d25a2a3adcf38c9b8ddb))
* allow undefined cache status ([42f8e55](https://github.com/raiyn27/AIOStreams/commit/42f8e558401f3e32dea77bdfa40b3af5627aa928))
* changeable sort direction for cached, size, seeders ([d0e506d](https://github.com/raiyn27/AIOStreams/commit/d0e506deb36451c306980a72c202c1e1ab9b7b31))
* clean results option ([2d76648](https://github.com/raiyn27/AIOStreams/commit/2d76648706321707652ea37d509ee623343ab7bb))
* configurable addon name per config ([4eca7ae](https://github.com/raiyn27/AIOStreams/commit/4eca7ae68d6f8b679040c93bb37ff2abb77fd29b)), closes [#74](https://github.com/raiyn27/AIOStreams/issues/74)
* configurable timeout for every addon ([8abf25b](https://github.com/raiyn27/AIOStreams/commit/8abf25b8e8217fbfe586165eaede9ebbc0035088))
* customisable filters for mediafusion and add MultiSelect component ([206d6cb](https://github.com/raiyn27/AIOStreams/commit/206d6cbc5c4cec9ac351c36d42602211a0bd0d2d))
* **frontend:** make services sortable ([71d570e](https://github.com/raiyn27/AIOStreams/commit/71d570e14ebb02b9287c534a054a835a3eeaa4df))
* improve logging, use new CredentialsInput component, used for mediaflow configs as well to encrypt them too, add mediaflow public IP option, forward requesting ip or mediaflow IP to upstream addon requests, adjust mediaflow option css, fix issues with decoding/encoding configs again ([d39c838](https://github.com/raiyn27/AIOStreams/commit/d39c83853ead3e88659a45a96443c1210054faef))
* make Config.mediaFlowConfig optional in type ([c06b099](https://github.com/raiyn27/AIOStreams/commit/c06b099c6062adae203e58ce04bf5b2c40afabf4))
* max results per resolution setting ([d4d1e35](https://github.com/raiyn27/AIOStreams/commit/d4d1e352e33ed4b9a51f829b506d8254d5d286b2))
* memory cache ([cb13a17](https://github.com/raiyn27/AIOStreams/commit/cb13a175c7d756acc11ce8fd15bba7ece0826de8))
* move config validator into addon package and also check config at each request ([27b2ef9](https://github.com/raiyn27/AIOStreams/commit/27b2ef9bd6a1f6ad4bc3c8aadf1bcd205057ea43))
* only use strings for addon options ([83149bf](https://github.com/raiyn27/AIOStreams/commit/83149bfec64fbab37280d273dc9b3825cfbe2ee4))
* potentially add mediaflow proxy support ([e069640](https://github.com/raiyn27/AIOStreams/commit/e06964039a0d67bd9e219dbd84a0784790be0ffa))
* prefer grouping duplicates by infohash ([c6b9765](https://github.com/raiyn27/AIOStreams/commit/c6b976501ae026da12811cc4a85f60506fc463e7))
* remove mediaflow public ip option ([9042af4](https://github.com/raiyn27/AIOStreams/commit/9042af4c8f690a2e5b0e3c178fd2e29a7bb5fe01))
* return error streams when failed to get streams for an addon ([c8bedcb](https://github.com/raiyn27/AIOStreams/commit/c8bedcb2a9bacb49128a9265a8dd41071c7d1ea6))
* separate size filters for movies and series ([8185f5e](https://github.com/raiyn27/AIOStreams/commit/8185f5e95b4da458f1d8f1b5821a59274e29b8be))
* some changes ([73bff80](https://github.com/raiyn27/AIOStreams/commit/73bff804f541c8240bdc1bf2ce7b227078ec7b67))
* support customising which streams to proxy, fix duplication check bypasses by setting falsy/false values to undefined to match intial state, refactor multi select component usage ([dcb0353](https://github.com/raiyn27/AIOStreams/commit/dcb0353f926cd2e72e5cd0d3e823d8436a4064ef)), closes [#8](https://github.com/raiyn27/AIOStreams/issues/8) [#17](https://github.com/raiyn27/AIOStreams/issues/17) [#18](https://github.com/raiyn27/AIOStreams/issues/18)
* use id for services across code ([c3e118b](https://github.com/raiyn27/AIOStreams/commit/c3e118b8d35fc27caa86048ec1ed475d405024d0))
* **wrappers:** improve basewrapper parsing ([6a3b005](https://github.com/raiyn27/AIOStreams/commit/6a3b00553f5d2e9c32e93a155e8c67285d453047))
