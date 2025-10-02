# [7.5.0](https://github.com/parse-community/parse-dashboard/compare/7.4.0...7.5.0) (2025-10-02)


### Features

* Add button to view table to open all pointers of a column in new browser tabs ([#2976](https://github.com/parse-community/parse-dashboard/issues/2976)) ([b8033a4](https://github.com/parse-community/parse-dashboard/commit/b8033a46f519ad98a1c8e59fe4c868aa65b5840c))
* Add data browser filter condition `containedIn` ([#2979](https://github.com/parse-community/parse-dashboard/issues/2979)) ([c1dc5bb](https://github.com/parse-community/parse-dashboard/commit/c1dc5bb81823923596e2e1c5c8545ff5cded7856))

# [7.4.0](https://github.com/parse-community/parse-dashboard/compare/7.3.0...7.4.0) (2025-09-01)


### Bug Fixes

* Legacy script in JavaScript console not imported to modern console ([#2963](https://github.com/parse-community/parse-dashboard/issues/2963)) ([8c8d084](https://github.com/parse-community/parse-dashboard/commit/8c8d0849521eccd23e590c57ca91069bb32c5035))

### Features

* Add App Settings option to store dashboard settings on server ([#2958](https://github.com/parse-community/parse-dashboard/issues/2958)) ([666e078](https://github.com/parse-community/parse-dashboard/commit/666e07860ba1478aec3cde9db5c98a5772ea07fb))
* Add config parameter name to quick add dialogs in Config page ([#2970](https://github.com/parse-community/parse-dashboard/issues/2970)) ([31988f6](https://github.com/parse-community/parse-dashboard/commit/31988f68cda16856b0c6afb22e4f06321cbcef03))
* Add info panel setting to auto-load first row on opening new browser tab ([#2972](https://github.com/parse-community/parse-dashboard/issues/2972)) ([020a25d](https://github.com/parse-community/parse-dashboard/commit/020a25dc302e45e947eb5c15a271bb9f0f1211f2))
* Modernize JavaScript console with tabs and server-side storage of scripts ([#2962](https://github.com/parse-community/parse-dashboard/issues/2962)) ([6e0c7f2](https://github.com/parse-community/parse-dashboard/commit/6e0c7f25b16fdfc0a34123359a8512c26252f269))

# [7.3.0](https://github.com/parse-community/parse-dashboard/compare/7.2.1...7.3.0) (2025-08-01)


### Bug Fixes

* Changing "Relative dates" option of saved filter does not enable save button ([#2947](https://github.com/parse-community/parse-dashboard/issues/2947)) ([4f4977d](https://github.com/parse-community/parse-dashboard/commit/4f4977dbb16fbf755584355d90b85d9efc9169fd))
* Class object counters in sidebar not updating ([#2950](https://github.com/parse-community/parse-dashboard/issues/2950)) ([0f1920b](https://github.com/parse-community/parse-dashboard/commit/0f1920b448787e57482c821b881c732f57fec614))
* Clicking linked pointer with Cmd key in view table doesn't open page in new browser tab ([#2902](https://github.com/parse-community/parse-dashboard/issues/2902)) ([101b194](https://github.com/parse-community/parse-dashboard/commit/101b1943b01367402b2bbab61cabf2c267540c3e))
* Fails to generate MFA code with CLI command `parse-dashboard --createMFA` ([#2883](https://github.com/parse-community/parse-dashboard/issues/2883)) ([544df1f](https://github.com/parse-community/parse-dashboard/commit/544df1ff606d45693596bc20179d129d6a9c91f1))
* Gracefully fail when trying to get new features in latest version of dashboard ([#2880](https://github.com/parse-community/parse-dashboard/issues/2880)) ([1969a0e](https://github.com/parse-community/parse-dashboard/commit/1969a0e826832179bcd8d5e5ea56e8d63ad84dd4))
* Header checkbox in data browser does not indicate when a few rows are selected ([#2957](https://github.com/parse-community/parse-dashboard/issues/2957)) ([e4ab666](https://github.com/parse-community/parse-dashboard/commit/e4ab66643085ab98d484aa0c484d0f66da7ed6d4))
* Hyperlink in Views table ignores `urlQuery` key ([#2926](https://github.com/parse-community/parse-dashboard/issues/2926)) ([c5eedf4](https://github.com/parse-community/parse-dashboard/commit/c5eedf4c0d3db6572ba47838970d259ce1e7e11f))
* Incorrect table cell width in App Settings table ([#2933](https://github.com/parse-community/parse-dashboard/issues/2933)) ([d46765b](https://github.com/parse-community/parse-dashboard/commit/d46765b16abfe3eda6d77525ae2f95a6f4be620c))
* Info panel scroll-to-top setting not persistent across dashboard sessions ([#2938](https://github.com/parse-community/parse-dashboard/issues/2938)) ([2b78087](https://github.com/parse-community/parse-dashboard/commit/2b7808766516a6833236c5a0721084f3ffe026b0))
* Invalid clipboard content for multi-cell copy in data browser ([#2882](https://github.com/parse-community/parse-dashboard/issues/2882)) ([22a2065](https://github.com/parse-community/parse-dashboard/commit/22a206501e4ca77dc0bb2a845b9cdf2bd3653b81))
* Legacy filters without `filterId` cannot be deleted in data browser ([#2946](https://github.com/parse-community/parse-dashboard/issues/2946)) ([65df9d6](https://github.com/parse-community/parse-dashboard/commit/65df9d60c080d100fac45c7a81cae83104f150ea))
* Legacy filters without `filterId` do not appear in sidebar ([#2945](https://github.com/parse-community/parse-dashboard/issues/2945)) ([fde3769](https://github.com/parse-community/parse-dashboard/commit/fde376923dc5a7ada689b5a35c54065c90870070))
* Modal text input can be resized smaller than its cell in Safari browser ([#2930](https://github.com/parse-community/parse-dashboard/issues/2930)) ([82a0cdc](https://github.com/parse-community/parse-dashboard/commit/82a0cdc397d58494c0c61a8241767d4930f742f1))
* Move settings button on data browser toolbar for better UI ([#2940](https://github.com/parse-community/parse-dashboard/issues/2940)) ([c473ce6](https://github.com/parse-community/parse-dashboard/commit/c473ce6153f12c1eebcb7467d185b9f7482d42a8))
* Pagination footer bar hides rows in data browser ([#2879](https://github.com/parse-community/parse-dashboard/issues/2879)) ([6bc2da8](https://github.com/parse-community/parse-dashboard/commit/6bc2da848f970ae50cc5de0a9b1d16a04e2c88ae))
* Race condition on info panel request shows info panel data not corresponding to selected cell ([#2909](https://github.com/parse-community/parse-dashboard/issues/2909)) ([6f45bb3](https://github.com/parse-community/parse-dashboard/commit/6f45bb348def3cf297e869bc58bb5edcd5ad2d60))
* Saved legacy filter in data browser cannot be deleted or cloned ([#2944](https://github.com/parse-community/parse-dashboard/issues/2944)) ([15da90d](https://github.com/parse-community/parse-dashboard/commit/15da90d05bf8cde6cc383a3f9bd060d48214ccc6))
* Saved legacy filter with classname in query cannot be deleted ([#2948](https://github.com/parse-community/parse-dashboard/issues/2948)) ([05ee5b3](https://github.com/parse-community/parse-dashboard/commit/05ee5b39e91737343ae4395cb63736802bd5c6cb))
* Selected text in info panel cannot be copied using Ctrl+C ([#2951](https://github.com/parse-community/parse-dashboard/issues/2951)) ([0164c19](https://github.com/parse-community/parse-dashboard/commit/0164c1939cbb4ada991dc488ef2cd156913353d0))
* Views not sorted alphabetically in sidebar ([#2943](https://github.com/parse-community/parse-dashboard/issues/2943)) ([4c81fe4](https://github.com/parse-community/parse-dashboard/commit/4c81fe423a9d437d0563285c9f67b13f8c7582ec))
* Warning dialog is shown after executing script on selected rows ([#2899](https://github.com/parse-community/parse-dashboard/issues/2899)) ([027f1ed](https://github.com/parse-community/parse-dashboard/commit/027f1edacaa74b67e9e28bbb039465b075fcf6b4))

### Features

* Add additional values in info panel key-value element ([#2904](https://github.com/parse-community/parse-dashboard/issues/2904)) ([a8f110e](https://github.com/parse-community/parse-dashboard/commit/a8f110e1349e8b51927be0386f8dd1a4a031fd6b))
* Add AI agent for natural language interaction with Parse Server ([#2954](https://github.com/parse-community/parse-dashboard/issues/2954)) ([32bd6e8](https://github.com/parse-community/parse-dashboard/commit/32bd6e855c67e3d4aa2fa4d8e8c3e076969486d0))
* Add clipboard icon to copy value of key-value element in info panel ([#2871](https://github.com/parse-community/parse-dashboard/issues/2871)) ([7862c42](https://github.com/parse-community/parse-dashboard/commit/7862c42e58bb8296635f3df1036eb5348f8897fa))
* Add Cloud Function as data source for views with optional text or file upload ([#2939](https://github.com/parse-community/parse-dashboard/issues/2939)) ([f5831c7](https://github.com/parse-community/parse-dashboard/commit/f5831c71b16c135b6bc51dd2ff37991d2b2b57f9))
* Add column freezing in data browser ([#2877](https://github.com/parse-community/parse-dashboard/issues/2877)) ([29f4a88](https://github.com/parse-community/parse-dashboard/commit/29f4a88dc8dc4c9e1673cfbbbbd39db37231f983))
* Add custom data views with aggregation query ([#2888](https://github.com/parse-community/parse-dashboard/issues/2888)) ([b1679db](https://github.com/parse-community/parse-dashboard/commit/b1679db1210a52c8c5299eb4b66e33f96963311e))
* Add environment variable support for AI agent configuration ([#2956](https://github.com/parse-community/parse-dashboard/issues/2956)) ([2ac9e7e](https://github.com/parse-community/parse-dashboard/commit/2ac9e7e13cec0edb085d582ef1c67bd7e8468ac5))
* Add hyperlink support in Views table ([#2925](https://github.com/parse-community/parse-dashboard/issues/2925)) ([06cfc11](https://github.com/parse-community/parse-dashboard/commit/06cfc11f6e62d2da99882dbf659bd7c6428f06ce))
* Add inclusive date filters "is on or after", "is on or before" in data browser ([#2929](https://github.com/parse-community/parse-dashboard/issues/2929)) ([c8d621b](https://github.com/parse-community/parse-dashboard/commit/c8d621b6e173621a01ee081b002f0673c4d90d91))
* Add quick-add button to array parameter in Cloud Config ([#2866](https://github.com/parse-community/parse-dashboard/issues/2866)) ([e98ccb2](https://github.com/parse-community/parse-dashboard/commit/e98ccb236459d891b60383fa3e040b212ac07044))
* Add row number column to data browser ([#2878](https://github.com/parse-community/parse-dashboard/issues/2878)) ([c0aa407](https://github.com/parse-community/parse-dashboard/commit/c0aa4072bd3dee4dcddaa3527de97479354683e5))
* Add Settings menu to scroll info panel to top when browsing through rows ([#2937](https://github.com/parse-community/parse-dashboard/issues/2937)) ([f339cb8](https://github.com/parse-community/parse-dashboard/commit/f339cb8d7a94ccda765c0d50ae00b57a53e03d7e))
* Add support for "not equal to" filter for Boolean values in data browser and analytics explorer ([#2914](https://github.com/parse-community/parse-dashboard/issues/2914)) ([d55b89c](https://github.com/parse-community/parse-dashboard/commit/d55b89c34caee7490eaf78787d28bc8cdbeedbe8))
* Add support for `Image` type in View table to display images ([#2952](https://github.com/parse-community/parse-dashboard/issues/2952)) ([6a6b1f0](https://github.com/parse-community/parse-dashboard/commit/6a6b1f02d546a3271493d4088bf356543b2c0394))
* Add type mismatch warning when quick-adding entry to Cloud Config array parameter ([#2875](https://github.com/parse-community/parse-dashboard/issues/2875)) ([bb1837f](https://github.com/parse-community/parse-dashboard/commit/bb1837fd7af64e75364b53210dd710bc70d0e764))
* Add view edit icon to views list in sidebar ([#2901](https://github.com/parse-community/parse-dashboard/issues/2901)) ([96e33b9](https://github.com/parse-community/parse-dashboard/commit/96e33b9f59fb590b0a4041d0b87cf8820c5551ff))
* Allow editing filter without loading data in data browser ([#2949](https://github.com/parse-community/parse-dashboard/issues/2949)) ([9623580](https://github.com/parse-community/parse-dashboard/commit/962358020c513d38a1bc175545f73aebc92d403a))
* Allow editing saved filters in data browser ([#2942](https://github.com/parse-community/parse-dashboard/issues/2942)) ([daaccaa](https://github.com/parse-community/parse-dashboard/commit/daaccaac75a0dad2082fb32abf1eb5f0cec17af7))
* Allow freeform text view resizing in modal dialogs ([#2910](https://github.com/parse-community/parse-dashboard/issues/2910)) ([1399162](https://github.com/parse-community/parse-dashboard/commit/139916211113dec14a835fea50838e495dc15077))
* Persist info panel visibility when navigating across classes in data browser ([#2908](https://github.com/parse-community/parse-dashboard/issues/2908)) ([1a3610a](https://github.com/parse-community/parse-dashboard/commit/1a3610a4632be78353db4f511781ca7757a12361))
* Prefetch info panel data with config options `prefetchObjects` and `prefetchStale` ([#2915](https://github.com/parse-community/parse-dashboard/issues/2915)) ([54a8156](https://github.com/parse-community/parse-dashboard/commit/54a8156994a4c720b9f09d9f97ac4342d8039a77))
* Warn when leaving data browser page with selected rows ([#2887](https://github.com/parse-community/parse-dashboard/issues/2887)) ([206ead1](https://github.com/parse-community/parse-dashboard/commit/206ead15fec0a505a3efcf9c50b78fa4d0561234))

### Performance Improvements

* Add config option `enableResourceCache` to cache dashboard resources locally for faster loading in additional browser tabs ([#2920](https://github.com/parse-community/parse-dashboard/issues/2920)) ([41a4963](https://github.com/parse-community/parse-dashboard/commit/41a4963ce6068e6f14a6a6008812ac3c1821e0fb))

## [7.2.1](https://github.com/parse-community/parse-dashboard/compare/7.2.0...7.2.1) (2025-07-01)


### Bug Fixes

* Data browser does not cancel obsolete long-loading request on sorting field change ([#2839](https://github.com/parse-community/parse-dashboard/issues/2839)) ([0f85376](https://github.com/parse-community/parse-dashboard/commit/0f85376b8ae1db7ae31626896b06fdc0bd8efd75))

# [7.2.0](https://github.com/parse-community/parse-dashboard/compare/7.1.0...7.2.0) (2025-06-01)


### Bug Fixes

* Data browser not scrolling to top when changing filter while cell selected ([#2821](https://github.com/parse-community/parse-dashboard/issues/2821)) ([c2527dc](https://github.com/parse-community/parse-dashboard/commit/c2527dc1d3e084dcab3d52955bae7760bb27da36))
* Data browser table shows loading indicator when info panel is loading ([#2782](https://github.com/parse-community/parse-dashboard/issues/2782)) ([da57e5e](https://github.com/parse-community/parse-dashboard/commit/da57e5ea5ec77abc1bbd4d97ba3a5a30cd82e4a7))
* Improperly aligned unfolding sub-items in context menu in data browser ([#2726](https://github.com/parse-community/parse-dashboard/issues/2726)) ([3fed292](https://github.com/parse-community/parse-dashboard/commit/3fed292b70f9400d4fb09b44d215de377d568c03))
* Notifications fade out erratically when executing a script on large number of rows ([#2822](https://github.com/parse-community/parse-dashboard/issues/2822)) ([3891381](https://github.com/parse-community/parse-dashboard/commit/38913813f0f3252b241a322aaf50142d5564201a))
* Pagination does not reset to page 1 when clicking on class or filter ([#2798](https://github.com/parse-community/parse-dashboard/issues/2798)) ([29d1447](https://github.com/parse-community/parse-dashboard/commit/29d1447509db74c2ddc0c7f01a1cb7c7cd8573ff))
* Saving new filter in data browser overwrites filters added in other dashboard instances ([#2769](https://github.com/parse-community/parse-dashboard/issues/2769)) ([46bc154](https://github.com/parse-community/parse-dashboard/commit/46bc154cc008c2d8f8d8248e52ec06b9e64cb779))
* Selecting a saved filter in data browser may highlight a different filter ([#2783](https://github.com/parse-community/parse-dashboard/issues/2783)) ([4c6e853](https://github.com/parse-community/parse-dashboard/commit/4c6e853f4aa660a8dab61f349f8ccf70572ab8ca))

### Features

* Add confirmation dialog before saving a Cloud Config parameter that has been modified since editing it ([#2770](https://github.com/parse-community/parse-dashboard/issues/2770)) ([adb9b5c](https://github.com/parse-community/parse-dashboard/commit/adb9b5c34c7e6cb02d63ad35fbcca8ea9544e36c))
* Add custom CSS styling for info panel items ([#2788](https://github.com/parse-community/parse-dashboard/issues/2788)) ([f031e5d](https://github.com/parse-community/parse-dashboard/commit/f031e5d4fa509c9fe098d0a6c77e960f79536334))
* Add relative date filter in data browser for date constraints relative to when the query is run ([#2736](https://github.com/parse-community/parse-dashboard/issues/2736)) ([d9dfd69](https://github.com/parse-community/parse-dashboard/commit/d9dfd69b0fcef01456f1feee9b939b7504113e29))
* Add script execution on parallel batches with option `script.executionBatchSize` ([#2828](https://github.com/parse-community/parse-dashboard/issues/2828)) ([cee8b8d](https://github.com/parse-community/parse-dashboard/commit/cee8b8dd12bc44a352e43073aed65782277841dd))
* Keyboard Enter key can be used to select item in data browser filter dialog field dropdown ([#2771](https://github.com/parse-community/parse-dashboard/issues/2771)) ([dc14710](https://github.com/parse-community/parse-dashboard/commit/dc14710b63b0dc79ae52b322c683204941c4cb11))

# [7.1.0](https://github.com/parse-community/parse-dashboard/compare/7.0.0...7.1.0) (2025-05-01)


### Bug Fixes

* Clicking on pointer in data browser when using pagination does not reset to first page ([#2767](https://github.com/parse-community/parse-dashboard/issues/2767)) ([ab512e5](https://github.com/parse-community/parse-dashboard/commit/ab512e52d137cdb30167ece53a9ce12c38f5d155))
* Dashboard crashes on login due to `passport` upgrade ([#2758](https://github.com/parse-community/parse-dashboard/issues/2758)) ([ee74321](https://github.com/parse-community/parse-dashboard/commit/ee743210f67dd9e206e6302f57a5d025099be0b4))
* Dashboard crashes when selecting app ([#2747](https://github.com/parse-community/parse-dashboard/issues/2747)) ([8b0cfea](https://github.com/parse-community/parse-dashboard/commit/8b0cfeae4759eaf41eef3d92aa52c79df2918e54))
* Data browser filters "key exists" and "key does not exist" not working ([#2760](https://github.com/parse-community/parse-dashboard/issues/2760)) ([0691b3c](https://github.com/parse-community/parse-dashboard/commit/0691b3cf30a77421e17299935880c54f9c8c9c32))
* Data browser filters "key exists" and "key does not exist" not working ([#2762](https://github.com/parse-community/parse-dashboard/issues/2762)) ([099eca3](https://github.com/parse-community/parse-dashboard/commit/099eca30be021c6466e4f5279ebd2e6f5cd1c1c3))
* Data loading indicator not showing when using pagination ([#2768](https://github.com/parse-community/parse-dashboard/issues/2768)) ([62d7aec](https://github.com/parse-community/parse-dashboard/commit/62d7aec3c43c634f8dc632ef7a563cfdad5cd773))
* Improperly aligned unfolding sub-items in context menu in data browser  ([#2713](https://github.com/parse-community/parse-dashboard/issues/2713)) ([189c817](https://github.com/parse-community/parse-dashboard/commit/189c8170425642fd94a9360e5c001e6687f50c29))
* Logout bar layout not aligned with data browser navigation bar ([#2720](https://github.com/parse-community/parse-dashboard/issues/2720)) ([01a2a1c](https://github.com/parse-community/parse-dashboard/commit/01a2a1c773484fef2f847e0c05a8823174782ee2))
* Navigation bar in data browser is transparent and partly covers info panel ([#2717](https://github.com/parse-community/parse-dashboard/issues/2717)) ([60b38a5](https://github.com/parse-community/parse-dashboard/commit/60b38a53e1e288aab2a47d43697fe660fef1fffb))
* Obsolete, long-running data fetch request overrides displayed data of newer fetch request in the data browser ([#2715](https://github.com/parse-community/parse-dashboard/issues/2715)) ([31668eb](https://github.com/parse-community/parse-dashboard/commit/31668ebdbb298b96597243947fd842be9063eed5))

### Features

* Add pagination to data browser ([#2659](https://github.com/parse-community/parse-dashboard/issues/2659)) ([a3c8a11](https://github.com/parse-community/parse-dashboard/commit/a3c8a119cb9f669e0e663ec6c018e2b2cf305596))
* Allow row selection in data browser by dragging mouse outside of selection box column ([#2716](https://github.com/parse-community/parse-dashboard/issues/2716)) ([7c0f607](https://github.com/parse-community/parse-dashboard/commit/7c0f607fbb6c704a9793165a9cf14d6a1be792db))
* Display filter list in data browser sorted alphabetically ([#2761](https://github.com/parse-community/parse-dashboard/issues/2761)) ([0209a0d](https://github.com/parse-community/parse-dashboard/commit/0209a0d78a3864ba059444ec5eb4a6d00a0430f4))

# [7.0.0](https://github.com/parse-community/parse-dashboard/compare/6.2.0...7.0.0) (2025-04-04)


### Bug Fixes

* Title row disappears when scrolling down in data browser ([#2690](https://github.com/parse-community/parse-dashboard/issues/2690)) ([7eebc45](https://github.com/parse-community/parse-dashboard/commit/7eebc45a17844e7d72c5a7e86963ee355f63dd77))

### Features

* Allow to select and copy multiple cells in data browser ([#2691](https://github.com/parse-community/parse-dashboard/issues/2691)) ([eb50315](https://github.com/parse-community/parse-dashboard/commit/eb503151b30a5fd35437559eaddfc7e7e5991dc7))
* Increase minimum required Node versions to `18.20.4`, `20.18.0`, `22.12.0` ([#2694](https://github.com/parse-community/parse-dashboard/issues/2694)) ([034df6a](https://github.com/parse-community/parse-dashboard/commit/034df6af3526edc33768f408c9e8faf018fa2ba9))


### BREAKING CHANGES

* Increases the minimum required Node versions to `18.20.4`, `20.18.0`, `22.12.0`. ([034df6a](034df6a))

# [6.2.0](https://github.com/ParsePlatform/parse-dashboard/compare/6.1.0...6.2.0) (2025-03-17)


### Bug Fixes

* Bump @babel/runtime from 7.20.13 to 7.26.10 ([#2677](https://github.com/ParsePlatform/parse-dashboard/issues/2677)) ([37f4ea6](https://github.com/ParsePlatform/parse-dashboard/commit/37f4ea64a39c0f54aaf2e3631fd1f7b6bc03ae96))
* Dashboard crashes when setting `unique` filter on pointer field in data browser ([#2660](https://github.com/ParsePlatform/parse-dashboard/issues/2660)) ([68fdbe8](https://github.com/ParsePlatform/parse-dashboard/commit/68fdbe8460d2afafbc922479bfef86e994449a20))
* Security upgrade node from 20.18.2-alpine3.20 to 20.19.0-alpine3.20 ([#2676](https://github.com/ParsePlatform/parse-dashboard/issues/2676)) ([d251334](https://github.com/ParsePlatform/parse-dashboard/commit/d251334df22fbe46e77076bb583b218be6f1889c))

### Features

* Use Enter key to edit cell content in data browser ([#2672](https://github.com/ParsePlatform/parse-dashboard/issues/2672)) ([ac2dc41](https://github.com/ParsePlatform/parse-dashboard/commit/ac2dc41122faedb1fb7da205ba26229a77417da8))

# [6.1.0](https://github.com/ParsePlatform/parse-dashboard/compare/6.0.0...6.1.0) (2025-03-04)


### Bug Fixes

* Info panel Cloud Code call is unauthenticated without using master key ([#2641](https://github.com/ParsePlatform/parse-dashboard/issues/2641)) ([e879e4f](https://github.com/ParsePlatform/parse-dashboard/commit/e879e4f541dc0aa3e23afe6606ee7df9ba22b63a))
* Info panel Cloud Code call sends `objectId` instead of `Parse.Object` ([#2643](https://github.com/ParsePlatform/parse-dashboard/issues/2643)) ([a4bcabc](https://github.com/ParsePlatform/parse-dashboard/commit/a4bcabc5c5eaf07bc9eed11814c19901e1d310da))
* Info panel item `panel` calls Cloud Code with parameter `objectId` instead of `Parse.Object` and without `masterKey` ([#2649](https://github.com/ParsePlatform/parse-dashboard/issues/2649)) ([884ff70](https://github.com/ParsePlatform/parse-dashboard/commit/884ff70567e372ff676297b6fb7856fbb7b71cbb))
* Info panel not configurable via `new ParseDashboard()` when running as express middleware ([#2639](https://github.com/ParsePlatform/parse-dashboard/issues/2639)) ([a9b8cd4](https://github.com/ParsePlatform/parse-dashboard/commit/a9b8cd4a7228837cbb462a45e39b01494852f347))
* Info panel not showing when some apps miss infoPanel config ([#2627](https://github.com/ParsePlatform/parse-dashboard/issues/2627)) ([539e883](https://github.com/ParsePlatform/parse-dashboard/commit/539e88348721bc100a80ae00de81a921bc2c53d4))
* Node 22 support missing in package.json ([#2617](https://github.com/ParsePlatform/parse-dashboard/issues/2617)) ([8c07284](https://github.com/ParsePlatform/parse-dashboard/commit/8c07284cd571c69426c3f080c2698b0624fd4ec4))
* Security upgrade cross-spawn from 7.0.3 to 7.0.6 ([#2629](https://github.com/ParsePlatform/parse-dashboard/issues/2629)) ([47a43e0](https://github.com/ParsePlatform/parse-dashboard/commit/47a43e0ac5d55fc9e214079895f71af7c7e3c350))
* Security upgrade express from 4.21.0 to 4.21.1 ([#2607](https://github.com/ParsePlatform/parse-dashboard/issues/2607)) ([54bf0af](https://github.com/ParsePlatform/parse-dashboard/commit/54bf0afa0691e448b7ec20395753468e047e1fd1))
* Security upgrade node from 20.17.0-alpine3.20 to 20.18.2-alpine3.20 ([#2647](https://github.com/ParsePlatform/parse-dashboard/issues/2647)) ([44df723](https://github.com/ParsePlatform/parse-dashboard/commit/44df723b56636607f44c16f2ca24e81e0e17dfb3))
* Security upgrade ws, parse and puppeteer ([#2618](https://github.com/ParsePlatform/parse-dashboard/issues/2618)) ([bab71dc](https://github.com/ParsePlatform/parse-dashboard/commit/bab71dc57195efa62518127de842edd5902603de))

### Features

* Add cell selection in data browser on space bar touch down ([#2661](https://github.com/ParsePlatform/parse-dashboard/issues/2661)) ([9d623a9](https://github.com/ParsePlatform/parse-dashboard/commit/9d623a97a4e9ff9692f72191a33441a22fb6956e))
* Add dynamic master key by allowing to set option `masterKey` to a function ([#2655](https://github.com/ParsePlatform/parse-dashboard/issues/2655)) ([9025ed0](https://github.com/ParsePlatform/parse-dashboard/commit/9025ed07b5e7fd801a6ec56c71a12299b2d57279))
* Add info panel `keyValue` item parameter `isRelativeUrl` to link to dashboard pages ([#2646](https://github.com/ParsePlatform/parse-dashboard/issues/2646)) ([6389fc6](https://github.com/ParsePlatform/parse-dashboard/commit/6389fc6097a76dc95e3cbcdab56c8d1f96909d97))
* Add info panel item `panel` to load and display data on demand ([#2622](https://github.com/ParsePlatform/parse-dashboard/issues/2622)) ([8e5741d](https://github.com/ParsePlatform/parse-dashboard/commit/8e5741d73b5a8c4fcb5d4248de1bdcd7bd957ee8))

# [6.0.0](https://github.com/ParsePlatform/parse-dashboard/compare/5.4.0...6.0.0) (2024-10-07)


### Bug Fixes

* App metrics for user and installation counts show dash ([#2528](https://github.com/ParsePlatform/parse-dashboard/issues/2528)) ([850d7b3](https://github.com/ParsePlatform/parse-dashboard/commit/850d7b3f20160761a21f68ec398d7207b8226770))
* Class Level Permissions dialog throws error `TypeError: ce.current is null` for newly created class ([#2549](https://github.com/ParsePlatform/parse-dashboard/issues/2549)) ([27ed692](https://github.com/ParsePlatform/parse-dashboard/commit/27ed6920d38bfe6476aaf2cebd4124dc30389959))
* Config page fails to load ([#2531](https://github.com/ParsePlatform/parse-dashboard/issues/2531)) ([d721b7c](https://github.com/ParsePlatform/parse-dashboard/commit/d721b7c4f3b98df96a229e60529604b038857d53))
* Crash after setting filter using context menu and opening filters panel ([#2579](https://github.com/ParsePlatform/parse-dashboard/issues/2579)) ([5a690eb](https://github.com/ParsePlatform/parse-dashboard/commit/5a690ebe91007698fe1a60334112deed5ce94be1))
* Dashboard crashes if Parse Server Cloud Function script returns object ([#2516](https://github.com/ParsePlatform/parse-dashboard/issues/2516)) ([5de08f8](https://github.com/ParsePlatform/parse-dashboard/commit/5de08f8f4d67f287a589c70d8b8d36f9f76897cf))
* Dashboard not building for Docker platform arm64/v8 ([#2534](https://github.com/ParsePlatform/parse-dashboard/issues/2534)) ([8c4a862](https://github.com/ParsePlatform/parse-dashboard/commit/8c4a862d63b8e568738a2eeab25b6e977cd1ee11))
* Dashboard scrolls when selecting row in data browser ([#2559](https://github.com/ParsePlatform/parse-dashboard/issues/2559)) ([2aa54a5](https://github.com/ParsePlatform/parse-dashboard/commit/2aa54a5bb1f356a7d4ed5abf3ea42c2e406d5b5a))
* Data browser redirects to wrong class when changing app ([#2526](https://github.com/ParsePlatform/parse-dashboard/issues/2526)) ([7713f54](https://github.com/ParsePlatform/parse-dashboard/commit/7713f542ef9ef97cbf784fa267f7ea2a51c9472a))
* Deleting all code in the JS Console editor fills in the default code ([#2558](https://github.com/ParsePlatform/parse-dashboard/issues/2558)) ([4b830ba](https://github.com/ParsePlatform/parse-dashboard/commit/4b830bac8dc6549555eca50e999a3283aff100c7))
* Descriptive statistics for number cells in data browser not showing ([#2581](https://github.com/ParsePlatform/parse-dashboard/issues/2581)) ([e146b6f](https://github.com/ParsePlatform/parse-dashboard/commit/e146b6f54c7dfcb50c83c70f0c55e5ab76dc3c19))
* Filter string is erased when changing filter condition ([#2586](https://github.com/ParsePlatform/parse-dashboard/issues/2586)) ([6fa2c8c](https://github.com/ParsePlatform/parse-dashboard/commit/6fa2c8c79201b9ea34321277ab085fa0ba988d77))
* Internal classes `_User`, `_Role`, `_Installation` referenced with pointer don't appear in data browser filter dialog ([#2599](https://github.com/ParsePlatform/parse-dashboard/issues/2599)) ([8239cc8](https://github.com/ParsePlatform/parse-dashboard/commit/8239cc8a05865c5f0b4f5b33dfb224e87d25a319))
* Open pointer in new tab in data browser not working when mount path is not root ([#2527](https://github.com/ParsePlatform/parse-dashboard/issues/2527)) ([2f4081f](https://github.com/ParsePlatform/parse-dashboard/commit/2f4081f217e1c5d906ed8789e09a3377ddc15121))

### Features

* Add Cloud Config change history to roll back to previous values ([#2554](https://github.com/ParsePlatform/parse-dashboard/issues/2554)) ([a784129](https://github.com/ParsePlatform/parse-dashboard/commit/a784129dd5f25d6464cdd5d768e296fda4501b42))
* Add data panel to display object related data fetched via Cloud Function ([#2584](https://github.com/ParsePlatform/parse-dashboard/issues/2584)) ([914cc71](https://github.com/ParsePlatform/parse-dashboard/commit/914cc71790157289c32b95cd9d4cdf3d0685989f))
* Add descriptive statistics for number cells in data browser ([#2529](https://github.com/ParsePlatform/parse-dashboard/issues/2529)) ([ead9ec4](https://github.com/ParsePlatform/parse-dashboard/commit/ead9ec4d39abc211540bc76616498533b31001a6))
* Add filter `starts with` in data browser for fields of type Pointer ([#2553](https://github.com/ParsePlatform/parse-dashboard/issues/2553)) ([0b94ab6](https://github.com/ParsePlatform/parse-dashboard/commit/0b94ab6ced8b338cd3539f8cad37feb4452e1bcc))
* Add Node 20 support; remove Node 14, 16 support ([#2532](https://github.com/ParsePlatform/parse-dashboard/issues/2532)) ([578a339](https://github.com/ParsePlatform/parse-dashboard/commit/578a339c04990b5ecb3f80d34c690c6d34218bfa))
* Add Node 20 support; remove Node 14, 16 support ([#2535](https://github.com/ParsePlatform/parse-dashboard/issues/2535)) ([5c90f2d](https://github.com/ParsePlatform/parse-dashboard/commit/5c90f2de1b98a2099453c8f8c0d6817330f7133d))
* Add optional restriction of script execution to certain object fields and values ([#2488](https://github.com/ParsePlatform/parse-dashboard/issues/2488)) ([8feac9b](https://github.com/ParsePlatform/parse-dashboard/commit/8feac9b8359f27ecd7bd4342be7bcae75289ba35))
* Add relational filter conditions in data browser ([#2576](https://github.com/ParsePlatform/parse-dashboard/issues/2576)) ([aa5c68d](https://github.com/ParsePlatform/parse-dashboard/commit/aa5c68dbca458069d93351edc0bc0287fe63b7e1))
* Add support for Node 22 ([#2603](https://github.com/ParsePlatform/parse-dashboard/issues/2603)) ([3689106](https://github.com/ParsePlatform/parse-dashboard/commit/3689106b4089aebe73ddb8668863dc82fd267b5c))
* Execute script for selected rows ([#2508](https://github.com/ParsePlatform/parse-dashboard/issues/2508)) ([5d9901e](https://github.com/ParsePlatform/parse-dashboard/commit/5d9901e27b14517f22993ac094bdd7d8fbac401f))
* Select rows in data browser by clicking and dragging mouse cursor over checkboxes ([#2548](https://github.com/ParsePlatform/parse-dashboard/issues/2548)) ([792ba9e](https://github.com/ParsePlatform/parse-dashboard/commit/792ba9e619224c6101ed21cd36add9fe83c3e348))


### BREAKING CHANGES

* Removes support for Node 14 and 16 ([5c90f2d](5c90f2d))

# [5.4.0](https://github.com/ParsePlatform/parse-dashboard/compare/5.3.0...5.4.0) (2024-05-16)


### Features

* Add refresh indicator to Cloud Config page ([#2505](https://github.com/ParsePlatform/parse-dashboard/issues/2505)) ([a10d1f0](https://github.com/ParsePlatform/parse-dashboard/commit/a10d1f0825688d403206ce7cbacada191dbf5c3b))

# [5.3.0](https://github.com/ParsePlatform/parse-dashboard/compare/5.2.0...5.3.0) (2023-11-16)


### Bug Fixes

* Adding a file when adding a new row in the data browser doesn't show filename ([#2471](https://github.com/ParsePlatform/parse-dashboard/issues/2471)) ([5bbb94e](https://github.com/ParsePlatform/parse-dashboard/commit/5bbb94e5b5266af5ed770d0241605eb859699831))
* File extension is hidden in file field when editing object in modal dialog in data browser ([#2472](https://github.com/ParsePlatform/parse-dashboard/issues/2472)) ([8df4e4d](https://github.com/ParsePlatform/parse-dashboard/commit/8df4e4d9abf2ef9e487a48b209f33bedc03b55a3))
* Incorrect highlight maker position in class list in data browser ([#2490](https://github.com/ParsePlatform/parse-dashboard/issues/2490)) ([8c28d24](https://github.com/ParsePlatform/parse-dashboard/commit/8c28d245cfe5d9558ffd276b9660f73449c4f35a))
* Pasting location coordinates into field of type `GeoPoint` does not work in data browser ([#2464](https://github.com/ParsePlatform/parse-dashboard/issues/2464)) ([a8ce343](https://github.com/ParsePlatform/parse-dashboard/commit/a8ce3436a4ffe76ccf892965fa21dc2a467e2d14))
* Selecting a saved filter in data browser also highlights other filters with equal names ([#2466](https://github.com/ParsePlatform/parse-dashboard/issues/2466)) ([35360fe](https://github.com/ParsePlatform/parse-dashboard/commit/35360fec68edbca619075227960062859bb9db2e))
* Vertical scrollbar in data browser is outside visible area when scrolling horizontally ([#2457](https://github.com/ParsePlatform/parse-dashboard/issues/2457)) ([5acac3f](https://github.com/ParsePlatform/parse-dashboard/commit/5acac3fb5c74cbb24ec96b721d874fbc36096c39))

### Features

* Add Cloud Function execution on Parse Object in data browser ([#2409](https://github.com/ParsePlatform/parse-dashboard/issues/2409)) ([996ce91](https://github.com/ParsePlatform/parse-dashboard/commit/996ce916bfedb92c36deede4c234dde8c0554cbb))
* Add parameter `selectedField` to script payload to determine which object field was selected when script was invoked ([#2483](https://github.com/ParsePlatform/parse-dashboard/issues/2483)) ([e98d653](https://github.com/ParsePlatform/parse-dashboard/commit/e98d653b96787720dad5310c5af98869e2ac2923))
* Add refresh button to Cloud Config page ([#2480](https://github.com/ParsePlatform/parse-dashboard/issues/2480)) ([be212b0](https://github.com/ParsePlatform/parse-dashboard/commit/be212b0ad6c777f7c5ee9a74cac0affa63faa1c1))
* Add security checks page ([#2491](https://github.com/ParsePlatform/parse-dashboard/issues/2491)) ([103b9c6](https://github.com/ParsePlatform/parse-dashboard/commit/103b9c61d152487898062485b40f11ecdac3d2e7))
* Add support for confirmation dialog before script execution in data browser ([#2481](https://github.com/ParsePlatform/parse-dashboard/issues/2481)) ([64d3913](https://github.com/ParsePlatform/parse-dashboard/commit/64d391320bbdb519af8ff93fe8579315ef48e36e))
* Add typing with auto-complete to select a filter field in the data browser ([#2463](https://github.com/ParsePlatform/parse-dashboard/issues/2463)) ([257f76b](https://github.com/ParsePlatform/parse-dashboard/commit/257f76bbf8d1e880e3b7b704edee2eebf76451c8))
* Reopen last opened class when navigating to data browser ([#2468](https://github.com/ParsePlatform/parse-dashboard/issues/2468)) ([3d7148e](https://github.com/ParsePlatform/parse-dashboard/commit/3d7148e75a6e9eaeeb7cbb546885b5916f6025bb))

### Reverts

* fix: Vertical scrollbar in data browser is outside visible area when scrolling horizontally ([#2457](https://github.com/ParsePlatform/parse-dashboard/issues/2457)) ([#2477](https://github.com/ParsePlatform/parse-dashboard/issues/2477)) ([2f1d84e](https://github.com/ParsePlatform/parse-dashboard/commit/2f1d84e41c24507b516b933037807f1061182991))

# [5.2.0](https://github.com/ParsePlatform/parse-dashboard/compare/5.1.0...5.2.0) (2023-09-15)


### Bug Fixes

* Back button in data browser disappears after page refresh ([#2421](https://github.com/ParsePlatform/parse-dashboard/issues/2421)) ([6c5f19f](https://github.com/ParsePlatform/parse-dashboard/commit/6c5f19f6ed2cda1f1f0dc59bdaed3ae49f264380))
* Cannot navigate to nested relation field in data browser ([#2420](https://github.com/ParsePlatform/parse-dashboard/issues/2420)) ([e7ace9e](https://github.com/ParsePlatform/parse-dashboard/commit/e7ace9efa068b92c5cf0e5ccdad169ac7d71e81a))
* Dashboard crashes when adding a row with modal in a class that contains a pointer to another class that contains an array of pointers ([#2416](https://github.com/ParsePlatform/parse-dashboard/issues/2416)) ([286269f](https://github.com/ParsePlatform/parse-dashboard/commit/286269f3e2c4e1c83b14003ce72caaf1f39b16c1))
* Empty table in data browser when navigating back using the "back” button ([#2423](https://github.com/ParsePlatform/parse-dashboard/issues/2423)) ([6f3dab6](https://github.com/ParsePlatform/parse-dashboard/commit/6f3dab60c257c76345235acfd3e43aafadeb84c8))
* File uploading status not updating in data browser ([#2422](https://github.com/ParsePlatform/parse-dashboard/issues/2422)) ([e761f97](https://github.com/ParsePlatform/parse-dashboard/commit/e761f9715a8366466c6620994ce698adbbfc48cd))
* Hitting backspace key in data browser crashes dashboard ([#2456](https://github.com/ParsePlatform/parse-dashboard/issues/2456)) ([32aeea2](https://github.com/ParsePlatform/parse-dashboard/commit/32aeea244d81404579f55adf25244c11e3a797d1))
* Incorrect date picker position in data browser filter dialog ([#2425](https://github.com/ParsePlatform/parse-dashboard/issues/2425)) ([b96b48f](https://github.com/ParsePlatform/parse-dashboard/commit/b96b48fdd5ce452783e0887c36231971a1822173))
* Option missing for Parse Config parameter to require master key ([#2440](https://github.com/ParsePlatform/parse-dashboard/issues/2440)) ([6623369](https://github.com/ParsePlatform/parse-dashboard/commit/66233698b333422f306dc7024949aef2ea028f34))
* Scroll position is preserved when re-opening the same class in data browser via navigation bar ([#2445](https://github.com/ParsePlatform/parse-dashboard/issues/2445)) ([667675c](https://github.com/ParsePlatform/parse-dashboard/commit/667675c031b0483be210a88da3b159f5f815d6fb))
* Text input cursor jumps to first position when writing long text ([#2413](https://github.com/ParsePlatform/parse-dashboard/issues/2413)) ([422ffb2](https://github.com/ParsePlatform/parse-dashboard/commit/422ffb2897bb2664eb47b5aaad5094a8b39431bf))
* Uncaught error when editing Number field in Edit Row dialog ([#2401](https://github.com/ParsePlatform/parse-dashboard/issues/2401)) ([26bd6fa](https://github.com/ParsePlatform/parse-dashboard/commit/26bd6fa39be1076621856a9c86dcd1307f8f7fdd))

### Features

* Add export of saved data browser filters via `classPreference` settings ([#2455](https://github.com/ParsePlatform/parse-dashboard/issues/2455)) ([f56f946](https://github.com/ParsePlatform/parse-dashboard/commit/f56f946023c628c96030e9d2d66284c53decd33e))
* Add filter views to save frequently used filters in data browser ([#2404](https://github.com/ParsePlatform/parse-dashboard/issues/2404)) ([a9ec3a9](https://github.com/ParsePlatform/parse-dashboard/commit/a9ec3a915ff354304f382c17e8d5311b2c96d7ff))
* Add links to users and roles in ACL dialog and handle invalid entries ([#2436](https://github.com/ParsePlatform/parse-dashboard/issues/2436)) ([a20cb8e](https://github.com/ParsePlatform/parse-dashboard/commit/a20cb8e534d3fecd8d337463864b15048772a9a5))
* Add visual configurator for Parse Dashboard settings ([#2406](https://github.com/ParsePlatform/parse-dashboard/issues/2406)) ([228d839](https://github.com/ParsePlatform/parse-dashboard/commit/228d83903fd8698da7b96a5b74699f3ff2d5dad4))
* Data types and pointer classes are sorted alphabetically in dialog to add new column ([#2400](https://github.com/ParsePlatform/parse-dashboard/issues/2400)) ([d9d285b](https://github.com/ParsePlatform/parse-dashboard/commit/d9d285b7f90434d3bb138c2c765272498e3f09c3))
* Sort Cloud Code Jobs alphabetically ([#2402](https://github.com/ParsePlatform/parse-dashboard/issues/2402)) ([77fc372](https://github.com/ParsePlatform/parse-dashboard/commit/77fc372bedb9fb4eca728c1bc076e823c5bc3a2c))

# [5.1.0](https://github.com/ParsePlatform/parse-dashboard/compare/5.0.0...5.1.0) (2023-05-01)


### Bug Fixes

* Add dashboard option `cookieSessionMaxAge` to keep user logged in across browser sessions ([#2366](https://github.com/ParsePlatform/parse-dashboard/issues/2366)) ([9ea95fc](https://github.com/ParsePlatform/parse-dashboard/commit/9ea95fc62103b52cf4fac1d1b567334b5298b318))
* Blank screen shown if server is unreachable; unsupported pages are accessible via direct URLs ([#2363](https://github.com/ParsePlatform/parse-dashboard/issues/2363)) ([9855258](https://github.com/ParsePlatform/parse-dashboard/commit/98552584df4d8d75d65d3e394b4acad522117a96))
* Dashboard may display blank page when selecting an app after login ([#2375](https://github.com/ParsePlatform/parse-dashboard/issues/2375)) ([f399b91](https://github.com/ParsePlatform/parse-dashboard/commit/f399b913490f15a0d3be8dde7242dd0b825fa02e))
* Data browser dialog "No data to display" may be outside of visible area in Safari browser ([#2387](https://github.com/ParsePlatform/parse-dashboard/issues/2387)) ([52bba62](https://github.com/ParsePlatform/parse-dashboard/commit/52bba6246cd05c255ca562dcb32da5b104f9908e))
* Internal error message on login with missing credential ([#2370](https://github.com/ParsePlatform/parse-dashboard/issues/2370)) ([9a6a31f](https://github.com/ParsePlatform/parse-dashboard/commit/9a6a31f7d45d1402bfc3a988bef21c4a5bb1b123))
* Navigation to page fails if user re-login is required ([#2369](https://github.com/ParsePlatform/parse-dashboard/issues/2369)) ([0db6f55](https://github.com/ParsePlatform/parse-dashboard/commit/0db6f5559f9b7bb1f5a282c6182810ca89945032))
* Screen goes blank when trying to add column of type `Object` or `GeoPoint` ([#2384](https://github.com/ParsePlatform/parse-dashboard/issues/2384)) ([0886386](https://github.com/ParsePlatform/parse-dashboard/commit/08863868b90455116232b2b73a39391ba990c30c))
* Text selection not visible in modal dialog header ([#2340](https://github.com/ParsePlatform/parse-dashboard/issues/2340)) ([fb0e79c](https://github.com/ParsePlatform/parse-dashboard/commit/fb0e79c0837c3acce27524e798e02da667cbc5a3))

### Features

* Add export all rows of a class and export in JSON format ([#2361](https://github.com/ParsePlatform/parse-dashboard/issues/2361)) ([9eb36a1](https://github.com/ParsePlatform/parse-dashboard/commit/9eb36a183b8b337960f6e8563ad686958001a22b))
* Add schema export ([#2362](https://github.com/ParsePlatform/parse-dashboard/issues/2362)) ([33df049](https://github.com/ParsePlatform/parse-dashboard/commit/33df0495a02c4e77f48b3566032bf5686227cce7))
* remove limitation to refresh Cloud Jobs list only after 30 seconds ([#2332](https://github.com/ParsePlatform/parse-dashboard/issues/2332)) ([ad1132f](https://github.com/ParsePlatform/parse-dashboard/commit/ad1132fb13e854a030e769fdf7689f35d363031d))

# [5.0.0](https://github.com/ParsePlatform/parse-dashboard/compare/4.2.0...5.0.0) (2022-11-01)


### Bug Fixes

* increase required Node engine version to `>=14.20.1`; this is a breaking change, but will be published as a patch version because the change should have been done with the release of `5.0.0-alpha.1` which has just been released ([#2281](https://github.com/ParsePlatform/parse-dashboard/issues/2281)) ([50de52b](https://github.com/ParsePlatform/parse-dashboard/commit/50de52b6dddad079224e3c3b21ed16f4df347a33))
* minor UI layout issues ([#2270](https://github.com/ParsePlatform/parse-dashboard/issues/2270)) ([51d083b](https://github.com/ParsePlatform/parse-dashboard/commit/51d083b218d1291fc27ee2a5f1727c5f2a1dc7d4))
* raw value of read-only date field in data browser cannot be copied ([#2326](https://github.com/ParsePlatform/parse-dashboard/issues/2326)) ([4af7b98](https://github.com/ParsePlatform/parse-dashboard/commit/4af7b981ec1c8356c33215a49f3757a4005525a1))
* using browser navigation backward / forward button clears data browser ([#2317](https://github.com/ParsePlatform/parse-dashboard/issues/2317)) ([7d9b957](https://github.com/ParsePlatform/parse-dashboard/commit/7d9b9575184d7b03fac0e74fa785409af399d314))

### Features

* improve distinction between deletion confirmation dialogs ([#2319](https://github.com/ParsePlatform/parse-dashboard/issues/2319)) ([23c12ff](https://github.com/ParsePlatform/parse-dashboard/commit/23c12ffbd49508de5c6e5e6155e6720e9f960fc5))
* keep entered filter value when changing filter operator ([#2313](https://github.com/ParsePlatform/parse-dashboard/issues/2313)) ([d6d38bf](https://github.com/ParsePlatform/parse-dashboard/commit/d6d38bfc2b06360c6a1ecc990f937cd675d1ff39))
* remove Node 12 support ([#2277](https://github.com/ParsePlatform/parse-dashboard/issues/2277)) ([18b0e76](https://github.com/ParsePlatform/parse-dashboard/commit/18b0e76e28938f4cb3eaaed7ba3292fc622a35c7))


### BREAKING CHANGES

* This version removes support for Node 12; the new minimum required Node version is 14. ([18b0e76](18b0e76))

# [4.2.0](https://github.com/ParsePlatform/parse-dashboard/compare/4.1.4...4.2.0) (2022-10-15)


### Bug Fixes

* button text "Show all" in column menu is truncated ([#2208](https://github.com/ParsePlatform/parse-dashboard/issues/2208)) ([b89d044](https://github.com/ParsePlatform/parse-dashboard/commit/b89d044a504c6748932907f075819a13aa08fb51))
* column names in data browser menu not left-aligned ([#2263](https://github.com/ParsePlatform/parse-dashboard/issues/2263)) ([fc5673a](https://github.com/ParsePlatform/parse-dashboard/commit/fc5673a0ebbc7b4d51e122dbb71172803513309e))
* context menu in data browser is not scrollable ([#2271](https://github.com/ParsePlatform/parse-dashboard/issues/2271)) ([6c54bd8](https://github.com/ParsePlatform/parse-dashboard/commit/6c54bd82b872d5efed827c3582b4fb3f0aa24a95))
* dashboard contains invalid html for top-level document ([#2254](https://github.com/ParsePlatform/parse-dashboard/issues/2254)) ([bbce857](https://github.com/ParsePlatform/parse-dashboard/commit/bbce8579ef634bf8e6800f3a6ab8cd650e971695))
* file upload dialog in data browser shows multiple times ([#2276](https://github.com/ParsePlatform/parse-dashboard/issues/2276)) ([3927340](https://github.com/ParsePlatform/parse-dashboard/commit/39273403568f7ca13a349cac53fbb6a99d8823cc))
* login fails with error `req.session.regenerate is not a function` ([#2260](https://github.com/ParsePlatform/parse-dashboard/issues/2260)) ([1dc2b91](https://github.com/ParsePlatform/parse-dashboard/commit/1dc2b915e16a2038268f886d4c24e7b081ae0531))
* security upgrade terser from 5.10.0 to 5.14.2 ([#2222](https://github.com/ParsePlatform/parse-dashboard/issues/2222)) ([645cfdd](https://github.com/ParsePlatform/parse-dashboard/commit/645cfdd5939aca429b988e7a7c1a1b6a68230810))
* unnecessary count operations in Data Browser ([#2250](https://github.com/ParsePlatform/parse-dashboard/issues/2250)) ([bfc1684](https://github.com/ParsePlatform/parse-dashboard/commit/bfc1684375b7c2120e2a4ae566e5b3c38c0ca110))
* view relation dialog requires browser refresh when navigating ([#2275](https://github.com/ParsePlatform/parse-dashboard/issues/2275)) ([d60a8b7](https://github.com/ParsePlatform/parse-dashboard/commit/d60a8b7c1ab6c4c8dd85051d9c1acb05a0a69a59))

### Features

* add column name to related records ([#2264](https://github.com/ParsePlatform/parse-dashboard/issues/2264)) ([cc82533](https://github.com/ParsePlatform/parse-dashboard/commit/cc82533ae3066daa7b789131a76a409720d45b0b))
* add Node 18 support ([#2206](https://github.com/ParsePlatform/parse-dashboard/issues/2206)) ([bc7895a](https://github.com/ParsePlatform/parse-dashboard/commit/bc7895aadacc2cc6b0bbcfe786b73d7b82527e55))
* add option to auto-sort columns alphabetically ([#2252](https://github.com/ParsePlatform/parse-dashboard/issues/2252)) ([2b7f20f](https://github.com/ParsePlatform/parse-dashboard/commit/2b7f20fcc088f74915b50ec1219038ba9b233c27))
* apply filter in data browser by pressing "Enter" key ([#2256](https://github.com/ParsePlatform/parse-dashboard/issues/2256)) ([bc4f9eb](https://github.com/ParsePlatform/parse-dashboard/commit/bc4f9eb9cad9eb8e362dca20bf932cb3d1e6721c))
* auto-submit one-time password (OTP) after entering ([#2257](https://github.com/ParsePlatform/parse-dashboard/issues/2257)) ([e528705](https://github.com/ParsePlatform/parse-dashboard/commit/e5287054cff3bff368ba4e379eebf05bfb7d8bd5))
* improve button labels to be more concise in text ([#2207](https://github.com/ParsePlatform/parse-dashboard/issues/2207)) ([230fc14](https://github.com/ParsePlatform/parse-dashboard/commit/230fc1419db4d4de67c7e591cde415dbbe461c84))
* remove support and documentation links ([#2203](https://github.com/ParsePlatform/parse-dashboard/issues/2203)) ([35e4476](https://github.com/ParsePlatform/parse-dashboard/commit/35e44768f65c64a228cb6ea8314aa534c5342f08))
* show skeleton as loading indicator in data browser while data is loading ([#2273](https://github.com/ParsePlatform/parse-dashboard/issues/2273)) ([059f616](https://github.com/ParsePlatform/parse-dashboard/commit/059f616718006c6f559b0b07a8da641367497d9a))

## [4.1.4](https://github.com/ParsePlatform/parse-dashboard/compare/4.1.3...4.1.4) (2022-07-03)


### Bug Fixes

* login fails with error `req.session.regenerate is not a function` ([#2196](https://github.com/ParsePlatform/parse-dashboard/issues/2196)) ([a71848c](https://github.com/ParsePlatform/parse-dashboard/commit/a71848ce44fa19e579f9731bab50a7244ab89b11))

## [4.1.3](https://github.com/ParsePlatform/parse-dashboard/compare/4.1.2...4.1.3) (2022-07-02)


### Bug Fixes

* security upgrade semver-regex from 3.1.3 to 3.1.4 ([#2154](https://github.com/ParsePlatform/parse-dashboard/issues/2154)) ([4f9090a](https://github.com/ParsePlatform/parse-dashboard/commit/4f9090ad22460913f7987964ee54f26d348ca254))

## [4.1.2](https://github.com/ParsePlatform/parse-dashboard/compare/4.1.1...4.1.2) (2022-06-18)


### Bug Fixes

* config options like `--port` or `--config` are ignored ([#2113](https://github.com/ParsePlatform/parse-dashboard/issues/2113)) ([6d70d8a](https://github.com/ParsePlatform/parse-dashboard/commit/6d70d8aa74caf0d9c0d335a99a48347dc412ac4e))
* data export is missing rows when exporting more than 100 rows ([#2087](https://github.com/ParsePlatform/parse-dashboard/issues/2087)) ([88f1eab](https://github.com/ParsePlatform/parse-dashboard/commit/88f1eab418ff5ef7af24f9ef6583ccaedef2788e))
* preserve previous condition field value on constraint change ([#1969](https://github.com/ParsePlatform/parse-dashboard/issues/1969)) ([f4c3060](https://github.com/ParsePlatform/parse-dashboard/commit/f4c30605f675bd7a681be127b2dfb3fc11f90e32))
* security upgrade async from 2.6.3 to 2.6.4 ([#2094](https://github.com/ParsePlatform/parse-dashboard/issues/2094)) ([283745c](https://github.com/ParsePlatform/parse-dashboard/commit/283745c7c1ebe1bc6f35670f1b6f3b644b94043e))
* security upgrade cross-fetch from 3.1.4 to 3.1.5 ([#2105](https://github.com/ParsePlatform/parse-dashboard/issues/2105)) ([8d42622](https://github.com/ParsePlatform/parse-dashboard/commit/8d426226e6431793e275b68d680776443675ee35))
* security upgrade node-fetch from 2.6.5 to 2.6.7 ([#2114](https://github.com/ParsePlatform/parse-dashboard/issues/2114)) ([5423b0d](https://github.com/ParsePlatform/parse-dashboard/commit/5423b0d70cb72081933ed7531a55f49d39f3b92c))
* upgrade graphiql from 1.8.4 to 1.8.5 ([#2111](https://github.com/ParsePlatform/parse-dashboard/issues/2111)) ([1a50d30](https://github.com/ParsePlatform/parse-dashboard/commit/1a50d30b6b7d769e04c2c8e82d60142dd2e52b70))

### Reverts

* feat: change string filter description ([#2059](https://github.com/ParsePlatform/parse-dashboard/issues/2059)) ([db5d23b](https://github.com/ParsePlatform/parse-dashboard/commit/db5d23bf17f65d0db3e5d0d4ef4ca506d8394fb9))

## [4.1.1](https://github.com/ParsePlatform/parse-dashboard/compare/4.1.0...4.1.1) (2022-05-01)


### Bug Fixes

* security upgrade js-beautify from 1.14.0 to 1.14.1 ([#2077](https://github.com/ParsePlatform/parse-dashboard/issues/2077)) ([e4ea787](https://github.com/ParsePlatform/parse-dashboard/commit/e4ea7879d88173b02d66b1339ba98805255ba82c))
* security vulnerability bump minimist from 1.2.5 to 1.2.6 ([#2070](https://github.com/ParsePlatform/parse-dashboard/issues/2070)) ([3d0407e](https://github.com/ParsePlatform/parse-dashboard/commit/3d0407ebd75051bbbe6f0a2aba87b26475e901b9))

# [4.1.0](https://github.com/ParsePlatform/parse-dashboard/compare/4.0.1...4.1.0) (2022-04-03)


### Bug Fixes

* adding internal class (e.g. `_User`) fails due to prefixed underscore ([#2036](https://github.com/ParsePlatform/parse-dashboard/issues/2036)) ([e004e70](https://github.com/ParsePlatform/parse-dashboard/commit/e004e701737718f010978b0830d64bf8e1d8c559))
* security upgrade prismjs from 1.26.0 to 1.27.0 ([#2047](https://github.com/ParsePlatform/parse-dashboard/issues/2047)) ([ffbca12](https://github.com/ParsePlatform/parse-dashboard/commit/ffbca12c80bf32052a1a2b5d315c8a3393d82248))
* upgrade @babel/runtime from 7.17.0 to 7.17.2 ([#2055](https://github.com/ParsePlatform/parse-dashboard/issues/2055)) ([3e8449b](https://github.com/ParsePlatform/parse-dashboard/commit/3e8449b1679f803e9d26876ccfd28f88fea814ff))
* upgrade express from 4.17.2 to 4.17.3 ([#2058](https://github.com/ParsePlatform/parse-dashboard/issues/2058)) ([d1357de](https://github.com/ParsePlatform/parse-dashboard/commit/d1357de1281244f040499a2ca54db0faee4d882c))
* upgrade otpauth from 7.0.10 to 7.0.11 ([#2061](https://github.com/ParsePlatform/parse-dashboard/issues/2061)) ([05c5ac8](https://github.com/ParsePlatform/parse-dashboard/commit/05c5ac87a6cf1675889e58330276dac185929a01))

### Features

* change string filter description ([#2059](https://github.com/ParsePlatform/parse-dashboard/issues/2059)) ([6470c8e](https://github.com/ParsePlatform/parse-dashboard/commit/6470c8e3221e3b4ec95ecd831726a914d24ff619))

## [4.0.1](https://github.com/ParsePlatform/parse-dashboard/compare/4.0.0...4.0.1) (2022-03-03)


### Bug Fixes

* bump follow-redirects from 1.14.4 to 1.14.7 ([#1997](https://github.com/ParsePlatform/parse-dashboard/issues/1997)) ([4ca2e97](https://github.com/ParsePlatform/parse-dashboard/commit/4ca2e971890c6ee7ee88195a4c75dbb73dc5a0b1))
* bump markdown-it from 12.3.0 to 12.3.2 ([#1996](https://github.com/ParsePlatform/parse-dashboard/issues/1996)) ([245c22e](https://github.com/ParsePlatform/parse-dashboard/commit/245c22ea21f1af6f3e74a269d74460d5c5ea5c03))
* bump marked from 0.8.2 to 4.0.10 ([#2001](https://github.com/ParsePlatform/parse-dashboard/issues/2001)) ([ae4cc90](https://github.com/ParsePlatform/parse-dashboard/commit/ae4cc900bdbdc4425f0f30c07c6ef689c8cebe8c))
* bump nanoid from 3.1.28 to 3.2.0 ([#2008](https://github.com/ParsePlatform/parse-dashboard/issues/2008)) ([6cfe9ca](https://github.com/ParsePlatform/parse-dashboard/commit/6cfe9cae63a49013489e5683b5e16ab3c4399730))
* calendar widget layout partly hides last days of a month ([#1990](https://github.com/ParsePlatform/parse-dashboard/issues/1990)) ([5bd86dd](https://github.com/ParsePlatform/parse-dashboard/commit/5bd86dd0a5c7857705089cb8a57c078d62863dfc))
* cannot save nullish values for required fields ([#2003](https://github.com/ParsePlatform/parse-dashboard/issues/2003)) ([e1a5497](https://github.com/ParsePlatform/parse-dashboard/commit/e1a5497d4a999d18dcf60f93cdba16d36250a7cc))
* crash when checking for new dashboard release without internet connection ([#2015](https://github.com/ParsePlatform/parse-dashboard/issues/2015)) ([8c36e69](https://github.com/ParsePlatform/parse-dashboard/commit/8c36e693c08a960c4002d7d29bde7d111eff2cd4))
* preserve column sorting preferences in data browser ([#2016](https://github.com/ParsePlatform/parse-dashboard/issues/2016)) ([c2e6557](https://github.com/ParsePlatform/parse-dashboard/commit/c2e65573ccfa29b6d6e727e93b9552380c520f86))
* upgrade parse from 3.4.0 to 3.4.1 ([#2011](https://github.com/ParsePlatform/parse-dashboard/issues/2011)) ([68cf9e2](https://github.com/ParsePlatform/parse-dashboard/commit/68cf9e238594df29c22a687b2976d56894897f34))
* various UI bugs (e.g. filter data browser, switch app, upload file) ([#2010](https://github.com/ParsePlatform/parse-dashboard/issues/2010)) ([a508a58](https://github.com/ParsePlatform/parse-dashboard/commit/a508a58ce927fd7e08d249818c38f6fb1305956c))

# [4.0.0](https://github.com/ParsePlatform/parse-dashboard/compare/3.3.0...4.0.0) (2022-02-06)


### Bug Fixes

* bump graphiql from 1.4.6 to 1.4.7 ([#1920](https://github.com/ParsePlatform/parse-dashboard/issues/1920)) ([26c0dfa](https://github.com/ParsePlatform/parse-dashboard/commit/26c0dfa7eaa68194d53beaeed1ca6705f3d11a6a))
* context menu in data browser not opening for cell of type number ([#1913](https://github.com/ParsePlatform/parse-dashboard/issues/1913)) ([fb0e3a9](https://github.com/ParsePlatform/parse-dashboard/commit/fb0e3a9882438069fef1d7926ec74bad6bb3eebc))
* opening filter menu in data browser leads to blank page ([#1958](https://github.com/ParsePlatform/parse-dashboard/issues/1958)) ([750e8b1](https://github.com/ParsePlatform/parse-dashboard/commit/750e8b1f018e37360e6577f423da005d7f773f20))
* saving relation column fails if class has required fields ([#1937](https://github.com/ParsePlatform/parse-dashboard/issues/1937)) ([c67db08](https://github.com/ParsePlatform/parse-dashboard/commit/c67db083a9657be2d16ba566a7f6ce497fd66092))
* security upgrade qrcode from 1.4.4 to 1.5.0 ([#1930](https://github.com/ParsePlatform/parse-dashboard/issues/1930)) ([244e1bb](https://github.com/ParsePlatform/parse-dashboard/commit/244e1bba1a3fb89b9ed8c93a3d0f7163eacd2691))
* various UI bugs (e.g. filter data browser, switch app, upload file) ([#2014](https://github.com/ParsePlatform/parse-dashboard/issues/2014)) ([785978e](https://github.com/ParsePlatform/parse-dashboard/commit/785978ecce501cf23cb7fc3d82fa3f7c7dce7f6a))

### Features

* upgrade graphiql from 1.4.7 to 1.5.1 ([#1943](https://github.com/ParsePlatform/parse-dashboard/issues/1943)) ([ebb1f66](https://github.com/ParsePlatform/parse-dashboard/commit/ebb1f660f1d10921f92d05eb58b09d548e00d3a9))
* upgrade graphql from 15.7.0 to 16.0.0 ([#1926](https://github.com/ParsePlatform/parse-dashboard/issues/1926)) ([7c94e51](https://github.com/ParsePlatform/parse-dashboard/commit/7c94e512ed5428797823d24ac205ece59e94f3ea))
* upgrade parse from 3.3.1 to 3.4.0 ([#1942](https://github.com/ParsePlatform/parse-dashboard/issues/1942)) ([13a250e](https://github.com/ParsePlatform/parse-dashboard/commit/13a250e2e04ba0f12be0c2da8c9075ea8eb4d83f))


### BREAKING CHANGES

* The minimum required Node.js version is 12.22.0. ([7c94e51](7c94e51))
* The required Node version was increased to >=12.20.0. ([ebb1f66](ebb1f66))

# [3.3.0](https://github.com/ParsePlatform/parse-dashboard/compare/3.2.1...3.3.0) (2022-01-01)


### Bug Fixes

* always pass boolean value when toggling checkbox ([#1872](https://github.com/ParsePlatform/parse-dashboard/issues/1872)) ([2e9fd59](https://github.com/ParsePlatform/parse-dashboard/commit/2e9fd59c2ce33f60c904213dc0b5956c4fbfe0c9))
* app icons are cropped in the app list for small screen sizes ([#1876](https://github.com/ParsePlatform/parse-dashboard/issues/1876)) ([9fc56a6](https://github.com/ParsePlatform/parse-dashboard/commit/9fc56a6be210d82c4f1b03e804bd492d0848a62d))
* bump graphiql from 1.4.6 to 1.4.7 ([#1920](https://github.com/ParsePlatform/parse-dashboard/issues/1920)) ([35fd021](https://github.com/ParsePlatform/parse-dashboard/commit/35fd021cb7d7cc05dd6a532948caa25b51fd8340))
* context menu in data browser not opening for cell of type number ([#1913](https://github.com/ParsePlatform/parse-dashboard/issues/1913)) ([8731c35](https://github.com/ParsePlatform/parse-dashboard/commit/8731c350bd1867cedbaa735f035d16dde4033bc7))
* link icon in pointer cell not visible when cell is too narrow ([#1856](https://github.com/ParsePlatform/parse-dashboard/issues/1856)) ([69b897d](https://github.com/ParsePlatform/parse-dashboard/commit/69b897d17f379f9e5af1a0f64c557f54054ebe67))
* manual column preferences are overwritten by columnPreference option on page refresh ([#1881](https://github.com/ParsePlatform/parse-dashboard/issues/1881)) ([7232b0b](https://github.com/ParsePlatform/parse-dashboard/commit/7232b0b13916ee9bc409279242b5d4bbc4fee033))
* notification to upgrade dashboard for latest features not working ([#1894](https://github.com/ParsePlatform/parse-dashboard/issues/1894)) ([81361b6](https://github.com/ParsePlatform/parse-dashboard/commit/81361b67946a347d31ef96d61e3dd11503a6ad5b))
* upgrade graphql from 15.4.0 to 15.6.0 ([#1853](https://github.com/ParsePlatform/parse-dashboard/issues/1853)) ([fca9b14](https://github.com/ParsePlatform/parse-dashboard/commit/fca9b14cbe23ea0537bebb48bc390484932257c7))
* upgrade graphql from 15.6.0 to 15.6.1 ([#1887](https://github.com/ParsePlatform/parse-dashboard/issues/1887)) ([0cfe59e](https://github.com/ParsePlatform/parse-dashboard/commit/0cfe59e475d9f991a3579eb81e8e8a24705eec6a))
* upgrade inquirer from 8.1.3 to 8.2.0 ([#1886](https://github.com/ParsePlatform/parse-dashboard/issues/1886)) ([c77f335](https://github.com/ParsePlatform/parse-dashboard/commit/c77f335f6203842d0c83bc161ced0376ae166f26))
* upgrade passport from 0.4.1 to 0.5.0 ([#1865](https://github.com/ParsePlatform/parse-dashboard/issues/1865)) ([8d845f0](https://github.com/ParsePlatform/parse-dashboard/commit/8d845f0b59d161d21b6b28691b9962869fac2f20))
* upload of file as default value fails when adding a new column ([#1875](https://github.com/ParsePlatform/parse-dashboard/issues/1875)) ([6040dd0](https://github.com/ParsePlatform/parse-dashboard/commit/6040dd0dfe3315131dfeccc42f54cdf4d6d6b90e))

### Features

* add config option `columnPreference.filterSortToTop` to set column name order in filter dialog ([#1884](https://github.com/ParsePlatform/parse-dashboard/issues/1884)) ([3acbda1](https://github.com/ParsePlatform/parse-dashboard/commit/3acbda1cf2adfaa4471ef761c81e000eb1d04a97))
* add pointer representation by a chosen column instead of objectId ([#1852](https://github.com/ParsePlatform/parse-dashboard/issues/1852)) ([d747786](https://github.com/ParsePlatform/parse-dashboard/commit/d7477860ebf972a1cb69a43761e77841831754e2))
* add visual distinction in data browser for internal classes and display their real names with underscore ([#1878](https://github.com/ParsePlatform/parse-dashboard/issues/1878)) ([ac8d85e](https://github.com/ParsePlatform/parse-dashboard/commit/ac8d85e368d1ff0f2bc644b30264b9af7c86c76d))
* allow GraphIQL headers ([#1836](https://github.com/ParsePlatform/parse-dashboard/issues/1836)) ([3afcf73](https://github.com/ParsePlatform/parse-dashboard/commit/3afcf730c1303b3957ab03d683ada86242175579))
* allow graphQL headers ([34536b3](https://github.com/ParsePlatform/parse-dashboard/commit/34536b3ba200728e38ff017e487b0339bf0bee6b))

### Reverts

* Revert "Update CloudCode.react.js" ([eea1e2d](https://github.com/ParsePlatform/parse-dashboard/commit/eea1e2dad28795e55467091dc2f7d99790bdd3c4))

## [3.2.1](https://github.com/ParsePlatform/parse-dashboard/compare/3.2.0...3.2.1) (2021-10-08)


### Bug Fixes

* enabling context menu for read-only cells ([#1844](https://github.com/ParsePlatform/parse-dashboard/issues/1844)) ([a38a885](https://github.com/ParsePlatform/parse-dashboard/commit/a38a885db23e3a76c1e24f880e061dc882e1d37f))

# [3.2.0](https://github.com/ParsePlatform/parse-dashboard/compare/3.1.2...3.2.0) (2021-10-05)


### Features

* add ctrl + arrow key to jump to first/last cell; fix left/right key navigation with hidden columns ([#1827](https://github.com/ParsePlatform/parse-dashboard/issues/1827)) ([b504c0f](https://github.com/ParsePlatform/parse-dashboard/commit/b504c0fc555e0b8adc2ce796cd6928ea05bb3092))

## [3.1.2](https://github.com/ParsePlatform/parse-dashboard/compare/3.1.1...3.1.2) (2021-10-04)


### Refactor

* upgrade react-router-dom from 5.2.1 to 5.3.0 ([#1817](https://github.com/ParsePlatform/parse-dashboard/pull/1817)) ([8f359b3](https://github.com/ParsePlatform/parse-dashboard/commit/8f359b326dc69c7294ca8a208533cf58280357ad))

## [3.1.1](https://github.com/ParsePlatform/parse-dashboard/compare/3.1.0...3.1.1) (2021-09-30)


### Bug Fixes

* incorrect autofocus for login form input fields ([#1825](https://github.com/ParsePlatform/parse-dashboard/issues/1825)) ([7ca6aae](https://github.com/ParsePlatform/parse-dashboard/commit/7ca6aaed7e748057662017224b4a796ce8b6c99e))

# [3.1.0](https://github.com/ParsePlatform/parse-dashboard/compare/3.0.0...3.1.0) (2021-09-29)


### Features

* add support for npm 7 and Node 16, migrate to graphiql ([#1807](https://github.com/ParsePlatform/parse-dashboard/issues/1807)) ([b61fc7f](https://github.com/ParsePlatform/parse-dashboard/commit/b61fc7fadad608699634e3ff57d0df3a76c6d74a))

# 3.0.0
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.2.0...3.0.0)

## BREAKING CHANGE
- Parse Dashboard requires Node >=12.0.0 <16.0.0
- Reverts PR [#1706](https://github.com/parse-community/parse-dashboard/pull/1706) which introduced new database index requirements for pagination and was a breaking change that can lead to database performance issues if database indices were not adapted; reverting #1706 removes the `objectId` from the compound query; make sure that the database indices satisfy your dashboard sorting and filter usage before upgrading to this release to prevent database performance issues due to missing indices (Christopher Brookes) [#1800](https://github.com/parse-community/parse-dashboard/pull/1800)

## New Features
- Add multi-factor authentication to dashboard login. To use one-time password, run `parse-dashboard --createMFA` or `parse-dashboard --createUser`. (Daniel Blyth) [#1624](https://github.com/parse-community/parse-dashboard/pull/1624)

## Improvements
- Sidebar: Class counts are now updated when all counts are returned instead of after each call (Christopher Brookes) [#1802](https://github.com/parse-community/parse-dashboard/pull/1802)
- Update sass to 5.0.0 and make docker image use node:lts-alpine (Corey Baker) [#1792](https://github.com/parse-community/parse-dashboard/pull/1792)
- Docker image use now node 12 version (Christopher Brookes) [#1788](https://github.com/parse-community/parse-dashboard/pull/1788)
- CI now pushes docker images to Docker Hub (Corey Baker) [#1781](https://github.com/parse-community/parse-dashboard/pull/1781)
- Add CI check to add changelog entry (Manuel Trezza) [#1764](https://github.com/parse-community/parse-dashboard/pull/1764)
- Refactor: uniform issue templates across repos (Manuel Trezza) [#1767](https://github.com/parse-community/parse-dashboard/pull/1767)
- fix: date cell value not selected on double clicks (fn-faisal) [#1730](https://github.com/parse-community/parse-dashboard/pull/1730)

## Fixes
- Fixed bug after creating new class, wrong CLP was shown for that class [#1784](https://github.com/parse-community/parse-dashboard/issues/1784)  (Prerna Mehra) [#1785](https://github.com/parse-community/parse-dashboard/pull/1785)
- Fixed bug when opening a big modal, modal content is not visible due to Sidebar (Prerna Mehra) [#1777](https://github.com/parse-community/parse-dashboard/pull/1778)
- Fixed UI for a field containing an array of pointers (Prerna Mehra) [#1776](https://github.com/parse-community/parse-dashboard/pull/1776)
- Fixed bug when editing or copying a field containing an array of pointers [#1770](https://github.com/parse-community/parse-dashboard/issues/1770) (Prerna Mehra) [#1771](https://github.com/parse-community/parse-dashboard/pull/1771)
- Modernize CI (Manuel Trezza) [#1789](https://github.com/parse-community/parse-dashboard/pull/1789)
- ci: Remove parse-server dev dependency (Manuel Trezza) [#1796](https://github.com/parse-community/parse-dashboard/pull/1796)

# 2.2.0
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.1.0...2.2.0)

## New Features
- Added data export in CSV format for classes (Cory Imdieke, Manuel Trezza) [#1494](https://github.com/parse-community/parse-dashboard/pull/1494)
- Added collapsing sidebar for small screens (Douglas Muraoka, Manuel Trezza) [#1760](https://github.com/parse-community/parse-dashboard/pull/1760)
- Added exclude hidden columns from being fetched from server (itzharDev) [#1694](https://github.com/parse-community/parse-dashboard/pull/1694)
- Added cloning rows (Prerna Mehra) [#1697](https://github.com/parse-community/parse-dashboard/pull/1697)
- Added `Cmd`-click on pointer to open link in new browser tab (fn-faisal) [#1757](https://github.com/parse-community/parse-dashboard/pull/1757)
- Added browsing as another user (Nino Črljenec, Manuel Trezza) [#1750](https://github.com/parse-community/parse-dashboard/pull/1750)
- Added `columnPreference.preventSort` configuration option to prevent a column from being used for sorting (Christopher Brookes) [#1709](https://github.com/parse-community/parse-dashboard/pull/1709)
- Added `columnPreference` configuration option for data browser (dblythy) [#1625](https://github.com/parse-community/parse-dashboard/pull/1625)

## Improvements
- Improved navigation by redesigning pointer cell with link icon (Prerna Mehra) [#1708](https://github.com/parse-community/parse-dashboard/pull/1708)
- Improved rendering an array of pointers in cell (fn-faisal) [#1727](https://github.com/parse-community/parse-dashboard/pull/1727)
- Improved flow when creating a class and adding columns (fn-faisal) [#1728](https://github.com/parse-community/parse-dashboard/pull/1728)
- Added indication of required fields when adding new row (Prerna Mehra) [#1720](https://github.com/parse-community/parse-dashboard/pull/1720)
- Added indication of auto-populated fields when adding new row (Prerna Mehra) [#1692](https://github.com/parse-community/parse-dashboard/pull/1692)
- Added cancel button while adding a new row (Prerna Mehra) [#1690](https://github.com/parse-community/parse-dashboard/pull/1690)
- Added progress indicator when uploading a file in modal dialog (Prerna Mehra) [#1717](https://github.com/parse-community/parse-dashboard/pull/1717)
- Added tooltip for read-only fields (Prerna Mehra) [#1688](https://github.com/parse-community/parse-dashboard/pull/1688)
- Added message when no locale is set for localizing push notifications (Prerna Mehra) [#1685](https://github.com/parse-community/parse-dashboard/pull/1685)
- Updated to Parse JS SDK 3.3.0 (Manuel Trezza) [#1745](https://github.com/parse-community/parse-dashboard/pull/1745)
- Transitioned CI to GitHub Actions (Diamond Lewis) [#1640](https://github.com/parse-community/parse-dashboard/pull/1640)
- Added finish date to Cloud Job status (Diamond Lewis) [#1620](https://github.com/parse-community/parse-dashboard/pull/1620)

## Fixes
- Fixed clear state.data when setting relation to prevent column type mismatch (John Dillick) [#1564](https://github.com/parse-community/parse-dashboard/pull/1564)
- Fixed incorrect setting of pointer CLPs (mess-lelouch) [#1556](https://github.com/parse-community/parse-dashboard/pull/1556)
- Fixed master key not being passed in when saving file in global config (stevestencil) [#1581](https://github.com/parse-community/parse-dashboard/pull/1581)
- Fixes toolbar overlap to page title (Sergei Smirnov) [#1578](https://github.com/parse-community/parse-dashboard/pull/1578)
- Fixed various issues with edit row dialog (Nino Črljenec) [#1586](https://github.com/parse-community/parse-dashboard/pull/1586)
- Fixed date filters in data browser (Prerna Mehra) [#1682](https://github.com/parse-community/parse-dashboard/pull/1682)
- Fixed `expiresAt` field in `Session` class not appearing as read-only (Prerna Mehra) [#1686](https://github.com/parse-community/parse-dashboard/pull/1686)
- Fixed missing error message on failed clone row task (Prerna Mehra) [#1687](https://github.com/parse-community/parse-dashboard/pull/1687)
- Fixes missing or duplicate rows displayed when scrolling; this fix may require the additional creation of database indices to avoid performance issues, see PR discussion (Prerna Mehra) [#1706](https://github.com/parse-community/parse-dashboard/pull/1706)
- Fixed missing key binding for copy, paste, cancel while adding a new row (Christopher Brookes) [#1714](https://github.com/parse-community/parse-dashboard/pull/1714)
- Fixed setup locales message when adding all locales to push notification (Prerna Mehra) [#1691](https://github.com/parse-community/parse-dashboard/pull/1691)
- Fixed no error message displayed when trying to add column with a name that has a leading number (Prerna Mehra) [#1718](https://github.com/parse-community/parse-dashboard/pull/1718)
- Fixed fetching data when un-hiding column despite that data is already cached (Prerna Mehra) [#1734](https://github.com/parse-community/parse-dashboard/pull/1734)
- Fixed incorrect documentation (Philipp B) [#1592](https://github.com/parse-community/parse-dashboard/pull/1592)
- Fixed various dependency vulnerabilities

# 2.1.0
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.0.5...2.1.0)

__New features:__
* Added JS Console to run custom queries ([#1464](https://github.com/parse-community/parse-dashboard/pull/1464)), thanks to [Pedro Mutter](https://github.com/MutterPedro).
* View/Edit single row modal ([#1448](https://github.com/parse-community/parse-dashboard/pull/1448)), thanks to [NIno Črljenec](https://github.com/NinoZX).
* Context menu with quick filters and links to related records in other Parse Objects ([#1431](https://github.com/parse-community/parse-dashboard/pull/1431)), thanks to [404-html](https://github.com/404-html).
* Add ProtectedFields dialog and enhance Permissions dialogs ([#1478](https://github.com/parse-community/parse-dashboard/pull/1478)), thanks to [Old Grandpa](https://github.com/BufferUnderflower).

__Improvements:__
* Added config param delete confirmation dialog ([#1443](https://github.com/parse-community/parse-dashboard/pull/1443)), thanks to [Manuel Trezza](https://github.com/mtrezza).

__Fixes:__
* Inifite scroll not working ([#1432](https://github.com/parse-community/parse-dashboard/pull/1432)), thanks to [Douglas Muraoka](https://github.com/douglasmuraoka).
* Fix crash in import semver re: npm/node-semver#305 ([#1441](https://github.com/parse-community/parse-dashboard/pull/1441)), thanks to [Ben Petty](https://github.com/benpetty).
* Taking hidden columns into account when calculating Editor position ([#1438](https://github.com/parse-community/parse-dashboard/pull/1438)), thanks to [404-html](https://github.com/404-html).
* Fix audience conditions when Installation class does not exist ([#1451](https://github.com/parse-community/parse-dashboard/pull/1451)), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo).

### 2.0.5
 [Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.0.4...2.0.5)
 * Fix: delete and regenerate package-lock to fix broken build

### 2.0.4
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.0.3...2.0.4)
* Fix: Restore `ObjectId` to filter ([#1315](https://github.com/parse-community/parse-dashboard/pull/1315)), thanks to [Wolfwood](https://github.com/W0lfw00d)
* Fix: Prevent duplicate entries when sorting by `createdAt` ([#1334](https://github.com/parse-community/parse-dashboard/pull/1334)), thanks to [Wolfwood](https://github.com/W0lfw00d)

### 2.0.3
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.0.2...2.0.3)
* Fix: Feature "masterkey parameters" requires Parse Server >= 3.9.0 ([#1281](https://github.com/parse-community/parse-dashboard/pull/1281)), thanks to [Manuel Trezza](https://github.com/mtrezza)
* Fix: CLP dialog for pointer fields ([#1283](https://github.com/parse-community/parse-dashboard/pull/1283)), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo)
* Fix: Force pointer array items to always be pointers ([#1291](https://github.com/parse-community/parse-dashboard/pull/1291)), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo)

### 2.0.2
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.0.1...2.0.2)
* Fix: filter tab not working for _User, and ohter classes starting with _ ([#1275](https://github.com/parse-community/parse-dashboard/pull/1275)), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo)
* Fix: Data Browser is not updating accordingly ([#1276](https://github.com/parse-community/parse-dashboard/pull/1276)), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo)
* NEW: Copy cell value using CTRL+C ([#1272](https://github.com/parse-community/parse-dashboard/pull/1272)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* Docs: Update NodeJS required version in README ([#1265](https://github.com/parse-community/parse-dashboard/pull/1265)), thanks to [Jerome](https://github.com/JeromeDeLeon)

### 2.0.1
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/2.0.0...2.0.1)
* Publishing it again since there is an old test 2.0.0 release already published to npm

### 2.0.0
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.4.3...2.0.0)
* Fix: Cell edit not updating partial view ([#1255](https://github.com/parse-community/parse-dashboard/pull/1255)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* Improve: Table performance improvements ([#1241](https://github.com/parse-community/parse-dashboard/pull/1241)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* Fix: Avoid filter tab disappears on apply filter ([#1229](https://github.com/parse-community/parse-dashboard/pull/1229)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* NEW: Change columns order and visibility ([#1235](https://github.com/parse-community/parse-dashboard/pull/1235)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* Improve: Table not scrolling when using arrow keys ([#1239](https://github.com/parse-community/parse-dashboard/pull/1239)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* NEW: Add masterkey parameters ([#1233](https://github.com/parse-community/parse-dashboard/pull/1233)), thanks to [Manuel](https://github.com/mtrezza)
* Improve: Editing values not possible on mobile ([#1222](https://github.com/parse-community/parse-dashboard/pull/1222)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* Fix: JSON conversion breaking file upload process ([#1225](https://github.com/parse-community/parse-dashboard/pull/1225)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* NEW: Support building on Windows ([#1115](https://github.com/parse-community/parse-dashboard/pull/1115)), thanks to [Diamond Lewis](https://github.com/dplewis)
* Improve: Avoid Parse transformations on array and object fields ([#1223](https://github.com/parse-community/parse-dashboard/pull/1223)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* NEW: Select all objects ([#1219](https://github.com/parse-community/parse-dashboard/pull/1219)), thanks to [Douglas Muaroka](https://github.com/douglasmuraoka)
* NEW: Boolean dropdown on installation condition ([#1221](https://github.com/parse-community/parse-dashboard/pull/1221)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* NEW: String editor resizable ([#1217](https://github.com/parse-community/parse-dashboard/pull/1217)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* Fix: Update PIG examples to work with react-dnd 3.x ([#1214](https://github.com/parse-community/parse-dashboard/pull/1214)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* Fix: Fonts on AppsIndex ([#1197](https://github.com/parse-community/parse-dashboard/pull/1197)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* NEW: Add required and default value options ([#1193](https://github.com/parse-community/parse-dashboard/pull/1193)), thanks to [Lucas Alencar](https://github.com/alencarlucas)

#### Breaking Changes:
* Parse Dashboard now requires Node.js version >= 8.9

### 1.4.3
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.4.2...1.4.3)
* Fix 1.4.2 release.

### 1.4.2
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.4.1...1.4.2)
* Feature: Include count CLP option ([#1180](https://github.com/parse-community/parse-dashboard/pull/1180)), thanks to [Douglas Muroaka](https://github.com/douglasmuraoka)
* Fix: AppsMenu broken layout when app name is too long ([#1164](https://github.com/parse-community/parse-dashboard/pull/1164)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* Fix: getFileName lib to display correctly the filename ([#1154](https://github.com/parse-community/parse-dashboard/pull/1154)), thanks to [Yago Tomé](https://github.com/yagotome)
* Fix: Scroll is not working properly ([#1151](https://github.com/parse-community/parse-dashboard/pull/1151)), thanks to [Lucas Alencar](https://github.com/alencarlucas)
* Fix: AppsMenu not closing after selecting app ([#1146](https://github.com/parse-community/parse-dashboard/pull/1146)), thanks to [Douglas Muroaka](https://github.com/douglasmuraoka)
* Feature: Add client key into GraphQL console by default ([#1142](https://github.com/parse-community/parse-dashboard/pull/1142)), thanks to [Douglas Muroaka](https://github.com/douglasmuraoka)
* Fix: GraphQL console headers menu not visible ([#1141](https://github.com/parse-community/parse-dashboard/pull/1141)), thanks to [Douglas Muroaka](https://github.com/douglasmuraoka)
* Fix: project not installing due to package-lock ([#1143](https://github.com/parse-community/parse-dashboard/pull/1143)), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo)

### 1.4.1
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.4.0...1.4.1)
* Fix: 1.4.0 failed to deploy to npm.  Reset credentials and trying again.

### 1.4.0
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.3.3...1.4.0)
* Security Fix: see the [advisory](https://github.com/parse-community/parse-dashboard/network/alert/package-lock.json/lodash/open) for details. [22d748](https://github.com/parse-community/parse-dashboard/pull/1134/commits/22d748fdc1e95661dc39226f5f797dc8fb0e5c2f)
* Feature: GraphQL API playground ([#1123](https://github.com/parse-community/parse-dashboard/pull/1123)), thanks to [Douglas Muraoka](https://github.com/douglasmuraoka)
* Fix: Can't switch (dropdown list) between servers [#1045](https://github.com/parse-community/parse-dashboard/issues/1045) ([#1125](https://github.com/parse-community/parse-dashboard/pull/1125)), thanks to [Douglas Muraoka](https://github.com/douglasmuraoka)

### 1.3.3
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.3.2...1.3.3)

* FIX: Travis configuration which was preventing 1.3.2 from publishing, thanks to [Diamond Lewis](https://github.com/dplewis)

### 1.3.2
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.3.1...1.3.2)

* FIX: Dockerhub configuration which was preventing 1.3.1 from publishing ([#1098](https://github.com/parse-community/parse-dashboard/pull/1098)), thanks to [Diamond Lewis](https://github.com/dplewis)

### 1.3.1
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.3.0...1.3.1)

* FIX: Correct inappropriate error message when no target audience is selected ([#1052](https://github.com/parse-community/parse-dashboard/pull/1052)), thanks to [Bouimadaghene](https://github.com/starbassma)
* FIX: issue regarding lost mount path ([#1070](https://github.com/parse-community/parse-dashboard/pull/1070)), thanks to [Diamond Lewis](https://github.com/dplewis)
* NEW: Add distinct / unique filter ([#920](https://github.com/parse-community/parse-dashboard/pull/920)), thanks to [Diamond Lewis](https://github.com/dplewis)

### 1.3.0
[Full Changelog](https://github.com/parse-community/parse-dashboard/compare/1.2.0...1.3.0)

* Node 10 Support, thanks [Florent Vilmart](https://github.com/flovilmart)
* Fix: Remove column dialog default values (#969), thanks to [Jonas Stendahl](https://github.com/JStonevalley)
* Fix: Handle case of null in array (#922), thanks to [Abdullah Alsigar](https://github.com/agent3bood)
* Fix: JSON file upload (#935), thanks to [joshuadiezmo](https://github.com/joshuadiezmo)
* Fix: Set initial audience null (#910), thanks to [Paulo Reis](https://github.com/paulovitin)
* Fix: Ensure we traverse the payloadJSON properly (#861), thanks [Florent Vilmart](https://github.com/flovilmart)
* Improvements: Push Audiences (#813), thanks [Florent Vilmart](https://github.com/flovilmart)
* Improvements: Docker Build
* Feature: `preventSchemaEdits` option (#960), thanks to [Cyril Chandelier](https://github.com/cyrilchandelier)
* Feature: Redirect to the first app browser when only a single app is registered (#958), thanks to [Cyril Chandelier](https://github.com/cyrilchandelier)
* Feature: Add classname to browser title (#913), thanks to [Paulo Reis](https://github.com/paulovitin)
* Feature: Support for Clone Object (#946), thanks to [Diamond Lewis](https://github.com/dplewis)
* Feature: Add tvOS support to push targeting (#936), thanks to [Thomas Kollbach](https://github.com/toto)
* Feature: When using username to login, display dashboard username (#800), thanks to [Abdullah Alsigar](https://github.com/agent3bood)


### 1.2.0
* Fix: Filtering with a 1-digit number (#831), thanks to [Pascal Giguère](https://github.com/pgiguere1)
* Fix: Databrowser shows correct count of filtered objects, thanks to [Tom Engelbrecht](https://github.com/engel)
* Feature: Add primaryBackgroundColor and secondaryBackgroundColor in AppCard, thanks to [AreyouHappy](https://github.com/AreyouHappy)
* Improvement: Removes forcing sort on createdAt (#796), thanks to [Florent Vilmart](https://github.com/flovilmart)
* Fix: Broken Learn More link to cloud code documentation page (#828), thanks to [Stefan Trauth](https://github.com/funkenstrahlen)
* Fix: Add `_PushStatus` add to SpecialClasses (#701), thanks to [Dongwoo Gim](https://github.com/gimdongwoo)
* Fix: Include PushAudience query (#795), thanks to [marvelm](https://github.com/marvelm)

### 1.1.2

* Fix: An issue introduced when using readOnlyMasterKey would make all users readOnly after one has logged in.
* Reverts: Dependency updates that would render the build unstable / broken.

### 1.1.1

* Fix: Updating array of Dates now keeps it's type (was changing to array of ISO strings, issue #590), thanks to [David Riha](https://github.com/rihadavid)
* Fix: NaN displayed when filter input is empty or negative number (#749), thanks to [Miguel Serrrano](https://github.com/miguel-s)
* Fix: Addresses issue related to displaying iOS alert object containing title and body keys (#539), thanks to [Robert Martin del Campo](https://github.com/repertus)
* Feature: Adds support for localized push notifications if server version is high enough, thanks to [Florent Vilmart](https://github.com/flovilmart)
* Feature: Adds support for readOnly masterKey, thanks to [Florent Vilmart](https://github.com/flovilmart)
* Feature: Adds support for polygon types, thansk to [Mads Bjerre](https://github.com/madsb)
* Feature: Adds support for push time, expiration time, and expiration interval, thanks to [Marvel Mathew](https://github.com/marvelm)

### 1.1.0

* Feature: UI for managing push audiences (#712), thanks to [Davi Macedo](https://github.com/davimacedo)
* Feature: When editing Object or Array fields the data is displayed in a prettier format and the textarea is resizable (#734), thanks to [Samuli Siivinen](https://github.com/ssamuli)
* Fix: Display bug on safari when table has empty cells ('') (#731), thanks to [Samuli Siivinen](https://github.com/ssamuli)
* Fix: Added message that notifies Background Jobs requiring additional setup (#740 & #741), thanks to [Samuli Siivinen](https://github.com/ssamuli) and [Natan Rolnik](https://github.com/natanrolnik)

### 1.0.28
* Feature: Add ability to search Object columns (#727), thanks to [Samuli Siivinen](https://github.com/ssamuli)
* Improvement: Added/fixed a filtering option "contains string" for String fields. Case insensitive for now (#728), thanks to [Samuli Siivinen](https://github.com/ssamuli)
* Improvement: Sort config data according to parameter names (#726), thanks to [Natan Rolnik](https://github.com/natanrolnik)

### 1.0.27
* Improvement: Show notifications upon success or failure of save and delete objects (#718), thanks to [Natan Rolnik](https://github.com/natanrolnik)
* Improvement: Moves download option into file editor (#716), thanks to [Natan Rolnik](https://github.com/natanrolnik)

### 1.0.26
* Improvement: Fixes broken links, thanks to [Arthur Cinader](https://github.com/acinader)
* Improvement: Title on the add row button, thanks to [Abdul Basit](https://github.com/basitsattar)
* Improvement: Use slim docker image, thanks to [Tyler Brock](https://github.com/tbrock)
* Fix: table scrolling on google chrome (#671), thanks to [Jacer Omri](https://github.com/JacerOmri)
* Various: adds eslint, thanks to [Jeremy Louie](https://github.com/JeremyPlease)

### 1.0.25

* Improvement: Update and add links to sidebar footer (#661), thanks to [Natan Rolnik](https://github.com/natanrolnik)
* Fix: Don’t call unsupported endpoints in Parse Server (#660), thanks to [Natan Rolnik](https://github.com/natanrolnik)
* Fix: Display correctly Files and GeoPoints in Config (#666), thanks to [Natan Rolnik](https://github.com/natanrolnik)

### 1.0.24

* Improvement: Data browser updates object count when table is filtered (#652), thanks to [Mike Rizzo](https://github.com/rizzomichaelg)
* Improvement: Apps name sorting by name (#654), thanks to [Thilo Schmalfuß](https://github.com/scthi)
* Fix: Fetch jobs list not showing (#656), thanks to [Natan Rolnik](https://github.com/natanrolnik)

### 1.0.23

* Improvement: Enabling web hooks (#584), thanks to [Antonio Davi Macedo Coelho de Castro](https://github.com/davimacedo)
* Improvement: Set autofocus on the username input field (#644), thanks to [Herman Liang](https://github.com/hermanliang)
* Fix: Browser won't render class table with field that contains an object (#623), thanks to [Jordan Haven](https://github.com/jordanhaven)
* Fix: Config FETCH results in 401 (#575), thanks to [Matt Simms](https://github.com/brndmg)

### 1.0.22

* Fix issue affecting logging screen with encrypted passwords, thanks to [lsohn](https://github.com/lsohn)

### 1.0.21

* Fix: Use mountPath for all log in and log out redirects

### 1.0.20

* New: Form based login page instead of basic auth (#562), thanks to [Jeremy Louie](https://github.com/JeremyPlease)
* Fix: Can't send push to specific user (#570), thanks to [Dan VanWinkle](https://github.com/dvanwinkle)
* Fix: Download link in footer menu (#567), thanks to [Pavel Ivanov](https://github.com/pivanov)

### 1.0.19

* New: Support for trusting proxies w/ HTTPS
* New: Support for filtering string with `ends with`
* New: View parse-server based jobs
* New: Button to add rows from browser toolbar
* New: Support for encrypted passwords
* New: Support for sorting by `createdAt`
* Improvement: Push audiences support
* Fix: Calendar dates support

### 1.0.18

* Fix: Revert history change that was causing issues when mounting on express

### 1.0.17

* Fix: Revert mount path change that was causing issues when mounting on express

### 1.0.16

* New: Add options to add selected rows to a relation, thanks to [Han BaHwan](https://github.com/Beingbook)
* New: Add ability to use bcrypted passwords, thanks to [Dan VanWinkle](https://github.com/dvanwinkle)
* Fix: Fix deletion of columns, thanks to [Bryan Rhea](https://github.com/brheal)

### 1.0.15

* New: Add ability to delete all rows in a class, thanks to [Marco Cheung](https://github.com/Marco129)
* New: Add relation editor, thanks to [Han BaHwan](https://github.com/Beingbook)
* Fix: Bug when alert is missing in payload, thanks to [Herman Liang](https://github.com/hermanliang)
* Fix: Improve target display in Push viewer, thanks to [Herman Liang](https://github.com/hermanliang)
* Fix: Open docs and other sidebar links in new tab, thanks to [Konstantinos N.](https://github.com/kwstasna)

### 1.0.14

* Fix bug in past push page

### 1.0.13

* Fix log retrieval, thanks to [Jérémy Thiry](https://github.com/poltib)
* Improved GeoPoint editor and ESC button in editors, thanks to [Sam Schooler](https://github.com/samschooler)
* Add push status page to dashboard, thanks to [Jeremy Pease](https://github.com/JeremyPlease)

### 1.0.12

* Fix minor style issues
* Add pointer permissions editor
* Allow cancellation of edits in data browser using ESC key, thanks to [Manuel](https://github.com/mtrezza)
* Show error messages in the console when your app's icons can't be found, thanks to [Saif Al-Dilaimi](https://github.com/deada92)

### 1.0.11

* Add the ability to specify SSL cert and key, thanks to [Cory Imdieke](https://github.com/Vortec4800)
* Trust proxy when enabling --allowInsecureHTTP, thanks to [Andrew Chen](https://github.com/yongjhih)
* Fix App index when apps have an apostrophe in the name
* Fix display of prod/dev flag
* Support for Node 6

### 1.0.10

* Add the ability to specify icons for your app, thanks to [Natan Rolnik](https://github.com/natanrolnik)
* Fix sending push with JSON data

### 1.0.9

* Add the ability to mount the dashboard express app on a custom mount path, thanks to [hpello](https://github.com/hpello) with bugfixes from [mamaso](https://github.com/mamaso)
* Add ability to restrict certain users to certain apps, thanks to [Felipe Andrade](https://github.com/felipemobile)
* Fix Dockerfile, thanks to [Kakashi Liu](https://github.com/kkc)
* Display Parse Dashboard version, thanks to [Aayush Kapoor](https://github.com/xeoneux) and [gateway](https://github.com/gateway)
* Add a refresh button to the data browser, thanks to [TylerBrock](https://github.com/TylerBrock)
* Add logs viewer
* Misc. performance improvements and bugfixes, thanks to [Pavel Ivanov](https://github.com/pivanov)

### 1.0.8

* Allow Dashboard to be mounted as Express middleware, thanks to [Florent Vilmart](https://github.com/flovilmart)
* Add an option to specify that your app is in production, thanks to [Dylan Diamond](https://github.com/dcdspace)
* Fix GeoPoints in Parse Config, thanks to [Dylan Diamond](https://github.com/dcdspace)
* Allow specification of the host the dashboard runs on, thanks to [hpello](https://github.com/hpello)
* Miscellaneous look-and-feel improvements

### 1.0.7

* Fix sending pushes with badge increment

### 1.0.6

* Send push notifications from the dashboard
* Add object count to relation browser, thanks to [Sergey Gavrilyuk](https://github.com/gavrix)

### 1.0.5

* Fix new features notification

### 1.0.4

* Class level permissions editor
