# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [6.2.9-nightly.20221003](https://github.com/ionic-team/ionic/compare/v6.0.0-beta.3...v6.2.9-nightly.20221003) (2022-10-03)


### Bug Fixes

* **accordion-group:** ionChange is now fired properly in vue ([#24063](https://github.com/ionic-team/ionic/issues/24063)) ([61b99d1](https://github.com/ionic-team/ionic/commit/61b99d13bfab5c57617cbcdc7e54e43f88885f66)), closes [#23762](https://github.com/ionic-team/ionic/issues/23762)
* **accordion-group:** only allow keyboard interaction if header is focused ([#25091](https://github.com/ionic-team/ionic/issues/25091)) ([e1b555f](https://github.com/ionic-team/ionic/commit/e1b555f286956574876924068304fc44a78c027c))
* **accordion:** accordions expand when using binding ([#25322](https://github.com/ionic-team/ionic/issues/25322)) ([61e571e](https://github.com/ionic-team/ionic/commit/61e571e585ed8ad9b0ca2f98f57bb16616413ba6)), closes [#25307](https://github.com/ionic-team/ionic/issues/25307)
* **accordion:** improve functionality with nested accordions ([#24302](https://github.com/ionic-team/ionic/issues/24302)) ([0920797](https://github.com/ionic-team/ionic/commit/0920797612a5ee3aac1c38d8bffe4fd1e80b6987))
* **accordion:** items inside of the content now correct display borders ([#24618](https://github.com/ionic-team/ionic/issues/24618)) ([d3311df](https://github.com/ionic-team/ionic/commit/d3311df96765948d0a395e4ba99fb9117b44adcb)), closes [#24613](https://github.com/ionic-team/ionic/issues/24613)
* **action-sheet:** add aria-labelledby ([#25837](https://github.com/ionic-team/ionic/issues/25837)) ([5270151](https://github.com/ionic-team/ionic/commit/527015184e9413c1037277d3197bcaa33044c38c))
* **action-sheet:** background includes safe area margin ([#24700](https://github.com/ionic-team/ionic/issues/24700)) ([8c22646](https://github.com/ionic-team/ionic/commit/8c22646d66e2077fc88aaacf350330097733bb9b)), closes [#24699](https://github.com/ionic-team/ionic/issues/24699)
* **action-sheet:** safe area is now accounted for in MD mode ([#24176](https://github.com/ionic-team/ionic/issues/24176)) ([642255e](https://github.com/ionic-team/ionic/commit/642255e514fd67238d9bd8ea90781111687c6d03)), closes [#24175](https://github.com/ionic-team/ionic/issues/24175)
* **alert:** add default aria-label ([#25800](https://github.com/ionic-team/ionic/issues/25800)) ([d395a73](https://github.com/ionic-team/ionic/commit/d395a73cb6c419e6c0072746b8e4768cd5f78ef3))
* **alert:** AlertButton role now has correct types ([#23791](https://github.com/ionic-team/ionic/issues/23791)) ([864212b](https://github.com/ionic-team/ionic/commit/864212b0f28d33daede5f4767aa03efa37c219ae))
* **alert:** made it easier to tell if alert is scrollable in MD mode ([#23976](https://github.com/ionic-team/ionic/issues/23976)) ([a262753](https://github.com/ionic-team/ionic/commit/a26275378f10835343ad8a6cdea50303e6c10a14))
* **alert:** use aria-labelledby and aria-describedby instead of aria-label ([#25805](https://github.com/ionic-team/ionic/issues/25805)) ([27318d7](https://github.com/ionic-team/ionic/commit/27318d75df60dfce1a90f23ba31ea2b6636ba42f))
* **all:** import path is now correct when using ionic in a stencil app ([#25123](https://github.com/ionic-team/ionic/issues/25123)) ([1b407ab](https://github.com/ionic-team/ionic/commit/1b407abdf5d8a2a18b6a2b9daca2d58b7b0f782b)), closes [#25122](https://github.com/ionic-team/ionic/issues/25122)
* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **all:** Ionic components that use child Ionic components are now correctly defined ([#24191](https://github.com/ionic-team/ionic/issues/24191)) ([5a2a335](https://github.com/ionic-team/ionic/commit/5a2a335784aab581cda90448193e48f687df6b15)), closes [#23571](https://github.com/ionic-team/ionic/issues/23571) [#24116](https://github.com/ionic-team/ionic/issues/24116) [#24129](https://github.com/ionic-team/ionic/issues/24129)
* **all:** long press now preserves activated state ([#25551](https://github.com/ionic-team/ionic/issues/25551)) ([a8286f6](https://github.com/ionic-team/ionic/commit/a8286f6e42f734a027416ac6cd659e3dce4edccb)), closes [#25544](https://github.com/ionic-team/ionic/issues/25544)
* **all:** ripple effect is no longer added when scrolling ([#25352](https://github.com/ionic-team/ionic/issues/25352)) ([0b275af](https://github.com/ionic-team/ionic/commit/0b275af5ac06f470b4d908b889f513956bf5d868)), closes [#22030](https://github.com/ionic-team/ionic/issues/22030)
* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **angular:** inline modals now add .ion-page class correctly ([#24751](https://github.com/ionic-team/ionic/issues/24751)) ([ef46eaf](https://github.com/ionic-team/ionic/commit/ef46eafc9476a85ea3369e542f528d01d3cca0a8)), closes [#24750](https://github.com/ionic-team/ionic/issues/24750)
* **angular:** prevent duplicate event emissions ([#24200](https://github.com/ionic-team/ionic/issues/24200)) ([fc1eae9](https://github.com/ionic-team/ionic/commit/fc1eae982d7493f5b69fb18829f9c796f05a0d47))
* **animation:** improve compatibility with ssr ([#25992](https://github.com/ionic-team/ionic/issues/25992)) ([02234f6](https://github.com/ionic-team/ionic/commit/02234f69e0333266b4d500f24b3bb002c099bda2)), closes [#25987](https://github.com/ionic-team/ionic/issues/25987)
* **back-button, breadcrumb, item:** flip chevron icons on RTL ([#24705](https://github.com/ionic-team/ionic/issues/24705)) ([a093544](https://github.com/ionic-team/ionic/commit/a093544fdfc438ed03024285b2a35c5f645ea011))
* **back-button:** MD ripple now accounts for --ripple-color ([#23749](https://github.com/ionic-team/ionic/issues/23749)) ([6b18a89](https://github.com/ionic-team/ionic/commit/6b18a89ac2c446082ce7faebe329157eedb13a0e)), closes [#23748](https://github.com/ionic-team/ionic/issues/23748)
* **back-button:** pass aria-label to native element ([#24027](https://github.com/ionic-team/ionic/issues/24027)) ([68a7e43](https://github.com/ionic-team/ionic/commit/68a7e43345a0261fdeed6054198c5a22fbbcb584))
* **breadcrumb:** separator is not announced by narrators ([#25796](https://github.com/ionic-team/ionic/issues/25796)) ([71fad38](https://github.com/ionic-team/ionic/commit/71fad3884bc55b266067efb346500c848b856946))
* **breadcrumb:** support routerLink on breadcrumb ([#24509](https://github.com/ionic-team/ionic/issues/24509)) ([5bb1414](https://github.com/ionic-team/ionic/commit/5bb1414f7fa04ea07954cb3f68883ee2f162586a)), closes [#24493](https://github.com/ionic-team/ionic/issues/24493)
* **col:** col no longer errors when running in non-browser environment ([#24603](https://github.com/ionic-team/ionic/issues/24603)) ([af0135c](https://github.com/ionic-team/ionic/commit/af0135ce7dbe737b2df46094fd3dc8a41bdb60ae)), closes [#24446](https://github.com/ionic-team/ionic/issues/24446)
* **content:** ensure fixed slot renders on top of content in iOS ([#24300](https://github.com/ionic-team/ionic/issues/24300)) ([e41b0e0](https://github.com/ionic-team/ionic/commit/e41b0e0cf2a794972d7f4d8943a0bec3d1e08016))
* **content:** ensure scrollEl is always available in scroll methods ([#24255](https://github.com/ionic-team/ionic/issues/24255)) ([36a096c](https://github.com/ionic-team/ionic/commit/36a096c9b60bd6b3b086f2c966a1cd40dbc54473))
* **core:** @axe-core/playwright should be a devDependency ([#25244](https://github.com/ionic-team/ionic/issues/25244)) ([617ec48](https://github.com/ionic-team/ionic/commit/617ec48265157d1502c443395472c21ebdb2989e)), closes [#25242](https://github.com/ionic-team/ionic/issues/25242)
* **core:** inherit aria attributes on host elements ([#25156](https://github.com/ionic-team/ionic/issues/25156)) ([611832b](https://github.com/ionic-team/ionic/commit/611832b0d51da295c1bf2897972c4e8baf6e23a3)), closes [#20127](https://github.com/ionic-team/ionic/issues/20127)
* **css:** inline css source in source maps ([#24514](https://github.com/ionic-team/ionic/issues/24514)) ([987d46c](https://github.com/ionic-team/ionic/commit/987d46cfa6e48a932330f04f2e8eb7054b11baf8)), closes [#24441](https://github.com/ionic-team/ionic/issues/24441)
* **css:** preserve whitespace in selectors when minifying css ([#25767](https://github.com/ionic-team/ionic/issues/25767)) ([bafa759](https://github.com/ionic-team/ionic/commit/bafa759655a0f3ca206255ba429f21d319c37aed)), closes [#25766](https://github.com/ionic-team/ionic/issues/25766)
* **datetime:** account for 12AM with min times and 12 hour format ([#25952](https://github.com/ionic-team/ionic/issues/25952)) ([55ebd6c](https://github.com/ionic-team/ionic/commit/55ebd6cdf39c01b401e876b76e755bfa04db8f65)), closes [#25183](https://github.com/ionic-team/ionic/issues/25183)
* **datetime:** account for 30 and 45 minute timezones when getting current date ([#25120](https://github.com/ionic-team/ionic/issues/25120)) ([96b2003](https://github.com/ionic-team/ionic/commit/96b2003b2bd5089d1faafe262e96c7445c5c3349)), closes [#25112](https://github.com/ionic-team/ionic/issues/25112)
* **datetime:** account for previous years with preferWheel ([#25656](https://github.com/ionic-team/ionic/issues/25656)) ([3a7f5f1](https://github.com/ionic-team/ionic/commit/3a7f5f166ee8d8d7e1861313e2bc6f4856e4fbe9))
* **datetime:** add correct null check when value changes ([#25716](https://github.com/ionic-team/ionic/issues/25716)) ([36bea1c](https://github.com/ionic-team/ionic/commit/36bea1ca2520c9eb9ee7705abb046607a52d198d)), closes [#25714](https://github.com/ionic-team/ionic/issues/25714)
* **datetime:** add dev warnings when setting out of bounds value ([#25513](https://github.com/ionic-team/ionic/issues/25513)) ([5dfaf63](https://github.com/ionic-team/ionic/commit/5dfaf63c6582811b61339a6fa50cf551cd8724d0))
* **datetime:** add ionBlur/ionFocus events to whole component ([#23980](https://github.com/ionic-team/ionic/issues/23980)) ([86a77bd](https://github.com/ionic-team/ionic/commit/86a77bd379c6dca57d5feb9694d18afe6d82934d))
* **datetime:** add top padding to MD calendar month grid ([#24522](https://github.com/ionic-team/ionic/issues/24522)) ([bd82b5d](https://github.com/ionic-team/ionic/commit/bd82b5dc1d06ba22a5410858802d57735fdcf450)), closes [#24408](https://github.com/ionic-team/ionic/issues/24408)
* **datetime:** arrow navigation respects min/max values ([#25182](https://github.com/ionic-team/ionic/issues/25182)) ([6946e09](https://github.com/ionic-team/ionic/commit/6946e09815da605e37ff8e4d613a14288ea35fb0)), closes [#25073](https://github.com/ionic-team/ionic/issues/25073)
* **datetime:** calendar day and years are now localized ([#25847](https://github.com/ionic-team/ionic/issues/25847)) ([cbd1268](https://github.com/ionic-team/ionic/commit/cbd1268a03204f05314f2ba284ad433457a9cf33)), closes [#25843](https://github.com/ionic-team/ionic/issues/25843)
* **datetime:** change now emitted when picker is typed into ([#24018](https://github.com/ionic-team/ionic/issues/24018)) ([0320164](https://github.com/ionic-team/ionic/commit/03201643ba9ae34fa969c1542742d9cd95298c81))
* **datetime:** clear button is now rendered even if showDefaultButtons is false ([#24075](https://github.com/ionic-team/ionic/issues/24075)) ([e3996cf](https://github.com/ionic-team/ionic/commit/e3996cfbd50f5e9ae54ffcbe2594124e3b9969b0))
* **datetime:** close month/year picker when hidden ([#25789](https://github.com/ionic-team/ionic/issues/25789)) ([3b211b6](https://github.com/ionic-team/ionic/commit/3b211b60fd9a88be6e232f839ecc4be090181530)), closes [#25787](https://github.com/ionic-team/ionic/issues/25787)
* **datetime:** closing time picker no longer changes month ([#25478](https://github.com/ionic-team/ionic/issues/25478)) ([f9ab9b5](https://github.com/ionic-team/ionic/commit/f9ab9b54ddb5a3004673e4aaa9cb62fd8e97ba07)), closes [#25438](https://github.com/ionic-team/ionic/issues/25438)
* **datetime:** confirm method now uses selected date ([#24827](https://github.com/ionic-team/ionic/issues/24827)) ([c35b898](https://github.com/ionic-team/ionic/commit/c35b898f1dc0fb706446b6971982df48fd72fe6d)), closes [#24823](https://github.com/ionic-team/ionic/issues/24823)
* **datetime:** correct year is set in wheel picker ([#25896](https://github.com/ionic-team/ionic/issues/25896)) ([fb653eb](https://github.com/ionic-team/ionic/commit/fb653ebe67458a088adf0626741d190ceb2880a6)), closes [#25895](https://github.com/ionic-team/ionic/issues/25895)
* **datetime:** datetime locale with h23 will respect max time range ([#24610](https://github.com/ionic-team/ionic/issues/24610)) ([5925e76](https://github.com/ionic-team/ionic/commit/5925e7608ef04f8877e4dd8a80b2c8bdc1cfd4bd)), closes [#24588](https://github.com/ionic-team/ionic/issues/24588)
* **datetime:** datetime works within stencil apps ([#25592](https://github.com/ionic-team/ionic/issues/25592)) ([7b10fa6](https://github.com/ionic-team/ionic/commit/7b10fa6476c2c2896c6810c57b3160f8c8896faa)), closes [#25591](https://github.com/ionic-team/ionic/issues/25591)
* **datetime:** default sizing preserves shape of datetime ([#24104](https://github.com/ionic-team/ionic/issues/24104)) ([71fab0f](https://github.com/ionic-team/ionic/commit/71fab0fa124254f8cdc3b513627aa7b045993f4e))
* **datetime:** disable intersection observer during month update ([#24713](https://github.com/ionic-team/ionic/issues/24713)) ([aab4d30](https://github.com/ionic-team/ionic/commit/aab4d306f80851bfd8a02a6361e26d60faeaadb4)), closes [#24712](https://github.com/ionic-team/ionic/issues/24712)
* **datetime:** display time in user's timezone after selection ([#25694](https://github.com/ionic-team/ionic/issues/25694)) ([11c69c8](https://github.com/ionic-team/ionic/commit/11c69c8df50b75440c9e876b4d99d469d16e144f)), closes [#25693](https://github.com/ionic-team/ionic/issues/25693)
* **datetime:** don't update value on confirm call if no date was selected ([#25338](https://github.com/ionic-team/ionic/issues/25338)) ([9e5b10a](https://github.com/ionic-team/ionic/commit/9e5b10a2155c6b9de565931da384e0e49aeca7b7))
* **datetime:** emit ionChange for non-calendar picker presentation ([#25380](https://github.com/ionic-team/ionic/issues/25380)) ([4e6a60b](https://github.com/ionic-team/ionic/commit/4e6a60b6a42287e5091728aecb61f6097e131b83)), closes [#25375](https://github.com/ionic-team/ionic/issues/25375)
* **datetime:** ensure that default month shown is always in bounds ([#25351](https://github.com/ionic-team/ionic/issues/25351)) ([866d452](https://github.com/ionic-team/ionic/commit/866d4528ad1b8ffa65258595d553ea934daa4add)), closes [#25320](https://github.com/ionic-team/ionic/issues/25320)
* **datetime:** fix datetime-ready class sometimes not being added due to race condition ([#24385](https://github.com/ionic-team/ionic/issues/24385)) ([e7d0674](https://github.com/ionic-team/ionic/commit/e7d06743ae2e09864510940bf8a97bc312ef1cf8))
* **datetime:** hide footer when month-year picker is open ([#25205](https://github.com/ionic-team/ionic/issues/25205)) ([aa5e1b9](https://github.com/ionic-team/ionic/commit/aa5e1b962150b9ed9629812ec566873784526c83))
* **datetime:** highlights now show above content in modal ([#25756](https://github.com/ionic-team/ionic/issues/25756)) ([d711658](https://github.com/ionic-team/ionic/commit/d7116581c8e92716f49877abc78d93dc39c34e1d)), closes [#25755](https://github.com/ionic-team/ionic/issues/25755)
* **datetime:** hourCycle formats hour correctly ([#25869](https://github.com/ionic-team/ionic/issues/25869)) ([1a1491d](https://github.com/ionic-team/ionic/commit/1a1491df0242da1cb3c9a7f128bbd4d5ce4dbf3e)), closes [#25862](https://github.com/ionic-team/ionic/issues/25862)
* **datetime:** if no default value, don't highlight active day until one is selected ([#25151](https://github.com/ionic-team/ionic/issues/25151)) ([9896939](https://github.com/ionic-team/ionic/commit/98969395abd400cc44d2d3825581a63eb64a56e0))
* **datetime:** improve datetime sizing in modals ([#24762](https://github.com/ionic-team/ionic/issues/24762)) ([b0ac7de](https://github.com/ionic-team/ionic/commit/b0ac7de168c353ba4899cb74a2b38e25fd0cc0f1)), closes [#23992](https://github.com/ionic-team/ionic/issues/23992)
* **datetime:** ionChange is no longer called for out of range dates ([#23940](https://github.com/ionic-team/ionic/issues/23940)) ([ea39c6e](https://github.com/ionic-team/ionic/commit/ea39c6e5b3781ceb4c87277cf4a5e0be9c75bc20)), closes [#23939](https://github.com/ionic-team/ionic/issues/23939)
* **datetime:** keyboard navigation of time picker columns ([#24251](https://github.com/ionic-team/ionic/issues/24251)) ([8bdcd3c](https://github.com/ionic-team/ionic/commit/8bdcd3c6c99d84a0a46b0f08dceca6b6929fd8f8))
* **datetime:** minutes only filtered when max hour matches current hour ([#24710](https://github.com/ionic-team/ionic/issues/24710)) ([231d6df](https://github.com/ionic-team/ionic/commit/231d6df622c1f5dd9ecdff6fed8f61a4bff332df)), closes [#24702](https://github.com/ionic-team/ionic/issues/24702)
* **datetime:** month and year column order is now locale aware ([#24802](https://github.com/ionic-team/ionic/issues/24802)) ([16647b2](https://github.com/ionic-team/ionic/commit/16647b2c7290389755a4093145788f281c84b7e2)), closes [#24548](https://github.com/ionic-team/ionic/issues/24548)
* **datetime:** month grid no longer loops on ios ([#25857](https://github.com/ionic-team/ionic/issues/25857)) ([c938054](https://github.com/ionic-team/ionic/commit/c938054605dffb6c3002a64a3d8aaf36892c7a93)), closes [#25752](https://github.com/ionic-team/ionic/issues/25752)
* **datetime:** month picker no longer gives duplicate months on ios 14 and older ([#24792](https://github.com/ionic-team/ionic/issues/24792)) ([b6d7e1c](https://github.com/ionic-team/ionic/commit/b6d7e1c75740a61dcd02c21692e4d4632fb8df5c)), closes [#24663](https://github.com/ionic-team/ionic/issues/24663)
* **datetime:** navigate to month within min range ([#24759](https://github.com/ionic-team/ionic/issues/24759)) ([7b3838c](https://github.com/ionic-team/ionic/commit/7b3838cc670de7845bb5937d204e86cdba93b6e6)), closes [#24757](https://github.com/ionic-team/ionic/issues/24757)
* **datetime:** next and previous buttons have correct labels ([#25845](https://github.com/ionic-team/ionic/issues/25845)) ([41e3387](https://github.com/ionic-team/ionic/commit/41e338730d32837fc9dd8a15477e37dea4cc76c9)), closes [#25844](https://github.com/ionic-team/ionic/issues/25844)
* **datetime:** only log out of bounds warning if value set ([#25835](https://github.com/ionic-team/ionic/issues/25835)) ([85af6ce](https://github.com/ionic-team/ionic/commit/85af6ce436890eb922d2ba32053fb8b8bc7fd4ff)), closes [#25833](https://github.com/ionic-team/ionic/issues/25833)
* **datetime:** persist minutes column on hour change ([#24829](https://github.com/ionic-team/ionic/issues/24829)) ([aacb58a](https://github.com/ionic-team/ionic/commit/aacb58a3224e3cc51c731d0c9aa52f52c9276692)), closes [#24821](https://github.com/ionic-team/ionic/issues/24821)
* **datetime:** preferWheel respects column ordering by locale ([#25726](https://github.com/ionic-team/ionic/issues/25726)) ([dee0f51](https://github.com/ionic-team/ionic/commit/dee0f513ee443c0c69ea8e38a292c900e9c70221)), closes [#25722](https://github.com/ionic-team/ionic/issues/25722)
* **datetime:** presentation time emits ionChange once  ([#24968](https://github.com/ionic-team/ionic/issues/24968)) ([2909b08](https://github.com/ionic-team/ionic/commit/2909b080b7020299a4554c1459b4b190ff739085)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **datetime:** prevent navigating to disabled months ([#24421](https://github.com/ionic-team/ionic/issues/24421)) ([b40fc46](https://github.com/ionic-team/ionic/commit/b40fc4632efcdc01f1062d9bcec826afff5cf4ea)), closes [#24208](https://github.com/ionic-team/ionic/issues/24208) [#24482](https://github.com/ionic-team/ionic/issues/24482)
* **datetime:** prevent vertical page scroll on interaction ([#23780](https://github.com/ionic-team/ionic/issues/23780)) ([950350a](https://github.com/ionic-team/ionic/commit/950350a948320f889589a0c9d2ec9045637215e5)), closes [#23554](https://github.com/ionic-team/ionic/issues/23554)
* **datetime:** reduce time presentation min height ([#23771](https://github.com/ionic-team/ionic/issues/23771)) ([bc4e826](https://github.com/ionic-team/ionic/commit/bc4e8267aa00e7f162cd01579d8d3adbf3cd7a83)), closes [#23690](https://github.com/ionic-team/ionic/issues/23690)
* **datetime:** reinit behavior on presentation change ([#24828](https://github.com/ionic-team/ionic/issues/24828)) ([d46e1e8](https://github.com/ionic-team/ionic/commit/d46e1e8506ca5095817b421e9edb37d41451e885))
* **datetime:** resolve month and year jumping issue on ios ([#24142](https://github.com/ionic-team/ionic/issues/24142)) ([27aef93](https://github.com/ionic-team/ionic/commit/27aef9343cada9a83adec8fe00e8bc3bafa8e049)), closes [#23910](https://github.com/ionic-team/ionic/issues/23910)
* **datetime:** resolve warnings when importing into Stencil app ([#25106](https://github.com/ionic-team/ionic/issues/25106)) ([a61c004](https://github.com/ionic-team/ionic/commit/a61c004fb0c10d9fb0eca0987edf798386251ec2))
* **datetime:** RTL will no longer infinitely scroll ([#24475](https://github.com/ionic-team/ionic/issues/24475)) ([8f00008](https://github.com/ionic-team/ionic/commit/8f000089c2986f292147c7f501f23c8c7d1df457)), closes [#24472](https://github.com/ionic-team/ionic/issues/24472)
* **datetime:** selecting today with multiple date select now works ([#25699](https://github.com/ionic-team/ionic/issues/25699)) ([86b7000](https://github.com/ionic-team/ionic/commit/86b7000bcd1b4519e8c20907050e15ba7c99bab0))
* **datetime:** showing calendar grid no longer causes month to switch on ios 15 ([#24554](https://github.com/ionic-team/ionic/issues/24554)) ([3d20959](https://github.com/ionic-team/ionic/commit/3d2095922147ea3763e977412977edd9586fec5d)), closes [#24405](https://github.com/ionic-team/ionic/issues/24405)
* **datetime:** swiping wheel no longer dismisses card modal ([#25981](https://github.com/ionic-team/ionic/issues/25981)) ([7543c84](https://github.com/ionic-team/ionic/commit/7543c84445e6698d29cafe75b423c33115bc534c))
* **datetime:** switching months in wheel picker now selected nearest neighbor ([#25559](https://github.com/ionic-team/ionic/issues/25559)) ([dd256e1](https://github.com/ionic-team/ionic/commit/dd256e1313fa1c307f30b0dbb7fd0d1da8c555f7))
* **datetime:** switching presentation closes month/year picker ([#25667](https://github.com/ionic-team/ionic/issues/25667)) ([57a21ad](https://github.com/ionic-team/ionic/commit/57a21adb38331ee5d74dacd1b0a2568f41a2d21e))
* **datetime:** text color on ios mode now accounts for color contrast ([#23729](https://github.com/ionic-team/ionic/issues/23729)) ([5980db4](https://github.com/ionic-team/ionic/commit/5980db44e5a765d15e681471325e916d566eca8d)), closes [#23723](https://github.com/ionic-team/ionic/issues/23723)
* **datetime:** time picker display matches dynamically set value ([#25010](https://github.com/ionic-team/ionic/issues/25010)) ([11493a0](https://github.com/ionic-team/ionic/commit/11493a086a4e3f2a4e9d3acdf5a9d49e810a5ef0)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **datetime:** time picker format with hourCycle h23 ([#24476](https://github.com/ionic-team/ionic/issues/24476)) ([a3724e6](https://github.com/ionic-team/ionic/commit/a3724e6a5662c5bc1b724d80540530472827506e)), closes [#24474](https://github.com/ionic-team/ionic/issues/24474)
* **datetime:** time picker now scrolls to correct value ([#24879](https://github.com/ionic-team/ionic/issues/24879)) ([331ce6d](https://github.com/ionic-team/ionic/commit/331ce6d6769900e2aec9e30d35b52cfd40cbb889)), closes [#24878](https://github.com/ionic-team/ionic/issues/24878)
* **datetime:** time picker uses new iOS 15 style ([#23996](https://github.com/ionic-team/ionic/issues/23996)) ([0ab37b5](https://github.com/ionic-team/ionic/commit/0ab37b5061728bd60fd42781645b96add130a79f)), closes [#23768](https://github.com/ionic-team/ionic/issues/23768)
* **datetime:** timepicker popover will position relative to click target ([#24616](https://github.com/ionic-team/ionic/issues/24616)) ([378c632](https://github.com/ionic-team/ionic/commit/378c63264366964e6ea11e1a2ff8791a40f182d4)), closes [#24531](https://github.com/ionic-team/ionic/issues/24531) [#24415](https://github.com/ionic-team/ionic/issues/24415)
* **datetime:** typing in time now updates value ([#25561](https://github.com/ionic-team/ionic/issues/25561)) ([1b1b1a3](https://github.com/ionic-team/ionic/commit/1b1b1a3800c4d044b4a3e7418f534e9271770ec6)), closes [#25560](https://github.com/ionic-team/ionic/issues/25560)
* **datetime:** update active calendar display when value changes ([#24244](https://github.com/ionic-team/ionic/issues/24244)) ([ec3bc52](https://github.com/ionic-team/ionic/commit/ec3bc52ff194f1e4db4ce49548c1418c259b8795))
* **datetime:** update active day styling when day is selected ([#24454](https://github.com/ionic-team/ionic/issues/24454)) ([4304391](https://github.com/ionic-team/ionic/commit/430439191dba824c11290d7f8622fea10ced6c40)), closes [#24414](https://github.com/ionic-team/ionic/issues/24414) [#24451](https://github.com/ionic-team/ionic/issues/24451)
* **datetime:** use scroll listener to detect month changes ([#25586](https://github.com/ionic-team/ionic/issues/25586)) ([b7afcb0](https://github.com/ionic-team/ionic/commit/b7afcb0f0c36d84f3b4d65844df28e6293bc1ea5)), closes [#25257](https://github.com/ionic-team/ionic/issues/25257) [#25608](https://github.com/ionic-team/ionic/issues/25608) [#24980](https://github.com/ionic-team/ionic/issues/24980)
* **datetime:** warn when parsing an invalid date value ([#25049](https://github.com/ionic-team/ionic/issues/25049)) ([982dc85](https://github.com/ionic-team/ionic/commit/982dc853befe8ccf54163a0b145e563da06f5dc1))
* **datetime:** wheel picker shows correct column order in rtl ([#24546](https://github.com/ionic-team/ionic/issues/24546)) ([c90ce31](https://github.com/ionic-team/ionic/commit/c90ce311a86ccb7c06b1cde91a4659f6682df04d)), closes [#24378](https://github.com/ionic-team/ionic/issues/24378)
* **fab-button:** aria attributes are inherited ([#25635](https://github.com/ionic-team/ionic/issues/25635)) ([64ae3d2](https://github.com/ionic-team/ionic/commit/64ae3d2b9729c5c6be8644b1df6c8b3d40584d3b)), closes [#25633](https://github.com/ionic-team/ionic/issues/25633)
* **fab-button:** improve ripple effect behavior on click ([#25413](https://github.com/ionic-team/ionic/issues/25413)) ([efdaf90](https://github.com/ionic-team/ionic/commit/efdaf90c5a767211e0034bab7cce5bd463ff5aa0)), closes [#21772](https://github.com/ionic-team/ionic/issues/21772)
* **footer:** padding is added correctly with tabs ([#25921](https://github.com/ionic-team/ionic/issues/25921)) ([edbb64c](https://github.com/ionic-team/ionic/commit/edbb64c4b6de7ace7043675a85fd503da18304d7)), closes [#25918](https://github.com/ionic-team/ionic/issues/25918)
* **footer:** remove toolbar bottom padding if near bottom slot tabs or keyboard is open ([#25746](https://github.com/ionic-team/ionic/issues/25746)) ([bb37446](https://github.com/ionic-team/ionic/commit/bb374460320b0ba2ee03a5a0ecebb3e7a9f0728e))
* **header:** hide from screen readers when collapsed ([#25744](https://github.com/ionic-team/ionic/issues/25744)) ([d0ba963](https://github.com/ionic-team/ionic/commit/d0ba9635998f2157970156438c1bb74d6b9682f2))
* **header:** role attribute can now be customized ([#23888](https://github.com/ionic-team/ionic/issues/23888)) ([8888e2b](https://github.com/ionic-team/ionic/commit/8888e2bafd76b59f32b932b5d4a6a961b52894d9)), closes [#21327](https://github.com/ionic-team/ionic/issues/21327)
* **icon:** update to ionicons 6 to resolve typescript 4.4 errors ([#24185](https://github.com/ionic-team/ionic/issues/24185)) ([118c606](https://github.com/ionic-team/ionic/commit/118c606703f792f830d92f1148882b5daa3f180f))
* **img:** correctly determine when to load image when scrolling quickly on slower devices ([#23704](https://github.com/ionic-team/ionic/issues/23704)) ([067e621](https://github.com/ionic-team/ionic/commit/067e621bbc3865184ae114b8c91122188c13c860)), closes [#23703](https://github.com/ionic-team/ionic/issues/23703)
* **img:** draggable attribute is now inherited to inner img element ([#24781](https://github.com/ionic-team/ionic/issues/24781)) ([19ac238](https://github.com/ionic-team/ionic/commit/19ac2389eb0843173f51a12de41ac808cd8f0569)), closes [#21325](https://github.com/ionic-team/ionic/issues/21325)
* **infinite-scroll:** infinite scroll event now fired with custom elements build ([#24043](https://github.com/ionic-team/ionic/issues/24043)) ([8a86cfb](https://github.com/ionic-team/ionic/commit/8a86cfb7050989e914fa85ccc1ea755d73f58c90)), closes [#24034](https://github.com/ionic-team/ionic/issues/24034)
* **input,textarea:** data-form-type attribute is assigned to inner input ([#25927](https://github.com/ionic-team/ionic/issues/25927)) ([9451b28](https://github.com/ionic-team/ionic/commit/9451b283e2cb30ac9087574461f6b9f4b6cc3e0f)), closes [#25908](https://github.com/ionic-team/ionic/issues/25908)
* **input:** clear button is not activated on swipe ([#25825](https://github.com/ionic-team/ionic/issues/25825)) ([ff71ad4](https://github.com/ionic-team/ionic/commit/ff71ad492d7671f8e550da7e08dbde30cb05ebf7)), closes [#24857](https://github.com/ionic-team/ionic/issues/24857)
* **input:** cursor position does not jump to end ([#24736](https://github.com/ionic-team/ionic/issues/24736)) ([4ff9524](https://github.com/ionic-team/ionic/commit/4ff9524e1057aa487069b5982c5f1ecdf51d982b)), closes [#24727](https://github.com/ionic-team/ionic/issues/24727)
* **input:** date type in ion-input now aligns correctly on iOS 15 ([#24213](https://github.com/ionic-team/ionic/issues/24213)) ([9cf7c89](https://github.com/ionic-team/ionic/commit/9cf7c897043854a9d0db81d18ad6c016eb964de8))
* **input:** date type in ion-input now aligns correctly on iOS 15 ([#24217](https://github.com/ionic-team/ionic/issues/24217)) ([0566ec0](https://github.com/ionic-team/ionic/commit/0566ec0da3b8a66a1a1ebb1b235e7297ec483c79))
* **input:** exclude date inputs from scroll assist ([#25749](https://github.com/ionic-team/ionic/issues/25749)) ([abb56d2](https://github.com/ionic-team/ionic/commit/abb56d22b4a81d1bc34c689de4ef7218e7503b20)), closes [#25745](https://github.com/ionic-team/ionic/issues/25745)
* **input:** IME composition mode ([#24735](https://github.com/ionic-team/ionic/issues/24735)) ([c6381ce](https://github.com/ionic-team/ionic/commit/c6381ce4f90707774d1c8662bba874f7b306bd1c)), closes [#24669](https://github.com/ionic-team/ionic/issues/24669)
* **input:** ion-input accepts any string value ([#24606](https://github.com/ionic-team/ionic/issues/24606)) ([43c5977](https://github.com/ionic-team/ionic/commit/43c5977d48cb12331c1d3107eb73f29b92c5e049)), closes [#19884](https://github.com/ionic-team/ionic/issues/19884)
* **input:** ionInput event emits with type of InputEvent ([#24111](https://github.com/ionic-team/ionic/issues/24111)) ([52cd5d0](https://github.com/ionic-team/ionic/commit/52cd5d0ccedb8013c860198fc69f6bc0d4e6d386))
* **input:** min/max compatibility with react-hook-form ([#24657](https://github.com/ionic-team/ionic/issues/24657)) ([1f91883](https://github.com/ionic-team/ionic/commit/1f918835f437a59f7a70fc59d9305647aa9c298d)), closes [#24489](https://github.com/ionic-team/ionic/issues/24489)
* **input:** only set native input value if different ([#24758](https://github.com/ionic-team/ionic/issues/24758)) ([fd031aa](https://github.com/ionic-team/ionic/commit/fd031aa1c3f05b7bfa3e0a0ee2a4793e29e22df5)), closes [#24753](https://github.com/ionic-team/ionic/issues/24753)
* **ios:** swipe to go back now works in rtl mode ([#24866](https://github.com/ionic-team/ionic/issues/24866)) ([2ac9105](https://github.com/ionic-team/ionic/commit/2ac9105796a0765fabc48592b5b44ac58c568579)), closes [#19488](https://github.com/ionic-team/ionic/issues/19488)
* **item-sliding:** close() will maintain disabled state ([#24847](https://github.com/ionic-team/ionic/issues/24847)) ([ea4a9bb](https://github.com/ionic-team/ionic/commit/ea4a9bb69465f8e97746b36638f0b3a26e45da18)), closes [#24747](https://github.com/ionic-team/ionic/issues/24747)
* **item-sliding:** closing an item can no longer be interrupted ([#23973](https://github.com/ionic-team/ionic/issues/23973)) ([3ca0419](https://github.com/ionic-team/ionic/commit/3ca04197a4186c85d04cdf04fa9cb2689ca1bbfb)), closes [#23969](https://github.com/ionic-team/ionic/issues/23969)
* **item-sliding:** item-sliding accounts for multiple ion-item elements ([#23943](https://github.com/ionic-team/ionic/issues/23943)) ([8108edd](https://github.com/ionic-team/ionic/commit/8108edd876b10834015016385dc3cd5b8f31fbfa)), closes [#19312](https://github.com/ionic-team/ionic/issues/19312)
* **item-sliding:** prevent scrolling during slide gesture ([#23774](https://github.com/ionic-team/ionic/issues/23774)) ([e0c4ad3](https://github.com/ionic-team/ionic/commit/e0c4ad30bec3f2bd325d65b210ffb0437149810f)), closes [#19564](https://github.com/ionic-team/ionic/issues/19564)
* **item-sliding:** swiping inside of virtual scroller now prevents scrolling ([#25345](https://github.com/ionic-team/ionic/issues/25345)) ([5a1a5f6](https://github.com/ionic-team/ionic/commit/5a1a5f6b4c2ab4059158986e907fff45d03be753))
* **item, list:** list aria roles are added ([#25336](https://github.com/ionic-team/ionic/issues/25336)) ([311c634](https://github.com/ionic-team/ionic/commit/311c634d20e9e597db676d6f54e4b79cfe742a61)), closes [#19939](https://github.com/ionic-team/ionic/issues/19939)
* **item:** allow click targets inside of label ([#24225](https://github.com/ionic-team/ionic/issues/24225)) ([3949a94](https://github.com/ionic-team/ionic/commit/3949a949dfe112668c69a36d64e5f01a5aef1435))
* **item:** counter defaults to false to make upgrade easier ([#24263](https://github.com/ionic-team/ionic/issues/24263)) ([f61f356](https://github.com/ionic-team/ionic/commit/f61f35600072c5df069a24c3b24eb8f283d586f8))
* **item:** counter has appropriate contrast ([#25266](https://github.com/ionic-team/ionic/issues/25266)) ([750be33](https://github.com/ionic-team/ionic/commit/750be33772e9ba71a3cda35709d17b7912aa68e2)), closes [#25262](https://github.com/ionic-team/ionic/issues/25262)
* **item:** error slot visible in Safari ([#24579](https://github.com/ionic-team/ionic/issues/24579)) ([af01a8b](https://github.com/ionic-team/ionic/commit/af01a8b3073dce784cc042923d712b9492638d32)), closes [#24575](https://github.com/ionic-team/ionic/issues/24575)
* **item:** form validation caret color renders correctly ([#25725](https://github.com/ionic-team/ionic/issues/25725)) ([de20541](https://github.com/ionic-team/ionic/commit/de20541486bcf6e1d15f0ae5b0c5f177cce5eb38)), closes [#25719](https://github.com/ionic-team/ionic/issues/25719)
* **item:** form validation states are now properly shown ([#23853](https://github.com/ionic-team/ionic/issues/23853)) ([5ca2ce9](https://github.com/ionic-team/ionic/commit/5ca2ce91971408218d7bdc52509ce61a6ebb46aa)), closes [#23733](https://github.com/ionic-team/ionic/issues/23733) [#23850](https://github.com/ionic-team/ionic/issues/23850)
* **item:** highlight now appears above helper/error text ([#23763](https://github.com/ionic-team/ionic/issues/23763)) ([2995e33](https://github.com/ionic-team/ionic/commit/2995e337c8b4612a87eb7111224ec702494fd1d7)), closes [#23510](https://github.com/ionic-team/ionic/issues/23510)
* **item:** label text aligns with input text ([#24620](https://github.com/ionic-team/ionic/issues/24620)) ([94d033c](https://github.com/ionic-team/ionic/commit/94d033c4216ae9978aed6346c1c0ea2aec4d375b)), closes [#24404](https://github.com/ionic-team/ionic/issues/24404)
* **item:** match material design character counter ([#24335](https://github.com/ionic-team/ionic/issues/24335)) ([54db1a1](https://github.com/ionic-team/ionic/commit/54db1a1e7c71c78e843370848fc768582768333e)), closes [#24334](https://github.com/ionic-team/ionic/issues/24334)
* **item:** multiple input appearance when using datetime ([#25484](https://github.com/ionic-team/ionic/issues/25484)) ([3089f38](https://github.com/ionic-team/ionic/commit/3089f38f4d335c44e9913e874813dd4205c2b160)), closes [#25479](https://github.com/ionic-team/ionic/issues/25479)
* **item:** multiple input appearance when using datetime ([#25498](https://github.com/ionic-team/ionic/issues/25498)) ([1a8d23d](https://github.com/ionic-team/ionic/commit/1a8d23da8125d54c3119eacb51206f7541c9f410)), closes [#25484](https://github.com/ionic-team/ionic/issues/25484) [#25483](https://github.com/ionic-team/ionic/issues/25483)
* **item:** remove empty padding space for item bottom ([#24323](https://github.com/ionic-team/ionic/issues/24323)) ([500985c](https://github.com/ionic-team/ionic/commit/500985ce04783f502a1f5c50fbd8b4c5e93294d7)), closes [#23892](https://github.com/ionic-team/ionic/issues/23892)
* **item:** show the highlight on iOS when --highlight-height is set ([#25905](https://github.com/ionic-team/ionic/issues/25905)) ([d7db133](https://github.com/ionic-team/ionic/commit/d7db1333f13834ecb447b4b1da62cfffed9fb333))
* **label:** label now only takes up as much space as needed when slotted ([#23807](https://github.com/ionic-team/ionic/issues/23807)) ([9932e26](https://github.com/ionic-team/ionic/commit/9932e26a2ef28317bc85761e71a8fc4d881b8ae8)), closes [#23806](https://github.com/ionic-team/ionic/issues/23806)
* **label:** only inherit color if color property is set on ion-item ([#23944](https://github.com/ionic-team/ionic/issues/23944)) ([ae1325c](https://github.com/ionic-team/ionic/commit/ae1325cee698066a71aae4e7deb953c4185c0926)), closes [#20125](https://github.com/ionic-team/ionic/issues/20125)
* **label:** text contents will repaint on change ([#25395](https://github.com/ionic-team/ionic/issues/25395)) ([52ec741](https://github.com/ionic-team/ionic/commit/52ec74193b4e2478cb84a6dfea261cb2113dcbff))
* **loading:** spinner now respects —spinner-color ([#25261](https://github.com/ionic-team/ionic/issues/25261)) ([65f4c74](https://github.com/ionic-team/ionic/commit/65f4c742e7a5e5756f6f72dd853e38e885f90385)), closes [#25180](https://github.com/ionic-team/ionic/issues/25180)
* **md/label:** apply error appearance when control is touched ([#24072](https://github.com/ionic-team/ionic/issues/24072)) ([009dff5](https://github.com/ionic-team/ionic/commit/009dff5584fea6398bb99aa55760d25dafd7fbcc))
* **menu:** added focus trapping, improved compatibility with screen readers ([#24076](https://github.com/ionic-team/ionic/issues/24076)) ([bdb268a](https://github.com/ionic-team/ionic/commit/bdb268aa12c5bf411c96529672486d35e018cefa))
* **menu:** focus trapping with menu and overlays no longer results in errors ([#24611](https://github.com/ionic-team/ionic/issues/24611)) ([632dafc](https://github.com/ionic-team/ionic/commit/632dafcd57de5086deebdc7d586b01710aa1a3ce)), closes [#24361](https://github.com/ionic-team/ionic/issues/24361) [#24481](https://github.com/ionic-team/ionic/issues/24481)
* **menu:** preserve scroll position when focusing on open ([#25044](https://github.com/ionic-team/ionic/issues/25044)) ([da89684](https://github.com/ionic-team/ionic/commit/da896848776105ba1f7035c4412495786199bade))
* **menu:** remove main attribute that was supposed to removed in v5 ([#24565](https://github.com/ionic-team/ionic/issues/24565)) ([7704ac3](https://github.com/ionic-team/ionic/commit/7704ac3a3710396248590daecb945b76825a0539)), closes [#24563](https://github.com/ionic-team/ionic/issues/24563)
* **menu:** rtl menu no longer disappears on ios 15 ([#25309](https://github.com/ionic-team/ionic/issues/25309)) ([6005431](https://github.com/ionic-team/ionic/commit/60054310afbab6151f6c29ff6e74666acd181a41)), closes [#25192](https://github.com/ionic-team/ionic/issues/25192)
* **modal, popover:** do not dismiss when ionDismiss is emitted from select ([#25125](https://github.com/ionic-team/ionic/issues/25125)) ([90115db](https://github.com/ionic-team/ionic/commit/90115db98540a5fc67b611ac2742d1221b8e96ff)), closes [#25124](https://github.com/ionic-team/ionic/issues/25124)
* **modal, popover:** opening modal and popover now works even if overlay was added to ion-app directly ([#24174](https://github.com/ionic-team/ionic/issues/24174)) ([da339a8](https://github.com/ionic-team/ionic/commit/da339a8a743548f9bde8b5a22f1a9d6b191f6e7b)), closes [#23728](https://github.com/ionic-team/ionic/issues/23728)
* **modal, popover:** quickly opening modal/popover no longer presents duplicates ([#24697](https://github.com/ionic-team/ionic/issues/24697)) ([928c5fb](https://github.com/ionic-team/ionic/commit/928c5fbfcbf3ef1b2c3074464fc20dcf1fe143ae))
* **modal:** add canDismiss option to modal options ([#25144](https://github.com/ionic-team/ionic/issues/25144)) ([2984ddf](https://github.com/ionic-team/ionic/commit/2984ddf111b6acbd9e47ed90830b6522179b6cee)), closes [#25143](https://github.com/ionic-team/ionic/issues/25143)
* **modal:** allow for custom dialog implementations ([#25630](https://github.com/ionic-team/ionic/issues/25630)) ([a6f3ae6](https://github.com/ionic-team/ionic/commit/a6f3ae67ab91ab95408ad425156167edc3570978)), closes [#24080](https://github.com/ionic-team/ionic/issues/24080)
* **modal:** backdrop animation when backdropBreakpoint is 1 ([#25430](https://github.com/ionic-team/ionic/issues/25430)) ([c10df52](https://github.com/ionic-team/ionic/commit/c10df52f39c527dd7e03176c56a2e6cb0ebe455f)), closes [#25402](https://github.com/ionic-team/ionic/issues/25402)
* **modal:** backdropBreakpoint allows interactivity behind sheet ([#24798](https://github.com/ionic-team/ionic/issues/24798)) ([fca3f56](https://github.com/ionic-team/ionic/commit/fca3f56ca4568e63fd493debda088263caa86c64)), closes [#24797](https://github.com/ionic-team/ionic/issues/24797)
* **modal:** backdropBreakpoint is now an exclusive value ([#23954](https://github.com/ionic-team/ionic/issues/23954)) ([ed455ab](https://github.com/ionic-team/ionic/commit/ed455ab4c6df73f801a3c941da21261c205c9634))
* **modal:** border radius is now correctly applied to card modals ([#24204](https://github.com/ionic-team/ionic/issues/24204)) ([1f4f8eb](https://github.com/ionic-team/ionic/commit/1f4f8eb6ca2b8adb543ade83c309177ac7f2044d))
* **modal:** card modal can now be swiped to close on the content ([#25185](https://github.com/ionic-team/ionic/issues/25185)) ([7633ddb](https://github.com/ionic-team/ionic/commit/7633ddbc845745dfe36b5c8025c54c22c083c2f4)), closes [#22046](https://github.com/ionic-team/ionic/issues/22046)
* **modal:** card modal no longer dismisses from content with refresher ([#25227](https://github.com/ionic-team/ionic/issues/25227)) ([c4f811f](https://github.com/ionic-team/ionic/commit/c4f811f1dde0dcbcdaebaa3a4f5ef87e192b5cc5))
* **modal:** card modal shadow now shows up correctly on ipad ([#24203](https://github.com/ionic-team/ionic/issues/24203)) ([5d4f5af](https://github.com/ionic-team/ionic/commit/5d4f5af36083eafcf7de91b22749ff307701087f))
* **modal:** expose breakpoint props in ModalOptions interface ([#23867](https://github.com/ionic-team/ionic/issues/23867)) ([5fd80fd](https://github.com/ionic-team/ionic/commit/5fd80fd43885a5d0cd65f0eef4e0ff15e82c4fe0)), closes [#23866](https://github.com/ionic-team/ionic/issues/23866)
* **modal:** fix backdrop animation for sheets with off-center backdropBreakpoint ([#24061](https://github.com/ionic-team/ionic/issues/24061)) ([49db6d0](https://github.com/ionic-team/ionic/commit/49db6d02883b11b5f179300e2eaa298002a381e8))
* **modal:** fix timing issue when rapidly closing and opening controller modal ([#24380](https://github.com/ionic-team/ionic/issues/24380)) ([732f8e1](https://github.com/ionic-team/ionic/commit/732f8e10ce604f1a3e98518ae9c3a4afd7803e9a))
* **modal:** handle on sheet modal can now be turned off ([#23900](https://github.com/ionic-team/ionic/issues/23900)) ([e2d2ad6](https://github.com/ionic-team/ionic/commit/e2d2ad6f8eaf798c6f4b4a69f2b8176f0ac22d32))
* **modal:** handleBehavior can be used with controller ([#25821](https://github.com/ionic-team/ionic/issues/25821)) ([79ef1b5](https://github.com/ionic-team/ionic/commit/79ef1b57dc74fd856ed7c2904d7400d283cc081e)), closes [#25820](https://github.com/ionic-team/ionic/issues/25820)
* **modal:** inline modals inherit ion-page styling ([#24723](https://github.com/ionic-team/ionic/issues/24723)) ([596aad4](https://github.com/ionic-team/ionic/commit/596aad435b5102307da89dd626ca4682b78db452)), closes [#24706](https://github.com/ionic-team/ionic/issues/24706)
* **modal:** life cycle events for controller modals ([#24508](https://github.com/ionic-team/ionic/issues/24508)) ([9a15753](https://github.com/ionic-team/ionic/commit/9a15753fd95e32155abdeb490ec57cb72385ad1a)), closes [#24460](https://github.com/ionic-team/ionic/issues/24460)
* **modal:** modal displays in middle of screen on desktop ([#23911](https://github.com/ionic-team/ionic/issues/23911)) ([9d87028](https://github.com/ionic-team/ionic/commit/9d87028e81723a0f1498c8cf231319676078eda0))
* **modal:** native keyboard will dismiss when bottom sheet is dragged ([#24642](https://github.com/ionic-team/ionic/issues/24642)) ([525f01f](https://github.com/ionic-team/ionic/commit/525f01f086ebf95ab62af0162b876a25f50a3d4b)), closes [#23878](https://github.com/ionic-team/ionic/issues/23878)
* **modal:** re-enable swipe gestures when modal is dismissed ([#24846](https://github.com/ionic-team/ionic/issues/24846)) ([836c01c](https://github.com/ionic-team/ionic/commit/836c01c73e42caab0101ac4988f0a9b27cf96a5b)), closes [#24817](https://github.com/ionic-team/ionic/issues/24817)
* **modal:** reset breakpoint to initial breakpoint on present ([#25246](https://github.com/ionic-team/ionic/issues/25246)) ([2557bf3](https://github.com/ionic-team/ionic/commit/2557bf3c3eed9e33e89e07a8d73489da8d81bee3)), closes [#25245](https://github.com/ionic-team/ionic/issues/25245)
* **modal:** role attribute can be customized ([#25804](https://github.com/ionic-team/ionic/issues/25804)) ([037d579](https://github.com/ionic-team/ionic/commit/037d579b2a3a660358f1e9c9b020c9510bb9c6b0))
* **modal:** sheet animation works correctly if breakpoints value does not include 1 ([#23927](https://github.com/ionic-team/ionic/issues/23927)) ([414f246](https://github.com/ionic-team/ionic/commit/414f24685cbc67a7fff142b7786d33ce1cd67a0c))
* **modal:** sheet is easier to dismiss with swipe ([#25883](https://github.com/ionic-team/ionic/issues/25883)) ([fa169d2](https://github.com/ionic-team/ionic/commit/fa169d2dca649107342fe365ef6c7da892ebb8fd)), closes [#24296](https://github.com/ionic-team/ionic/issues/24296)
* **modal:** sheet modal handle is now positioned correctly ([#23901](https://github.com/ionic-team/ionic/issues/23901)) ([58a4ba2](https://github.com/ionic-team/ionic/commit/58a4ba285389e45276df49a0b4a3412daa95e92c))
* **modal:** sheet modal now accounts for safe area ([#23884](https://github.com/ionic-team/ionic/issues/23884)) ([195d817](https://github.com/ionic-team/ionic/commit/195d8179676155315f8532636b6371dd2a63e4b9)), closes [#23874](https://github.com/ionic-team/ionic/issues/23874)
* **modal:** sheet modal now allows input focusing when backdrop disabled ([#24840](https://github.com/ionic-team/ionic/issues/24840)) ([e4ec572](https://github.com/ionic-team/ionic/commit/e4ec572043e22bd2626dbcfd204fc22a7335282c)), closes [#24581](https://github.com/ionic-team/ionic/issues/24581)
* **modal:** status bar color now correct with sheet modal ([#25424](https://github.com/ionic-team/ionic/issues/25424)) ([377c4f5](https://github.com/ionic-team/ionic/commit/377c4f597b972818d90132017d50c33074ddadab)), closes [#20501](https://github.com/ionic-team/ionic/issues/20501)
* **modal:** swipe to close on content blocks scroll in ion-nav ([#25300](https://github.com/ionic-team/ionic/issues/25300)) ([fdc55c0](https://github.com/ionic-team/ionic/commit/fdc55c072765c87ad7c783e6d8a238b007f5f3ff)), closes [#25298](https://github.com/ionic-team/ionic/issues/25298)
* **nav:** custom animation is now used correctly ([#23779](https://github.com/ionic-team/ionic/issues/23779)) ([f9415ef](https://github.com/ionic-team/ionic/commit/f9415ef8a689e26078bdd01623348c79f9f818ad)), closes [#23777](https://github.com/ionic-team/ionic/issues/23777)
* **nav:** exclude nav from custom dialog ([#25689](https://github.com/ionic-team/ionic/issues/25689)) ([d1e517b](https://github.com/ionic-team/ionic/commit/d1e517bfef03b822dfa7651681013277762eda08)), closes [#25677](https://github.com/ionic-team/ionic/issues/25677) [#25688](https://github.com/ionic-team/ionic/issues/25688)
* **nav:** pop() will unmount views within a modal ([#25638](https://github.com/ionic-team/ionic/issues/25638)) ([db28794](https://github.com/ionic-team/ionic/commit/db28794f0b75f2824ae26c101a8c52af70f43ffd)), closes [#25637](https://github.com/ionic-team/ionic/issues/25637) [#21831](https://github.com/ionic-team/ionic/issues/21831)
* **nav:** swipe to go back works inside card modal ([#25333](https://github.com/ionic-team/ionic/issues/25333)) ([0156be6](https://github.com/ionic-team/ionic/commit/0156be61cbf73b25cb3c2cba1bd20adebbb3db4f)), closes [#25327](https://github.com/ionic-team/ionic/issues/25327)
* **overlays:** declarative modals now work properly with the hardware back button ([#24165](https://github.com/ionic-team/ionic/issues/24165)) ([b3759ae](https://github.com/ionic-team/ionic/commit/b3759aed5bd1ec6a7c744af03d0dac9c8055c5af))
* **overlays:** define children custom elements ([#24372](https://github.com/ionic-team/ionic/issues/24372)) ([7c700b4](https://github.com/ionic-team/ionic/commit/7c700b4caa35d7eb50c877d794f9db9fad6ed88b)), closes [#24366](https://github.com/ionic-team/ionic/issues/24366)
* **overlays:** define custom element children ([#24439](https://github.com/ionic-team/ionic/issues/24439)) ([4715b83](https://github.com/ionic-team/ionic/commit/4715b83abb30ec5930710d16e5bfe8fc88a940ce)), closes [#24393](https://github.com/ionic-team/ionic/issues/24393)
* **overlays:** focus is not moved if active element is in overlay ([#25481](https://github.com/ionic-team/ionic/issues/25481)) ([dcc2da2](https://github.com/ionic-team/ionic/commit/dcc2da2800e69d938b4a62db436d9f07d9663dce)), closes [#24127](https://github.com/ionic-team/ionic/issues/24127) [#24820](https://github.com/ionic-team/ionic/issues/24820)
* **overlays:** focus trapping no longer includes disabled elements ([#25949](https://github.com/ionic-team/ionic/issues/25949)) ([6cb5827](https://github.com/ionic-team/ionic/commit/6cb5827d069c255ab0a9a8c319aba9994a4c5196))
* **overlays:** focus trapping no longer includes hidden elements ([#25948](https://github.com/ionic-team/ionic/issues/25948)) ([5c10f98](https://github.com/ionic-team/ionic/commit/5c10f98ceb3ae42d3363b38ba786b9122676a59c))
* **overlays:** getTop now returns the top-most presented overlay ([#24547](https://github.com/ionic-team/ionic/issues/24547)) ([f5b4382](https://github.com/ionic-team/ionic/commit/f5b4382fd5728365e4badf39bc1dd0c149b45c2c)), closes [#19111](https://github.com/ionic-team/ionic/issues/19111)
* **overlays:** thrown errors are no longer suppressed ([#23831](https://github.com/ionic-team/ionic/issues/23831)) ([a212eb5](https://github.com/ionic-team/ionic/commit/a212eb52599e35d3706e2d3cef751e490e3a7259)), closes [#22724](https://github.com/ionic-team/ionic/issues/22724)
* **picker-column-internal:** center active item when rapidly opened ([#25155](https://github.com/ionic-team/ionic/issues/25155)) ([8e17fa9](https://github.com/ionic-team/ionic/commit/8e17fa9d5f9b00139693e34bc93b1f9c718ea3cf)), closes [#25154](https://github.com/ionic-team/ionic/issues/25154)
* **picker-column-internal:** prevent multiple items from being highlighted at once ([#24268](https://github.com/ionic-team/ionic/issues/24268)) ([c2bef8d](https://github.com/ionic-team/ionic/commit/c2bef8df14111dc00c382a3ab36c27a08a92f0b7))
* **picker-column-internal:** switching off an input mode column preserves scroll ([#25467](https://github.com/ionic-team/ionic/issues/25467)) ([989429d](https://github.com/ionic-team/ionic/commit/989429d65cf57ef8fb69854639f8eac1a12369bc))
* **picker-column-internal:** tabbing between columns works ([#25464](https://github.com/ionic-team/ionic/issues/25464)) ([db02772](https://github.com/ionic-team/ionic/commit/db027721ac299e7d23c42b52b0274be06b909f89))
* **picker-column:** column renders correctly with selected value ([#24988](https://github.com/ionic-team/ionic/issues/24988)) ([8318659](https://github.com/ionic-team/ionic/commit/83186598ed6cf08b0f0421076c4afb3ab53e1e57)), closes [#17664](https://github.com/ionic-team/ionic/issues/17664)
* **popover:** allow arrow configuration with controller approach ([#24512](https://github.com/ionic-team/ionic/issues/24512)) ([b39003a](https://github.com/ionic-team/ionic/commit/b39003a4c67cd7e01d09be012c9e12d99ca1730a)), closes [#24487](https://github.com/ionic-team/ionic/issues/24487)
* **popover:** allow arrow on desktop ([#25056](https://github.com/ionic-team/ionic/issues/25056)) ([bcd00c7](https://github.com/ionic-team/ionic/commit/bcd00c7a6ebb6a00193f04458976ff8b86395215))
* **popover:** default alignment to 'center' for ios mode ([#24815](https://github.com/ionic-team/ionic/issues/24815)) ([243f673](https://github.com/ionic-team/ionic/commit/243f67362f25699bdb373be6b72cb9c14dc95a32))
* **popover:** dismissing nested popover via backdrop now works ([#24957](https://github.com/ionic-team/ionic/issues/24957)) ([9e84ef7](https://github.com/ionic-team/ionic/commit/9e84ef7f91d76ca5a1ecaffc7592287267d5368b)), closes [#24954](https://github.com/ionic-team/ionic/issues/24954)
* **popover:** ensure popover does not go offscreen when adjusting top position ([#25350](https://github.com/ionic-team/ionic/issues/25350)) ([6926538](https://github.com/ionic-team/ionic/commit/692653842b43b5e36c51163f8261fde3b5bea40d)), closes [#25349](https://github.com/ionic-team/ionic/issues/25349)
* **popover:** handle scrolling in content so header can be sticky ([#24294](https://github.com/ionic-team/ionic/issues/24294)) ([f6a00ea](https://github.com/ionic-team/ionic/commit/f6a00ea9544aa70620b5f8f65a7702fa3bedd974))
* **popover:** only focus trap ion-item children ([#24990](https://github.com/ionic-team/ionic/issues/24990)) ([0cd06a6](https://github.com/ionic-team/ionic/commit/0cd06a675474e1893b4c0801fab8ab79813537c8)), closes [#24633](https://github.com/ionic-team/ionic/issues/24633)
* **popover:** use alignment with popover options ([#24711](https://github.com/ionic-team/ionic/issues/24711)) ([f5c5c3c](https://github.com/ionic-team/ionic/commit/f5c5c3cffa4f34046b0e9471a9f193db3772180e)), closes [#24709](https://github.com/ionic-team/ionic/issues/24709)
* **radio:** fix radio not showing checked state when not in a group ([#24423](https://github.com/ionic-team/ionic/issues/24423)) ([94a781c](https://github.com/ionic-team/ionic/commit/94a781cb6a3d92c5e6cab1a7603bfe25826a753c))
* **range:** dragging knob no longer scrolls page ([#25343](https://github.com/ionic-team/ionic/issues/25343)) ([0b92dff](https://github.com/ionic-team/ionic/commit/0b92dffa92c05705ff83518c10608e3dc3651d51)), closes [#19004](https://github.com/ionic-team/ionic/issues/19004)
* **range:** setting dir on ion-range to enable rtl mode now supported ([#24597](https://github.com/ionic-team/ionic/issues/24597)) ([5dba4e5](https://github.com/ionic-team/ionic/commit/5dba4e5ce0a07f69a08f2b427e8010b311910f88)), closes [#20201](https://github.com/ionic-team/ionic/issues/20201)
* **react, vue:** remove sideeffects to improve treeshaking ([#24313](https://github.com/ionic-team/ionic/issues/24313)) ([13d4418](https://github.com/ionic-team/ionic/commit/13d4418588b98d301b05ebd94e0eac670163a553))
* **react, vue:** scroll is no longer interrupted on ios ([#24791](https://github.com/ionic-team/ionic/issues/24791)) ([99c91ef](https://github.com/ionic-team/ionic/commit/99c91eff8764c9a1630adedab6a9765dd9754f7d)), closes [#24435](https://github.com/ionic-team/ionic/issues/24435)
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** building app for production now works correctly with vite ([#24515](https://github.com/ionic-team/ionic/issues/24515)) ([32fad3d](https://github.com/ionic-team/ionic/commit/32fad3d02cb6b012a772de03eafe3e3a6b1300e0)), closes [#24229](https://github.com/ionic-team/ionic/issues/24229)
* **react:** improve component compatibility with preact ([#24132](https://github.com/ionic-team/ionic/issues/24132)) ([15fc293](https://github.com/ionic-team/ionic/commit/15fc293d75aa21426616459c2596b46e2d460f49)), closes [#23516](https://github.com/ionic-team/ionic/issues/23516)
* **react:** overlays shown with useIonModal and useIonPopover no longer render outside of main react tree ([f3e492c](https://github.com/ionic-team/ionic/commit/f3e492c897c8cda2b98050156f130654f4d7014a)), closes [#23516](https://github.com/ionic-team/ionic/issues/23516) [#23516](https://github.com/ionic-team/ionic/issues/23516)
* **refresher:** attach scroll listener to custom scroll target ([#25335](https://github.com/ionic-team/ionic/issues/25335)) ([8f5e4cd](https://github.com/ionic-team/ionic/commit/8f5e4cd9350b10a98afb7c98353c6719eee918bb)), closes [#25318](https://github.com/ionic-team/ionic/issues/25318)
* **refresher:** import icons to avoid errors in react and vue ([#24525](https://github.com/ionic-team/ionic/issues/24525)) ([388622f](https://github.com/ionic-team/ionic/commit/388622f9734b7b832bca3ede99820a7124faa618)), closes [#24480](https://github.com/ionic-team/ionic/issues/24480)
* **refresher:** quickly swiping down no longer causes duplicate refresh ([#25476](https://github.com/ionic-team/ionic/issues/25476)) ([3abfa78](https://github.com/ionic-team/ionic/commit/3abfa780ccb32484b4d9f1b509e7ab910dfb901a)), closes [#25418](https://github.com/ionic-team/ionic/issues/25418)
* **refresher:** refresher is visible with multiple custom scroll targets ([#25750](https://github.com/ionic-team/ionic/issues/25750)) ([e750e33](https://github.com/ionic-team/ionic/commit/e750e336167397ed996d9833763286f4881e79b5)), closes [#25495](https://github.com/ionic-team/ionic/issues/25495)
* **refresher:** use componentOnReady utility for CE build ([#25783](https://github.com/ionic-team/ionic/issues/25783)) ([bd715a5](https://github.com/ionic-team/ionic/commit/bd715a52562f1f175d4bb6ea2dbfdd67a3e91db1)), closes [#25782](https://github.com/ionic-team/ionic/issues/25782)
* **reorder-group:** dragging reorder item to bottom no longer gives out of bounds index ([#23797](https://github.com/ionic-team/ionic/issues/23797)) ([02409f2](https://github.com/ionic-team/ionic/commit/02409f2abfa8acbab05d0f1217b9d1c13721746e)), closes [#23796](https://github.com/ionic-team/ionic/issues/23796)
* **reorder-group:** wait for content to render before getting scroll position ([#24007](https://github.com/ionic-team/ionic/issues/24007)) ([225a278](https://github.com/ionic-team/ionic/commit/225a2787407c5ce68a953ee3448647d00af26517)), closes [#23875](https://github.com/ionic-team/ionic/issues/23875)
* **ripple-effect:** ripple displays on click or touch ([#25102](https://github.com/ionic-team/ionic/issues/25102)) ([2a313e9](https://github.com/ionic-team/ionic/commit/2a313e91179e19660a758470ed2218bbcf03e0bb)), closes [#25094](https://github.com/ionic-team/ionic/issues/25094)
* **router-outlet:** getRouteId() returns the params set in setRouteId(). ([#24656](https://github.com/ionic-team/ionic/issues/24656)) ([be2205e](https://github.com/ionic-team/ionic/commit/be2205e5a2b2f8778bd1f7b4ea5cae0bf96f9ef3)), closes [#24652](https://github.com/ionic-team/ionic/issues/24652)
* **router-outlet:** navigating to same route with different params now activates component ([#24760](https://github.com/ionic-team/ionic/issues/24760)) ([abc36ae](https://github.com/ionic-team/ionic/commit/abc36ae80b060a659f7557ad90efe98b78f5ead9)), closes [#24653](https://github.com/ionic-team/ionic/issues/24653)
* **router:** popping route now accounts for route params ([#24315](https://github.com/ionic-team/ionic/issues/24315)) ([5e5054d](https://github.com/ionic-team/ionic/commit/5e5054d369ad68c9ac43e12439d71fb42d6ca26b))
* **router:** router push with relative path ([#24719](https://github.com/ionic-team/ionic/issues/24719)) ([d40c0c3](https://github.com/ionic-team/ionic/commit/d40c0c3a0993eaefbe5107e98958c6b0699a62c2)), closes [#24718](https://github.com/ionic-team/ionic/issues/24718)
* **scroll-assist:** touch end events continue to bubble on inputs ([#25282](https://github.com/ionic-team/ionic/issues/25282)) ([780f16d](https://github.com/ionic-team/ionic/commit/780f16d9e04ee5aaaf91bb7c6ef15c72cc8aeb45)), closes [#25229](https://github.com/ionic-team/ionic/issues/25229)
* **searchbar:** clear button has focus indicator ([#25828](https://github.com/ionic-team/ionic/issues/25828)) ([373b4ff](https://github.com/ionic-team/ionic/commit/373b4ffe216ba584b92014cef501f64668e1f177))
* **searchbar:** keypress can activate clear button ([#25824](https://github.com/ionic-team/ionic/issues/25824)) ([c270756](https://github.com/ionic-team/ionic/commit/c270756356c7b23a1959ac5f4b8206a5cd1825c2))
* **searchbar:** setting dir on ion-searchbar to enable rtl mode now supported ([#24602](https://github.com/ionic-team/ionic/issues/24602)) ([35e5235](https://github.com/ionic-team/ionic/commit/35e523564561c0f3323efa761c4654016b97ef69))
* **segment:** setting dir on ion-segment to enable rtl mode now supported ([#24601](https://github.com/ionic-team/ionic/issues/24601)) ([2940e73](https://github.com/ionic-team/ionic/commit/2940e73a4504247eecb0de6c433104f529530850)), closes [#23978](https://github.com/ionic-team/ionic/issues/23978)
* **select-popover:** non-scrollable popovers no longer have forced overscroll ([#23972](https://github.com/ionic-team/ionic/issues/23972)) ([aa4ba89](https://github.com/ionic-team/ionic/commit/aa4ba890e9c18e8a911c5188b3e2e85433658be9)), closes [#23971](https://github.com/ionic-team/ionic/issues/23971)
* **select:** avoid duplicate dialogs and backdrops when clicking ([#25175](https://github.com/ionic-team/ionic/issues/25175)) ([70d2784](https://github.com/ionic-team/ionic/commit/70d278414eb5124d17c5ffaba5231c6bfd285656)), closes [#25126](https://github.com/ionic-team/ionic/issues/25126)
* **select:** compareWith passes params in correct order ([#25764](https://github.com/ionic-team/ionic/issues/25764)) ([d631195](https://github.com/ionic-team/ionic/commit/d6311951243fd9b867ae5d4a7a08c8d341f8eb7a)), closes [#25759](https://github.com/ionic-team/ionic/issues/25759)
* **select:** ensure popover options with number values are searched for correctly ([#23998](https://github.com/ionic-team/ionic/issues/23998)) ([c204083](https://github.com/ionic-team/ionic/commit/c20408369bd332b5e225a3d50ec94978f6f5ec97))
* **select:** focus selected item in popovers ([#23991](https://github.com/ionic-team/ionic/issues/23991)) ([2497a53](https://github.com/ionic-team/ionic/commit/2497a53255dc43052755bba842dfcf556d930dcd))
* **select:** interface components now show correctly ([#24810](https://github.com/ionic-team/ionic/issues/24810)) ([2fc2de5](https://github.com/ionic-team/ionic/commit/2fc2de51771f4a5c3f20c6071284096e5bf31ec8)), closes [#24807](https://github.com/ionic-team/ionic/issues/24807)
* **select:** value is selected when given array ([#24687](https://github.com/ionic-team/ionic/issues/24687)) ([6ee7d15](https://github.com/ionic-team/ionic/commit/6ee7d159ecfff3382fadb524c5c430172d40c267)), closes [#24742](https://github.com/ionic-team/ionic/issues/24742)
* **slides:** update swiper instance after initialization ([#24257](https://github.com/ionic-team/ionic/issues/24257)) ([89e4bc5](https://github.com/ionic-team/ionic/commit/89e4bc56a1c3cd4fb26fc5514f38c6a01f047297))
* **spinner:** alignment is now correct in rtl ([#25260](https://github.com/ionic-team/ionic/issues/25260)) ([e3c996d](https://github.com/ionic-team/ionic/commit/e3c996dea878a8dd276a0ca99f59b330125f9b75))
* **spinner:** ensure transform doesn't overwrite circular animation ([#24643](https://github.com/ionic-team/ionic/issues/24643)) ([88ce010](https://github.com/ionic-team/ionic/commit/88ce010418eaca38786b51720c696860b417ab6d))
* **status-bar:** tapping status bar correctly scrolls content to top ([#24001](https://github.com/ionic-team/ionic/issues/24001)) ([25eb8cd](https://github.com/ionic-team/ionic/commit/25eb8cdf98fe455433ca6185e89d9e1223a6d3ae)), closes [#20423](https://github.com/ionic-team/ionic/issues/20423)
* **tab-bar:** safe area padding now added when slot="top" ([#23895](https://github.com/ionic-team/ionic/issues/23895)) ([4782969](https://github.com/ionic-team/ionic/commit/47829690b538903b70ad4fe77657404013270263)), closes [#23893](https://github.com/ionic-team/ionic/issues/23893)
* **tab-bar:** use correct import path ([#25898](https://github.com/ionic-team/ionic/issues/25898)) ([ad46045](https://github.com/ionic-team/ionic/commit/ad46045bcc251c9719ecf6621792f1a5b3c6afce)), closes [#25897](https://github.com/ionic-team/ionic/issues/25897)
* **textarea:** auto grow textarea line wraps long contents ([#25928](https://github.com/ionic-team/ionic/issues/25928)) ([777109a](https://github.com/ionic-team/ionic/commit/777109a7e8625ed61a8cc09e52fc06e104b124ea)), closes [#25893](https://github.com/ionic-team/ionic/issues/25893)
* **textarea:** floating label with autogrow textareas ([#24202](https://github.com/ionic-team/ionic/issues/24202)) ([713f0f5](https://github.com/ionic-team/ionic/commit/713f0f55261205d3f7e25874939cb1f998f38d4a))
* **textarea:** textarea with autogrow will size to its contents ([#24205](https://github.com/ionic-team/ionic/issues/24205)) ([a9cf2ab](https://github.com/ionic-team/ionic/commit/a9cf2ab87012cdb6360d10536a29213adda3f585)), closes [#24793](https://github.com/ionic-team/ionic/issues/24793) [#21242](https://github.com/ionic-team/ionic/issues/21242)
* **toast:** allow input focus while toast is visible ([#24572](https://github.com/ionic-team/ionic/issues/24572)) ([29f1140](https://github.com/ionic-team/ionic/commit/29f1140384ae7e1402b09c3760e168cf79833619)), closes [#24571](https://github.com/ionic-team/ionic/issues/24571)
* **toast:** screen readers now announce toasts when presented ([#24937](https://github.com/ionic-team/ionic/issues/24937)) ([8a97f6b](https://github.com/ionic-team/ionic/commit/8a97f6b5c9ca1e77c1790abd1e924955b6b6ea27)), closes [#22333](https://github.com/ionic-team/ionic/issues/22333)
* **toast:** toast is now correctly excluded from focus trapping ([#24816](https://github.com/ionic-team/ionic/issues/24816)) ([8246112](https://github.com/ionic-team/ionic/commit/8246112ca12f90edb98629ab82e27a792a1fafad)), closes [#24733](https://github.com/ionic-team/ionic/issues/24733)
* **toast:** ToastOptions interface now contains icon prop ([#23737](https://github.com/ionic-team/ionic/issues/23737)) ([fbd32ff](https://github.com/ionic-team/ionic/commit/fbd32ffb2633b17d71a34a8760386a319f2e2bca)), closes [#23736](https://github.com/ionic-team/ionic/issues/23736)
* **toggle:** setting dir on ion-toggle to enable rtl mode now supported ([#24600](https://github.com/ionic-team/ionic/issues/24600)) ([353dbc0](https://github.com/ionic-team/ionic/commit/353dbc0537ef3b46b9ba13a365ebc5da269de4c7))
* **types:** improve intellisense with colors ([#25347](https://github.com/ionic-team/ionic/issues/25347)) ([97cfbbb](https://github.com/ionic-team/ionic/commit/97cfbbb65d3e63c32d720e01c7368c68616bb531))
* **vue:** components have correct type definitions ([#25499](https://github.com/ionic-team/ionic/issues/25499)) ([b1821e9](https://github.com/ionic-team/ionic/commit/b1821e9d0a55f20f74696f119de724ab70647977)), closes [#25485](https://github.com/ionic-team/ionic/issues/25485)
* **vue:** custom element internal properties are no longer overridden in vue 3.1.0 ([#23738](https://github.com/ionic-team/ionic/issues/23738)) ([ea39c70](https://github.com/ionic-team/ionic/commit/ea39c70b3ec78b2ea5ef64263e8528b543378784)), closes [#23539](https://github.com/ionic-team/ionic/issues/23539)
* **vue:** input v-model accepts numbers ([#25666](https://github.com/ionic-team/ionic/issues/25666)) ([ab65e9a](https://github.com/ionic-team/ionic/commit/ab65e9a7b51c3a3f8c59962d3e1faff1564ab801)), closes [#25575](https://github.com/ionic-team/ionic/issues/25575)


### Features

* **action-sheet, loading, modal, picker, popover:** pass HTML attributes to host element ([#23929](https://github.com/ionic-team/ionic/issues/23929)) ([bd96a81](https://github.com/ionic-team/ionic/commit/bd96a81ff80ffe32914804ba9b6234c0286a33db))
* **action-sheet:** add data property to ActionSheetButton ([#23744](https://github.com/ionic-team/ionic/issues/23744)) ([30f8508](https://github.com/ionic-team/ionic/commit/30f8508296cfc8f8b1c03d04b24abfa184624200)), closes [#23700](https://github.com/ionic-team/ionic/issues/23700)
* **alert, toast:** pass arbitrary HTML attributes to host element ([#23891](https://github.com/ionic-team/ionic/issues/23891)) ([73a1daf](https://github.com/ionic-team/ionic/commit/73a1daf0aaf6ffe8c7871619f2aec5f6fca1321a)), closes [#23825](https://github.com/ionic-team/ionic/issues/23825)
* **all:** add CustomEvents types to components that emit events ([#23956](https://github.com/ionic-team/ionic/issues/23956)) ([8708095](https://github.com/ionic-team/ionic/commit/87080951112a409893a4bac2def1deca06642b16)), closes [#22925](https://github.com/ionic-team/ionic/issues/22925)
* **angular, react, vue:** add support for autoMountComponent ([#25552](https://github.com/ionic-team/ionic/issues/25552)) ([805dfa0](https://github.com/ionic-team/ionic/commit/805dfa05663098ef9c02b0745a383b5e7555908b))
* **angular:** build for angular 12.0 ([#23970](https://github.com/ionic-team/ionic/issues/23970)) ([3451a34](https://github.com/ionic-team/ionic/commit/3451a34ad0c893be0b6c17dc91ac9a75d2b9b52c))
* **content, reorder-group, header, footer, infinite-scroll, refresher:** add custom scroll target to improve compatibility with virtual scroll ([#24883](https://github.com/ionic-team/ionic/issues/24883)) ([2a438da](https://github.com/ionic-team/ionic/commit/2a438da010ddd4d4211e1879e27d7b28409daaa2)), closes [#23437](https://github.com/ionic-team/ionic/issues/23437)
* **datetime-button:** add button for displaying datetime in overlays ([#25655](https://github.com/ionic-team/ionic/issues/25655)) ([4997331](https://github.com/ionic-team/ionic/commit/499733105e4be23405e8afeeb26fee5cd2afc25b)), closes [#24316](https://github.com/ionic-team/ionic/issues/24316)
* **datetime:** add ability to select only month, year, or month and year ([#23913](https://github.com/ionic-team/ionic/issues/23913)) ([4ae44b7](https://github.com/ionic-team/ionic/commit/4ae44b7a236004738d593406d7b1236600bc6d95))
* **datetime:** add clear button ([#23920](https://github.com/ionic-team/ionic/issues/23920)) ([18765e7](https://github.com/ionic-team/ionic/commit/18765e7e39b9f205f47f394d26d6ecc4b53e17ef)), closes [#17482](https://github.com/ionic-team/ionic/issues/17482)
* **datetime:** add firstDayOfWeek property ([#23692](https://github.com/ionic-team/ionic/issues/23692)) ([ea348f0](https://github.com/ionic-team/ionic/commit/ea348f005aef7b2fda581a99338139f6fefcda63)), closes [#23556](https://github.com/ionic-team/ionic/issues/23556)
* **datetime:** add hourCycle property ([#23686](https://github.com/ionic-team/ionic/issues/23686)) ([6342fde](https://github.com/ionic-team/ionic/commit/6342fde56c7687703edd212b8383536c8b9a6400)), closes [#23661](https://github.com/ionic-team/ionic/issues/23661)
* **datetime:** add multiple date selection ([#25514](https://github.com/ionic-team/ionic/issues/25514)) ([9d31608](https://github.com/ionic-team/ionic/commit/9d31608f2d471f531eb253832c8558d1effaf68a))
* **datetime:** add wheel style picker for dates and times ([#25468](https://github.com/ionic-team/ionic/issues/25468)) ([3d19771](https://github.com/ionic-team/ionic/commit/3d19771185301870a2eb60f1ef4afd6f1c182494))
* **datetime:** isDateEnabled to enable/disable specific days  ([#24898](https://github.com/ionic-team/ionic/issues/24898)) ([e932a04](https://github.com/ionic-team/ionic/commit/e932a042237e6f44bf278bcbd895d8569fc17348)), closes [#24209](https://github.com/ionic-team/ionic/issues/24209)
* **datetime:** localize am/pm labels in time picker ([#25389](https://github.com/ionic-team/ionic/issues/25389)) ([6bc0acc](https://github.com/ionic-team/ionic/commit/6bc0acc4279a18c3309b11eeec76676c5015419a)), closes [#16279](https://github.com/ionic-team/ionic/issues/16279)
* **header, footer:** add ios fading header style ([#24011](https://github.com/ionic-team/ionic/issues/24011)) ([7ce3959](https://github.com/ionic-team/ionic/commit/7ce3959b66a08e980c7dac3bb7d7df6bf0ae874e))
* **item:** counter formatter to customize counter text display ([#24336](https://github.com/ionic-team/ionic/issues/24336)) ([171020e](https://github.com/ionic-team/ionic/commit/171020e9d200ccfdef0f01c427b295bb50dd1fef)), closes [#24327](https://github.com/ionic-team/ionic/issues/24327)
* **menu:** add console error for incorrect usage of contentId ([#23871](https://github.com/ionic-team/ionic/issues/23871)) ([879ab8e](https://github.com/ionic-team/ionic/commit/879ab8ebdacc1468ed206701c00b60100dbab9e4)), closes [#23810](https://github.com/ionic-team/ionic/issues/23810)
* **modal:** ability to programmatically set current sheet breakpoint ([#24648](https://github.com/ionic-team/ionic/issues/24648)) ([3145c76](https://github.com/ionic-team/ionic/commit/3145c76934ac711038f9dcba98a385dfbe754953)), closes [#23917](https://github.com/ionic-team/ionic/issues/23917)
* **modal:** add bottom sheet functionality ([#23828](https://github.com/ionic-team/ionic/issues/23828)) ([12216d3](https://github.com/ionic-team/ionic/commit/12216d378df091e16fd77d271b107e819278481c)), closes [#21039](https://github.com/ionic-team/ionic/issues/21039)
* **modal:** add canDismiss property to manage modal dismissing ([#24928](https://github.com/ionic-team/ionic/issues/24928)) ([4b21958](https://github.com/ionic-team/ionic/commit/4b21958ec57019afcde786598880e1f8edada2b1)), closes [#22297](https://github.com/ionic-team/ionic/issues/22297)
* **modal:** clicking handle advances to the next breakpoint ([#25540](https://github.com/ionic-team/ionic/issues/25540)) ([7cdc388](https://github.com/ionic-team/ionic/commit/7cdc388b7805cbf23c9e1e928aa977cd77ebc8c4)), closes [#24069](https://github.com/ionic-team/ionic/issues/24069)
* **picker-column-internal:** add ability to disable items ([#25412](https://github.com/ionic-team/ionic/issues/25412)) ([8b7c079](https://github.com/ionic-team/ionic/commit/8b7c07968e1a60389a22e5af0e0cac62d31d397a))
* **platform:** add ability to override platform detection methods ([#23915](https://github.com/ionic-team/ionic/issues/23915)) ([45cabae](https://github.com/ionic-team/ionic/commit/45cabae04bf9236cd069793fbf2ac8f68c372cc3)), closes [#19737](https://github.com/ionic-team/ionic/issues/19737)
* **popover:** add ability to pass event to present method ([#23827](https://github.com/ionic-team/ionic/issues/23827)) ([1d2ee92](https://github.com/ionic-team/ionic/commit/1d2ee92ca01b77bcf87c7783b50d59efcf0a402a)), closes [#23813](https://github.com/ionic-team/ionic/issues/23813)
* **range:** add knobMoveStart and knobMoveEnd events ([#25011](https://github.com/ionic-team/ionic/issues/25011)) ([f5cb1f8](https://github.com/ionic-team/ionic/commit/f5cb1f8444ba050042e788f9f9ec7b6309bf1b60))
* **range:** add reference point for start position of range slider ([#25598](https://github.com/ionic-team/ionic/issues/25598)) ([c2781cc](https://github.com/ionic-team/ionic/commit/c2781cc1c3b7e56a0e6f6c03cfa04fc2c82d6e8a)), closes [#24348](https://github.com/ionic-team/ionic/issues/24348)
* **react:** add custom elements bundle ([#23896](https://github.com/ionic-team/ionic/issues/23896)) ([c50d895](https://github.com/ionic-team/ionic/commit/c50d895370a56d0809019dc59fe32ec840b72f03))
* **select:** add event for when overlay is dismissed ([#24099](https://github.com/ionic-team/ionic/issues/24099)) ([c1ecf94](https://github.com/ionic-team/ionic/commit/c1ecf94e4e6e320b61606da3c889926f7372ced7))
* **select:** add event for when overlay is dismissed ([#24400](https://github.com/ionic-team/ionic/issues/24400)) ([b835b7c](https://github.com/ionic-team/ionic/commit/b835b7c0c7840f41c54f96743cc0a779ff474ab6))
* **slides:** add IonicSlides module for Swiper migration, deprecate ion-slides ([#23844](https://github.com/ionic-team/ionic/issues/23844)) ([11fda41](https://github.com/ionic-team/ionic/commit/11fda41420343886dabd97096690be38f1c40524)), closes [#23447](https://github.com/ionic-team/ionic/issues/23447)
* **slides:** add support for Swiper 7 ([#24190](https://github.com/ionic-team/ionic/issues/24190)) ([d0b6130](https://github.com/ionic-team/ionic/commit/d0b61307c6b7ff1589646c43f989260b59db1473))
* **toggle:** on/off icons for toggle ([#25459](https://github.com/ionic-team/ionic/issues/25459)) ([bc0bdc4](https://github.com/ionic-team/ionic/commit/bc0bdc438ba72c695f9d961ddf837ec45e7816dd)), closes [#20524](https://github.com/ionic-team/ionic/issues/20524)


### Performance Improvements

* **card:** avoid force compositing on ios ([#25942](https://github.com/ionic-team/ionic/issues/25942)) ([174c3b3](https://github.com/ionic-team/ionic/commit/174c3b30a0bce7e7ab13e5605348ec107af69dd6))
* **content:** remove global click listener to improve interaction performance ([#24360](https://github.com/ionic-team/ionic/issues/24360)) ([1bfac52](https://github.com/ionic-team/ionic/commit/1bfac52331d3f296e5721b2a6c3fd94a97450a1d)), closes [#24359](https://github.com/ionic-team/ionic/issues/24359)
* improve treeshaking functionality ([#24895](https://github.com/ionic-team/ionic/issues/24895)) ([805907a](https://github.com/ionic-team/ionic/commit/805907af4e78179f1acc9cb02263b1ea10d4e3df)), closes [#24280](https://github.com/ionic-team/ionic/issues/24280)
* **input:** passive event listener for touch start events ([#25610](https://github.com/ionic-team/ionic/issues/25610)) ([2d1efdb](https://github.com/ionic-team/ionic/commit/2d1efdbe6dd9436badab4684f2a484476489c166)), closes [#25599](https://github.com/ionic-team/ionic/issues/25599)
* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))


### BREAKING CHANGES

* **all:** The `RadioChangeEventDetail` interface has been removed in favor of `RadioGroupChangeEventDetail`.





## [6.2.8](https://github.com/ionic-team/ionic/compare/v6.2.7...v6.2.8) (2022-09-21)


### Bug Fixes

* **datetime:** account for 12AM with min times and 12 hour format ([#25952](https://github.com/ionic-team/ionic/issues/25952)) ([55ebd6c](https://github.com/ionic-team/ionic/commit/55ebd6cdf39c01b401e876b76e755bfa04db8f65)), closes [#25183](https://github.com/ionic-team/ionic/issues/25183)
* **item:** show the highlight on iOS when --highlight-height is set ([#25905](https://github.com/ionic-team/ionic/issues/25905)) ([d7db133](https://github.com/ionic-team/ionic/commit/d7db1333f13834ecb447b4b1da62cfffed9fb333))
* **overlays:** focus trapping no longer includes disabled elements ([#25949](https://github.com/ionic-team/ionic/issues/25949)) ([6cb5827](https://github.com/ionic-team/ionic/commit/6cb5827d069c255ab0a9a8c319aba9994a4c5196))
* **overlays:** focus trapping no longer includes hidden elements ([#25948](https://github.com/ionic-team/ionic/issues/25948)) ([5c10f98](https://github.com/ionic-team/ionic/commit/5c10f98ceb3ae42d3363b38ba786b9122676a59c))


### Performance Improvements

* **card:** avoid force compositing on ios ([#25942](https://github.com/ionic-team/ionic/issues/25942)) ([174c3b3](https://github.com/ionic-team/ionic/commit/174c3b30a0bce7e7ab13e5605348ec107af69dd6))





## [6.2.7](https://github.com/ionic-team/ionic/compare/v6.2.6...v6.2.7) (2022-09-14)


### Bug Fixes

* **datetime:** correct year is set in wheel picker ([#25896](https://github.com/ionic-team/ionic/issues/25896)) ([fb653eb](https://github.com/ionic-team/ionic/commit/fb653ebe67458a088adf0626741d190ceb2880a6)), closes [#25895](https://github.com/ionic-team/ionic/issues/25895)
* **footer:** padding is added correctly with tabs ([#25921](https://github.com/ionic-team/ionic/issues/25921)) ([edbb64c](https://github.com/ionic-team/ionic/commit/edbb64c4b6de7ace7043675a85fd503da18304d7)), closes [#25918](https://github.com/ionic-team/ionic/issues/25918)
* **input,textarea:** data-form-type attribute is assigned to inner input ([#25927](https://github.com/ionic-team/ionic/issues/25927)) ([9451b28](https://github.com/ionic-team/ionic/commit/9451b283e2cb30ac9087574461f6b9f4b6cc3e0f)), closes [#25908](https://github.com/ionic-team/ionic/issues/25908)
* **modal:** sheet is easier to dismiss with swipe ([#25883](https://github.com/ionic-team/ionic/issues/25883)) ([fa169d2](https://github.com/ionic-team/ionic/commit/fa169d2dca649107342fe365ef6c7da892ebb8fd)), closes [#24296](https://github.com/ionic-team/ionic/issues/24296)
* **tab-bar:** use correct import path ([#25898](https://github.com/ionic-team/ionic/issues/25898)) ([ad46045](https://github.com/ionic-team/ionic/commit/ad46045bcc251c9719ecf6621792f1a5b3c6afce)), closes [#25897](https://github.com/ionic-team/ionic/issues/25897)
* **textarea:** auto grow textarea line wraps long contents ([#25928](https://github.com/ionic-team/ionic/issues/25928)) ([777109a](https://github.com/ionic-team/ionic/commit/777109a7e8625ed61a8cc09e52fc06e104b124ea)), closes [#25893](https://github.com/ionic-team/ionic/issues/25893)





## [6.2.6](https://github.com/ionic-team/ionic/compare/v6.2.5...v6.2.6) (2022-09-07)


### Bug Fixes

* **datetime:** calendar day and years are now localized ([#25847](https://github.com/ionic-team/ionic/issues/25847)) ([cbd1268](https://github.com/ionic-team/ionic/commit/cbd1268a03204f05314f2ba284ad433457a9cf33)), closes [#25843](https://github.com/ionic-team/ionic/issues/25843)
* **datetime:** hourCycle formats hour correctly ([#25869](https://github.com/ionic-team/ionic/issues/25869)) ([1a1491d](https://github.com/ionic-team/ionic/commit/1a1491df0242da1cb3c9a7f128bbd4d5ce4dbf3e)), closes [#25862](https://github.com/ionic-team/ionic/issues/25862)
* **datetime:** month grid no longer loops on ios ([#25857](https://github.com/ionic-team/ionic/issues/25857)) ([c938054](https://github.com/ionic-team/ionic/commit/c938054605dffb6c3002a64a3d8aaf36892c7a93)), closes [#25752](https://github.com/ionic-team/ionic/issues/25752)





## [6.2.5](https://github.com/ionic-team/ionic/compare/v6.2.4...v6.2.5) (2022-08-31)


### Bug Fixes

* **action-sheet:** add aria-labelledby ([#25837](https://github.com/ionic-team/ionic/issues/25837)) ([5270151](https://github.com/ionic-team/ionic/commit/527015184e9413c1037277d3197bcaa33044c38c))
* **datetime:** next and previous buttons have correct labels ([#25845](https://github.com/ionic-team/ionic/issues/25845)) ([41e3387](https://github.com/ionic-team/ionic/commit/41e338730d32837fc9dd8a15477e37dea4cc76c9)), closes [#25844](https://github.com/ionic-team/ionic/issues/25844)
* **datetime:** only log out of bounds warning if value set ([#25835](https://github.com/ionic-team/ionic/issues/25835)) ([85af6ce](https://github.com/ionic-team/ionic/commit/85af6ce436890eb922d2ba32053fb8b8bc7fd4ff)), closes [#25833](https://github.com/ionic-team/ionic/issues/25833)
* **input:** clear button is not activated on swipe ([#25825](https://github.com/ionic-team/ionic/issues/25825)) ([ff71ad4](https://github.com/ionic-team/ionic/commit/ff71ad492d7671f8e550da7e08dbde30cb05ebf7)), closes [#24857](https://github.com/ionic-team/ionic/issues/24857)
* **modal:** handleBehavior can be used with controller ([#25821](https://github.com/ionic-team/ionic/issues/25821)) ([79ef1b5](https://github.com/ionic-team/ionic/commit/79ef1b57dc74fd856ed7c2904d7400d283cc081e)), closes [#25820](https://github.com/ionic-team/ionic/issues/25820)
* **searchbar:** clear button has focus indicator ([#25828](https://github.com/ionic-team/ionic/issues/25828)) ([373b4ff](https://github.com/ionic-team/ionic/commit/373b4ffe216ba584b92014cef501f64668e1f177))
* **searchbar:** keypress can activate clear button ([#25824](https://github.com/ionic-team/ionic/issues/25824)) ([c270756](https://github.com/ionic-team/ionic/commit/c270756356c7b23a1959ac5f4b8206a5cd1825c2))





## [6.2.4](https://github.com/ionic-team/ionic/compare/v6.2.3...v6.2.4) (2022-08-24)


### Bug Fixes

* **alert:** add default aria-label ([#25800](https://github.com/ionic-team/ionic/issues/25800)) ([d395a73](https://github.com/ionic-team/ionic/commit/d395a73cb6c419e6c0072746b8e4768cd5f78ef3))
* **alert:** use aria-labelledby and aria-describedby instead of aria-label ([#25805](https://github.com/ionic-team/ionic/issues/25805)) ([27318d7](https://github.com/ionic-team/ionic/commit/27318d75df60dfce1a90f23ba31ea2b6636ba42f))
* **breadcrumb:** separator is not announced by narrators ([#25796](https://github.com/ionic-team/ionic/issues/25796)) ([71fad38](https://github.com/ionic-team/ionic/commit/71fad3884bc55b266067efb346500c848b856946))
* **datetime:** close month/year picker when hidden ([#25789](https://github.com/ionic-team/ionic/issues/25789)) ([3b211b6](https://github.com/ionic-team/ionic/commit/3b211b60fd9a88be6e232f839ecc4be090181530)), closes [#25787](https://github.com/ionic-team/ionic/issues/25787)
* **modal:** role attribute can be customized ([#25804](https://github.com/ionic-team/ionic/issues/25804)) ([037d579](https://github.com/ionic-team/ionic/commit/037d579b2a3a660358f1e9c9b020c9510bb9c6b0))
* **refresher:** use componentOnReady utility for CE build ([#25783](https://github.com/ionic-team/ionic/issues/25783)) ([bd715a5](https://github.com/ionic-team/ionic/commit/bd715a52562f1f175d4bb6ea2dbfdd67a3e91db1)), closes [#25782](https://github.com/ionic-team/ionic/issues/25782)
* **select:** compareWith passes params in correct order ([#25764](https://github.com/ionic-team/ionic/issues/25764)) ([d631195](https://github.com/ionic-team/ionic/commit/d6311951243fd9b867ae5d4a7a08c8d341f8eb7a)), closes [#25759](https://github.com/ionic-team/ionic/issues/25759)





## [6.2.3](https://github.com/ionic-team/ionic/compare/v6.2.2...v6.2.3) (2022-08-17)


### Bug Fixes

* **css:** preserve whitespace in selectors when minifying css ([#25767](https://github.com/ionic-team/ionic/issues/25767)) ([bafa759](https://github.com/ionic-team/ionic/commit/bafa759655a0f3ca206255ba429f21d319c37aed)), closes [#25766](https://github.com/ionic-team/ionic/issues/25766)
* **datetime:** highlights now show above content in modal ([#25756](https://github.com/ionic-team/ionic/issues/25756)) ([d711658](https://github.com/ionic-team/ionic/commit/d7116581c8e92716f49877abc78d93dc39c34e1d)), closes [#25755](https://github.com/ionic-team/ionic/issues/25755)
* **footer:** remove toolbar bottom padding if near bottom slot tabs or keyboard is open ([#25746](https://github.com/ionic-team/ionic/issues/25746)) ([bb37446](https://github.com/ionic-team/ionic/commit/bb374460320b0ba2ee03a5a0ecebb3e7a9f0728e))
* **header:** hide from screen readers when collapsed ([#25744](https://github.com/ionic-team/ionic/issues/25744)) ([d0ba963](https://github.com/ionic-team/ionic/commit/d0ba9635998f2157970156438c1bb74d6b9682f2))
* **input:** exclude date inputs from scroll assist ([#25749](https://github.com/ionic-team/ionic/issues/25749)) ([abb56d2](https://github.com/ionic-team/ionic/commit/abb56d22b4a81d1bc34c689de4ef7218e7503b20)), closes [#25745](https://github.com/ionic-team/ionic/issues/25745)
* **item:** form validation caret color renders correctly ([#25725](https://github.com/ionic-team/ionic/issues/25725)) ([de20541](https://github.com/ionic-team/ionic/commit/de20541486bcf6e1d15f0ae5b0c5f177cce5eb38)), closes [#25719](https://github.com/ionic-team/ionic/issues/25719)
* **refresher:** refresher is visible with multiple custom scroll targets ([#25750](https://github.com/ionic-team/ionic/issues/25750)) ([e750e33](https://github.com/ionic-team/ionic/commit/e750e336167397ed996d9833763286f4881e79b5)), closes [#25495](https://github.com/ionic-team/ionic/issues/25495)





## [6.2.2](https://github.com/ionic-team/ionic/compare/v6.2.1...v6.2.2) (2022-08-10)


### Bug Fixes

* **datetime:** add correct null check when value changes ([#25716](https://github.com/ionic-team/ionic/issues/25716)) ([36bea1c](https://github.com/ionic-team/ionic/commit/36bea1ca2520c9eb9ee7705abb046607a52d198d)), closes [#25714](https://github.com/ionic-team/ionic/issues/25714)
* **datetime:** preferWheel respects column ordering by locale ([#25726](https://github.com/ionic-team/ionic/issues/25726)) ([dee0f51](https://github.com/ionic-team/ionic/commit/dee0f513ee443c0c69ea8e38a292c900e9c70221)), closes [#25722](https://github.com/ionic-team/ionic/issues/25722)





## [6.2.1](https://github.com/ionic-team/ionic/compare/v6.2.0...v6.2.1) (2022-08-03)


### Bug Fixes

* **datetime:** display time in user's timezone after selection ([#25694](https://github.com/ionic-team/ionic/issues/25694)) ([11c69c8](https://github.com/ionic-team/ionic/commit/11c69c8df50b75440c9e876b4d99d469d16e144f)), closes [#25693](https://github.com/ionic-team/ionic/issues/25693)
* **datetime:** selecting today with multiple date select now works ([#25699](https://github.com/ionic-team/ionic/issues/25699)) ([86b7000](https://github.com/ionic-team/ionic/commit/86b7000bcd1b4519e8c20907050e15ba7c99bab0))
* **nav:** exclude nav from custom dialog ([#25689](https://github.com/ionic-team/ionic/issues/25689)) ([d1e517b](https://github.com/ionic-team/ionic/commit/d1e517bfef03b822dfa7651681013277762eda08)), closes [#25677](https://github.com/ionic-team/ionic/issues/25677) [#25688](https://github.com/ionic-team/ionic/issues/25688)





# [6.2.0 Chromium](https://github.com/ionic-team/ionic-framework/compare/v6.1.15...v6.2.0) (2022-07-27)


### Bug Fixes

* **datetime:** account for previous years with preferWheel ([#25656](https://github.com/ionic-team/ionic-framework/issues/25656)) ([3a7f5f1](https://github.com/ionic-team/ionic-framework/commit/3a7f5f166ee8d8d7e1861313e2bc6f4856e4fbe9))
* **datetime:** switching months in wheel picker now selected nearest neighbor ([#25559](https://github.com/ionic-team/ionic-framework/issues/25559)) ([dd256e1](https://github.com/ionic-team/ionic-framework/commit/dd256e1313fa1c307f30b0dbb7fd0d1da8c555f7))
* **datetime:** switching presentation closes month/year picker ([#25667](https://github.com/ionic-team/ionic-framework/issues/25667)) ([57a21ad](https://github.com/ionic-team/ionic-framework/commit/57a21adb38331ee5d74dacd1b0a2568f41a2d21e))
* **nav:** pop() will unmount views within a modal ([#25638](https://github.com/ionic-team/ionic-framework/issues/25638)) ([db28794](https://github.com/ionic-team/ionic-framework/commit/db28794f0b75f2824ae26c101a8c52af70f43ffd)), closes [#25637](https://github.com/ionic-team/ionic-framework/issues/25637) [#21831](https://github.com/ionic-team/ionic-framework/issues/21831)
* **textarea:** textarea with autogrow will size to its contents ([#24205](https://github.com/ionic-team/ionic-framework/issues/24205)) ([a9cf2ab](https://github.com/ionic-team/ionic-framework/commit/a9cf2ab87012cdb6360d10536a29213adda3f585)), closes [#24793](https://github.com/ionic-team/ionic-framework/issues/24793) [#21242](https://github.com/ionic-team/ionic-framework/issues/21242)
* **vue:** input v-model accepts numbers ([#25666](https://github.com/ionic-team/ionic-framework/issues/25666)) ([ab65e9a](https://github.com/ionic-team/ionic-framework/commit/ab65e9a7b51c3a3f8c59962d3e1faff1564ab801)), closes [#25575](https://github.com/ionic-team/ionic-framework/issues/25575)


### Features

* **angular, react, vue:** add support for autoMountComponent ([#25552](https://github.com/ionic-team/ionic-framework/issues/25552)) ([805dfa0](https://github.com/ionic-team/ionic-framework/commit/805dfa05663098ef9c02b0745a383b5e7555908b))
* **datetime-button:** add button for displaying datetime in overlays ([#25655](https://github.com/ionic-team/ionic-framework/issues/25655)) ([4997331](https://github.com/ionic-team/ionic-framework/commit/499733105e4be23405e8afeeb26fee5cd2afc25b)), closes [#24316](https://github.com/ionic-team/ionic-framework/issues/24316)
* **datetime:** add multiple date selection ([#25514](https://github.com/ionic-team/ionic-framework/issues/25514)) ([9d31608](https://github.com/ionic-team/ionic-framework/commit/9d31608f2d471f531eb253832c8558d1effaf68a)), closes [#24674](https://github.com/ionic-team/ionic-framework/issues/24674)
* **datetime:** add wheel style picker for dates and times ([#25468](https://github.com/ionic-team/ionic-framework/issues/25468)) ([3d19771](https://github.com/ionic-team/ionic-framework/commit/3d19771185301870a2eb60f1ef4afd6f1c182494)), closes [#23981](https://github.com/ionic-team/ionic-framework/issues/23981)
* **datetime:** localize am/pm labels in time picker ([#25389](https://github.com/ionic-team/ionic-framework/issues/25389)) ([6bc0acc](https://github.com/ionic-team/ionic-framework/commit/6bc0acc4279a18c3309b11eeec76676c5015419a)), closes [#16279](https://github.com/ionic-team/ionic-framework/issues/16279)
* **modal:** clicking handle advances to the next breakpoint ([#25540](https://github.com/ionic-team/ionic-framework/issues/25540)) ([7cdc388](https://github.com/ionic-team/ionic-framework/commit/7cdc388b7805cbf23c9e1e928aa977cd77ebc8c4)), closes [#24069](https://github.com/ionic-team/ionic-framework/issues/24069)
* **range:** add reference point for start position of range slider ([#25598](https://github.com/ionic-team/ionic-framework/issues/25598)) ([c2781cc](https://github.com/ionic-team/ionic-framework/commit/c2781cc1c3b7e56a0e6f6c03cfa04fc2c82d6e8a)), closes [#24348](https://github.com/ionic-team/ionic-framework/issues/24348)
* **toggle:** on/off icons for toggle ([#25459](https://github.com/ionic-team/ionic-framework/issues/25459)) ([bc0bdc4](https://github.com/ionic-team/ionic-framework/commit/bc0bdc438ba72c695f9d961ddf837ec45e7816dd)), closes [#20524](https://github.com/ionic-team/ionic-framework/issues/20524)




## [6.1.15](https://github.com/ionic-team/ionic/compare/v6.1.14...v6.1.15) (2022-07-20)


### Bug Fixes

* **datetime:** use scroll listener to detect month changes ([#25586](https://github.com/ionic-team/ionic/issues/25586)) ([b7afcb0](https://github.com/ionic-team/ionic/commit/b7afcb0f0c36d84f3b4d65844df28e6293bc1ea5)), closes [#25257](https://github.com/ionic-team/ionic/issues/25257) [#25608](https://github.com/ionic-team/ionic/issues/25608) [#24980](https://github.com/ionic-team/ionic/issues/24980)
* **fab-button:** aria attributes are inherited ([#25635](https://github.com/ionic-team/ionic/issues/25635)) ([64ae3d2](https://github.com/ionic-team/ionic/commit/64ae3d2b9729c5c6be8644b1df6c8b3d40584d3b)), closes [#25633](https://github.com/ionic-team/ionic/issues/25633)
* **modal:** allow for custom dialog implementations ([#25630](https://github.com/ionic-team/ionic/issues/25630)) ([a6f3ae6](https://github.com/ionic-team/ionic/commit/a6f3ae67ab91ab95408ad425156167edc3570978)), closes [#24080](https://github.com/ionic-team/ionic/issues/24080)


### Performance Improvements

* **input:** passive event listener for touch start events ([#25610](https://github.com/ionic-team/ionic/issues/25610)) ([2d1efdb](https://github.com/ionic-team/ionic/commit/2d1efdbe6dd9436badab4684f2a484476489c166)), closes [#25599](https://github.com/ionic-team/ionic/issues/25599)





## [6.1.14](https://github.com/ionic-team/ionic/compare/v6.1.13...v6.1.14) (2022-07-13)


### Bug Fixes

* **datetime:** datetime works within stencil apps ([#25592](https://github.com/ionic-team/ionic/issues/25592)) ([7b10fa6](https://github.com/ionic-team/ionic/commit/7b10fa6476c2c2896c6810c57b3160f8c8896faa)), closes [#25591](https://github.com/ionic-team/ionic/issues/25591)





## [6.1.13](https://github.com/ionic-team/ionic/compare/v6.1.12...v6.1.13) (2022-07-06)


### Bug Fixes

* **all:** long press now preserves activated state ([#25551](https://github.com/ionic-team/ionic/issues/25551)) ([a8286f6](https://github.com/ionic-team/ionic/commit/a8286f6e42f734a027416ac6cd659e3dce4edccb)), closes [#25544](https://github.com/ionic-team/ionic/issues/25544)
* **datetime:** typing in time now updates value ([#25561](https://github.com/ionic-team/ionic/issues/25561)) ([1b1b1a3](https://github.com/ionic-team/ionic/commit/1b1b1a3800c4d044b4a3e7418f534e9271770ec6)), closes [#25560](https://github.com/ionic-team/ionic/issues/25560)





## [6.1.12](https://github.com/ionic-team/ionic/compare/v6.1.11...v6.1.12) (2022-06-29)


### Bug Fixes

* **datetime:** add dev warnings when setting out of bounds value ([#25513](https://github.com/ionic-team/ionic/issues/25513)) ([5dfaf63](https://github.com/ionic-team/ionic/commit/5dfaf63c6582811b61339a6fa50cf551cd8724d0))





## [6.1.11](https://github.com/ionic-team/ionic/compare/v6.1.10...v6.1.11) (2022-06-22)


### Bug Fixes

* **datetime:** closing time picker no longer changes month ([#25478](https://github.com/ionic-team/ionic/issues/25478)) ([f9ab9b5](https://github.com/ionic-team/ionic/commit/f9ab9b54ddb5a3004673e4aaa9cb62fd8e97ba07)), closes [#25438](https://github.com/ionic-team/ionic/issues/25438)
* **item:** multiple input appearance when using datetime ([#25484](https://github.com/ionic-team/ionic/issues/25484)) ([3089f38](https://github.com/ionic-team/ionic/commit/3089f38f4d335c44e9913e874813dd4205c2b160)), closes [#25479](https://github.com/ionic-team/ionic/issues/25479)
* **item:** multiple input appearance when using datetime ([#25498](https://github.com/ionic-team/ionic/issues/25498)) ([1a8d23d](https://github.com/ionic-team/ionic/commit/1a8d23da8125d54c3119eacb51206f7541c9f410)), closes [#25484](https://github.com/ionic-team/ionic/issues/25484) [#25483](https://github.com/ionic-team/ionic/issues/25483)
* **overlays:** focus is not moved if active element is in overlay ([#25481](https://github.com/ionic-team/ionic/issues/25481)) ([dcc2da2](https://github.com/ionic-team/ionic/commit/dcc2da2800e69d938b4a62db436d9f07d9663dce)), closes [#24127](https://github.com/ionic-team/ionic/issues/24127) [#24820](https://github.com/ionic-team/ionic/issues/24820)
* **refresher:** quickly swiping down no longer causes duplicate refresh ([#25476](https://github.com/ionic-team/ionic/issues/25476)) ([3abfa78](https://github.com/ionic-team/ionic/commit/3abfa780ccb32484b4d9f1b509e7ab910dfb901a)), closes [#25418](https://github.com/ionic-team/ionic/issues/25418)
* **vue:** components have correct type definitions ([#25499](https://github.com/ionic-team/ionic/issues/25499)) ([b1821e9](https://github.com/ionic-team/ionic/commit/b1821e9d0a55f20f74696f119de724ab70647977)), closes [#25485](https://github.com/ionic-team/ionic/issues/25485)





## [6.1.10](https://github.com/ionic-team/ionic/compare/v6.1.9...v6.1.10) (2022-06-15)


### Bug Fixes

* **fab-button:** improve ripple effect behavior on click ([#25413](https://github.com/ionic-team/ionic/issues/25413)) ([efdaf90](https://github.com/ionic-team/ionic/commit/efdaf90c5a767211e0034bab7cce5bd463ff5aa0)), closes [#21772](https://github.com/ionic-team/ionic/issues/21772)
* **modal:** backdrop animation when backdropBreakpoint is 1 ([#25430](https://github.com/ionic-team/ionic/issues/25430)) ([c10df52](https://github.com/ionic-team/ionic/commit/c10df52f39c527dd7e03176c56a2e6cb0ebe455f)), closes [#25402](https://github.com/ionic-team/ionic/issues/25402)
* **modal:** status bar color now correct with sheet modal ([#25424](https://github.com/ionic-team/ionic/issues/25424)) ([377c4f5](https://github.com/ionic-team/ionic/commit/377c4f597b972818d90132017d50c33074ddadab)), closes [#20501](https://github.com/ionic-team/ionic/issues/20501)
* **picker-column-internal:** switching off an input mode column preserves scroll ([#25467](https://github.com/ionic-team/ionic/issues/25467)) ([989429d](https://github.com/ionic-team/ionic/commit/989429d65cf57ef8fb69854639f8eac1a12369bc))
* **popover:** ensure popover does not go offscreen when adjusting top position ([#25350](https://github.com/ionic-team/ionic/issues/25350)) ([6926538](https://github.com/ionic-team/ionic/commit/692653842b43b5e36c51163f8261fde3b5bea40d)), closes [#25349](https://github.com/ionic-team/ionic/issues/25349)





## [6.1.9](https://github.com/ionic-team/ionic/compare/v6.1.8...v6.1.9) (2022-06-08)


### Bug Fixes

* **all:** ripple effect is no longer added when scrolling ([#25352](https://github.com/ionic-team/ionic/issues/25352)) ([0b275af](https://github.com/ionic-team/ionic/commit/0b275af5ac06f470b4d908b889f513956bf5d868)), closes [#22030](https://github.com/ionic-team/ionic/issues/22030)
* **datetime:** emit ionChange for non-calendar picker presentation ([#25380](https://github.com/ionic-team/ionic/issues/25380)) ([4e6a60b](https://github.com/ionic-team/ionic/commit/4e6a60b6a42287e5091728aecb61f6097e131b83)), closes [#25375](https://github.com/ionic-team/ionic/issues/25375)
* **datetime:** ensure that default month shown is always in bounds ([#25351](https://github.com/ionic-team/ionic/issues/25351)) ([866d452](https://github.com/ionic-team/ionic/commit/866d4528ad1b8ffa65258595d553ea934daa4add)), closes [#25320](https://github.com/ionic-team/ionic/issues/25320)
* **label:** text contents will repaint on change ([#25395](https://github.com/ionic-team/ionic/issues/25395)) ([52ec741](https://github.com/ionic-team/ionic/commit/52ec74193b4e2478cb84a6dfea261cb2113dcbff))





## [6.1.8](https://github.com/ionic-team/ionic/compare/v6.1.7...v6.1.8) (2022-06-01)


### Bug Fixes

* **all:** improve compatibility with vite ([#25381](https://github.com/ionic-team/ionic/issues/25381)) ([d83bcd2](https://github.com/ionic-team/ionic/commit/d83bcd2b7f9937550008f995ff91517777584373)), closes [#23823](https://github.com/ionic-team/ionic/issues/23823)
* **item-sliding:** swiping inside of virtual scroller now prevents scrolling ([#25345](https://github.com/ionic-team/ionic/issues/25345)) ([5a1a5f6](https://github.com/ionic-team/ionic/commit/5a1a5f6b4c2ab4059158986e907fff45d03be753))
* **range:** dragging knob no longer scrolls page ([#25343](https://github.com/ionic-team/ionic/issues/25343)) ([0b92dff](https://github.com/ionic-team/ionic/commit/0b92dffa92c05705ff83518c10608e3dc3651d51)), closes [#19004](https://github.com/ionic-team/ionic/issues/19004)





## [6.1.7](https://github.com/ionic-team/ionic/compare/v6.1.6...v6.1.7) (2022-05-26)


### Bug Fixes

* **accordion:** accordions expand when using binding ([#25322](https://github.com/ionic-team/ionic/issues/25322)) ([61e571e](https://github.com/ionic-team/ionic/commit/61e571e585ed8ad9b0ca2f98f57bb16616413ba6)), closes [#25307](https://github.com/ionic-team/ionic/issues/25307)
* **datetime:** don't update value on confirm call if no date was selected ([#25338](https://github.com/ionic-team/ionic/issues/25338)) ([9e5b10a](https://github.com/ionic-team/ionic/commit/9e5b10a2155c6b9de565931da384e0e49aeca7b7))
* **item, list:** list aria roles are added ([#25336](https://github.com/ionic-team/ionic/issues/25336)) ([311c634](https://github.com/ionic-team/ionic/commit/311c634d20e9e597db676d6f54e4b79cfe742a61)), closes [#19939](https://github.com/ionic-team/ionic/issues/19939)
* **menu:** rtl menu no longer disappears on ios 15 ([#25309](https://github.com/ionic-team/ionic/issues/25309)) ([6005431](https://github.com/ionic-team/ionic/commit/60054310afbab6151f6c29ff6e74666acd181a41)), closes [#25192](https://github.com/ionic-team/ionic/issues/25192)
* **modal:** swipe to close on content blocks scroll in ion-nav ([#25300](https://github.com/ionic-team/ionic/issues/25300)) ([fdc55c0](https://github.com/ionic-team/ionic/commit/fdc55c072765c87ad7c783e6d8a238b007f5f3ff)), closes [#25298](https://github.com/ionic-team/ionic/issues/25298)
* **nav:** swipe to go back works inside card modal ([#25333](https://github.com/ionic-team/ionic/issues/25333)) ([0156be6](https://github.com/ionic-team/ionic/commit/0156be61cbf73b25cb3c2cba1bd20adebbb3db4f)), closes [#25327](https://github.com/ionic-team/ionic/issues/25327)
* **refresher:** attach scroll listener to custom scroll target ([#25335](https://github.com/ionic-team/ionic/issues/25335)) ([8f5e4cd](https://github.com/ionic-team/ionic/commit/8f5e4cd9350b10a98afb7c98353c6719eee918bb)), closes [#25318](https://github.com/ionic-team/ionic/issues/25318)
* **types:** improve intellisense with colors ([#25347](https://github.com/ionic-team/ionic/issues/25347)) ([97cfbbb](https://github.com/ionic-team/ionic/commit/97cfbbb65d3e63c32d720e01c7368c68616bb531))





## [6.1.6](https://github.com/ionic-team/ionic/compare/v6.1.5...v6.1.6) (2022-05-18)


### Bug Fixes

* **loading:** spinner now respects —spinner-color ([#25261](https://github.com/ionic-team/ionic/issues/25261)) ([65f4c74](https://github.com/ionic-team/ionic/commit/65f4c742e7a5e5756f6f72dd853e38e885f90385)), closes [#25180](https://github.com/ionic-team/ionic/issues/25180)
* **modal:** reset breakpoint to initial breakpoint on present ([#25246](https://github.com/ionic-team/ionic/issues/25246)) ([2557bf3](https://github.com/ionic-team/ionic/commit/2557bf3c3eed9e33e89e07a8d73489da8d81bee3)), closes [#25245](https://github.com/ionic-team/ionic/issues/25245)
* **scroll-assist:** touch end events continue to bubble on inputs ([#25282](https://github.com/ionic-team/ionic/issues/25282)) ([780f16d](https://github.com/ionic-team/ionic/commit/780f16d9e04ee5aaaf91bb7c6ef15c72cc8aeb45)), closes [#25229](https://github.com/ionic-team/ionic/issues/25229)





## [6.1.5](https://github.com/ionic-team/ionic/compare/v6.1.4...v6.1.5) (2022-05-11)


### Bug Fixes

* **core:** @axe-core/playwright should be a devDependency ([#25244](https://github.com/ionic-team/ionic/issues/25244)) ([617ec48](https://github.com/ionic-team/ionic/commit/617ec48265157d1502c443395472c21ebdb2989e)), closes [#25242](https://github.com/ionic-team/ionic/issues/25242)
* **item:** counter has appropriate contrast ([#25266](https://github.com/ionic-team/ionic/issues/25266)) ([750be33](https://github.com/ionic-team/ionic/commit/750be33772e9ba71a3cda35709d17b7912aa68e2)), closes [#25262](https://github.com/ionic-team/ionic/issues/25262)
* **spinner:** alignment is now correct in rtl ([#25260](https://github.com/ionic-team/ionic/issues/25260)) ([e3c996d](https://github.com/ionic-team/ionic/commit/e3c996dea878a8dd276a0ca99f59b330125f9b75))





## [6.1.4](https://github.com/ionic-team/ionic/compare/v6.1.3...v6.1.4) (2022-05-04)


### Bug Fixes

* **datetime:** arrow navigation respects min/max values ([#25182](https://github.com/ionic-team/ionic/issues/25182)) ([6946e09](https://github.com/ionic-team/ionic/commit/6946e09815da605e37ff8e4d613a14288ea35fb0)), closes [#25073](https://github.com/ionic-team/ionic/issues/25073)
* **datetime:** hide footer when month-year picker is open ([#25205](https://github.com/ionic-team/ionic/issues/25205)) ([aa5e1b9](https://github.com/ionic-team/ionic/commit/aa5e1b962150b9ed9629812ec566873784526c83))
* **modal:** card modal can now be swiped to close on the content ([#25185](https://github.com/ionic-team/ionic/issues/25185)) ([7633ddb](https://github.com/ionic-team/ionic/commit/7633ddbc845745dfe36b5c8025c54c22c083c2f4)), closes [#22046](https://github.com/ionic-team/ionic/issues/22046)
* **modal:** card modal no longer dismisses from content with refresher ([#25227](https://github.com/ionic-team/ionic/issues/25227)) ([c4f811f](https://github.com/ionic-team/ionic/commit/c4f811f1dde0dcbcdaebaa3a4f5ef87e192b5cc5))





## [6.1.3](https://github.com/ionic-team/ionic/compare/v6.1.2...v6.1.3) (2022-04-27)


### Bug Fixes

* **core:** inherit aria attributes on host elements ([#25156](https://github.com/ionic-team/ionic/issues/25156)) ([611832b](https://github.com/ionic-team/ionic/commit/611832b0d51da295c1bf2897972c4e8baf6e23a3)), closes [#20127](https://github.com/ionic-team/ionic/issues/20127)
* **datetime:** if no default value, don't highlight active day until one is selected ([#25151](https://github.com/ionic-team/ionic/issues/25151)) ([9896939](https://github.com/ionic-team/ionic/commit/98969395abd400cc44d2d3825581a63eb64a56e0))
* **picker-column-internal:** center active item when rapidly opened ([#25155](https://github.com/ionic-team/ionic/issues/25155)) ([8e17fa9](https://github.com/ionic-team/ionic/commit/8e17fa9d5f9b00139693e34bc93b1f9c718ea3cf)), closes [#25154](https://github.com/ionic-team/ionic/issues/25154)
* **select:** avoid duplicate dialogs and backdrops when clicking ([#25175](https://github.com/ionic-team/ionic/issues/25175)) ([70d2784](https://github.com/ionic-team/ionic/commit/70d278414eb5124d17c5ffaba5231c6bfd285656)), closes [#25126](https://github.com/ionic-team/ionic/issues/25126)





## [6.1.2](https://github.com/ionic-team/ionic/compare/v6.1.1...v6.1.2) (2022-04-20)


### Bug Fixes

* **datetime:** time picker display matches dynamically set value ([#25010](https://github.com/ionic-team/ionic/issues/25010)) ([11493a0](https://github.com/ionic-team/ionic/commit/11493a086a4e3f2a4e9d3acdf5a9d49e810a5ef0)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **modal:** add canDismiss option to modal options ([#25144](https://github.com/ionic-team/ionic/issues/25144)) ([2984ddf](https://github.com/ionic-team/ionic/commit/2984ddf111b6acbd9e47ed90830b6522179b6cee)), closes [#25143](https://github.com/ionic-team/ionic/issues/25143)





## [6.1.1](https://github.com/ionic-team/ionic/compare/v6.1.0...v6.1.1) (2022-04-15)


### Bug Fixes

* **all:** import path is now correct when using ionic in a stencil app ([#25123](https://github.com/ionic-team/ionic/issues/25123)) ([1b407ab](https://github.com/ionic-team/ionic/commit/1b407abdf5d8a2a18b6a2b9daca2d58b7b0f782b)), closes [#25122](https://github.com/ionic-team/ionic/issues/25122)
* **datetime:** account for 30 and 45 minute timezones when getting current date ([#25120](https://github.com/ionic-team/ionic/issues/25120)) ([96b2003](https://github.com/ionic-team/ionic/commit/96b2003b2bd5089d1faafe262e96c7445c5c3349)), closes [#25112](https://github.com/ionic-team/ionic/issues/25112)
* **modal, popover:** do not dismiss when ionDismiss is emitted from select ([#25125](https://github.com/ionic-team/ionic/issues/25125)) ([90115db](https://github.com/ionic-team/ionic/commit/90115db98540a5fc67b611ac2742d1221b8e96ff)), closes [#25124](https://github.com/ionic-team/ionic/issues/25124)





# [6.1.0](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.1.0) (2022-04-13)


### Bug Fixes

* **accordion-group:** only allow keyboard interaction if header is focused ([#25091](https://github.com/ionic-team/ionic/issues/25091)) ([e1b555f](https://github.com/ionic-team/ionic/commit/e1b555f286956574876924068304fc44a78c027c))
* **datetime:** resolve warnings when importing into Stencil app ([#25106](https://github.com/ionic-team/ionic/issues/25106)) ([a61c004](https://github.com/ionic-team/ionic/commit/a61c004fb0c10d9fb0eca0987edf798386251ec2))
* **datetime:** warn when parsing an invalid date value ([#25049](https://github.com/ionic-team/ionic/issues/25049)) ([982dc85](https://github.com/ionic-team/ionic/commit/982dc853befe8ccf54163a0b145e563da06f5dc1))
* **menu:** preserve scroll position when focusing on open ([#25044](https://github.com/ionic-team/ionic/issues/25044)) ([da89684](https://github.com/ionic-team/ionic/commit/da896848776105ba1f7035c4412495786199bade))
* **picker-column:** column renders correctly with selected value ([#24988](https://github.com/ionic-team/ionic/issues/24988)) ([8318659](https://github.com/ionic-team/ionic/commit/83186598ed6cf08b0f0421076c4afb3ab53e1e57)), closes [#17664](https://github.com/ionic-team/ionic/issues/17664)
* **popover:** allow arrow on desktop ([#25056](https://github.com/ionic-team/ionic/issues/25056)) ([bcd00c7](https://github.com/ionic-team/ionic/commit/bcd00c7a6ebb6a00193f04458976ff8b86395215))
* **popover:** only focus trap ion-item children ([#24990](https://github.com/ionic-team/ionic/issues/24990)) ([0cd06a6](https://github.com/ionic-team/ionic/commit/0cd06a675474e1893b4c0801fab8ab79813537c8)), closes [#24633](https://github.com/ionic-team/ionic/issues/24633)
* **ripple-effect:** ripple displays on click or touch ([#25102](https://github.com/ionic-team/ionic/issues/25102)) ([2a313e9](https://github.com/ionic-team/ionic/commit/2a313e91179e19660a758470ed2218bbcf03e0bb)), closes [#25094](https://github.com/ionic-team/ionic/issues/25094)


### Features

* **content, reorder-group, header, footer, infinite-scroll, refresher:** add custom scroll target to improve compatibility with virtual scroll ([#24883](https://github.com/ionic-team/ionic/issues/24883)) ([2a438da](https://github.com/ionic-team/ionic/commit/2a438da010ddd4d4211e1879e27d7b28409daaa2)), closes [#23437](https://github.com/ionic-team/ionic/issues/23437)
* **datetime:** isDateEnabled to enable/disable specific days  ([#24898](https://github.com/ionic-team/ionic/issues/24898)) ([e932a04](https://github.com/ionic-team/ionic/commit/e932a042237e6f44bf278bcbd895d8569fc17348)), closes [#24209](https://github.com/ionic-team/ionic/issues/24209)
* **item:** counter formatter to customize counter text display ([#24336](https://github.com/ionic-team/ionic/issues/24336)) ([171020e](https://github.com/ionic-team/ionic/commit/171020e9d200ccfdef0f01c427b295bb50dd1fef)), closes [#24327](https://github.com/ionic-team/ionic/issues/24327)
* **modal:** ability to programmatically set current sheet breakpoint ([#24648](https://github.com/ionic-team/ionic/issues/24648)) ([3145c76](https://github.com/ionic-team/ionic/commit/3145c76934ac711038f9dcba98a385dfbe754953)), closes [#23917](https://github.com/ionic-team/ionic/issues/23917)
* **modal:** add canDismiss property to manage modal dismissing ([#24928](https://github.com/ionic-team/ionic/issues/24928)) ([4b21958](https://github.com/ionic-team/ionic/commit/4b21958ec57019afcde786598880e1f8edada2b1)), closes [#22297](https://github.com/ionic-team/ionic/issues/22297)
* **range:** add knobMoveStart and knobMoveEnd events ([#25011](https://github.com/ionic-team/ionic/issues/25011)) ([f5cb1f8](https://github.com/ionic-team/ionic/commit/f5cb1f8444ba050042e788f9f9ec7b6309bf1b60))
* **select:** add event for when overlay is dismissed ([#24400](https://github.com/ionic-team/ionic/issues/24400)) ([b835b7c](https://github.com/ionic-team/ionic/commit/b835b7c0c7840f41c54f96743cc0a779ff474ab6))





## [6.0.16](https://github.com/ionic-team/ionic/compare/v6.0.15...v6.0.16) (2022-04-08)

**Note:** Version bump only for package @ionic/core





## [6.0.15](https://github.com/ionic-team/ionic/compare/v6.0.14...v6.0.15) (2022-04-06)


### Bug Fixes

* **datetime:** warn when parsing an invalid date value ([#25049](https://github.com/ionic-team/ionic/issues/25049)) ([982dc85](https://github.com/ionic-team/ionic/commit/982dc853befe8ccf54163a0b145e563da06f5dc1))
* **picker-column:** column renders correctly with selected value ([#24988](https://github.com/ionic-team/ionic/issues/24988)) ([8318659](https://github.com/ionic-team/ionic/commit/83186598ed6cf08b0f0421076c4afb3ab53e1e57)), closes [#17664](https://github.com/ionic-team/ionic/issues/17664)
* **popover:** allow arrow on desktop ([#25056](https://github.com/ionic-team/ionic/issues/25056)) ([bcd00c7](https://github.com/ionic-team/ionic/commit/bcd00c7a6ebb6a00193f04458976ff8b86395215))





## [6.0.14](https://github.com/ionic-team/ionic/compare/v6.0.13...v6.0.14) (2022-03-30)

**Note:** Version bump only for package @ionic/core





## [6.0.13](https://github.com/ionic-team/ionic/compare/v6.0.12...v6.0.13) (2022-03-23)


### Bug Fixes

* **datetime:** presentation time emits ionChange once  ([#24968](https://github.com/ionic-team/ionic/issues/24968)) ([2909b08](https://github.com/ionic-team/ionic/commit/2909b080b7020299a4554c1459b4b190ff739085)), closes [#24967](https://github.com/ionic-team/ionic/issues/24967)
* **popover:** dismissing nested popover via backdrop now works ([#24957](https://github.com/ionic-team/ionic/issues/24957)) ([9e84ef7](https://github.com/ionic-team/ionic/commit/9e84ef7f91d76ca5a1ecaffc7592287267d5368b)), closes [#24954](https://github.com/ionic-team/ionic/issues/24954)





## [6.0.12](https://github.com/ionic-team/ionic/compare/v6.0.11...v6.0.12) (2022-03-16)


### Bug Fixes

* **datetime:** reinit behavior on presentation change ([#24828](https://github.com/ionic-team/ionic/issues/24828)) ([d46e1e8](https://github.com/ionic-team/ionic/commit/d46e1e8506ca5095817b421e9edb37d41451e885))
* **toast:** screen readers now announce toasts when presented ([#24937](https://github.com/ionic-team/ionic/issues/24937)) ([8a97f6b](https://github.com/ionic-team/ionic/commit/8a97f6b5c9ca1e77c1790abd1e924955b6b6ea27)), closes [#22333](https://github.com/ionic-team/ionic/issues/22333)





## [6.0.11](https://github.com/ionic-team/ionic/compare/v6.0.10...v6.0.11) (2022-03-09)


### Bug Fixes

* **datetime:** time picker now scrolls to correct value ([#24879](https://github.com/ionic-team/ionic/issues/24879)) ([331ce6d](https://github.com/ionic-team/ionic/commit/331ce6d6769900e2aec9e30d35b52cfd40cbb889)), closes [#24878](https://github.com/ionic-team/ionic/issues/24878)
* **ios:** swipe to go back now works in rtl mode ([#24866](https://github.com/ionic-team/ionic/issues/24866)) ([2ac9105](https://github.com/ionic-team/ionic/commit/2ac9105796a0765fabc48592b5b44ac58c568579)), closes [#19488](https://github.com/ionic-team/ionic/issues/19488)


### Performance Improvements

* improve treeshaking functionality ([#24895](https://github.com/ionic-team/ionic/issues/24895)) ([805907a](https://github.com/ionic-team/ionic/commit/805907af4e78179f1acc9cb02263b1ea10d4e3df)), closes [#24280](https://github.com/ionic-team/ionic/issues/24280)





## [6.0.10](https://github.com/ionic-team/ionic/compare/v6.0.9...v6.0.10) (2022-03-02)


### Bug Fixes

* **datetime:** confirm method now uses selected date ([#24827](https://github.com/ionic-team/ionic/issues/24827)) ([c35b898](https://github.com/ionic-team/ionic/commit/c35b898f1dc0fb706446b6971982df48fd72fe6d)), closes [#24823](https://github.com/ionic-team/ionic/issues/24823)
* **datetime:** persist minutes column on hour change ([#24829](https://github.com/ionic-team/ionic/issues/24829)) ([aacb58a](https://github.com/ionic-team/ionic/commit/aacb58a3224e3cc51c731d0c9aa52f52c9276692)), closes [#24821](https://github.com/ionic-team/ionic/issues/24821)
* **item-sliding:** close() will maintain disabled state ([#24847](https://github.com/ionic-team/ionic/issues/24847)) ([ea4a9bb](https://github.com/ionic-team/ionic/commit/ea4a9bb69465f8e97746b36638f0b3a26e45da18)), closes [#24747](https://github.com/ionic-team/ionic/issues/24747)
* **modal:** re-enable swipe gestures when modal is dismissed ([#24846](https://github.com/ionic-team/ionic/issues/24846)) ([836c01c](https://github.com/ionic-team/ionic/commit/836c01c73e42caab0101ac4988f0a9b27cf96a5b)), closes [#24817](https://github.com/ionic-team/ionic/issues/24817)
* **modal:** sheet modal now allows input focusing when backdrop disabled ([#24840](https://github.com/ionic-team/ionic/issues/24840)) ([e4ec572](https://github.com/ionic-team/ionic/commit/e4ec572043e22bd2626dbcfd204fc22a7335282c)), closes [#24581](https://github.com/ionic-team/ionic/issues/24581)





## [6.0.9](https://github.com/ionic-team/ionic/compare/v6.0.8...v6.0.9) (2022-02-23)


### Bug Fixes

* **datetime:** improve datetime sizing in modals ([#24762](https://github.com/ionic-team/ionic/issues/24762)) ([b0ac7de](https://github.com/ionic-team/ionic/commit/b0ac7de168c353ba4899cb74a2b38e25fd0cc0f1)), closes [#23992](https://github.com/ionic-team/ionic/issues/23992)
* **datetime:** month and year column order is now locale aware ([#24802](https://github.com/ionic-team/ionic/issues/24802)) ([16647b2](https://github.com/ionic-team/ionic/commit/16647b2c7290389755a4093145788f281c84b7e2)), closes [#24548](https://github.com/ionic-team/ionic/issues/24548)
* **datetime:** month picker no longer gives duplicate months on ios 14 and older ([#24792](https://github.com/ionic-team/ionic/issues/24792)) ([b6d7e1c](https://github.com/ionic-team/ionic/commit/b6d7e1c75740a61dcd02c21692e4d4632fb8df5c)), closes [#24663](https://github.com/ionic-team/ionic/issues/24663)
* **img:** draggable attribute is now inherited to inner img element ([#24781](https://github.com/ionic-team/ionic/issues/24781)) ([19ac238](https://github.com/ionic-team/ionic/commit/19ac2389eb0843173f51a12de41ac808cd8f0569)), closes [#21325](https://github.com/ionic-team/ionic/issues/21325)
* **modal:** backdropBreakpoint allows interactivity behind sheet ([#24798](https://github.com/ionic-team/ionic/issues/24798)) ([fca3f56](https://github.com/ionic-team/ionic/commit/fca3f56ca4568e63fd493debda088263caa86c64)), closes [#24797](https://github.com/ionic-team/ionic/issues/24797)
* **popover:** default alignment to 'center' for ios mode ([#24815](https://github.com/ionic-team/ionic/issues/24815)) ([243f673](https://github.com/ionic-team/ionic/commit/243f67362f25699bdb373be6b72cb9c14dc95a32))
* **react, vue:** scroll is no longer interrupted on ios ([#24791](https://github.com/ionic-team/ionic/issues/24791)) ([99c91ef](https://github.com/ionic-team/ionic/commit/99c91eff8764c9a1630adedab6a9765dd9754f7d)), closes [#24435](https://github.com/ionic-team/ionic/issues/24435)
* **select:** interface components now show correctly ([#24810](https://github.com/ionic-team/ionic/issues/24810)) ([2fc2de5](https://github.com/ionic-team/ionic/commit/2fc2de51771f4a5c3f20c6071284096e5bf31ec8)), closes [#24807](https://github.com/ionic-team/ionic/issues/24807)
* **toast:** toast is now correctly excluded from focus trapping ([#24816](https://github.com/ionic-team/ionic/issues/24816)) ([8246112](https://github.com/ionic-team/ionic/commit/8246112ca12f90edb98629ab82e27a792a1fafad)), closes [#24733](https://github.com/ionic-team/ionic/issues/24733)





## [6.0.8](https://github.com/ionic-team/ionic/compare/v6.0.7...v6.0.8) (2022-02-15)


### Bug Fixes

* **back-button, breadcrumb, item:** flip chevron icons on RTL ([#24705](https://github.com/ionic-team/ionic/issues/24705)) ([a093544](https://github.com/ionic-team/ionic/commit/a093544fdfc438ed03024285b2a35c5f645ea011))
* **datetime:** navigate to month within min range ([#24759](https://github.com/ionic-team/ionic/issues/24759)) ([7b3838c](https://github.com/ionic-team/ionic/commit/7b3838cc670de7845bb5937d204e86cdba93b6e6)), closes [#24757](https://github.com/ionic-team/ionic/issues/24757)
* **input:** only set native input value if different ([#24758](https://github.com/ionic-team/ionic/issues/24758)) ([fd031aa](https://github.com/ionic-team/ionic/commit/fd031aa1c3f05b7bfa3e0a0ee2a4793e29e22df5)), closes [#24753](https://github.com/ionic-team/ionic/issues/24753)
* **router-outlet:** getRouteId() returns the params set in setRouteId(). ([#24656](https://github.com/ionic-team/ionic/issues/24656)) ([be2205e](https://github.com/ionic-team/ionic/commit/be2205e5a2b2f8778bd1f7b4ea5cae0bf96f9ef3)), closes [#24652](https://github.com/ionic-team/ionic/issues/24652)
* **router-outlet:** navigating to same route with different params now activates component ([#24760](https://github.com/ionic-team/ionic/issues/24760)) ([abc36ae](https://github.com/ionic-team/ionic/commit/abc36ae80b060a659f7557ad90efe98b78f5ead9)), closes [#24653](https://github.com/ionic-team/ionic/issues/24653)





## [6.0.7](https://github.com/ionic-team/ionic/compare/v6.0.6...v6.0.7) (2022-02-09)


### Bug Fixes

* **angular:** inline modals now add .ion-page class correctly ([#24751](https://github.com/ionic-team/ionic/issues/24751)) ([ef46eaf](https://github.com/ionic-team/ionic/commit/ef46eafc9476a85ea3369e542f528d01d3cca0a8)), closes [#24750](https://github.com/ionic-team/ionic/issues/24750)





## [6.0.6](https://github.com/ionic-team/ionic/compare/v6.0.5...v6.0.6) (2022-02-09)


### Bug Fixes

* **action-sheet:** background includes safe area margin ([#24700](https://github.com/ionic-team/ionic/issues/24700)) ([8c22646](https://github.com/ionic-team/ionic/commit/8c22646d66e2077fc88aaacf350330097733bb9b)), closes [#24699](https://github.com/ionic-team/ionic/issues/24699)
* **angular, react,  vue:** overlays no longer throw errors when used inside tests ([#24681](https://github.com/ionic-team/ionic/issues/24681)) ([897ae4a](https://github.com/ionic-team/ionic/commit/897ae4a4546ac0dd811125d5513ef23d133a1589)), closes [#24549](https://github.com/ionic-team/ionic/issues/24549) [#24590](https://github.com/ionic-team/ionic/issues/24590)
* **datetime:** disable intersection observer during month update ([#24713](https://github.com/ionic-team/ionic/issues/24713)) ([aab4d30](https://github.com/ionic-team/ionic/commit/aab4d306f80851bfd8a02a6361e26d60faeaadb4)), closes [#24712](https://github.com/ionic-team/ionic/issues/24712)
* **datetime:** minutes only filtered when max hour matches current hour ([#24710](https://github.com/ionic-team/ionic/issues/24710)) ([231d6df](https://github.com/ionic-team/ionic/commit/231d6df622c1f5dd9ecdff6fed8f61a4bff332df)), closes [#24702](https://github.com/ionic-team/ionic/issues/24702)
* **input:** cursor position does not jump to end ([#24736](https://github.com/ionic-team/ionic/issues/24736)) ([4ff9524](https://github.com/ionic-team/ionic/commit/4ff9524e1057aa487069b5982c5f1ecdf51d982b)), closes [#24727](https://github.com/ionic-team/ionic/issues/24727)
* **input:** IME composition mode ([#24735](https://github.com/ionic-team/ionic/issues/24735)) ([c6381ce](https://github.com/ionic-team/ionic/commit/c6381ce4f90707774d1c8662bba874f7b306bd1c)), closes [#24669](https://github.com/ionic-team/ionic/issues/24669)
* **modal, popover:** quickly opening modal/popover no longer presents duplicates ([#24697](https://github.com/ionic-team/ionic/issues/24697)) ([928c5fb](https://github.com/ionic-team/ionic/commit/928c5fbfcbf3ef1b2c3074464fc20dcf1fe143ae))
* **modal:** inline modals inherit ion-page styling ([#24723](https://github.com/ionic-team/ionic/issues/24723)) ([596aad4](https://github.com/ionic-team/ionic/commit/596aad435b5102307da89dd626ca4682b78db452)), closes [#24706](https://github.com/ionic-team/ionic/issues/24706)
* **popover:** use alignment with popover options ([#24711](https://github.com/ionic-team/ionic/issues/24711)) ([f5c5c3c](https://github.com/ionic-team/ionic/commit/f5c5c3cffa4f34046b0e9471a9f193db3772180e)), closes [#24709](https://github.com/ionic-team/ionic/issues/24709)
* **router:** router push with relative path ([#24719](https://github.com/ionic-team/ionic/issues/24719)) ([d40c0c3](https://github.com/ionic-team/ionic/commit/d40c0c3a0993eaefbe5107e98958c6b0699a62c2)), closes [#24718](https://github.com/ionic-team/ionic/issues/24718)
* **select:** value is selected when given array ([#24687](https://github.com/ionic-team/ionic/issues/24687)) ([6ee7d15](https://github.com/ionic-team/ionic/commit/6ee7d159ecfff3382fadb524c5c430172d40c267)), closes [#24742](https://github.com/ionic-team/ionic/issues/24742)





## [6.0.5](https://github.com/ionic-team/ionic/compare/v6.0.4...v6.0.5) (2022-02-02)


### Bug Fixes

* **datetime:** prevent navigating to disabled months ([#24421](https://github.com/ionic-team/ionic/issues/24421)) ([b40fc46](https://github.com/ionic-team/ionic/commit/b40fc4632efcdc01f1062d9bcec826afff5cf4ea)), closes [#24208](https://github.com/ionic-team/ionic/issues/24208) [#24482](https://github.com/ionic-team/ionic/issues/24482)
* **input:** min/max compatibility with react-hook-form ([#24657](https://github.com/ionic-team/ionic/issues/24657)) ([1f91883](https://github.com/ionic-team/ionic/commit/1f918835f437a59f7a70fc59d9305647aa9c298d)), closes [#24489](https://github.com/ionic-team/ionic/issues/24489)


### Performance Improvements

* **various:** don't use lazy-loaded icon names in components ([#24671](https://github.com/ionic-team/ionic/issues/24671)) ([484de50](https://github.com/ionic-team/ionic/commit/484de5074de212dffb4bf4f73bade7acec103fe8))





## [6.0.4](https://github.com/ionic-team/ionic/compare/v6.0.3...v6.0.4) (2022-01-26)


### Bug Fixes

* **accordion:** items inside of the content now correct display borders ([#24618](https://github.com/ionic-team/ionic/issues/24618)) ([d3311df](https://github.com/ionic-team/ionic/commit/d3311df96765948d0a395e4ba99fb9117b44adcb)), closes [#24613](https://github.com/ionic-team/ionic/issues/24613)
* **col:** col no longer errors when running in non-browser environment ([#24603](https://github.com/ionic-team/ionic/issues/24603)) ([af0135c](https://github.com/ionic-team/ionic/commit/af0135ce7dbe737b2df46094fd3dc8a41bdb60ae)), closes [#24446](https://github.com/ionic-team/ionic/issues/24446)
* **datetime:** datetime locale with h23 will respect max time range ([#24610](https://github.com/ionic-team/ionic/issues/24610)) ([5925e76](https://github.com/ionic-team/ionic/commit/5925e7608ef04f8877e4dd8a80b2c8bdc1cfd4bd)), closes [#24588](https://github.com/ionic-team/ionic/issues/24588)
* **datetime:** timepicker popover will position relative to click target ([#24616](https://github.com/ionic-team/ionic/issues/24616)) ([378c632](https://github.com/ionic-team/ionic/commit/378c63264366964e6ea11e1a2ff8791a40f182d4)), closes [#24531](https://github.com/ionic-team/ionic/issues/24531) [#24415](https://github.com/ionic-team/ionic/issues/24415)
* **input:** ion-input accepts any string value ([#24606](https://github.com/ionic-team/ionic/issues/24606)) ([43c5977](https://github.com/ionic-team/ionic/commit/43c5977d48cb12331c1d3107eb73f29b92c5e049)), closes [#19884](https://github.com/ionic-team/ionic/issues/19884)
* **item:** label text aligns with input text ([#24620](https://github.com/ionic-team/ionic/issues/24620)) ([94d033c](https://github.com/ionic-team/ionic/commit/94d033c4216ae9978aed6346c1c0ea2aec4d375b)), closes [#24404](https://github.com/ionic-team/ionic/issues/24404)
* **item:** match material design character counter ([#24335](https://github.com/ionic-team/ionic/issues/24335)) ([54db1a1](https://github.com/ionic-team/ionic/commit/54db1a1e7c71c78e843370848fc768582768333e)), closes [#24334](https://github.com/ionic-team/ionic/issues/24334)
* **menu:** focus trapping with menu and overlays no longer results in errors ([#24611](https://github.com/ionic-team/ionic/issues/24611)) ([632dafc](https://github.com/ionic-team/ionic/commit/632dafcd57de5086deebdc7d586b01710aa1a3ce)), closes [#24361](https://github.com/ionic-team/ionic/issues/24361) [#24481](https://github.com/ionic-team/ionic/issues/24481)
* **modal:** native keyboard will dismiss when bottom sheet is dragged ([#24642](https://github.com/ionic-team/ionic/issues/24642)) ([525f01f](https://github.com/ionic-team/ionic/commit/525f01f086ebf95ab62af0162b876a25f50a3d4b)), closes [#23878](https://github.com/ionic-team/ionic/issues/23878)
* **range:** setting dir on ion-range to enable rtl mode now supported ([#24597](https://github.com/ionic-team/ionic/issues/24597)) ([5dba4e5](https://github.com/ionic-team/ionic/commit/5dba4e5ce0a07f69a08f2b427e8010b311910f88)), closes [#20201](https://github.com/ionic-team/ionic/issues/20201)
* **searchbar:** setting dir on ion-searchbar to enable rtl mode now supported ([#24602](https://github.com/ionic-team/ionic/issues/24602)) ([35e5235](https://github.com/ionic-team/ionic/commit/35e523564561c0f3323efa761c4654016b97ef69))
* **segment:** setting dir on ion-segment to enable rtl mode now supported ([#24601](https://github.com/ionic-team/ionic/issues/24601)) ([2940e73](https://github.com/ionic-team/ionic/commit/2940e73a4504247eecb0de6c433104f529530850)), closes [#23978](https://github.com/ionic-team/ionic/issues/23978)
* **spinner:** ensure transform doesn't overwrite circular animation ([#24643](https://github.com/ionic-team/ionic/issues/24643)) ([88ce010](https://github.com/ionic-team/ionic/commit/88ce010418eaca38786b51720c696860b417ab6d))
* **toast:** allow input focus while toast is visible ([#24572](https://github.com/ionic-team/ionic/issues/24572)) ([29f1140](https://github.com/ionic-team/ionic/commit/29f1140384ae7e1402b09c3760e168cf79833619)), closes [#24571](https://github.com/ionic-team/ionic/issues/24571)
* **toggle:** setting dir on ion-toggle to enable rtl mode now supported ([#24600](https://github.com/ionic-team/ionic/issues/24600)) ([353dbc0](https://github.com/ionic-team/ionic/commit/353dbc0537ef3b46b9ba13a365ebc5da269de4c7))





## [6.0.3](https://github.com/ionic-team/ionic/compare/v6.0.2...v6.0.3) (2022-01-19)


### Bug Fixes

* **datetime:** showing calendar grid no longer causes month to switch on ios 15 ([#24554](https://github.com/ionic-team/ionic/issues/24554)) ([3d20959](https://github.com/ionic-team/ionic/commit/3d2095922147ea3763e977412977edd9586fec5d)), closes [#24405](https://github.com/ionic-team/ionic/issues/24405)
* **item:** error slot visible in Safari ([#24579](https://github.com/ionic-team/ionic/issues/24579)) ([af01a8b](https://github.com/ionic-team/ionic/commit/af01a8b3073dce784cc042923d712b9492638d32)), closes [#24575](https://github.com/ionic-team/ionic/issues/24575)
* **menu:** remove main attribute that was supposed to removed in v5 ([#24565](https://github.com/ionic-team/ionic/issues/24565)) ([7704ac3](https://github.com/ionic-team/ionic/commit/7704ac3a3710396248590daecb945b76825a0539)), closes [#24563](https://github.com/ionic-team/ionic/issues/24563)
* **modal:** life cycle events for controller modals ([#24508](https://github.com/ionic-team/ionic/issues/24508)) ([9a15753](https://github.com/ionic-team/ionic/commit/9a15753fd95e32155abdeb490ec57cb72385ad1a)), closes [#24460](https://github.com/ionic-team/ionic/issues/24460)
* **overlays:** getTop now returns the top-most presented overlay ([#24547](https://github.com/ionic-team/ionic/issues/24547)) ([f5b4382](https://github.com/ionic-team/ionic/commit/f5b4382fd5728365e4badf39bc1dd0c149b45c2c)), closes [#19111](https://github.com/ionic-team/ionic/issues/19111)





## [6.0.2](https://github.com/ionic-team/ionic/compare/v6.0.1...v6.0.2) (2022-01-11)


### Bug Fixes

* **breadcrumb:** support routerLink on breadcrumb ([#24509](https://github.com/ionic-team/ionic/issues/24509)) ([5bb1414](https://github.com/ionic-team/ionic/commit/5bb1414f7fa04ea07954cb3f68883ee2f162586a)), closes [#24493](https://github.com/ionic-team/ionic/issues/24493)
* **css:** inline css source in source maps ([#24514](https://github.com/ionic-team/ionic/issues/24514)) ([987d46c](https://github.com/ionic-team/ionic/commit/987d46cfa6e48a932330f04f2e8eb7054b11baf8)), closes [#24441](https://github.com/ionic-team/ionic/issues/24441)
* **datetime:** add top padding to MD calendar month grid ([#24522](https://github.com/ionic-team/ionic/issues/24522)) ([bd82b5d](https://github.com/ionic-team/ionic/commit/bd82b5dc1d06ba22a5410858802d57735fdcf450)), closes [#24408](https://github.com/ionic-team/ionic/issues/24408)
* **datetime:** RTL will no longer infinitely scroll ([#24475](https://github.com/ionic-team/ionic/issues/24475)) ([8f00008](https://github.com/ionic-team/ionic/commit/8f000089c2986f292147c7f501f23c8c7d1df457)), closes [#24472](https://github.com/ionic-team/ionic/issues/24472)
* **datetime:** time picker format with hourCycle h23 ([#24476](https://github.com/ionic-team/ionic/issues/24476)) ([a3724e6](https://github.com/ionic-team/ionic/commit/a3724e6a5662c5bc1b724d80540530472827506e)), closes [#24474](https://github.com/ionic-team/ionic/issues/24474)
* **datetime:** update active day styling when day is selected ([#24454](https://github.com/ionic-team/ionic/issues/24454)) ([4304391](https://github.com/ionic-team/ionic/commit/430439191dba824c11290d7f8622fea10ced6c40)), closes [#24414](https://github.com/ionic-team/ionic/issues/24414) [#24451](https://github.com/ionic-team/ionic/issues/24451)
* **datetime:** wheel picker shows correct column order in rtl ([#24546](https://github.com/ionic-team/ionic/issues/24546)) ([c90ce31](https://github.com/ionic-team/ionic/commit/c90ce311a86ccb7c06b1cde91a4659f6682df04d)), closes [#24378](https://github.com/ionic-team/ionic/issues/24378)
* **overlays:** define custom element children ([#24439](https://github.com/ionic-team/ionic/issues/24439)) ([4715b83](https://github.com/ionic-team/ionic/commit/4715b83abb30ec5930710d16e5bfe8fc88a940ce)), closes [#24393](https://github.com/ionic-team/ionic/issues/24393)
* **popover:** allow arrow configuration with controller approach ([#24512](https://github.com/ionic-team/ionic/issues/24512)) ([b39003a](https://github.com/ionic-team/ionic/commit/b39003a4c67cd7e01d09be012c9e12d99ca1730a)), closes [#24487](https://github.com/ionic-team/ionic/issues/24487)
* **radio:** fix radio not showing checked state when not in a group ([#24423](https://github.com/ionic-team/ionic/issues/24423)) ([94a781c](https://github.com/ionic-team/ionic/commit/94a781cb6a3d92c5e6cab1a7603bfe25826a753c))
* **react,vue:** backdrop for inline modal/popover overlay ([#24453](https://github.com/ionic-team/ionic/issues/24453)) ([77f8412](https://github.com/ionic-team/ionic/commit/77f8412b746222793cd9d17f12f50d512ab5e886)), closes [#24449](https://github.com/ionic-team/ionic/issues/24449)
* **react:** building app for production now works correctly with vite ([#24515](https://github.com/ionic-team/ionic/issues/24515)) ([32fad3d](https://github.com/ionic-team/ionic/commit/32fad3d02cb6b012a772de03eafe3e3a6b1300e0)), closes [#24229](https://github.com/ionic-team/ionic/issues/24229)
* **refresher:** import icons to avoid errors in react and vue ([#24525](https://github.com/ionic-team/ionic/issues/24525)) ([388622f](https://github.com/ionic-team/ionic/commit/388622f9734b7b832bca3ede99820a7124faa618)), closes [#24480](https://github.com/ionic-team/ionic/issues/24480)
