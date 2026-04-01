# Changelog

## [1.0.0-alpha.30](https://github.com/incu6us/chain-sdk/compare/ts/v1.0.0-alpha.29...ts/v1.0.0-alpha.30) (2026-04-01)


### ⚠ BREAKING CHANGES

* **ts:** simplifies TxClient interface ([#210](https://github.com/incu6us/chain-sdk/issues/210))
* **ts:** adds SDL json-schema and refactors validation ([#184](https://github.com/incu6us/chain-sdk/issues/184))

### Features

* add EventAggregatedPrice ([#269](https://github.com/incu6us/chain-sdk/issues/269)) ([5c5cdea](https://github.com/incu6us/chain-sdk/commit/5c5cdea57bb1be7b8c1796e2f10d16064c2b013c))
* adds automatic fee calculation for transactions ([#150](https://github.com/incu6us/chain-sdk/issues/150)) ([0139d73](https://github.com/incu6us/chain-sdk/commit/0139d7347e0560e921860a4fe2eaf240955771f8))
* adds grpc gateway transport ([#71](https://github.com/incu6us/chain-sdk/issues/71)) ([581ed49](https://github.com/incu6us/chain-sdk/commit/581ed49930309a7177d2b71d76c7fd86c6ed5cef))
* adds possibility to specify cert serial number ([#274](https://github.com/incu6us/chain-sdk/issues/274)) ([5322905](https://github.com/incu6us/chain-sdk/commit/532290565a8a8112276372411480400431e7a409))
* allows uact denom ([#222](https://github.com/incu6us/chain-sdk/issues/222)) ([39e2329](https://github.com/incu6us/chain-sdk/commit/39e23295da6114afde9d5642907e3f4458ee9051))
* **bme:** add endblocker params ([#245](https://github.com/incu6us/chain-sdk/issues/245)) ([4f6a1d2](https://github.com/incu6us/chain-sdk/commit/4f6a1d2e2e1bf3f25af59bf89f24e18f24b999a7))
* **bme:** add FundVault rpc ([#250](https://github.com/incu6us/chain-sdk/issues/250)) ([bf19b1a](https://github.com/incu6us/chain-sdk/commit/bf19b1a7fe2a1e2f14987267efed547a1843476b))
* **build:** add ibc proto generation for ts ([#152](https://github.com/incu6us/chain-sdk/issues/152)) ([aa247f0](https://github.com/incu6us/chain-sdk/commit/aa247f05eb28c1a4414f26d97a1d116d9dbbd8e4))
* **code-style:** adds staged make code style targets ([5ecc2bc](https://github.com/incu6us/chain-sdk/commit/5ecc2bccb73e8b676190268b932dc686e61ce2b8))
* generate proto types index files and export in package.json ([#63](https://github.com/incu6us/chain-sdk/issues/63)) ([3ea9661](https://github.com/incu6us/chain-sdk/commit/3ea9661b01c6a62dbd34120ff45834f234aac964))
* **go/sdl:** add permissions params ([#200](https://github.com/incu6us/chain-sdk/issues/200)) ([38be010](https://github.com/incu6us/chain-sdk/commit/38be010ce056239b063ab9a66d70ad17b571ab24))
* implement ledger failed record for bme ([#255](https://github.com/incu6us/chain-sdk/issues/255)) ([4dc78aa](https://github.com/incu6us/chain-sdk/commit/4dc78aa46dd0538a2d7ce099e274ca47115581c4))
* implement ts code generation ([#184](https://github.com/incu6us/chain-sdk/issues/184)) ([#138](https://github.com/incu6us/chain-sdk/issues/138)) ([14b1f7d](https://github.com/incu6us/chain-sdk/commit/14b1f7d3992ee5834d59be0ba1dc62048131a13b))
* implements generate manifest function ([#225](https://github.com/incu6us/chain-sdk/issues/225)) ([6ad9d64](https://github.com/incu6us/chain-sdk/commit/6ad9d6488c8af74ae1a91783353469cbbb368964))
* include spread in the ledger records ([#262](https://github.com/incu6us/chain-sdk/issues/262)) ([48edd00](https://github.com/incu6us/chain-sdk/commit/48edd000a0186be1cf3791080817690538244c75))
* makes all query inputs to be DeepPartial and all tx inputs are required ([#70](https://github.com/incu6us/chain-sdk/issues/70)) ([d234f23](https://github.com/incu6us/chain-sdk/commit/d234f23e1fe2929d2c7b61794dcbef87ced0547a))
* makes tx options to be optional for chain sdk ([#84](https://github.com/incu6us/chain-sdk/issues/84)) ([a0da1a3](https://github.com/incu6us/chain-sdk/commit/a0da1a3f33cfb7e4980c97502fefa58c983ad980))
* **market:** add OfferPrices and BidMinDeposits to market proto ([#242](https://github.com/incu6us/chain-sdk/issues/242)) ([0433094](https://github.com/incu6us/chain-sdk/commit/0433094ddd9ca07e905a7d7c8b5b272fb267ea50))
* moves jwt auth from console ([#67](https://github.com/incu6us/chain-sdk/issues/67)) ([5a4372f](https://github.com/incu6us/chain-sdk/commit/5a4372f7e536e2674ed8cebae41b8b2e71efe4da))
* oracle api v2 ([#271](https://github.com/incu6us/chain-sdk/issues/271)) ([9bf1e08](https://github.com/incu6us/chain-sdk/commit/9bf1e0855620fd5b9a87a74268bbbbe4a3249131))
* **oracle:** add future time drift param ([#272](https://github.com/incu6us/chain-sdk/issues/272)) ([05f70f8](https://github.com/incu6us/chain-sdk/commit/05f70f8a40ee7d650f35c5aee4c0eefdf3908d79))
* **proto/node/market:** add reason explaining close if deployment ([#112](https://github.com/incu6us/chain-sdk/issues/112)) ([411e61a](https://github.com/incu6us/chain-sdk/commit/411e61a9c94c93138fd5803551d81c0b809519f3))
* **provider:** add BidScreening RPC and validation proto ([#243](https://github.com/incu6us/chain-sdk/issues/243)) ([1fadf95](https://github.com/incu6us/chain-sdk/commit/1fadf955bae5d60e4a79701ad1e7591d64f0b0a8))
* **ts:** add essential exports by versions ([#165](https://github.com/incu6us/chain-sdk/issues/165)) ([43563b8](https://github.com/incu6us/chain-sdk/commit/43563b8fce85beb5fd8fd151611684c13f304ceb))
* **ts:** add required market exports ([#175](https://github.com/incu6us/chain-sdk/issues/175)) ([dd6f4d4](https://github.com/incu6us/chain-sdk/commit/dd6f4d40f3517e5a5376e5dd0a0ecdcd14d4656a))
* **ts:** adds gas multiplier option to chain sdk ([#93](https://github.com/incu6us/chain-sdk/issues/93)) ([8d332d3](https://github.com/incu6us/chain-sdk/commit/8d332d300749f18f230dd7d125d0545226a0f226))
* **ts:** adds retry options to grpc transports ([#174](https://github.com/incu6us/chain-sdk/issues/174)) ([02bd13b](https://github.com/incu6us/chain-sdk/commit/02bd13bfb0a4f24a2770c57dc96081cd235b6115))
* **ts:** adds sdl permissions validation ([419e3b7](https://github.com/incu6us/chain-sdk/commit/419e3b7f73ec3c7b49926ec079d4cf357d61853c))
* **ts:** adds several deprecated modules ([#184](https://github.com/incu6us/chain-sdk/issues/184)) ([873447f](https://github.com/incu6us/chain-sdk/commit/873447f73f1a6f1ba4cde69c3234382d6f2480ce))
* **ts:** adds some static paths and renames .bin to script ([#184](https://github.com/incu6us/chain-sdk/issues/184)) ([a6fcddb](https://github.com/incu6us/chain-sdk/commit/a6fcddb06dc9d7420af84d3d851dba87bd579002))
* **ts:** adds support for chain transactions ([#246](https://github.com/incu6us/chain-sdk/issues/246)) ([0d175db](https://github.com/incu6us/chain-sdk/commit/0d175db778634eeb65815972f3c6263ab590d619))
* **ts:** adds yaml.raw helper ([#260](https://github.com/incu6us/chain-sdk/issues/260)) ([28ead7b](https://github.com/incu6us/chain-sdk/commit/28ead7b910320702d38443d73a4dd00236032ce6))
* **ts:** exports all the generated namespaces ([#184](https://github.com/incu6us/chain-sdk/issues/184)) ([d46ed7e](https://github.com/incu6us/chain-sdk/commit/d46ed7e694c1b1311893ce37a3fc925b8bc054ba))
* **ts:** expose builtInTypes option for tx transport ([#102](https://github.com/incu6us/chain-sdk/issues/102)) ([a1f3c6d](https://github.com/incu6us/chain-sdk/commit/a1f3c6d27a7a74607d1e939ecddee7d740827ace))
* **ts:** expose validateSDL and its primitives ([#204](https://github.com/incu6us/chain-sdk/issues/204)) ([38b2e98](https://github.com/incu6us/chain-sdk/commit/38b2e981c6c3000def92e9c1918bcae53f2356d7))
* **ts:** exposes grpc transport options via SDK options for provider and chain ([#138](https://github.com/incu6us/chain-sdk/issues/138)) ([33a4d08](https://github.com/incu6us/chain-sdk/commit/33a4d08ad4c24f5a0e86eab479a82bd111d4311c))
* **ts:** implement grpc-js client services ([#158](https://github.com/incu6us/chain-sdk/issues/158)) ([c0913e0](https://github.com/incu6us/chain-sdk/commit/c0913e06355169380e01bb9780d2120bfe6eddd8))
* **ts:** implements testing and release ([#184](https://github.com/incu6us/chain-sdk/issues/184)) ([#143](https://github.com/incu6us/chain-sdk/issues/143)) ([279f807](https://github.com/incu6us/chain-sdk/commit/279f8070af32722cb439c2d8bb9d68570ecfcdfe))
* **ts:** patch cosmos proto decimal parsing ([e382e32](https://github.com/incu6us/chain-sdk/commit/e382e32ee44061b364599bbac5b85a9213ed53e4))
* **ts:** support service permissions in SDL manifest ([b58ab52](https://github.com/incu6us/chain-sdk/commit/b58ab52554cf08f911569b9e115c715ddd29d32a))
* **ts:** supports partial fee option in transaction calls ([#105](https://github.com/incu6us/chain-sdk/issues/105)) ([f8e48b6](https://github.com/incu6us/chain-sdk/commit/f8e48b61d9a74da99dd710edcd996a869bcc5892))


### Bug Fixes

* add ledger failed event ([#257](https://github.com/incu6us/chain-sdk/issues/257)) ([40c2596](https://github.com/incu6us/chain-sdk/commit/40c2596fe4e03bbbd30254b5b40063075f5b5a0b))
* ceil resource convert string ([#172](https://github.com/incu6us/chain-sdk/issues/172)) ([4a2663b](https://github.com/incu6us/chain-sdk/commit/4a2663b2307bc5e4fe8f2449a9b57c62e885b02f))
* ensure nodejs can import exported files ([#86](https://github.com/incu6us/chain-sdk/issues/86)) ([a301b4d](https://github.com/incu6us/chain-sdk/commit/a301b4d33cf7f6aa936d522bbc5ab60f46394d9d))
* ensure that sdk method properly infers type from schema ([#74](https://github.com/incu6us/chain-sdk/issues/74)) ([a92d086](https://github.com/incu6us/chain-sdk/commit/a92d0864e92b962322901b3965a64c502dba3544))
* **go/jwt:** update test according to jwt schema ([#119](https://github.com/incu6us/chain-sdk/issues/119)) ([d324705](https://github.com/incu6us/chain-sdk/commit/d3247050049ae596e9108ea7cce7e59767a49a68))
* **oracle:** params tag IDs ([#273](https://github.com/incu6us/chain-sdk/issues/273)) ([602a567](https://github.com/incu6us/chain-sdk/commit/602a56793ee1726699f9c66be6c80f62416cf667))
* **proto:** correct description to funds field in balance ([#97](https://github.com/incu6us/chain-sdk/issues/97)) ([c9d9757](https://github.com/incu6us/chain-sdk/commit/c9d9757f1c428d9ffc7fbc0f4efc9c356a8028fe))
* syncs generated proto files ([#65](https://github.com/incu6us/chain-sdk/issues/65)) ([1cfec74](https://github.com/incu6us/chain-sdk/commit/1cfec744dc4c4264ed40da29b68657bd1bc9d42a))
* syncs json-schema with go jwt implementation ([#108](https://github.com/incu6us/chain-sdk/issues/108)) ([24f5c28](https://github.com/incu6us/chain-sdk/commit/24f5c28b5b5f9b58444c744d3c8c8cccbca667c4))
* ts build runtime ([#68](https://github.com/incu6us/chain-sdk/issues/68)) ([98b7525](https://github.com/incu6us/chain-sdk/commit/98b7525c9b1ebcd0487967a1e4ad5c73515e7965))
* **ts:** adds missing build dep ([847c73f](https://github.com/incu6us/chain-sdk/commit/847c73fc923e534722bba0ea0fdeb84e116002e1))
* **ts:** adds retry to chain sdk queries on connection errors ([#277](https://github.com/incu6us/chain-sdk/issues/277)) ([49c5d6b](https://github.com/incu6us/chain-sdk/commit/49c5d6bddeab5de7194c53cf0b625edacede908b))
* **ts:** decodes/encodes negative LegacyDec values ([#156](https://github.com/incu6us/chain-sdk/issues/156)) ([035cdc0](https://github.com/incu6us/chain-sdk/commit/035cdc0633cc9b74fab80f2624ca8ea48b72d223))
* **ts:** does not add ts hooks by default ([#152](https://github.com/incu6us/chain-sdk/issues/152)) ([5ecc2bc](https://github.com/incu6us/chain-sdk/commit/5ecc2bccb73e8b676190268b932dc686e61ce2b8))
* **ts:** does not mark ts release as latest in github ([#146](https://github.com/incu6us/chain-sdk/issues/146)) ([53f5008](https://github.com/incu6us/chain-sdk/commit/53f50086018e70b40d01cced03dc74452f6da30e))
* **ts:** ensure that we create only 1 stargate client per sdk ([#94](https://github.com/incu6us/chain-sdk/issues/94)) ([a0fd0f3](https://github.com/incu6us/chain-sdk/commit/a0fd0f35d4d3f3584e31b6b37ebe2e4e67603151))
* **ts:** ensures esbuild replaces imports with require calls ([#157](https://github.com/incu6us/chain-sdk/issues/157)) ([aa1c1e9](https://github.com/incu6us/chain-sdk/commit/aa1c1e92740f1e786d81462445fefda0891caf24))
* **ts:** ensures patches are preserved during code generation ([#166](https://github.com/incu6us/chain-sdk/issues/166)) ([f004622](https://github.com/incu6us/chain-sdk/commit/f004622e989c51af49acd46547657aea8f96e9c1))
* **ts:** handles service.expose as an optional value ([#247](https://github.com/incu6us/chain-sdk/issues/247)) ([c56179e](https://github.com/incu6us/chain-sdk/commit/c56179ef4b0d624ccbe853fb93dd42de244e3728))
* **ts:** makes sure zipped source files are excluded from registry ([03dcb65](https://github.com/incu6us/chain-sdk/commit/03dcb65aadef9c16963f797a9ccb191c27f0354c))
* **ts:** passes patches to createSDK functions ([#91](https://github.com/incu6us/chain-sdk/issues/91)) ([7dde75d](https://github.com/incu6us/chain-sdk/commit/7dde75da22263fc5ee70956dff8950f7ed252676))
* **ts:** re-expoort sdl types and error ([#143](https://github.com/incu6us/chain-sdk/issues/143)) ([beac385](https://github.com/incu6us/chain-sdk/commit/beac385d6da31f1e56b6f3f60cc090cd500f11bd))
* **ts:** removes defaultRegistryTypes from cosmjs ([#104](https://github.com/incu6us/chain-sdk/issues/104)) ([d1c5735](https://github.com/incu6us/chain-sdk/commit/d1c5735681549c0254486bf5ab49d4a07926af71))
* **ts:** skips type patching for gRPC gateway transport since it is done on gateway side ([#145](https://github.com/incu6us/chain-sdk/issues/145)) ([0c888e0](https://github.com/incu6us/chain-sdk/commit/0c888e0fa966e3237193ea2cf850e3940c8e9f09))
* **ts:** sort storage keys during manifest generation ([#233](https://github.com/incu6us/chain-sdk/issues/233)) ([1d5e0e4](https://github.com/incu6us/chain-sdk/commit/1d5e0e4c8bd9d417f7829ab9d65467054d695341))
* **ts:** splits index files by proto target ([21fe987](https://github.com/incu6us/chain-sdk/commit/21fe987fdf041a914dc22a0d425d9c67c932ccc9))
* **ts:** syncs ts type with json-schema changes ([#109](https://github.com/incu6us/chain-sdk/issues/109)) ([94ac1d8](https://github.com/incu6us/chain-sdk/commit/94ac1d8cb03c670f62ba43f9c37e49e94a47b85b))
* **ts:** updates cosmjs deps to 0.36.1 ([#111](https://github.com/incu6us/chain-sdk/issues/111)) ([5e5fe5d](https://github.com/incu6us/chain-sdk/commit/5e5fe5d6538fdfebdb0ed408fb2323942e6dab2d))
* update how manifest is generated ([#107](https://github.com/incu6us/chain-sdk/issues/107)) ([33e7a31](https://github.com/incu6us/chain-sdk/commit/33e7a31b73b2e66fbd8a004b92b6139f02a17fd2))


### Code Refactoring

* **ts:** adds SDL json-schema and refactors validation ([#184](https://github.com/incu6us/chain-sdk/issues/184)) ([4b67a98](https://github.com/incu6us/chain-sdk/commit/4b67a989dbd204f52f40937e5434a75f57b495e5))
* **ts:** simplifies TxClient interface ([#210](https://github.com/incu6us/chain-sdk/issues/210)) ([42c02b3](https://github.com/incu6us/chain-sdk/commit/42c02b30639d6ae68079fac58afc3cc8ebdf9f08))

## [1.0.0-alpha.29](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.28...ts/v1.0.0-alpha.29) (2026-03-31)


### Features

* adds possibility to specify cert serial number ([#274](https://github.com/akash-network/chain-sdk/issues/274)) ([5322905](https://github.com/akash-network/chain-sdk/commit/532290565a8a8112276372411480400431e7a409))


### Bug Fixes

* **ts:** adds retry to chain sdk queries on connection errors ([#277](https://github.com/akash-network/chain-sdk/issues/277)) ([49c5d6b](https://github.com/akash-network/chain-sdk/commit/49c5d6bddeab5de7194c53cf0b625edacede908b))
* **ts:** handles service.expose as an optional value ([#247](https://github.com/akash-network/chain-sdk/issues/247)) ([c56179e](https://github.com/akash-network/chain-sdk/commit/c56179ef4b0d624ccbe853fb93dd42de244e3728))

## [1.0.0-alpha.28](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.27...ts/v1.0.0-alpha.28) (2026-03-30)


### Features

* add EventAggregatedPrice ([#269](https://github.com/akash-network/chain-sdk/issues/269)) ([5c5cdea](https://github.com/akash-network/chain-sdk/commit/5c5cdea57bb1be7b8c1796e2f10d16064c2b013c))
* include spread in the ledger records ([#262](https://github.com/akash-network/chain-sdk/issues/262)) ([48edd00](https://github.com/akash-network/chain-sdk/commit/48edd000a0186be1cf3791080817690538244c75))
* oracle api v2 ([#271](https://github.com/akash-network/chain-sdk/issues/271)) ([9bf1e08](https://github.com/akash-network/chain-sdk/commit/9bf1e0855620fd5b9a87a74268bbbbe4a3249131))
* **oracle:** add future time drift param ([#272](https://github.com/akash-network/chain-sdk/issues/272)) ([05f70f8](https://github.com/akash-network/chain-sdk/commit/05f70f8a40ee7d650f35c5aee4c0eefdf3908d79))


### Bug Fixes

* **oracle:** params tag IDs ([#273](https://github.com/akash-network/chain-sdk/issues/273)) ([602a567](https://github.com/akash-network/chain-sdk/commit/602a56793ee1726699f9c66be6c80f62416cf667))

## [1.0.0-alpha.27](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.26...ts/v1.0.0-alpha.27) (2026-03-18)


### Features

* implement ledger failed record for bme ([#255](https://github.com/akash-network/chain-sdk/issues/255)) ([4dc78aa](https://github.com/akash-network/chain-sdk/commit/4dc78aa46dd0538a2d7ce099e274ca47115581c4))
* **ts:** adds yaml.raw helper ([#260](https://github.com/akash-network/chain-sdk/issues/260)) ([28ead7b](https://github.com/akash-network/chain-sdk/commit/28ead7b910320702d38443d73a4dd00236032ce6))


### Bug Fixes

* add ledger failed event ([#257](https://github.com/akash-network/chain-sdk/issues/257)) ([40c2596](https://github.com/akash-network/chain-sdk/commit/40c2596fe4e03bbbd30254b5b40063075f5b5a0b))

## [1.0.0-alpha.26](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.25...ts/v1.0.0-alpha.26) (2026-03-13)


### Features

* **bme:** add FundVault rpc ([#250](https://github.com/akash-network/chain-sdk/issues/250)) ([bf19b1a](https://github.com/akash-network/chain-sdk/commit/bf19b1a7fe2a1e2f14987267efed547a1843476b))

## [1.0.0-alpha.25](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.24...ts/v1.0.0-alpha.25) (2026-03-09)


### Features

* **bme:** add endblocker params ([#245](https://github.com/akash-network/chain-sdk/issues/245)) ([4f6a1d2](https://github.com/akash-network/chain-sdk/commit/4f6a1d2e2e1bf3f25af59bf89f24e18f24b999a7))
* **go/sdl:** add permissions params ([#200](https://github.com/akash-network/chain-sdk/issues/200)) ([38be010](https://github.com/akash-network/chain-sdk/commit/38be010ce056239b063ab9a66d70ad17b571ab24))
* **market:** add OfferPrices and BidMinDeposits to market proto ([#242](https://github.com/akash-network/chain-sdk/issues/242)) ([0433094](https://github.com/akash-network/chain-sdk/commit/0433094ddd9ca07e905a7d7c8b5b272fb267ea50))
* **provider:** add BidScreening RPC and validation proto ([#243](https://github.com/akash-network/chain-sdk/issues/243)) ([1fadf95](https://github.com/akash-network/chain-sdk/commit/1fadf955bae5d60e4a79701ad1e7591d64f0b0a8))
* **ts:** adds support for chain transactions ([#246](https://github.com/akash-network/chain-sdk/issues/246)) ([0d175db](https://github.com/akash-network/chain-sdk/commit/0d175db778634eeb65815972f3c6263ab590d619))


### Bug Fixes

* **ts:** sort storage keys during manifest generation ([#233](https://github.com/akash-network/chain-sdk/issues/233)) ([1d5e0e4](https://github.com/akash-network/chain-sdk/commit/1d5e0e4c8bd9d417f7829ab9d65467054d695341))

## [1.0.0-alpha.24](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.23...ts/v1.0.0-alpha.24) (2026-02-12)


### Features

* **ts:** support service permissions in SDL manifest ([b58ab52](https://github.com/akash-network/chain-sdk/commit/b58ab52554cf08f911569b9e115c715ddd29d32a))

## [1.0.0-alpha.23](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.22...ts/v1.0.0-alpha.23) (2026-02-11)


### Features

* allows uact denom ([#222](https://github.com/akash-network/chain-sdk/issues/222)) ([39e2329](https://github.com/akash-network/chain-sdk/commit/39e23295da6114afde9d5642907e3f4458ee9051))
* implements generate manifest function ([#225](https://github.com/akash-network/chain-sdk/issues/225)) ([6ad9d64](https://github.com/akash-network/chain-sdk/commit/6ad9d6488c8af74ae1a91783353469cbbb368964))

## [1.0.0-alpha.22](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.21...ts/v1.0.0-alpha.22) (2026-02-09)


### Features

* **ts:** adds sdl permissions validation ([419e3b7](https://github.com/akash-network/chain-sdk/commit/419e3b7f73ec3c7b49926ec079d4cf357d61853c))

## [1.0.0-alpha.21](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.20...ts/v1.0.0-alpha.21) (2026-02-09)


### Features

* **ts:** adds sdl permissions validation ([419e3b7](https://github.com/akash-network/chain-sdk/commit/419e3b7f73ec3c7b49926ec079d4cf357d61853c))

## [1.0.0-alpha.21](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.20...ts/v1.0.0-alpha.21) (2026-01-25)

### Code Refactoring

* **ts:** reduces generated types size

## [1.0.0-alpha.20](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.19...ts/v1.0.0-alpha.20) (2026-01-20)


### ⚠ BREAKING CHANGES

* **ts:** simplifies TxClient interface ([#210](https://github.com/akash-network/chain-sdk/issues/210))

### Features

* **ts:** expose validateSDL and its primitives ([#204](https://github.com/akash-network/chain-sdk/issues/204)) ([38b2e98](https://github.com/akash-network/chain-sdk/commit/38b2e981c6c3000def92e9c1918bcae53f2356d7))


### Code Refactoring

* **ts:** simplifies TxClient interface ([#210](https://github.com/akash-network/chain-sdk/issues/210)) ([42c02b3](https://github.com/akash-network/chain-sdk/commit/42c02b30639d6ae68079fac58afc3cc8ebdf9f08))

## [1.0.0-alpha.19](https://github.com/akash-network/chain-sdk/compare/ts/v1.0.0-alpha.18...ts/v1.0.0-alpha.19) (2026-01-13)


### ⚠ BREAKING CHANGES

* **ts:** adds SDL json-schema and refactors validation ([#184](https://github.com/akash-network/chain-sdk/issues/184))

### Features

* **ts:** adds retry options to grpc transports ([#174](https://github.com/akash-network/chain-sdk/issues/174)) ([02bd13b](https://github.com/akash-network/chain-sdk/commit/02bd13bfb0a4f24a2770c57dc96081cd235b6115))


### Bug Fixes

* ceil resource convert string ([#172](https://github.com/akash-network/chain-sdk/issues/172)) ([4a2663b](https://github.com/akash-network/chain-sdk/commit/4a2663b2307bc5e4fe8f2449a9b57c62e885b02f))


### Code Refactoring

* **ts:** adds SDL json-schema and refactors validation ([#184](https://github.com/akash-network/chain-sdk/issues/184)) ([4b67a98](https://github.com/akash-network/chain-sdk/commit/4b67a989dbd204f52f40937e5434a75f57b495e5))
