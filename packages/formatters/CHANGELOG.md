# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 1.15.0 (2025-03-17)


### Bug Fixes

* extract entire string for usenet age rather than just the number ([007059c](https://github.com/raiyn27/AIOStreams/commit/007059c42a0f1155e3efa1aa7f59ff6ca62a597b))
* **formatters:** add spacing after P2P/service tag for torrentio format ([026d702](https://github.com/raiyn27/AIOStreams/commit/026d702b2c970f301c58a543bc0b48a41af4fe15))
* **formatters:** add spacing after service shortname for 'unknown' and 'download' for torrentio formatter ([8675151](https://github.com/raiyn27/AIOStreams/commit/867515145ef19f8d41cd311cd411e0da29186b35))
* **formatters:** adjust spacing in stream name for gdrive format ([5b95f79](https://github.com/raiyn27/AIOStreams/commit/5b95f79e8001e1ddcce5c81d78a4bed84191f73a))
* **formatters:** explicitly check for undefined seeders to prevent 0 seeders from not being displayed ([768a724](https://github.com/raiyn27/AIOStreams/commit/768a724e86c26a49645816bee146204f4908ba5a))
* remove unused dependency ([e6f3aed](https://github.com/raiyn27/AIOStreams/commit/e6f3aed690345077f2cbaf996fe06aa4072f94a1))


### Features

* add `addon` sort criterion ([aa74c37](https://github.com/raiyn27/AIOStreams/commit/aa74c370a2c9c86e641ea6cd77ce538c324e64ae))
* add 🇲🇽 as value for latino to handle torrentio results ([cc0f675](https://github.com/raiyn27/AIOStreams/commit/cc0f6750f19215ac8f97ab24570c80083e2e4159))
* add easynews and easynews+ addons ([2ddac6b](https://github.com/raiyn27/AIOStreams/commit/2ddac6b0715330bd79ee40ef2b12e0328a121b9d))
* add indexer to gdrive formats ([719a815](https://github.com/raiyn27/AIOStreams/commit/719a815da14bf8ee71d8c105e6176af89704f4ae))
* add minimalistic-gdrive format ([d4871a3](https://github.com/raiyn27/AIOStreams/commit/d4871a3bfd795fd2bccb405125d19cf29919d9b0))
* add personal stream identification to formatters and wrappers ([f32ef8b](https://github.com/raiyn27/AIOStreams/commit/f32ef8b4ab29f5edc5e5885ee88cd836b16f33e1))
* **addon:** support a custom formatter ([b0f27c8](https://github.com/raiyn27/AIOStreams/commit/b0f27c8b5547fbf1d40f4e1216a6b59da9746af5))
* don't add newlines in stream name for gdrive and torrentio format ([7174a17](https://github.com/raiyn27/AIOStreams/commit/7174a17c241bd9a2c8b7530fc622b5d94ad5154a))
* don't show indexer in minimalistic format ([dd27c25](https://github.com/raiyn27/AIOStreams/commit/dd27c254db2d501f5d000ef985354c4042ec07f5)), closes [#71](https://github.com/raiyn27/AIOStreams/issues/71)
* **formatters:** add torbox format ([0bc2072](https://github.com/raiyn27/AIOStreams/commit/0bc2072de17a2c7a62b2944b3c3e23b43f0b1ef7))
* **formatters:** correctly handle undefined cache status ([9145dcb](https://github.com/raiyn27/AIOStreams/commit/9145dcb691c6da33492fdd780e1ba1e7d2ea327e))
* **formatters:** display duration in same line as size for gdrive format ([ee2116e](https://github.com/raiyn27/AIOStreams/commit/ee2116e3a63ca424976505947146907a675168f2))
* **formatter:** show duration on gdrive format ([9f32ae2](https://github.com/raiyn27/AIOStreams/commit/9f32ae2145b60d698d21090614a8f396f99c69b4))
* **formatters:** move visual tags and audio tags back to separate line for gdrive ([a43f628](https://github.com/raiyn27/AIOStreams/commit/a43f62838053fe136db235b53d8c3482a400692e))
* **formatters:** show visual tags, audio tags, quaity, and encode in one line for gdrive format ([260e4eb](https://github.com/raiyn27/AIOStreams/commit/260e4ebbd791acdfa3571df4d1d2b319006cd76e))
* **formatters:** switch to base 2 units ([a36ff5f](https://github.com/raiyn27/AIOStreams/commit/a36ff5f06647673b4230dee9e0310c1a9a403b10))
* **formatters:** use emojis for languages in torrentio format ([6c5fa92](https://github.com/raiyn27/AIOStreams/commit/6c5fa9296790143eb100c54826b73213d5afeb69))
* **parser:** don't show meta if value is unknown ([2b67f2f](https://github.com/raiyn27/AIOStreams/commit/2b67f2f1865b9fbf97b46b70796b41729025758a))
* remove custom formatter for now ([63665cc](https://github.com/raiyn27/AIOStreams/commit/63665cc87ff0f62d81e059b7e9dd63726bc9bef3))
* show p2p in torrentio format ([321bf98](https://github.com/raiyn27/AIOStreams/commit/321bf988a8e80f66196b8c4ee60b9c3e358c61b4))
* some changes ([73bff80](https://github.com/raiyn27/AIOStreams/commit/73bff804f541c8240bdc1bf2ce7b227078ec7b67))
* super secret format ([6ca10f4](https://github.com/raiyn27/AIOStreams/commit/6ca10f4d8799890775f451a379e3f8ebe7dcf707))
* use id for services across code ([c3e118b](https://github.com/raiyn27/AIOStreams/commit/c3e118b8d35fc27caa86048ec1ed475d405024d0))
* **wrappers:** improve basewrapper parsing ([6a3b005](https://github.com/raiyn27/AIOStreams/commit/6a3b00553f5d2e9c32e93a155e8c67285d453047))
