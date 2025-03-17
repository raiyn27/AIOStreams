# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.15.0 (2025-03-17)


### Bug Fixes

* **addon:** allow any IDs ([ccbd649](https://github.com/raiyn27/AIOStreams/commit/ccbd649bc8d173edb7fb30c67cc9c30b32cd9e8e))
* **cloudflare-worker:** handle requests for static assets ([9c12cfc](https://github.com/raiyn27/AIOStreams/commit/9c12cfc08bb5222a82543e9f36b7734f28919e3f))
* **cloudflare-workers:** correctly import manifest from addon package ([447cabb](https://github.com/raiyn27/AIOStreams/commit/447cabbee8c7a689737acb326e4d35d66cead2a3))
* correctly determine configurationRequired value depending on whether addon is configured ([c3c421e](https://github.com/raiyn27/AIOStreams/commit/c3c421e85771f77036601ac238abde0e44265d30))
* correctly determine user ip ([42dd251](https://github.com/raiyn27/AIOStreams/commit/42dd2517cea1fe5f2ff550301a40510cec6e0cce))
* decode on cf worker ([befbf31](https://github.com/raiyn27/AIOStreams/commit/befbf31527345adf511a2c8ff9fcb4a4b9f249be))
* dont include config in regex ([af577da](https://github.com/raiyn27/AIOStreams/commit/af577da620ed4565da38481bbcab1400fed3e19d))
* potentially fix cf workers ([9e7b3b1](https://github.com/raiyn27/AIOStreams/commit/9e7b3b1abceb609b89524eb3647d26143b954652))
* update cf worker to use new responses ([f810e13](https://github.com/raiyn27/AIOStreams/commit/f810e1324eb6c734ca58eddc1b9ca179f5ee91ac))


### Features

* add cf worker ([d0f90e0](https://github.com/raiyn27/AIOStreams/commit/d0f90e0c7ed6ed353a5197c82562eb0d1a0af9ac))
* adjust logs and fix loading config from url ([6b1d65d](https://github.com/raiyn27/AIOStreams/commit/6b1d65dc43a18e0ca2883fb963d0cafcecad2fa1))
* **cf-worker:** set status to 404 when returning 404 page ([64ac639](https://github.com/raiyn27/AIOStreams/commit/64ac6394b25504213899a3c1f6757cb1563e39a8))
* encrypted config ([f12c13d](https://github.com/raiyn27/AIOStreams/commit/f12c13d0fdad718d0932151a0ba4b94ef964e9ca))
* memory cache ([cb13a17](https://github.com/raiyn27/AIOStreams/commit/cb13a175c7d756acc11ce8fd15bba7ece0826de8))
* rename cf worker name from aiostreams-cloudflare-workers to aiostreams ([04117a3](https://github.com/raiyn27/AIOStreams/commit/04117a3f101caae3a12695f62d19246bcf329483))
* use winston for logging ([7026597](https://github.com/raiyn27/AIOStreams/commit/70265971f910c5304b146005784ae17171b1c1be))
