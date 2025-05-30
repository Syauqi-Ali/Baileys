## [6.8.1](https://syauqi-ali/compare/v6.8.0...v6.8.1) (2025-05-25)



# [6.8.0](https://syauqi-ali/compare/v6.7.22...v6.8.0) (2025-05-25)



## [6.7.22](https://syauqi-ali/compare/v6.7.21...v6.7.22) (2025-05-25)



## [6.7.21](https://syauqi-ali/compare/v6.7.20...v6.7.21) (2025-05-25)



## [6.7.20](https://syauqi-ali/compare/v6.7.19...v6.7.20) (2025-05-24)



## [6.7.19](https://syauqi-ali/compare/v6.7.18...v6.7.19) (2025-05-24)


### Bug Fixes

* allow media upload retries ([f58a38f](https://syauqi-ali/commits/f58a38fde96297858f372b5abdbb75bc92c438db))
* memory blow on large files sending through URL ([bff86ed](https://syauqi-ali/commits/bff86ed4c1fec3f42ed46e6ccbdead378f4107b6))



## [6.7.18](https://syauqi-ali/compare/v6.7.17...v6.7.18) (2025-05-23)



## [6.7.17](https://syauqi-ali/compare/v6.7.16...v6.7.17) (2025-05-15)


### Bug Fixes

* failed to send message to self, add checks for empty strings and invalid nodes ([#1322](https://syauqi-ali/issues/1322)) ([bca5102](https://syauqi-ali/commits/bca51028197a1cd3c57ec60d48156923d0977cca))
* lint ([131aead](https://syauqi-ali/commits/131aeadd45065512bd0b2d420673d605f209c373))
* makeCacheableSignalKeyStore logger optional ([#1332](https://syauqi-ali/issues/1332)) ([ae5a7d1](https://syauqi-ali/commits/ae5a7d14c3b492b3e5543eed26e3655d33341548))
* proper send receipt to Meta Ia trigger messages to avoid offline pending notifications hang ([36456d6](https://syauqi-ali/commits/36456d6db68e20c234265bbc1ef8cc5b085daba4))
* readAdJid domainType ([47540e9](https://syauqi-ali/commits/47540e961ed1530b3fa2b46847258fdaceacce5b))
* send message to LID addressing_mode groups ([53d6e3a](https://syauqi-ali/commits/53d6e3a8d5d8b141b2c806a09ba59ae50957f6f5))
* send message to lid groups ([a4338fa](https://syauqi-ali/commits/a4338fac12a54a36890845c99abd56e92b88cdf6))
* simplify domainType ([f4dc41e](https://syauqi-ali/commits/f4dc41eda10b01e638c85d434a9db4822467ee0d))


### Features

* add per-jid patching ([e1aadc5](https://syauqi-ali/commits/e1aadc5546c6bf8ee8c299e4b88b254bcc0cdeaa))



## [6.7.16](https://syauqi-ali/compare/v6.7.15...v6.7.16) (2025-03-04)


### Bug Fixes

* **sync:** complete unfinished async implementation ([fccca8a](https://syauqi-ali/commits/fccca8ab309ef729d182bc7212bc2d2642af2882)), closes [#1286](https://syauqi-ali/issues/1286)



## [6.7.15](https://syauqi-ali/compare/v6.7.14...v6.7.15) (2025-03-02)


### Bug Fixes

* resolve DataView constructor error in lt-hash ([#1279](https://syauqi-ali/issues/1279)) ([af17232](https://syauqi-ali/commits/af17232611702b98274a52d0ff88f828c56afa5a))



## [6.7.14](https://syauqi-ali/compare/v6.7.13...v6.7.14) (2025-03-01)


### Bug Fixes

* migrating to @cacheable/node-cache as it is maintained ([#1074](https://syauqi-ali/issues/1074)) ([588de6c](https://syauqi-ali/commits/588de6ce10f74f9d68fd834cbc44cf2a7ba9378e))
* sending SERVER_ACK to messages.update ([#1101](https://syauqi-ali/issues/1101)) ([cfbfcd8](https://syauqi-ali/commits/cfbfcd8e14dd3d62cfa6c9e9fa45408e7f29ca16))
* typo on doc 'messaging.history-set' -> 'messaging-history.set'. ([#1275](https://syauqi-ali/issues/1275)) ([5255491](https://syauqi-ali/commits/5255491cb851f8fd1f240beceeed7714ac6e66a2))
* update fetchLatestWaWebVersion to retrieve client revision from new endpoint ([#1234](https://syauqi-ali/issues/1234)) ([36690fc](https://syauqi-ali/commits/36690fc46260c76d95ddcd4912a6ea616696c2d5))


### Features

* add Id support for desktop ([#1240](https://syauqi-ali/issues/1240)) ([89b28a4](https://syauqi-ali/commits/89b28a438bd95d297ccfdb72a3e385bd59a62a75))
* add last message in chat.update event if is real message ([#1203](https://syauqi-ali/issues/1203)) ([ae60f3f](https://syauqi-ali/commits/ae60f3fe62bb05a97111c5145fa247492f40ddae))



## [6.7.13](https://syauqi-ali/compare/v6.7.12...v6.7.13) (2025-02-16)



## [6.7.12](https://syauqi-ali/compare/v6.7.11...v6.7.12) (2025-01-31)



## [6.7.11](https://syauqi-ali/compare/v6.7.10...v6.7.11) (2025-01-31)



## [6.7.10](https://syauqi-ali/compare/v6.7.9...v6.7.10) (2025-01-31)



## [6.7.9](https://syauqi-ali/compare/v6.7.8...v6.7.9) (2024-10-22)


### Bug Fixes

* **master:** Fixes prop hash reset due to missing property in the response ([bf578c7](https://syauqi-ali/commits/bf578c79e797c9e3a270fede674f840b3d2496cb))
* **master:** Small fix to the profile picture endpoints ([47b2f6d](https://syauqi-ali/commits/47b2f6dd413e649eaf62b29ef7a0c69ed370b436))



## [6.7.8](https://syauqi-ali/compare/v6.7.7...v6.7.8) (2024-09-22)


### Bug Fixes

* **master:** New profile update/removal endpoint (inspired by [#1048](https://syauqi-ali/issues/1048)) ([70f0321](https://syauqi-ali/commits/70f03213810fb821c05ea5f024f6f270babe4df5))
* messaging-history.set event not emitting syncType and progress / add PDO request id ([#1042](https://syauqi-ali/issues/1042)) ([fda2689](https://syauqi-ali/commits/fda268916927c81e407b4f5d2830b63ed8c23b30))


### Features

* add label feature ([#955](https://syauqi-ali/issues/955)) ([6ff9455](https://syauqi-ali/commits/6ff945502d9e78c42a1d05fca79f951e81b946df))



## [6.7.7](https://syauqi-ali/compare/v6.7.6...v6.7.7) (2024-08-22)


### Bug Fixes

* do not fetch group metadata for status ([#986](https://syauqi-ali/issues/986)) ([09f8df4](https://syauqi-ali/commits/09f8df445c8c3d6b4d709de33c65bb3df4caf7d5)), closes [#985](https://syauqi-ali/issues/985)
* Fixed contacts.update when received changed picture event ([#979](https://syauqi-ali/issues/979)) ([c02b772](https://syauqi-ali/commits/c02b772de0ad2e8b418a807a1fb174590d298c68))



## [6.7.6](https://syauqi-ali/compare/v6.7.5...v6.7.6) (2024-08-14)


### Bug Fixes

* **fix/buttons-deprecation:** initial/final commit ([#956](https://syauqi-ali/issues/956)) ([35f6d75](https://syauqi-ali/commits/35f6d75cf8609f2c7633bd58373672c79f722c8b))
* invalid children for header "companion_platform_id": 49 (number) ([#897](https://syauqi-ali/issues/897)) ([fdf9d48](https://syauqi-ali/commits/fdf9d4816283a8a10145112965e3d8ea05b919e1))
* **master:** Deploy docs to custom CNAME (baileys.whiskeysockets.io) ([f25f836](https://syauqi-ali/commits/f25f83656a7cadbcdaf66b7fea72b9d4b3a72aa0))
* **master:** update linting workflow to node 20 (current LTS) ([703933f](https://syauqi-ali/commits/703933f44ce1b0d0301fc51392f9ae5c7e548b08))
* **master:** yarn lock and axios error + move to WhiskeySockets libsignal ([c8aab8d](https://syauqi-ali/commits/c8aab8d03f7e5823b57b7168cca593f11191aa05))
* profilePictureUrl ([#901](https://syauqi-ali/issues/901)) ([5bdfc63](https://syauqi-ali/commits/5bdfc631058fdb0f7a83b6865339b134a3f62453))
* remove 'none' from updateGroupsAddPrivacy ([#966](https://syauqi-ali/issues/966)) ([ffafc16](https://syauqi-ali/commits/ffafc167fb667713229467d2ad62a9444fddc6e3))


### Features

* emit WAMessageStubType.GROUP_CHANGE_DESCRIPTION event ([#967](https://syauqi-ali/issues/967)) ([c32ea03](https://syauqi-ali/commits/c32ea03de605e52c8b6e26655db38db589161a97))
* **feature/group-invite-v4:** initial/final commit ([#958](https://syauqi-ali/issues/958)) ([7c9f2eb](https://syauqi-ali/commits/7c9f2ebd46194ffff77bb56b759452478fe02e40))
* **feature/poll-v3:** initial/final commit ([#957](https://syauqi-ali/issues/957)) ([e915010](https://syauqi-ali/commits/e91501026c34223a2a8c6b39cf59f8dd6bd075e8))


### Reverts

* Revert "Update module to latest version  (#926)" (#947) ([1885157](https://syauqi-ali/commits/188515791d8337580c182e890290a34019b13438)), closes [#926](https://syauqi-ali/issues/926) [#947](https://syauqi-ali/issues/947)
* Revert "Update module to latest version  (#926)" ([4594997](https://syauqi-ali/commits/45949972e173741d5e0b82bc44317e620b861460)), closes [#926](https://syauqi-ali/issues/926)



## [6.7.5](https://syauqi-ali/compare/v6.7.4...v6.7.5) (2024-06-12)


### Bug Fixes

* **master:** fix lockfile (after [#847](https://syauqi-ali/issues/847)) ([c964615](https://syauqi-ali/commits/c964615cf9b2eaaa6f72e2bd5fa660eb2ae9ab9b))
* **master:** generate new message id ([0cc888e](https://syauqi-ali/commits/0cc888e87bc931d7608cdc78c536de3d8ee4cb82))
* **master:** prevent detection ([e91f9e0](https://syauqi-ali/commits/e91f9e05c5493f410882aa2dcb7396a945725691))



## [6.7.4](https://syauqi-ali/compare/v6.7.3...v6.7.4) (2024-06-02)


### Bug Fixes

* **fix-routing-info:** initial commit ([#837](https://syauqi-ali/issues/837)) ([d7037cf](https://syauqi-ali/commits/d7037cf6fab71d86128c6f3eb4aeaeb3e7eccec3))



## [6.7.3](https://syauqi-ali/compare/v6.7.2...v6.7.3) (2024-06-02)


### Bug Fixes

* downloadMediaMessage return type matched parameter ([#757](https://syauqi-ali/issues/757)) ([2ae664c](https://syauqi-ali/commits/2ae664c6550804795cc0fb25c05b147d9633a887))
* **master:** linting ([88cf6f5](https://syauqi-ali/commits/88cf6f52347fe31ac91d300daa3de66fc70cfc59))
* **master:** linting and making functionality better ([5ffa3a5](https://syauqi-ali/commits/5ffa3a51b65b53ebf5c85ac327c281f2fd7c7a33))
* **master:** linting warnings ([ce325d1](https://syauqi-ali/commits/ce325d11828b6f32584b39e7e427aa47b0ee555d))


### Features

* add event that handles join approval requests ([#802](https://syauqi-ali/issues/802)) ([ffec4af](https://syauqi-ali/commits/ffec4af454b7eaef5af0f9cde03faa3664969b78))
* **add-logger:** initial commit ([#777](https://syauqi-ali/issues/777)) ([7d80bf0](https://syauqi-ali/commits/7d80bf0ea25eb3cbbfa48331eed38399e4506b54))
* **add-routing-info:** initial commit ([#773](https://syauqi-ali/issues/773)) ([0eaa5af](https://syauqi-ali/commits/0eaa5af909d90df935f79a4cc96740b2e89ff518))



## [6.7.2](https://syauqi-ali/compare/v6.7.1...v6.7.2) (2024-05-06)


### Bug Fixes

* **master:** error in init queries ([fbbb511](https://syauqi-ali/commits/fbbb511fb8464ea744e2abc416c8cef54c0e317c))
* **master:** nightly builds ([2ef59bf](https://syauqi-ali/commits/2ef59bf924dde792c40106e4253357f5b810f25b))



## [6.7.1](https://syauqi-ali/compare/v6.7.0...v6.7.1) (2024-04-29)


### Bug Fixes

* **master:** final workflow fix ([eb5eddd](https://syauqi-ali/commits/eb5edddf2fe847159c308fba314c5ad4f27df467))
* **master:** fix whiskeysockets publishing ([649dee4](https://syauqi-ali/commits/649dee41eb734d5675068e9795c5904e50a8bcb9))


### Reverts

* Revert "fix: inefficient method of extracting url from text (#741)" (#748) ([d91967a](https://syauqi-ali/commits/d91967aa1c025f96336dbe8e390ae38ed6845566)), closes [#741](https://syauqi-ali/issues/741) [#748](https://syauqi-ali/issues/748) [#741](https://syauqi-ali/issues/741)



# [6.7.0](https://syauqi-ali/compare/v6.6.1...v6.7.0) (2024-04-28)



## [6.6.1](https://syauqi-ali/compare/v6.6.0...v6.6.1) (2024-04-28)


### Bug Fixes

* **#681:** Fixed import (credit to [#611](https://syauqi-ali/issues/611)) ([c218f37](https://syauqi-ali/commits/c218f3746e18ff75d552e130ccf01f30280e1e16))
* enable viewOnce messages to quote ([#736](https://syauqi-ali/issues/736)) ([03f82f5](https://syauqi-ali/commits/03f82f599ec687117b17381593dd9c4c945c37d9))
* inefficient method of extracting url from text ([#741](https://syauqi-ali/issues/741)) ([f5c1aff](https://syauqi-ali/commits/f5c1affc4d97c00e01cdbff6e2575a18ddf896fc))
* **master:** fix lockfile ([0792755](https://syauqi-ali/commits/07927554a2a7689b0e024e4ce3fe67c599b242ed))
* **missing messages:** revert to normal ([#732](https://syauqi-ali/issues/732)) ([9d2f9ed](https://syauqi-ali/commits/9d2f9ed4e3ab4ddce8d754b23ab7a5495e4470f6))
* **missing-messages:** linting and bug ([c264633](https://syauqi-ali/commits/c264633291b16ffd897e9a98d29d3bf6a11502ff))
* **missing-messages:** linting fix ([9d3dcfd](https://syauqi-ali/commits/9d3dcfd08b161983f2b7654eaccbf93f2362b442))
* old_version in mobile connection ([#722](https://syauqi-ali/issues/722)) ([495bb67](https://syauqi-ali/commits/495bb6775af76a5f214b2fa9063079d5d139cd0a))
* **retry:** final commit: linting ([767af0b](https://syauqi-ali/commits/767af0b688a21a5737ef745997f8687870dc1294))


### Features

* add support to ptvMessage in sendMessage method ([#738](https://syauqi-ali/issues/738)) ([111601b](https://syauqi-ali/commits/111601bc732176ddb1bcb8feeee018e7d46d2e5a))
* **fix-workflow:** push to the 2 npm packages at the same time ([#746](https://syauqi-ali/issues/746)) ([098908d](https://syauqi-ali/commits/098908d05b59126cdce5fadc07e370f85cde310a))



# [6.6.0](https://syauqi-ali/compare/v6.5.0...v6.6.0) (2024-01-19)


### Bug Fixes

* find platform type based on browser second argument ([32533ed](https://syauqi-ali/commits/32533ed7f6ebbd8bd70a0a871c43ee0b579b8ce8)), closes [#481](https://syauqi-ali/issues/481) [#228](https://syauqi-ali/issues/228)
* Fix linting ([cbffb29](https://syauqi-ali/commits/cbffb2941cd7e61142a25ef9e58149230621db36))
* fix message content type detection ([a07922b](https://syauqi-ali/commits/a07922b136e84d99f036b7d51bfe1cead8236368))
* fix pairing code ([abe4256](https://syauqi-ali/commits/abe42564bed1d2f34014ef580d249a644142bdc2))
* quick test to diagnose working dir issue ([b5e5239](https://syauqi-ali/commits/b5e5239c94b838e72a2e0f5fa6c613a4306ba66f))


### Features

* Add max msg retry count ([#572](https://syauqi-ali/issues/572)) ([18990f8](https://syauqi-ali/commits/18990f874f9faf2423c9f6a024bfc7d72f8b4c9e))
* add option for Windows browser ([#303](https://syauqi-ali/issues/303)) ([3fc5d4b](https://syauqi-ali/commits/3fc5d4b8036cc72e672e646399bcf9f6bd72ccc9))
* auto version hash ([#290](https://syauqi-ali/issues/290)) ([6b4d917](https://syauqi-ali/commits/6b4d91737f375070ae4869b7ec43d7728d48d2ee))
* If need approval to join the group in groupMetadata ([#533](https://syauqi-ali/issues/533)) ([c41be3a](https://syauqi-ali/commits/c41be3ac4fd90bf1ce748b7905e74600cef8a1d1))
* memberAddMode and joinApprovalMode in groups.update ([#532](https://syauqi-ali/issues/532)) ([3efd3e0](https://syauqi-ali/commits/3efd3e00ca64b795a6e1f7581aaf260880a09202))
* Set in group settings memberAddMode and joinApprovalMode ([#534](https://syauqi-ali/issues/534)) ([408c007](https://syauqi-ali/commits/408c0070ba85d33a05cfeab66f447464b2bbf36f))



# [6.5.0](https://syauqi-ali/compare/v6.4.2...v6.5.0) (2023-09-28)



## [6.4.2](https://syauqi-ali/compare/v6.4.1...v6.4.2) (2023-09-28)



## [6.4.1](https://syauqi-ali/compare/v6.4.0...v6.4.1) (2023-08-27)


### Bug Fixes

* do not send message to self if the device is 0 (mobile) ([64349ca](https://syauqi-ali/commits/64349cac15fad8fa9bb1ace741d161ec8b5c140d))
* registration + add captcha support ([#227](https://syauqi-ali/issues/227)) ([49ab16f](https://syauqi-ali/commits/49ab16f5925789b85219bec2f35686234dab08a0))
* Use new useragent and token for mobile ([a6bc59f](https://syauqi-ali/commits/a6bc59f3f0957e83657c9d1e9f4b41fd36542e26))



# [6.4.0](https://syauqi-ali/compare/v6.3.1...v6.4.0) (2023-07-18)


### Bug Fixes

* adjusted default keepAliveIntervalMs ([#233](https://syauqi-ali/issues/233)) ([0aaa008](https://syauqi-ali/commits/0aaa0086f9900abc142a2eba0982f8bd9c2e60a5))


### Features

* Add queue in enc/dec group message ([#191](https://syauqi-ali/issues/191)) ([e0e7d40](https://syauqi-ali/commits/e0e7d40847e8c01bbf18680bfba1682293168d5e))
* Add waveforms to voice messages ([#180](https://syauqi-ali/issues/180)) ([2c76713](https://syauqi-ali/commits/2c7671356511b766520d1173bd4f2f6575bf0ba2))
* expose makeWASocket as named ([#190](https://syauqi-ali/issues/190)) ([a1fb826](https://syauqi-ali/commits/a1fb826ceaa2b7562875c2860b40de5a1bc49759))
* Send Status (status@broadcast) {text, media, audio(with waveform)} ([#249](https://syauqi-ali/issues/249)) ([cba9827](https://syauqi-ali/commits/cba982785159ff10816ee067363031644c4e197d))
* Whatsapp v2.2329.9 proto/version change ([#169](https://syauqi-ali/issues/169)) ([a84f75e](https://syauqi-ali/commits/a84f75ef2a3af231454efca28bdf3d590a751812))



## [6.3.1](https://syauqi-ali/compare/v6.3.0...v6.3.1) (2023-07-08)


### Bug Fixes

* added invite property ([#218](https://syauqi-ali/issues/218)) ([1ef0ab0](https://syauqi-ali/commits/1ef0ab01aaf9bb46e70edea4259b835070f92922))
* Added jid of people who added to the group ([#223](https://syauqi-ali/issues/223)) ([c2d88fd](https://syauqi-ali/commits/c2d88fddc605f07f4d6990e0d705e3e65140d439))
* fix edit message ([#192](https://syauqi-ali/issues/192)) ([8e1e9b9](https://syauqi-ali/commits/8e1e9b9386af7d36601a35eb7ca327eefd36efc8))
* Fixed ephemeral message visual bug ([#185](https://syauqi-ali/issues/185)) ([a683cbe](https://syauqi-ali/commits/a683cbe633eccaa961852b49aa80dc41c54b17a8))



# [6.3.0](https://syauqi-ali/compare/v6.2.1...v6.3.0) (2023-06-17)


### Bug Fixes

* added @adiwajshing/keyed-db to dependencies ([#146](https://syauqi-ali/issues/146)) ([eb744a4](https://syauqi-ali/commits/eb744a4fc39e8bfffc20e3932763d61ae35a09e7))
* cannot find module "@adiwajshing/keyed-db" ([#124](https://syauqi-ali/issues/124)) ([6ed9298](https://syauqi-ali/commits/6ed9298d960c2a14eeaa7b42206119a6693857fd))
* Fixed In Memory Store: contacts.upsert handle ([#144](https://syauqi-ali/issues/144)) ([aa9872b](https://syauqi-ali/commits/aa9872b039d9f872267b0f2dba60bdede3b45b14))
* Fixed redirects in link-preview ([842b372](https://syauqi-ali/commits/842b372778c7060e93f45f9255d670b53a10c272))
* Fixed typescript build at chat-utils.ts file ([#118](https://syauqi-ali/issues/118)) ([2f438a6](https://syauqi-ali/commits/2f438a65394e92a0187083bf7cab0384a75f3691))
* Re-added the option to use proxy agent forn non-mobile api ([#148](https://syauqi-ali/issues/148)) ([54f8215](https://syauqi-ali/commits/54f8215eef2ec8911ac0fd71bdf5e2a362f98fcb))


### Features

* add contextInfo support ([13c3b91](https://syauqi-ali/commits/13c3b9185254a53dda2ad31bda3d73424781fa0c))
* Added makeCacheManagerAuthState Implementation ([#109](https://syauqi-ali/issues/109)) ([df6b318](https://syauqi-ali/commits/df6b31847282c10b884c69ffe39ca0e93a76b603))
* approve, reject, list request join ([#117](https://syauqi-ali/issues/117)) ([7dc1cd6](https://syauqi-ali/commits/7dc1cd64766b41f4fc9a3210777533e16fede94f))



## [6.2.1](https://syauqi-ali/compare/v6.2.0...v6.2.1) (2023-06-07)


### Bug Fixes

* updated proto/version to v2.2323.4 ([#96](https://syauqi-ali/issues/96)) ([63575e9](https://syauqi-ali/commits/63575e9b85520bd7621bd16ac0508cdd523a3a43))



# [6.2.0](https://syauqi-ali/compare/v6.1.0...v6.2.0) (2023-06-07)


### Bug Fixes

* auth store transactions + tests ([4a2db5a](https://syauqi-ali/commits/4a2db5a033e507a630a1d5b96a4779cc6f0f84e9))
* mobile app state key + message events ([a6640bb](https://syauqi-ali/commits/a6640bb0f651a194cfc1e847b7e8eff47f51777d))
* socket options ([6ecc5a8](https://syauqi-ali/commits/6ecc5a87578f3c15a13cfedc4278daa1b0dfaaa1))


### Features

* add md-msg-hist to MEDIA_PATH_MAP ([5c5b23e](https://syauqi-ali/commits/5c5b23ec85983963d4d797e1437eca4808ad76f7))
* add native mobile api docs ([844de43](https://syauqi-ali/commits/844de431a30f39d4b160c9fac8b6efd6677f9034))
* fetch groups if ib:dirty ([07562c2](https://syauqi-ali/commits/07562c220473237e9575b8cd5b0e7ea6b05b5b26))
* native-mobile-api ([ef673f6](https://syauqi-ali/commits/ef673f62ca29c4bf3f2b8a60ba16a0bd13d86862))
* update baileys-version.json to 2.2322.15 ([#91](https://syauqi-ali/issues/91)) ([534b1ea](https://syauqi-ali/commits/534b1ea778152fa77bee47da291e1f3f5c153091))
* use axios and config.options for registration ([c2bff56](https://syauqi-ali/commits/c2bff56054f58905a1efbbc69ac76fb3e0446d84))


### Reverts

* example logger ([d9a4dae](https://syauqi-ali/commits/d9a4dae23580444b87384f62d71b4d78fd84df4d))



# [6.1.0](https://syauqi-ali/compare/v6.0.1...v6.1.0) (2023-05-26)


### Bug Fixes

* Fixed installation from Yarn v2 (close [#41](https://syauqi-ali/issues/41)) ([5ff88d8](https://syauqi-ali/commits/5ff88d82a17062ab3446712d8cd9c6d48b1d7ac8))
* onWhatsApp query for multiple jids ([#85](https://syauqi-ali/issues/85)) ([bb25723](https://syauqi-ali/commits/bb25723b6ac019ec790c22b95738cc14a725f32a))


### Features

* **labels:** add label association types ([00a7b48](https://syauqi-ali/commits/00a7b48749b378332c8bd216628195214124aa49))
* **labels:** add label entity ([534ea17](https://syauqi-ali/commits/534ea174b959dcca699e9e655d54936872688aff))
* **labels:** modify chat utils ([38f2857](https://syauqi-ali/commits/38f285760df426314b75ed752f1edcd6f23e9d23))
* **store/labels:** add ability to store and query labels ([ce019dc](https://syauqi-ali/commits/ce019dcf0f0e3c3f1a8c57b776aa5fe39854b598))



## [6.0.1](https://syauqi-ali/compare/v6.0.0...v6.0.1) (2023-05-18)


### Bug Fixes

* get poll request from getAggregateVotesInPollMessage in v1 v2 v3 ([#74](https://syauqi-ali/issues/74)) ([7f60f16](https://syauqi-ali/commits/7f60f163e667b3aee769b1624adc4abf057502ba))
* In memory store: normalize user when asserting message list to update messages ([#49](https://syauqi-ali/issues/49)) ([7b4abcd](https://syauqi-ali/commits/7b4abcdb231434c08c14dbb5879cd1fd4939fc41))



# [6.0.0](https://syauqi-ali/compare/v3.5.3...v6.0.0) (2023-05-10)


### Bug Fixes

* "receivedPendingNotifications" not firing on zero offline notifications ([7d174ca](https://syauqi-ali/commits/7d174ca77b3993b0f17c6215b934a35d026b4377))
* `undefined` on unpin action ([#1551](https://syauqi-ali/issues/1551)) ([767120a](https://syauqi-ali/commits/767120a555e7dd7145019f28462991fdad43a927))
* 10x better compression for image thumbs ([9f8223d](https://syauqi-ali/commits/9f8223d46bc1b8deb1e1e0cc7fdc7eb334a1060d))
* acc signature ([fda266f](https://syauqi-ali/commits/fda266ff734303abb1ae264f51ef5b48ee23b89a))
* account for 0 messages in stanza ([27cf395](https://syauqi-ali/commits/27cf3954e8926313153d5be87b057770f6408842))
* account for missing owner prop in legacy ([e7c2d4e](https://syauqi-ali/commits/e7c2d4e117925f16967de86810775e22d035ef5a))
* account for no initial state while patching ([94df582](https://syauqi-ali/commits/94df5826f816cae6a167e66f1db2e74ea05cce1b))
* ack all calls ([669fcaa](https://syauqi-ali/commits/669fcaa43864522d38503f18e45563271101ccbf))
* ack before sending retry receipt ([bd6be89](https://syauqi-ali/commits/bd6be89d57b7898fba5d343aef42ef214109e1fb))
* ack for participants on MD ([dac5a63](https://syauqi-ali/commits/dac5a63ff98fa41d4cb287779f485970a880e645))
* ack receipts ([5120f1d](https://syauqi-ali/commits/5120f1d1e419c7fadef7b35a04974dbd7c3bb4d8))
* add "offer" call ack ([d5e3d04](https://syauqi-ali/commits/d5e3d049c4d53cbad71c636106fac4e4c60ca5b0))
* add `senderTimestampMs` automatically in reactMessage ([#1845](https://syauqi-ali/issues/1845)) ([200b75d](https://syauqi-ali/commits/200b75d53ef71f778eafe48e391f4a37b7e1d6d0))
* add history msg to creds.update to prevent race condition ([e547310](https://syauqi-ali/commits/e547310a193f4f88ecec2e37b6bbed0af6d49617))
* add legacy constants for decoding ([3c278b3](https://syauqi-ali/commits/3c278b35f038365e05a0266926c7efbb4ebb8ee3))
* add missing "isLatest" flag ([b125638](https://syauqi-ali/commits/b125638253a1176d26699707e77de4c5ab913173))
* add missing isAnimated flag ([#1767](https://syauqi-ali/issues/1767)) ([084c39c](https://syauqi-ali/commits/084c39ca7338196b901aa98270ab40beaf7edbb4))
* add more escape chars for multi file auth state ([a0548fb](https://syauqi-ali/commits/a0548fbc4c2c444a21d047e81f0405f80bcc4382))
* add option for appStateMacVerification ([4aadc9d](https://syauqi-ali/commits/4aadc9dc6c63b4e7be4de095a092316955cd4c2d))
* appstatesyncdata in multifileauthstate ([24a2b41](https://syauqi-ali/commits/24a2b4150a2d6041ee98af9b29dca37ee86b92cb))
* auth store transactions + tests ([d02066d](https://syauqi-ali/commits/d02066dec8f4b460b2f4539c5cba26dd12cec553))
* bad request on sending messages in some cases ([d9cfed6](https://syauqi-ali/commits/d9cfed64ff668426e8419a3dc565c51747422a79))
* better registration ID ([3717854](https://syauqi-ali/commits/37178547ba6f4a6bd718d5b40693efce40335277))
* better WS error map ([6c4f632](https://syauqi-ali/commits/6c4f63237f65a1a3dfe8bebd7692910e9e45df58))
* browser version ([fe9a6d0](https://syauqi-ali/commits/fe9a6d07ae9b14beedae8561f2469358b98aa4d2))
* BufferJSON failing with empty string ([c00c3da](https://syauqi-ali/commits/c00c3da313922c20385015314981e2ea571f3123))
* buttonText should be optional ([ed4f234](https://syauqi-ali/commits/ed4f234fd82761a68440bebc929dda4ff32271fc))
* catch promise rejection on presence update ([9424d04](https://syauqi-ali/commits/9424d04f5d716f9a9d305c9771266c9030359cf7))
* catch unexpected errors on MD ([13b0da0](https://syauqi-ali/commits/13b0da095478e0fa08922c92e350b95f0481b50b))
* catch unknown user action ([2696af4](https://syauqi-ali/commits/2696af4da1fa62639ea60043b3b33837412d9f9b))
* chats.delete patch on sync ([41ca76a](https://syauqi-ali/commits/41ca76a0af74b1fe994d70b4e8840c34f9afd6bc))
* check for content in "isRealMessage" ([02f9df5](https://syauqi-ali/commits/02f9df5de4ca7948ad505bff935598f2b03ddf58))
* cleanMessage for reaction messages ([4ea2c33](https://syauqi-ali/commits/4ea2c33cfa6faeec8ff7908c8f7d01fb074be4d2))
* clear debounce timeout on close ([89a159a](https://syauqi-ali/commits/89a159aac3116282c5df75add2bd598aa57e29dc))
* correct operation type on chat patch ([7b42fa5](https://syauqi-ali/commits/7b42fa5a54ed71c28e4992db4adc38779e6d909d))
* correct verify ([b68efb1](https://syauqi-ali/commits/b68efb15b67b398ae8d2205945b5e63adbf64a4e))
* correctly check for image processing lib ([35b7a31](https://syauqi-ali/commits/35b7a310a40bcf8ca57e7995b331a3a8e6effec2))
* correctly check isLatest ([696fe0d](https://syauqi-ali/commits/696fe0de9fcd75e25d1cee9aff3fda39c93e775e))
* correctly clear qrTimer ([ba3cbd4](https://syauqi-ali/commits/ba3cbd476ebdeaf52b7cb919cfc34eb6e5995513))
* correctly copy msg for forward ([c1301de](https://syauqi-ali/commits/c1301deda00c55465e0e9e56fb0e410d805d88fc))
* correctly create product ([3131f2a](https://syauqi-ali/commits/3131f2aa353b96c9a3bbe6939cd2eaa28cccaa27))
* correctly extract media content ([24dd767](https://syauqi-ali/commits/24dd76771eabe11c2804052dd87dd5b0a834082e))
* correctly fire product edit ([ebd92e0](https://syauqi-ali/commits/ebd92e033711cb6f91b1ef06ecb66d21a1b8b8e8))
* correctly generate quoted msgs ([4a8c6ed](https://syauqi-ali/commits/4a8c6ed66de43d3df8d8ad032dbd2d74e0878d63))
* correctly handle deleteMessageFromMe ([dc07d31](https://syauqi-ali/commits/dc07d31dc7045bb6c64f3427a679580359c94f73))
* correctly handle devices & encrypt notif ([ae94e0a](https://syauqi-ali/commits/ae94e0ac38e00bf86c1f87b5ca0f65c68f1e6887))
* correctly handle receipts fromMe ([f2859e5](https://syauqi-ali/commits/f2859e53871a4ca14165f9646a25ff6f052b8090))
* correctly handle retry from own devices ([ef1b01b](https://syauqi-ali/commits/ef1b01b6df0e3c10f139c57aa842cbc5aec245e7))
* correctly map left group notification ([088bae4](https://syauqi-ali/commits/088bae44e801d72b29ebade263880a6e2e63ac3a))
* correctly parse protocol message ([9ca4663](https://syauqi-ali/commits/9ca46635d608ebcce4337dd0b6074f30c7808702))
* correctly respond to retry requests ([442489f](https://syauqi-ali/commits/442489faaec8f98838dee7969c0f1d3304270062))
* correctly set latest message in chat + lastMsgRecvTimestamp ([c20865d](https://syauqi-ali/commits/c20865dff1d45042fd70f8ac8605fd81de22b557))
* correctly set reaction msg key ([66f49e0](https://syauqi-ali/commits/66f49e0b3d6613ebd2de49778e77585ac0c142e9))
* correctly sync app state ([a5d263d](https://syauqi-ali/commits/a5d263d31be7f3244d399aa6c9c5e4e65380e8f1))
* curve verification return boolean ([40abd71](https://syauqi-ali/commits/40abd71d2e8ee75f10e251b037eefd4a7c31cd88))
* deadlock on processNodeWithBuffer ([9e3c208](https://syauqi-ali/commits/9e3c2082de288ad680224e32ae3098cc029b50bf))
* decode app state key correctly ([0650c10](https://syauqi-ali/commits/0650c10c736a6b386700b29c7ab664b4203cd3d4))
* decrypt race condition ([01a641d](https://syauqi-ali/commits/01a641d3bdffd21d9f92489d9a749c7ae05afabf))
* delete chat + star message actions not syncing ([7b8390f](https://syauqi-ali/commits/7b8390f1ca80b962e35887aac334bf1efe04acc1))
* delete chat on legacy ([4710f66](https://syauqi-ali/commits/4710f6603ad4bd5f23954a997adc0a3b9eb1a6d2))
* Delete Message For Me ([#1718](https://syauqi-ali/issues/1718)) ([e7087ca](https://syauqi-ali/commits/e7087cabf5aed941b290a9fab45845e535f02a1d))
* delete tmp file if failed enc ([cc1fc9a](https://syauqi-ali/commits/cc1fc9a53cdbb3785947d68938782bf2ac5727bd))
* delivery receipt ([7ffa10a](https://syauqi-ali/commits/7ffa10a5c5aa6d35e26ac886132a2100c6e7d34d))
* delivery receipts ([609c925](https://syauqi-ali/commits/609c925225843220e3a47deeba6607300a825a3f))
* desc for groups ([6c3958b](https://syauqi-ali/commits/6c3958bb16596bebb8f2097b0fce1f5a966c7d6b))
* detectLinks was not being used as described in docs ([#1922](https://syauqi-ali/issues/1922)) ([847a1dd](https://syauqi-ali/commits/847a1dd5717089ef3b3431784d0c5b52f1589378))
* different passive settings for reg + login ([5f3db19](https://syauqi-ali/commits/5f3db192dca1fb0110fcd83f197f0fd551c0ba4c))
* do not add "reason: identity" for details fetch ([1dc5d4e](https://syauqi-ali/commits/1dc5d4eae063c41cac62909dee45947301c407b3))
* do not add default check for sharp ([b05ce25](https://syauqi-ali/commits/b05ce25dfa3aa28151ce57c939d4bde76380c568))
* do not add to pre-buffer if waiting for end ([a589e88](https://syauqi-ali/commits/a589e881366eb6110ddbb0a3c2533d48a9e59202))
* do not call REMOVE op for mutations ([eac75af](https://syauqi-ali/commits/eac75afbe21d8304563548424250054264fa30d0))
* do not fetch empty ID list on transaction ([13b49e6](https://syauqi-ali/commits/13b49e658dd1ea75873fbde463e68593749080c9))
* do not fire chat update for reactions ([b933970](https://syauqi-ali/commits/b933970d51e405da08e0b2b59c8077f74c7f075c))
* do not fire presence update without name ([54d31ed](https://syauqi-ali/commits/54d31edc1db14a8de7daa49c18d034c499005061))
* do not generate preview if title not present ([26828d3](https://syauqi-ali/commits/26828d3dea46d78397a77f667b2f4f3f34db5de6))
* do not mutate update object reference ([284c7e7](https://syauqi-ali/commits/284c7e781288671aab43d9f3fd3fdecfc5d0bb5f))
* do not retry not fromMe ([2b33a52](https://syauqi-ali/commits/2b33a5202c0001e7e5e98506bf009cfad0c92f37))
* do not send accountSignatureKey in retry ([fad63f1](https://syauqi-ali/commits/fad63f1fd2a5e1801c16dfbd48f8f0ae0a9ae50d))
* do not throw error on conditions not matching in lastMessage check ([dba6d2e](https://syauqi-ali/commits/dba6d2e0cbfe0dc27ee23e46bc14776ce39ebe8d))
* do not throw error on missing message for retry ([cccd930](https://syauqi-ali/commits/cccd9305a26003cafaeff197066981ad66730eb8))
* do not update chat + contact on prepend messages ([da65ae8](https://syauqi-ali/commits/da65ae8f42d169436a74e526db29050309275922))
* download on axios ([db941f1](https://syauqi-ali/commits/db941f147278f64b473653b2691242b257eba93e))
* dup close events ([c982d8c](https://syauqi-ali/commits/c982d8c3a0fd963262eb5f3ec876ab1510856b53))
* duplicate mutation release on failed patch ([f892a1e](https://syauqi-ali/commits/f892a1e81f7ad14818858cb9f7d982e2e578addb))
* emit messages.update on successful reupload ([f62898d](https://syauqi-ali/commits/f62898dee7e37a591a79075bde2ff83609a38636))
* empty messages upsert event on history sync ([e142f0b](https://syauqi-ali/commits/e142f0b76ec46eb62d74cde8d7bc1de19b289111))
* ensure media cache does not override caption & other properties ([03f3385](https://syauqi-ali/commits/03f33852dfb76e521d483f3cec24cd54f7e6f1f3))
* ephemeral toggle not being applied correctly on legacy ([d09025e](https://syauqi-ali/commits/d09025e8dd6339312cf3818481ea54c97774381c))
* error in type ([1550fc5](https://syauqi-ali/commits/1550fc5ce60deb710710b522748be7d77ec2ca6a))
* example ([80b9e74](https://syauqi-ali/commits/80b9e74066fb1f2c3111663c664b974a35eb523d))
* example TypeError ([7d72498](https://syauqi-ali/commits/7d7249887c020e17f2467416c0eddd2f3fafddb5))
* exclude emails from URL gen ([a4208a4](https://syauqi-ali/commits/a4208a4bf68dca7b276ace41c49241ab487e64d5))
* experimental patch to correctly identify end of offline notifications ([c2c27a5](https://syauqi-ali/commits/c2c27a5dea8a5bdd14e518ff94cf8b6d45ccc904))
* export correct processMessage function ([cc7c895](https://syauqi-ali/commits/cc7c89532001dd5a1f6428b52b928883901f006d))
* extract msg content correctly ([cd59b8f](https://syauqi-ali/commits/cd59b8fc9724fbc80f3ef175596ef0a895bbcb08))
* fetch order details on MD ([8a9de2f](https://syauqi-ali/commits/8a9de2f0429cbea022a6eb629e737f13c769d758))
* file not found in `unlink` ([2b854b3](https://syauqi-ali/commits/2b854b37e4f93632cee57eda723d11211568d373))
* fire "connection-update" on legacy socket create ([ae59d6e](https://syauqi-ali/commits/ae59d6e9c6ecc4d16b73ed13275fae18344b5ae1))
* fire init queries in parallel ([3cefad2](https://syauqi-ali/commits/3cefad2c8e13597ac34054c7f22888d00795fd57))
* fire init queries toggle ([19484e5](https://syauqi-ali/commits/19484e5cfced4c2d229687e74f714534375a57a3))
* fire presence when name is recv ([6637e32](https://syauqi-ali/commits/6637e32be979be7130250140c8c4d7501314afd4))
* forward message content ([d192ffe](https://syauqi-ali/commits/d192ffe6bc9d96011a6222ba85005dc2f40b969c))
* getChatId ([41851d9](https://syauqi-ali/commits/41851d9e34e43029134a89ceabce528422d1faff))
* give preview even if thumbnail gen fails ([be535f0](https://syauqi-ali/commits/be535f0a34934985082524e7d77987895943f03b))
* group cipher signatures ([2eea17f](https://syauqi-ali/commits/2eea17fe9f8a0e875d59ac8f762435e9c3238416))
* group metadata mapping on legacy ([1af46bf](https://syauqi-ali/commits/1af46bfb3d091024cf7ea169c453006479d82a7a))
* handle case with 0 app state sync keys ([09b3815](https://syauqi-ali/commits/09b3815d89fd44a7404da628deb28af99fb33c68))
* handle errors in validateconnection ([3977444](https://syauqi-ali/commits/3977444bc5b1f701c41014dd107549f0d8e7e817))
* handle receipts more accurately ([59f834c](https://syauqi-ali/commits/59f834ca39e6272ff75091cb905edfbba7a375b9))
* handle when buffered tasks fail ([8d6e00e](https://syauqi-ali/commits/8d6e00eab60f70ddbed6f8b1921c26a0f52ab13e))
* history sync missing contacts ([93262b3](https://syauqi-ali/commits/93262b38f4a519c754af7cc98795005d4d201611))
* include [0] byte when encoding on MD ([43df500](https://syauqi-ali/commits/43df500899818706f06069dd08d59f2476bc0760))
* include accountSignatureKey in retry requests ([31b54ec](https://syauqi-ali/commits/31b54ec7c33d5fce11b1fe606db4a968ab9d2780))
* include isLatest in events ([09553de](https://syauqi-ali/commits/09553def8aa9210fd5ce0543cc69aabb5ae4f2c8))
* incorrect enc msg detection ([af08040](https://syauqi-ali/commits/af0804048c7e68abe3032de6e0d71019c47a6c09))
* incorrect from me ([6c08f0c](https://syauqi-ali/commits/6c08f0cd76077fbeb0f1cbe2792e86ae8104f047))
* incorrect group owner ([1cd96ad](https://syauqi-ali/commits/1cd96ad0390897fe0bc2652e16f87db388446ac3))
* incorrect updates being forwarded to messages.update ([b9d37a0](https://syauqi-ali/commits/b9d37a06a3ac5723765d01fedc43e89d280de0d6))
* isLatest flag ([8742bc2](https://syauqi-ali/commits/8742bc2fd5b927f0e72ebe4698d6c8315d3af4e7))
* jidNormalizedUser should not throw TypeError ([b0a7561](https://syauqi-ali/commits/b0a7561726d69c94652af048bd5e701fb9dbe92a))
* jimp thumb gen ([733345b](https://syauqi-ali/commits/733345bb959f282da61665e022756431c0a9d88c))
* listen to all failure messages ([3c6edde](https://syauqi-ali/commits/3c6edde1d61af6619dd0eedefd8e286de4ab0d4d))
* log failed app syncs ([070722f](https://syauqi-ali/commits/070722fcac6c84b713fccd83a22afc68fe5078da))
* logout error when not logged in ([9f19666](https://syauqi-ali/commits/9f196663e8aec704de7d89b587172d3b3293d063))
* LT hash computation failing ([b433248](https://syauqi-ali/commits/b4332488b833f1a079d89636eb1a09293050dee7))
* map eph duration on legacy group metadata ([4ac39d7](https://syauqi-ali/commits/4ac39d72ff59a495a81a03e629bbe1e8c463fd77))
* media cache ([3713646](https://syauqi-ali/commits/3713646980d1b6e6c2283254b1c5bf3d8b1a3d52))
* media cache throwing error ([3173e0d](https://syauqi-ali/commits/3173e0d034cd446be131d6cab71008bfc45f1c19))
* merge conflict errors ([d8b415a](https://syauqi-ali/commits/d8b415a075079d05e93f617dcc58c6293e178b96))
* message ack on group messages ([05b3095](https://syauqi-ali/commits/05b3095bfdf9b24beb5816a25820177d1716b37a))
* message delete not reflecting correctly for others ([5febb86](https://syauqi-ali/commits/5febb86e14e12064173b9565637080944af38b94))
* minor retry logic cleanup ([9ed4c28](https://syauqi-ali/commits/9ed4c28b8ebd4651541fc084ce052318efef76ed))
* msgs not appearing in chat ([5e28d23](https://syauqi-ali/commits/5e28d2346078cf7d101e5ce1792589d3b90ccb6d))
* mutex app state sync to prevent race conditions that log connection out ([bb5f13d](https://syauqi-ali/commits/bb5f13d188e1dc044e6e091bfac87b40f677038f))
* NaN last seen ([dfc030b](https://syauqi-ali/commits/dfc030b453d65dc547f12711acbc53b5ea3f33a0))
* normalize participant in last message ([ebf4aa6](https://syauqi-ali/commits/ebf4aa6772f886d35d949b1232deadbf1412f5d3))
* normalize participants API ([85a58fb](https://syauqi-ali/commits/85a58fbc10caa92e726044336a7e6ff3f562fc62))
* only fire valid events ([4c800b9](https://syauqi-ali/commits/4c800b95d149ad083a4a3371b109048fccf0cbda))
* only generate urlInfo if not provided ([d5e46b7](https://syauqi-ali/commits/d5e46b784bcd0496d7e17d12a998f55f3ffdd436))
* only send receipt if participant present ([a75d911](https://syauqi-ali/commits/a75d9118bdc7829a12dcb5f758dc5f92528a272d))
* only sync app state on one batch of history ([e93e6e2](https://syauqi-ali/commits/e93e6e26561274c664f22dbfd5a8c65f887ebd59))
* only update last account sync when required ([ad9314c](https://syauqi-ali/commits/ad9314c1f2dfb16fa8ead9fb76ebda0a7617d8bd))
* participant count ([729f19e](https://syauqi-ali/commits/729f19ef3eb93a086405f5341587d55513e1d5d9))
* patch proto sync receipts ([64bab02](https://syauqi-ali/commits/64bab02b7cf9e9c8bb5ba49fdbe6481f4f94bf9b))
* pin modification ([5e94a2b](https://syauqi-ali/commits/5e94a2b6e3a6011a437b455e1a5a416eb13c0363))
* possible ack fix ([cfa7e8e](https://syauqi-ali/commits/cfa7e8ec66aab05baa30aeb1e167d149528f9f52))
* possible ack issue ([d5b857a](https://syauqi-ali/commits/d5b857ad61a68fbc6b03383a908e7c67e4d526db))
* possible leak on waitForMessage ([b91a1cb](https://syauqi-ali/commits/b91a1cbcf30b6170fd1097fc6668f3e0584fb4ed))
* possible typeerror ([4962070](https://syauqi-ali/commits/4962070c2943febc5f3a2a039137dc8cd8affad6))
* possibly more accurate receipts ([4edfc75](https://syauqi-ali/commits/4edfc7531b7a9c0c64d6d21193dcc2dcd6a1def7))
* prevent duplicate frame emit ([21f163d](https://syauqi-ali/commits/21f163d6cf44a29ee85bf3886410d4349376b240))
* prevent duplicate receipts on multiple messages recv in stanza ([cff2b14](https://syauqi-ali/commits/cff2b1427abd010f7fae1ae20b4b18a34b7f5d94))
* pub key type is buffer ([5a3ef65](https://syauqi-ali/commits/5a3ef65e50762e763358f54b90b52825a6c0328b))
* reaction message doesn't appear when send to a group ([#1700](https://syauqi-ali/issues/1700)) ([bd98b13](https://syauqi-ali/commits/bd98b138959875a4bd0213027907fe1b5bdcd782))
* reaction sender map ([4e85a10](https://syauqi-ali/commits/4e85a100432fdd76a8f473f0c61cedf66cdedc74))
* read receipts ([5a33fd8](https://syauqi-ali/commits/5a33fd85a4396ada752ef9b6b3d15015500e4638))
* read receipts not being available ([a0003f0](https://syauqi-ali/commits/a0003f0fe97572b4ebe37eef54898d4dbf96fa36))
* readonly chats on sync ([bf8ff6d](https://syauqi-ali/commits/bf8ff6d253b87254ada256a40930108ef836b42e))
* receipt not being sent on empty message ([1f86630](https://syauqi-ali/commits/1f8663092fa8ee7e3791e6f1636ac94e435249b1))
* redundant array ([3d56d61](https://syauqi-ali/commits/3d56d610aea28e09c73749416ba2e51dbde360cc))
* remove "connection.update" listener from ev instead of ws ([49da0e4](https://syauqi-ali/commits/49da0e4e71255a69bb7426cda1c5c367395472f8))
* remove blocklist console log ([6eaed69](https://syauqi-ali/commits/6eaed6947032ca822b66fa3a8298352f938d9efa))
* remove dup eventemitter ([e9d90aa](https://syauqi-ali/commits/e9d90aa0a5cac9987fabfef632a92c8d020b9677))
* remove limits on max body and content length ([b191e1b](https://syauqi-ali/commits/b191e1b23a9a66d65c872f4f3c991aeb65ddfbfe))
* remove need for firstQR in socket ([4405905](https://syauqi-ali/commits/44059059d98305c99d326f9635db5d1e1448faa8))
* remove recipient from ack ([29bee92](https://syauqi-ali/commits/29bee92e792b5388b695f0a5a58cf656ea83e7b5))
* remove redundant chat updates ([030a534](https://syauqi-ali/commits/030a5346376e33b73141978ca82941820c718104))
* remove redundant console ([b988f42](https://syauqi-ali/commits/b988f4261fe4e9c2c91410744e68c65df0caca78))
* resync all collections on mainappresync ([aae2b7a](https://syauqi-ali/commits/aae2b7a55972f6018c55b8be327e6c922157539b))
* return mutations on patch ([a417d6d](https://syauqi-ali/commits/a417d6dc5abadbe5d74ee7c0375099ca1ae7744a))
* self read receipt on groups ([a06f639](https://syauqi-ali/commits/a06f639774ca78851007e21e8ead525da728190f))
* send init queries in queue ([dc50159](https://syauqi-ali/commits/dc5015996f63ff786e6c13851f07d154452e7de6))
* send unavailable if markOnlineOnConnect=false ([3b43153](https://syauqi-ali/commits/3b43153e92e6643247f326e9fd2baa7eab2cd34f))
* sending list of contacts ([6c4a9c7](https://syauqi-ali/commits/6c4a9c7354a6da393e9b4fbe9bc3104e14a5dfca))
* sending multiple contacts ([4f674d3](https://syauqi-ali/commits/4f674d3e2666ca2a49607b6bf05ee89ea9b6a10e))
* set "treatCiphertextMessagesAsReal" flag as default false ([7f7ae5e](https://syauqi-ali/commits/7f7ae5edbd6e30c01b66d190735cb09e60decc1e))
* set default status code ([92960bb](https://syauqi-ali/commits/92960bbf04ad4edc560914a6887774f29648e601))
* set remote jid on quoted participant ([0ef9ce1](https://syauqi-ali/commits/0ef9ce166d02d21e3e3704bd98a59f1f21fee665))
* signal curve key update ([ffe38b6](https://syauqi-ali/commits/ffe38b657aa730bfcf60d1e43d82ee4b98b918b9))
* stream destroy ([bd17f37](https://syauqi-ali/commits/bd17f3742e3c7e9e7c9285e501bc3900f7bdc957))
* stream errors not being handled ([7e9b9b7](https://syauqi-ali/commits/7e9b9b7f9aabbbd7f99de3c0a84c2997605f6eaf))
* temp patch for button/list messages ([9f3b00d](https://syauqi-ali/commits/9f3b00d58d4f6b1527db42069acafff01123cbf8))
* throw connection closed instead of WS error ([5624ecf](https://syauqi-ali/commits/5624ecf96c8a638ce8821d5755892232acfceff1))
* throw error if no decrypt-able message found ([913b384](https://syauqi-ali/commits/913b38493c863af7f8bac056a5664291512d36c2))
* timeout send call ([b2c1cfb](https://syauqi-ali/commits/b2c1cfbf9c0c665db1c708b159a9be9b9d9aa5cd))
* timestamp & other details not appearing + remove participant property from root message ([d2e3abf](https://syauqi-ali/commits/d2e3abfe49088777dcd20256be7f282868957638))
* toNumber ([0a331ce](https://syauqi-ali/commits/0a331ceab3b09d154c708e75a2be398664f86c4f))
* transaction not respecting null set ([110b9d1](https://syauqi-ali/commits/110b9d1f096fbb1591cab65bd918bb85ed812cf3))
* tsc error ([6bced98](https://syauqi-ali/commits/6bced9812818cfba19983b74acbde98b42ad9290))
* tsc error ([8c37ccf](https://syauqi-ali/commits/8c37ccf525a2e6ebcb1d2e05a67ec974cf1e9b6a))
* tsc error ([ed30e36](https://syauqi-ali/commits/ed30e368ad048edbb977098e672bf962e6aa934c))
* tsc error for DOM ([bacd046](https://syauqi-ali/commits/bacd046a4e977c859f6f100cc24aba7bfbeed8fb))
* tsc error in legacy version ([7b3fd7c](https://syauqi-ali/commits/7b3fd7c3c531160c343b0de2c0934c5e18c8d505))
* tsc issue ([070e24e](https://syauqi-ali/commits/070e24e3fd77a784e925c74334e1f18680b1f993))
* typeerror on no messages provided ([b3e0f26](https://syauqi-ali/commits/b3e0f26ec025a0b5eaf1c79b1ca8a3560b446268))
* typeerror on patch ([cea9e9d](https://syauqi-ali/commits/cea9e9da8a98664f91086af6f6c5fd9967acd323))
* typeerror on some group create ([49e7ad4](https://syauqi-ali/commits/49e7ad4b258026c2368e8a61bc76174e190a4bbd))
* typo in ciphertext check ([850611e](https://syauqi-ali/commits/850611e50084e7d0ec75c8a70c30848c8230c4e3))
* unarchive chats if reaction to my message ([e710ed9](https://syauqi-ali/commits/e710ed96f9e8b7b1c27b4c665fd6fd6c8d06e037))
* update MD mismatch error code ([ede40b1](https://syauqi-ali/commits/ede40b16f1de8616a62e4e576de7da4dea3bc1e7))
* upload for product ([765dcc1](https://syauqi-ali/commits/765dcc1d1f58619d1ce03547172fcb3bd91e4301))
* use correct ID for retry recp ([ac17225](https://syauqi-ali/commits/ac17225cf34fbfd8803d5873acbafac29c4e5975))
* use correct status code for throwing media error ([de95694](https://syauqi-ali/commits/de956942665ba19b34dff0495bb370737a4bbe59))
* use correct version in validation ([179db2c](https://syauqi-ali/commits/179db2c52018d29a42396168037d87dd251e2dab))
* use direct path in product img ([14def12](https://syauqi-ali/commits/14def126cf523264a09745c68dcd2393c4b79b58))
* use fetchAgent for uploading data ([9e33c80](https://syauqi-ali/commits/9e33c80add0b267631b1075f5644947ff40064dd))
* use handshake timeout ([64a6070](https://syauqi-ali/commits/64a60708459efaeef8cb866ab99af99ea595e897))
* use new registrationId function ([a4ae352](https://syauqi-ali/commits/a4ae3526de917a414d6feaba4512ce0857c76544))
* use normalized jid for messages ([9b86847](https://syauqi-ali/commits/9b8684701a8f022989a20d691cfff2c24ddc10ce))
* use semver for os build number ([0a02742](https://syauqi-ali/commits/0a02742060fbb2d45da82c46ff7457c23c47c238))
* use string values in business catalog ([0995b12](https://syauqi-ali/commits/0995b1231a689f1ffade0e2387a43dd22419b317))
* use tmp buffer for upload for multiple retries ([63c510a](https://syauqi-ali/commits/63c510a8691694f032f868d641fdab1610a1173c))
* validateConnection mutating account ([fae4aaf](https://syauqi-ali/commits/fae4aafdcdf2150e604991fbb0dec0c322936398))
* wait for pre-key upload ([5655cca](https://syauqi-ali/commits/5655ccaca7cf052b45aab7265021235b79464f09))
* xml-not-well-formed on +255 size lists ([#1762](https://syauqi-ali/issues/1762)) ([27f53bf](https://syauqi-ali/commits/27f53bfa5140081db818984d274190b4c394e98f))
* yarn lock ([8f8dba9](https://syauqi-ali/commits/8f8dba934460e7bfe57412852afc1e0e15525dcd))


### Features

* (hopefully) correctly implement account timestamp sync ([f5fcaa3](https://syauqi-ali/commits/f5fcaa36f3c4898dcc0f7f8c6e1f66e7005576ab))
* absorb existing message updates into upsert ([665e461](https://syauqi-ali/commits/665e461e83a8ea612b5056afa0bf097eb7eeefcc))
* add 'updateMessageWithReceipt' utility ([08cd253](https://syauqi-ali/commits/08cd253e90136418379ffe7d1351686e3ce578a4))
* add "--no-store" + "--no-reply" flags to example ([dda909e](https://syauqi-ali/commits/dda909eb0546396c8c970cb146924d0a48c73998))
* add "--no-store" option ([d399cbf](https://syauqi-ali/commits/d399cbf81075f36cd0bc9dfe7f9d5f9d981cc4c0))
* add "assertMediaContent" util ([4c51800](https://syauqi-ali/commits/4c51800b099750e4a6cfefc73ea5001fcabebf73))
* add "decodeMessageNode" util ([4f27a2b](https://syauqi-ali/commits/4f27a2b3f42b5f310edf3f3b00f6b15be6b9cdf0))
* add "device_fanout" flag for retry receipt ([399b4d3](https://syauqi-ali/commits/399b4d3cb82f87d4e6531ff513e921836e0d7f11))
* add "direct_path" to media messages ([d15dd6e](https://syauqi-ali/commits/d15dd6e1d2a65add35027d1690b413e2bcb20f83))
* add "getMessage" to example ([71a545e](https://syauqi-ali/commits/71a545e97221a119d1906c3c9f4901c87226c4a6))
* add "multi file auth state" implementation ([06437e1](https://syauqi-ali/commits/06437e182d095ff171f2a38f79c3bdabb93d1694))
* add "receivedInitialSync" connection update ([c76c2af](https://syauqi-ali/commits/c76c2afa0cb57a3da61a20f8e00191916f12167a))
* add "strictNullChecks" ([40a1e26](https://syauqi-ali/commits/40a1e268aaf4c89b0c08f7dc64725dda397cdfcc))
* add bulk "process" capability to BaileysBufferableEventEmitter ([5cc58d4](https://syauqi-ali/commits/5cc58d4aed961687264646c05102247b393cd1b6))
* add button reply ([32fadda](https://syauqi-ali/commits/32fadda86a79c1b114ab5b9954f676424d0af333))
* add check WA business account ([34f2095](https://syauqi-ali/commits/34f2095263a15dd93679f6dd804b00806a28e716))
* add clean message util before calling "messages.upsert" ([ebec029](https://syauqi-ali/commits/ebec02908c56abe240555699e01ac8ca6fa1e6f8))
* add contacts to chats.set event ([677f50b](https://syauqi-ali/commits/677f50baaa3e858242835e5e02ba2309980aa004))
* add custom host names ([792c4bf](https://syauqi-ali/commits/792c4bf0a42dcf142d9aa23b1477dfe4691d07ef))
* add custom patchMsg function + remove patch for btns ([b2aa51a](https://syauqi-ali/commits/b2aa51a13dd963f3926d0ee32cddae56253bd1d7))
* add delay between retry requests ([8d7fde1](https://syauqi-ali/commits/8d7fde1bf466c327221266a1c5d41bbe1d790540))
* add desktop + full history sync opts ([d04718e](https://syauqi-ali/commits/d04718e27a023b31fb2e5ad483755e71d865fd1b))
* add getContentType ([f09e0f8](https://syauqi-ali/commits/f09e0f85ccf93e47a7ca81a35df7928ed24623f4))
* add legacy connection ([19a9980](https://syauqi-ali/commits/19a99804921df46b19825b085ccc92c9f97c5de6))
* add lint workflow ([3160e35](https://syauqi-ali/commits/3160e35d9153c1449a79f106eb0415c0fbe98f0a))
* add listReply ([47900ea](https://syauqi-ali/commits/47900eae1433b72ade4009d688a9d26fdcbbaeaf))
* add logging event stream ([806138a](https://syauqi-ali/commits/806138a35e0d24a48498674f41e54cf6e5bca1bb))
* add makeCacheableSignalKeyStore util ([6735263](https://syauqi-ali/commits/6735263696472181de7d41b0b1f674c8d60451c5))
* add media retry for MD ([06ce5f9](https://syauqi-ali/commits/06ce5f9be055090ebd6f86dda638b2e43b8d1469))
* add message events for reactions ([9fee7fa](https://syauqi-ali/commits/9fee7faaf6d04c2d4a2396abfa16bf100d3fceac))
* add more logging to media ([9d7aec1](https://syauqi-ali/commits/9d7aec11dab7e7b3b753c71d62f232975d9c5b76))
* add more receipt types ([8addc71](https://syauqi-ali/commits/8addc714c7b6af683ff5e83fcc9312bc11b9ad26))
* add more sanity checks to chat patch ([87c1a04](https://syauqi-ali/commits/87c1a045033369868d7612b353093183cd679576))
* add newLTHashState util ([920e608](https://syauqi-ali/commits/920e60815b1087f2a4d4032c4abca017e07c3032))
* add nextPageCursor ([c96a765](https://syauqi-ali/commits/c96a7652d9165a162a1196e109864f96aa1c230d))
* add normalizeMessageContent util ([5c05a5d](https://syauqi-ali/commits/5c05a5d34b4527a86b4486a525a32a78fb9cdd15))
* Add notification group: change inviteCode ([704aa1e](https://syauqi-ali/commits/704aa1e434f90ede6132ffcb8fd6a78527bfe38a))
* add notification node type `picture` ([58b5df4](https://syauqi-ali/commits/58b5df4d4bfa2f6830b7b310bfa69c7e3256c5b0))
* add option to reupload in downloadMediaMessage ([cafc707](https://syauqi-ali/commits/cafc707628c2905cf43daff05bc18564093287c0))
* add option to set timeout between each qr generation ([f2917f0](https://syauqi-ali/commits/f2917f0a6d6ac3cfef7a7f11d42043e8a024015d))
* add option to specify limit for custom upload host ([9c0a3b8](https://syauqi-ali/commits/9c0a3b89629ea2e011d050840e857151282ec177))
* add product API for legacy connections ([d21a39c](https://syauqi-ali/commits/d21a39c3021807ce220cb483ea8cec75f8de9a82))
* add proto-extract script ([6c90241](https://syauqi-ali/commits/6c902411422d7bfb1f9a6ce152c573ac62152cd8))
* add reaction update to the store ([9e096c7](https://syauqi-ali/commits/9e096c731c3974004555131e16f3bd686ba4d1e5))
* add readMessages function ([5aa64f2](https://syauqi-ali/commits/5aa64f2c3967a89d22ae41c9db0c654e9a394da7))
* add replace type for messages.upsert ([5ae0b98](https://syauqi-ali/commits/5ae0b9863685f31f9fc8fd911894720fe6441cef))
* add retry capability to SignalKeyStore ([a8e2097](https://syauqi-ali/commits/a8e209705a6b711872cf7b2e2fa2ba83515f1fcb))
* add sanity check for chat modifications ([0d27fc4](https://syauqi-ali/commits/0d27fc467b2bf32ef9da0d06052e3c6d1c6f7972))
* add signal repository + tests ([fe1d064](https://syauqi-ali/commits/fe1d0649b5824416383ea8176758eeed28c9f5c1))
* add state sync keys in transaction ([e731de5](https://syauqi-ali/commits/e731de5deb7601e97b94e59de0aae530a3b25593))
* add support for "sharp" for image generation ([e51bbc4](https://syauqi-ali/commits/e51bbc489367d882caed06f92b712a3817bf814f))
* add timeoutMs to link preview ([68a6f34](https://syauqi-ali/commits/68a6f34cdea486613fcafa26ad77ebc097f5dd64))
* add toggle to download history ([9a39a46](https://syauqi-ali/commits/9a39a46398ed7b2fdf0446fa4216edad5a4506fc))
* add url options to link preview gen ([b33c753](https://syauqi-ali/commits/b33c753928a0dc25681b90e9ae3d6e5fe0fa45cb))
* add WA Web version auto fetch ([75582e4](https://syauqi-ali/commits/75582e4541e0682c4241556774889f312d86d82e))
* added played receipt ([bed9e38](https://syauqi-ali/commits/bed9e384ba6bac53203de785ddd329dd3f564e21))
* Added workflow to release at NPM site ([#48](https://syauqi-ali/issues/48)) ([7c3f0df](https://syauqi-ali/commits/7c3f0df560239c60699ac656d8fda1c039e9b332))
* allow downloading extendedTextMessage thumbs ([561163c](https://syauqi-ali/commits/561163c88d36a6c5329b117565162b68e28519c6))
* allow ignoring jids ([a58b73f](https://syauqi-ali/commits/a58b73fba54b033a64a02990ee969926a22885b9))
* allow meId in getKeyAuthor ([bda2bb4](https://syauqi-ali/commits/bda2bb471799c5f87b93b8e09f8b36f4b003b757))
* allow messageSecret as param to poll create ([cd42881](https://syauqi-ali/commits/cd42881201cc9fdb85a7196270365ed3c8d12b4d))
* allow passing of url info in text message ([5655961](https://syauqi-ali/commits/5655961d12552b676fe05fe1d7d08e2c27cb603d))
* async import got wherever required ([9474017](https://syauqi-ali/commits/9474017930d8e594928c9daa4df369ed09f45ac3))
* automatic upload detection for product images ([238cde2](https://syauqi-ali/commits/238cde23b770f511a9c19994c5c14338531f2cac))
* better mapping for WS errors ([c24ffc1](https://syauqi-ali/commits/c24ffc1bed322022bab2adcecf37e978f650a9f4))
* cache media uploads ([3e54741](https://syauqi-ali/commits/3e5474104213ba6e37a6951cbf2cb21b325e11e1))
* cache user devices ([dee8154](https://syauqi-ali/commits/dee815448b4d7fc9ec946b06533186fa487eb02b))
* catch groups create notification ([469f345](https://syauqi-ali/commits/469f3451d266464c85c2ff025a57c64dc6d5998e))
* cleaner auth state management ([3d0704a](https://syauqi-ali/commits/3d0704a317c1441789f0c995fc5748791167048f))
* cleaner auth state management + store SK keys ([2b8256d](https://syauqi-ali/commits/2b8256d56b234b01c5a0b9b569fe7c1239761a9a))
* copy in axios options headers to WebSocket ([f8fd5ec](https://syauqi-ali/commits/f8fd5ec0080e9f53288b96b0073212e53a40f57b))
* correctly handle presence being offline for receipts ([6824a20](https://syauqi-ali/commits/6824a203d03111e548ecfb21e100781ad7b2a459))
* correctly send retry messages w count ([4c60e31](https://syauqi-ali/commits/4c60e311f44cf0c92c0ba6984b7bcddb2ade38a8))
* customize link preview image width ([f421f5d](https://syauqi-ali/commits/f421f5d3876f9ff35f5f4f6559f976ec4a6ff1d6))
* debounced app state resync ([ced2f5d](https://syauqi-ali/commits/ced2f5d5ab5818a2fb97f5ea21a025f96d6c24e3))
* define DEFAULT_CACHE_TTLS ([090c916](https://syauqi-ali/commits/090c916f9f93e2c4b91b9af9d271d0be284491d1))
* detect when multi-device beta not joined ([d523bf8](https://syauqi-ali/commits/d523bf8981324634e18f19667f09c923766515b8))
* enforce default timeout to prevent any hanging promises ([6e830c1](https://syauqi-ali/commits/6e830c1e1b6af890407de9d2b401b5b10b4402f9))
* export resyncmainappstate ([79100a3](https://syauqi-ali/commits/79100a3164cf444c228b2ff4ffd2206d6797a1bc))
* expose axios options ([116b30d](https://syauqi-ali/commits/116b30dff059d60e8dea13687ffb4a3d67969f0a))
* expose isBuffering ([a4a48a1](https://syauqi-ali/commits/a4a48a196960d31c3f5ab20c10c270f6369206eb))
* expose sendRetryRequest ([4112c68](https://syauqi-ali/commits/4112c685564087fc10346c22654f14064121d494))
* extract code from WS error ([23acc1f](https://syauqi-ali/commits/23acc1fb39264b56c5cf62a66d0b15f1e10f4435))
* fire "receivedPendingNotifications" after flush ([f7b723f](https://syauqi-ali/commits/f7b723f97b4501574938499847663efddff06d6d))
* force include identity when enc is missing ([33851cd](https://syauqi-ali/commits/33851cdd55b8a9baa4a264c8bc30530a4652e0c2))
* functional legacy socket ([c803e22](https://syauqi-ali/commits/c803e22e8a143f118477f1dc3802e9bb0ba90496))
* generate high quality thumbs on link preview ([f0bdb12](https://syauqi-ali/commits/f0bdb12e56cea8b0bfbb0dff37c01690274e3e31))
* getChatId for broadcasts ([9591a02](https://syauqi-ali/commits/9591a02382cfc4bb9117ccaecccc66b1baa3e696))
* handle "peer_msg" receipts ([334f85f](https://syauqi-ali/commits/334f85f8c5fc4251ee94201965c7593a48d36990))
* handle bad message acks + send retry to all correctly ([721d0f3](https://syauqi-ali/commits/721d0f32d6025204d4b506fe58cd3c80f46f52e5))
* handle call events ([ae4aa67](https://syauqi-ali/commits/ae4aa67950dbcba1df96d252e0daaec5c33bfcc8))
* handle chat deletes + message stars ([59652a5](https://syauqi-ali/commits/59652a5368163700aba48014266f937268972515))
* handle default disappearing mode change notifications ([6663357](https://syauqi-ali/commits/6663357a37c6e295338cd82ecff5cabceeee1736))
* handle delayed myAppStateKeyId ([e1fc22b](https://syauqi-ali/commits/e1fc22b3d3b285d90b50187b246d93f783844e80))
* handle delete events accurately ([d143ef0](https://syauqi-ali/commits/d143ef0b7d3fe619dd58b5a5d488ca76ba6f760f))
* handle encrypt notification ([355b066](https://syauqi-ali/commits/355b0664df977df1e0402ea40f0661cd0b9386d7))
* handle failed msgs ([a4ecac7](https://syauqi-ali/commits/a4ecac788c9a90ceb570cb89007180fd16fa5ba1))
* handle futureproofmessage ([5041be7](https://syauqi-ali/commits/5041be776e9d905c3abb4d4a9965a6da0dfb9947))
* handle maxContentLength in downloading media ([4ba8283](https://syauqi-ali/commits/4ba828320e36d5cf936dc4a6eb11cca12084c66c))
* handle picture change events ([b329c73](https://syauqi-ali/commits/b329c73b208c8e61ae0fc64980aa64a68f98385d))
* handle stream:errors more gracefully ([211a899](https://syauqi-ali/commits/211a899ed4f56d85fc1acbb9439de8865ac4d777))
* handle unarchiveChats setting ([0d94315](https://syauqi-ali/commits/0d94315776b39e8d04bc7dcb782642c8f80e2aad))
* handle verified name in message ([fd80448](https://syauqi-ali/commits/fd80448fcb79705ec12a8e2df14552d5655fc88c))
* implement "groupAcceptInviteV4" add participant msg ([cacc1ce](https://syauqi-ali/commits/cacc1ce13085f888e80acab8dcc7ddb86eaa57cc))
* implement "snapshot" resyncing ([983b28b](https://syauqi-ali/commits/983b28ba0e40b1d1be8978311fc98e6d94f622ea))
* implement "treatCiphertextMessagesAsReal" flag ([93c8db3](https://syauqi-ali/commits/93c8db319ee56921de38cc15fe1f32046ed6f799))
* implement account sync ([d796b28](https://syauqi-ali/commits/d796b286a616b62ae6a104730292043d4bae7866))
* implement call ack ([d8c8d46](https://syauqi-ali/commits/d8c8d46adb6fc4ffd67aa9e477d25994cb789d78))
* implement event buffer for offline msgs ([7421f55](https://syauqi-ali/commits/7421f55daa526611fc85b8ca532a9878c4fe66a4))
* implement external patch parsing + app state sync on login ([ba453a5](https://syauqi-ali/commits/ba453a588be05825b76d90632e8876ad43d7c8c9))
* implement fetching product catalog + order details on MD ([c4edcef](https://syauqi-ali/commits/c4edcef5da575b675b04a7aed7826bd69528fca7))
* implement getAuthenticationCredsType ([127e21b](https://syauqi-ali/commits/127e21b92026b96bfc5c24eaaf28ff361ca7c3de))
* implement getOrder on legacy ([8a52eeb](https://syauqi-ali/commits/8a52eeb310ebafd6a124a8891c36bf066a5dac16))
* implement in memory store ([fb66733](https://syauqi-ali/commits/fb66733b61ddb1a0c851d621de59ee251770eb47))
* implement message retry handling ([78fd72c](https://syauqi-ali/commits/78fd72c8e509198aba73c509a990699de4fb57be))
* implement partial media downloads ([b5ac28d](https://syauqi-ali/commits/b5ac28d4263c665f2d373c67daf9376912844306))
* implement pin chat modification ([ddf6dab](https://syauqi-ali/commits/ddf6daba657f108df8644a7d29437dca6d389db4))
* implement privacy token fetch ([33fffc4](https://syauqi-ali/commits/33fffc4aadededba35483ff5b5959bba63fbaa54))
* implement product CRUD on MD ([6967e53](https://syauqi-ali/commits/6967e53164a80a624dd693dec99a310db2a5cb88))
* implement product message sending ([8a234e1](https://syauqi-ali/commits/8a234e107340e57fa8c000850882382b1cb8fb5d))
* implement stream:error events ([56c17ce](https://syauqi-ali/commits/56c17ce0d142c5393955eb8fa22fe3f603691e48))
* implement tc token handling ([572d0f1](https://syauqi-ali/commits/572d0f1dd60bc1c8e8ea7913d487e60a681485da))
* implement transactions on auth state ([f284217](https://syauqi-ali/commits/f284217d35d8352bcf8160df3818ac5b2ab10804))
* include chats.delete in example ([ba486f9](https://syauqi-ali/commits/ba486f93672225891169e2f6eb15f6bc1aadaf17))
* include correct browser version in connect ([2e61d04](https://syauqi-ali/commits/2e61d04d681d33b24a7ec747573436b8a7b5fe85))
* include last message in chat ([ee7ed1d](https://syauqi-ali/commits/ee7ed1d4e5d45e4e79a89e3e7173cf4db99e5cc2))
* include platform in creds ([7db8796](https://syauqi-ali/commits/7db8796fed2f1d1f47994abbe0065351ce77ae95))
* limit number of message retries being sent ([af7b2a5](https://syauqi-ali/commits/af7b2a5dd26202c16bc6308c605e78f7d432273a))
* link previews on MD ([872536f](https://syauqi-ali/commits/872536fa5bad590846866ddf8dd2855b66360ee8))
* log fromMe messages in trace mode ([98c9af4](https://syauqi-ali/commits/98c9af4acfb769925a28811875a8513723ed19af))
* log thumb gen errors ([64f3f08](https://syauqi-ali/commits/64f3f08adbaacb87c545c59d27d550cad08e393a))
* log timestamps in ISO format ([4b6e97c](https://syauqi-ali/commits/4b6e97cf93876549dfb97d4c2ae4b79b46055171))
* log updated disappearing mode ([a85698b](https://syauqi-ali/commits/a85698b20123f83ef7b8c384d81d03364d14180a))
* logout if myAppStateKeyId not present ([1b71072](https://syauqi-ali/commits/1b710729e538b4d483646d6db337f9caa3cc0483))
* map all WA media types ([3a891e0](https://syauqi-ali/commits/3a891e071edd8a46cc9dcfabfbdacd2940167c71))
* map template message content ([0da4621](https://syauqi-ali/commits/0da4621999ee591aa05a422b1b5c6825291b09f5))
* message reaction fix from other party ([46f3099](https://syauqi-ali/commits/46f309929b7db574c4a0217b830f0b558882cecb))
* more accurately handle app state sync ([5cb71ac](https://syauqi-ali/commits/5cb71ac862a789dbff352064628319516bfef736))
* more efficient message send ([e9f494e](https://syauqi-ali/commits/e9f494ec5db4884ac1a47df1795a30b5b46b5cb4))
* move conversation up when missed call ([6e0ac68](https://syauqi-ali/commits/6e0ac6899cbdfc0af2ad8a994afb7aa3a72870f9))
* move upsertMessage in processingMutex ([7f7565b](https://syauqi-ali/commits/7f7565b7a2e34de5b3ae42e9294e4d85709d040c))
* mutex processing in a chat to preserve order of events ([1f2a664](https://syauqi-ali/commits/1f2a6641f32d563ba8707997e6a13e60b94237fe))
* narrower definition of cachestore ([79aa2e5](https://syauqi-ali/commits/79aa2e5176a615727220725e23dfc60b2ed5971b))
* pass axios config to all axios instances ([ae3ac78](https://syauqi-ali/commits/ae3ac78dc3e02daba9b126157914ec5aa768c3dc))
* pass cachedGroupMetadata from sendMessage ([e131b7c](https://syauqi-ali/commits/e131b7c4d32f4e7b19b8a19c6c8edf4369e9fcb6))
* pass original thumbnail url in WAUrlInfo ([586db48](https://syauqi-ali/commits/586db48d2bd404a6645438997d20525724e8ca83))
* prevent urlInfo gen ([7951878](https://syauqi-ali/commits/79518787b6c33fcf0e878e4acf855d03c8e9dc95))
* privacy settings update functions and profile pic remove function ([#5](https://syauqi-ali/issues/5)) ([13810ec](https://syauqi-ali/commits/13810ec7ea3700ec0e1b676869a2522993827de5))
* process pollupdate automatically ([9d8aa67](https://syauqi-ali/commits/9d8aa67f22d5c9e1fba6205b779f9acb41b1eb54))
* push failed decryption messages as "CIPHERTEXT" ([2dfe5ad](https://syauqi-ali/commits/2dfe5adbe11997e4ea1813c673a413d65515b350))
* put entire mutation in transaction ([b7d8401](https://syauqi-ali/commits/b7d8401f626e9608c7183f07a50e25989bf08cd5))
* remove need for "serverHasPreKeys" ([75c637c](https://syauqi-ali/commits/75c637cf6cb5736a3b04d4c3b07be93c49ec0e29))
* reset ping timeout on any frame recv ([f82f547](https://syauqi-ali/commits/f82f5470cd2ebddb466dca59011c4daf25dc3e68))
* resync main app state on new key ([7288955](https://syauqi-ali/commits/72889551b9fd6d484c6507553a7cc92c490b5818))
* return og dimensions when generating thumb ([864a01f](https://syauqi-ali/commits/864a01f9a555bebd2fb683d97154987beefc0cf2))
* Returns an object with information about the invite code's group ([#1562](https://syauqi-ali/issues/1562)) ([227cab2](https://syauqi-ali/commits/227cab2f95396ae67756c1cf1489365e34fe76a6))
* send presence update when name changed ([f1b64c3](https://syauqi-ali/commits/f1b64c3c353ff67216de47c8b05175639f6ef8b1))
* support caption in document ([7f2384a](https://syauqi-ali/commits/7f2384a058282e6c203139d42ef371f4fd747a76))
* track history being stored ([5305730](https://syauqi-ali/commits/5305730d8255981ea9a9ff14a413e7e8e5fe1a9a))
* update proto ([2549d10](https://syauqi-ali/commits/2549d10be9b3ae4674822cd39ab5dd5e3a47f48c))
* update real msg logic ([b9d13a5](https://syauqi-ali/commits/b9d13a57d853ac4739f7b6072130db4c9ba8c72b))
* use (participant, ID) tuple for retry counter ([3490028](https://syauqi-ali/commits/349002857ea66b091e3f85f52c63e7b3cb6fd128))
* use futoin-hkdf instead of custom function ([5200bf6](https://syauqi-ali/commits/5200bf64775ea5cc3ca5b3790932acb9e4ca286c))
* use message receipt on MD ([57d6ab6](https://syauqi-ali/commits/57d6ab62a157eb7807b42a741ef7756818e0bd16))
* use store.loadMessage for getMessage in example ([af1d5f6](https://syauqi-ali/commits/af1d5f6a0167e8fc1ac34c0de2e0c69c7a9ff0e8))
* use transaction when uploading prekeys ([89e35ec](https://syauqi-ali/commits/89e35ec18a9f27c61f49d967d9d173f30552ff49))
* utility functions for poll updates ([d98d415](https://syauqi-ali/commits/d98d4156fe1e0bcf6f9f3bc4e4de2fe666232d4e))


### Performance Improvements

* avoid excess memory usage when syncing state ([f87f893](https://syauqi-ali/commits/f87f89329b467dca6472b5f24c505918bfcbdd01))
* do not resync on every reconnect ([aa3309d](https://syauqi-ali/commits/aa3309db3c20aa3965291a3c8c8f98237a8f53dd))
* experimental do not use fs for enc stream ([38a44be](https://syauqi-ali/commits/38a44be006d4d43c9a283bae026c21746fca5ee6))
* nicer "shouldIncludeDeviceIdentity" flag computation ([7863c0e](https://syauqi-ali/commits/7863c0e4c2baa1c19aaf7ca71ba67f05a7299b19))
* put main app state sync in transaction ([a21e3b0](https://syauqi-ali/commits/a21e3b0bacfdb9e5c53e13d029789b754c40da61))
* single process event for processSyncActions ([a07a63f](https://syauqi-ali/commits/a07a63fa2858bfd86dc1df48fa366a76a09057b7))


### Reverts

* Revert "temp: do not handle dirty account_sync" ([56139b2](https://syauqi-ali/commits/56139b2d0300cca388aff57459283a1c76f58ee3))
* Revert "chore: disable init queries" ([b3e8b38](https://syauqi-ali/commits/b3e8b38917fa86a0621832ecf743746675d22f62))
* Revert "chore: add WS ping" ([c4ffb2b](https://syauqi-ali/commits/c4ffb2bfaf4184dcdcfeabdf3b147b0a9e3d4cd2))



## [3.5.3](https://syauqi-ali/compare/v3.5.2...v3.5.3) (2021-11-15)



## [3.5.2](https://syauqi-ali/compare/v3.5.1...v3.5.2) (2021-08-09)



## [3.5.1](https://syauqi-ali/compare/v3.5.0...v3.5.1) (2021-06-16)



# [3.5.0](https://syauqi-ali/compare/v3.4.1...v3.5.0) (2021-03-24)



## [3.4.1](https://syauqi-ali/compare/v3.3.2...v3.4.1) (2020-12-31)



## [3.3.2](https://syauqi-ali/compare/v3.3.1...v3.3.2) (2020-12-08)



## [3.3.1](https://syauqi-ali/compare/v3.3.0...v3.3.1) (2020-11-30)



# [3.3.0](https://syauqi-ali/compare/v3.2.4...v3.3.0) (2020-11-17)



## [3.2.4](https://syauqi-ali/compare/v3.2.2...v3.2.4) (2020-11-07)



## [3.2.2](https://syauqi-ali/compare/v3.2.1...v3.2.2) (2020-10-29)



## [3.2.1](https://syauqi-ali/compare/v3.2.0...v3.2.1) (2020-10-23)



# [3.2.0](https://syauqi-ali/compare/v3.1.0...v3.2.0) (2020-10-11)


### Bug Fixes

* presence event when contact not exists ([eac324b](https://syauqi-ali/commits/eac324bc1cd234cd19ee803968fe82dd3d219b9c))



# [3.1.0](https://syauqi-ali/compare/v3.0.0...v3.1.0) (2020-09-11)


### Bug Fixes

* call loadMessages multiple times ([3d34a0e](https://syauqi-ali/commits/3d34a0e55c5fc8fcbbcabee30828f94d14ebd2e4))



# [3.0.0](https://syauqi-ali/compare/2.1.0...v3.0.0) (2020-09-02)


### Bug Fixes

* TypeError caused by empty chat ([07291d8](https://syauqi-ali/commits/07291d8ef69c886bd1aefb3b474a8b7553daebad))



# [2.1.0](https://syauqi-ali/compare/1.1.0...2.1.0) (2020-07-08)



# [1.1.0](https://syauqi-ali/compare/1.0.2...1.1.0) (2020-06-06)



## [1.0.2](https://syauqi-ali/compare/0.9.0...1.0.2) (2020-05-20)



# 0.9.0 (2020-05-09)



