# Fable Cosmos assets

Optional files for Fable Cosmos. Nothing here is needed to run the app: the app downloads the mood pack only when the GM presses "Download mood pack", and it checks every file against a size and SHA-256 that ship inside the app before it installs anything.

## mood-pack-1: the mood pack

27 music loops for scene moods (tavern, travel, exploration, tension, battle, boss battle, victory, sorrow, mystery, town, wilderness, night, calm), each in two formats: Ogg Opus (`.opus`, 80 kbps) and AAC-LC (`.m4a`, 96 kbps) for devices that cannot play Opus. Files are served from the tag `mood-pack-1`, folder `mood-pack-1/`:

    https://raw.githubusercontent.com/Some-Assembly-Imagined/fable-cosmos-assets/mood-pack-1/mood-pack-1/<file>

The tag is pinned: the app never follows a branch. To replace a file, publish a new tag and change `PACK_TAG` in `devtools/mood_pack_bk18.py` of the app (then rebuild the manifest with `devtools.mood_pack_bk18 build --only pack`, or run `set-base-url`).

## Licence and credits

All music is by Kevin MacLeod (incompetech.com), licensed under Creative Commons: By Attribution 4.0 License (http://creativecommons.org/licenses/by/4.0/). The files are transcoded from his MP3s (trimmed, levelled and re-encoded); that is a change under the licence. Credit lines (also in `CREDITS.txt`):

- Fiddles McGinty Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Lord of the Land Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Myst on the Moor Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Gloom Horizon Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Movement Proposition Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Devastation and Revenge Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Heroic Age Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Bittersweet Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Mystery Bazaar Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Village Consort Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Errigal Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Midnight Tale Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- The Britons Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Halls of the Undead Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Spider Eyes Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Stoneworld Battle Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Final Battle of the Dark Wizards Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- At Launch Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Long Road Ahead Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Lamentation Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Magic Forest Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Skye Cuillin Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Night Vigil Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Thatched Villagers Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Dreamer Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Enchanted Journey Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/
- Comfortable Mystery Kevin MacLeod (incompetech.com) Licensed under Creative Commons: By Attribution 4.0 License http://creativecommons.org/licenses/by/4.0/

## Files and SHA-256

Check with `sha256sum -c SHA256SUMS` from the root of this repository.

| File | Bytes | SHA-256 |
| --- | ---: | --- |
| `fiddles_mcginty.opus` | 2450186 | `103f694178bd0a88fc4a6e7e2df0eb592911d74634a2cb7a274edb1c5c5264fc` |
| `fiddles_mcginty.m4a` | 2510825 | `b1081fb4a0968d0e764198337749d4c1fc2a537c354846f0d589c506fceb1d87` |
| `lord_of_the_land.opus` | 2028732 | `bc931273bf896820327bb86c0aa116a87362e92cfdd9d6b5a60248bf049788c2` |
| `lord_of_the_land.m4a` | 2258072 | `fb1d54f631ff8e38c09bab78fde85c6c9235d77c02927b2aa302f341b416ddc4` |
| `myst_on_the_moor.opus` | 2233640 | `818caeb2f1337a7f9aa78e9ed6084790872e127600024d127b12c65af6835d42` |
| `myst_on_the_moor.m4a` | 2760892 | `74e8345779cfc77342b6c87a89c3e70ecaf53633d8cc7b31cb1f2b102284b7cd` |
| `gloom_horizon.opus` | 1357032 | `67cdbf72ef2822e8a4b95ddbc9d7a45af5a5aec1551ca378ddf2ecc9dc14be89` |
| `gloom_horizon.m4a` | 1518414 | `be4af4076ca52fb81e951fec1a2a19c0032417412aa2d41ce1dd9defa396c91f` |
| `movement_proposition.opus` | 1508836 | `1361d51610b92ec2bbadda7dfd404d04701ddc2826a56d082340b1443e99ec37` |
| `movement_proposition.m4a` | 1699624 | `caa9473dfbbb7bc6582830887f0c9e3483b851f4e45217817f8810b01eb10831` |
| `devastation_and_revenge.opus` | 1930890 | `152b7030a21885e90ab7d35499b1d46d487f4b58d24b961c766a3396e158596c` |
| `devastation_and_revenge.m4a` | 2230429 | `00c3fda9e6da9b29848292be2c0c22a09511fa1627e37fd1c576d45cc44196d8` |
| `heroic_age.opus` | 951212 | `001cb8ec88e229051e613123b5b570a1da9440192b569b24fa2cb14b377ebaa0` |
| `heroic_age.m4a` | 1106904 | `3662ecaf54aaafb55b6b7ceb29133fd95fdbcdd03bc8d2a8e59a50aadd0d5334` |
| `bittersweet.opus` | 2284037 | `64427361cf0f3c6d6b64617ef5afc2decc8e85d09770ea7e5c1cc6dbad559f45` |
| `bittersweet.m4a` | 2449005 | `33156903ca979c5e6b4ef620781456f5fdd8f785c83dae74e8cd85d63c1772a8` |
| `mystery_bazaar.opus` | 1739903 | `e4cb6d6dc7c15d0e832ca1f8d2c5b5f0fbb5fce860cd7ebf0cbff81ed1726db4` |
| `mystery_bazaar.m4a` | 1900185 | `ec2b6292f17b3d47b022c1895269967a3d7c064e2d6e7e433819a015bfeef08e` |
| `village_consort.opus` | 2448554 | `4fe158daa28297b617685a75455494b2da302f1629481a65739731bddb472046` |
| `village_consort.m4a` | 2635326 | `2575474cdf4381ee11173f1558c9ca69e5611d6cbe283d16c7e20ee7c6634620` |
| `errigal.opus` | 1537416 | `d42b920a43a82e118b750d7806fe89caf38899e60502da70fefdebaf51dad3d5` |
| `errigal.m4a` | 1591451 | `5feafe1c3419f449b0103cac039b355a8332096a295158b6655414c2525d50f1` |
| `midnight_tale.opus` | 1898997 | `24057b4b2fb73f5e34139429b7d38f0b2b1fd9eef993e1b62b577520c447a9ae` |
| `midnight_tale.m4a` | 1894980 | `f54da2ed0ee1226a031cfa638821e3a8161b5c1581e090094c524e63669fe93f` |
| `the_britons.opus` | 3501902 | `a6d7f68ec520714b6c97567c3252be50d67ef9dfc0006f033c614f54c80d8e5b` |
| `the_britons.m4a` | 3754615 | `3f3cbb05df7e8967f96bf4d12919b3b5bc56a904a0011f87aa8438f2b70898d7` |
| `halls_of_the_undead.opus` | 3073784 | `cfeca37329636ea0f813315b2b0cc379e1281029afda29ea023d94dbe5059aa4` |
| `halls_of_the_undead.m4a` | 3546389 | `65fb9b971d8a0440ce89291767b25f675e33556b15db3cb504107162d2ff7dc4` |
| `spider_eyes.opus` | 2322076 | `ef261a340b60720c736f70eca2b822b1001ce8fe19aff6565a956e613711a666` |
| `spider_eyes.m4a` | 2541215 | `9af3d28492a22180e9cd09398a1645e1499fecac51b2807450b5ed22a9bb4c0f` |
| `stoneworld_battle.opus` | 2340673 | `ec6f66d965fb2fc2a402c99c4cf11ca732c8d8c236044a1f95b33586ebb356a8` |
| `stoneworld_battle.m4a` | 2847868 | `d8f2fafd29e7934f64dcdd5201bea0120252cb60fb80d19a42012e41b73b7b97` |
| `final_battle_of_the_dark_wizards.opus` | 2890070 | `fe0503407c0f1226b8f82fdead546208376794edf1ab196581ea38d1b70171dd` |
| `final_battle_of_the_dark_wizards.m4a` | 3307813 | `ab99a550a03cf37dffe332535309d4af20c008fad6a6092eaff8a02cdf707353` |
| `at_launch.opus` | 2077319 | `628314ae9f05bd8c8249096b7ff9235d8df5a63d73feca8efbb7bc270787312e` |
| `at_launch.m4a` | 2233030 | `9dc5e2059a887fd50bf8de21e2bc043d4258baf873a467f9fb8d69b3c3822f91` |
| `long_road_ahead.opus` | 1592292 | `51a63488845eb96c3002b2bd71e8f832aa73bd63df822cc5cd7722687d89816b` |
| `long_road_ahead.m4a` | 1738055 | `7ffc8cefdf78222a1e010c4679437cfef77bbddcfcea048855b0741239f24d50` |
| `lamentation.opus` | 2343179 | `0b5a79a5f627d0f561328f1e2e7bd55271cebd3908ff0ba2d699abcfcce36fb2` |
| `lamentation.m4a` | 2337516 | `ea3e84891790b6e06c4c2062b2889174be6cde0cb04fad1606b5d580fa09f46d` |
| `magic_forest.opus` | 2985896 | `bee30c75ceb754a494b92341c331c1f654221b7ddb48973bd4f481a62daf6f27` |
| `magic_forest.m4a` | 3151044 | `d8eff0841aa32fde24c115bbe55d1be009fb9f3f05faa493be346cea2bb32043` |
| `skye_cuillin.opus` | 2211049 | `3978621b7f8b5d910e16447b7b641b794ec4ab3d65cbf3aabb6d51134bc2789a` |
| `skye_cuillin.m4a` | 2345955 | `4ea1843d247813dfcaee75c8b43ec4f189239c6dd13c2ba091a1dd6003cc1895` |
| `night_vigil.opus` | 3088394 | `7680cd76840585be369ee03e87500f371ccdae540292d0c1a1cbb7636a70f070` |
| `night_vigil.m4a` | 3420462 | `cbfb98247a992650e0db67782509bfa0d578fd79b26c6bb7f2e094f338b2f643` |
| `thatched_villagers.opus` | 2956053 | `a228d8fb49ad844a8e4a4a3e8ca63327270c9e5a5d916494b875655f6388a7ce` |
| `thatched_villagers.m4a` | 3009264 | `f55b82e15be648a3832252d44f80e80db70b1a6d02c47c2602c8d89ae1730012` |
| `dreamer.opus` | 2168322 | `dd2576dcc072cb8516164e25d911d41e3cc80d9c670e569fdf67f8b562c33ae2` |
| `dreamer.m4a` | 2476039 | `0962a3234d8f4481101e6a21d48f284e3fe0d99845f049d76d1f34cff61eb169` |
| `enchanted_journey.opus` | 3209365 | `158e040f12ba1ae9ddf9375fb724f6cf9619e359bade32df5f02005883308edc` |
| `enchanted_journey.m4a` | 3256767 | `b744708dc15a73929993b835bacb40d51257f90cff11d5243a1b277f806e8913` |
| `comfortable_mystery.opus` | 2977352 | `40fb4f809ee2461bb624128f16b9a13977f95a80dfa8d8449874596fd993b43e` |
| `comfortable_mystery.m4a` | 2879647 | `a7a2927465a7c80af214ff0af6ff4ac174e0833bec5fdfe8b0d755b1702ecfc3` |
