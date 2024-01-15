# Tested with the following networks

Not all of these example URLs are valid as of 15-01-2024, but all of them can be scraped through the API

The tables under each network show the network and studio name as they are returned from the API, sort of. While they do use these terms explicitly the scene objects returned from the API can roughly be mapped into the studio/network relationships we use on StashDB.

## Babes

- 7 studios listed on StashDB, 5 scrapable from API

  Missing:

  - Babes Live (which only has one scene, no fingerprints)
  - Black is Better (folded into Babes Unleashed)

- No special handling required

| Network | Studio           | URL                                                                   |
| ------: | :--------------- | --------------------------------------------------------------------- |
|         | Babes            | https://www.babes.com/scene/4474211/forbidden-fruit                   |
|   Babes | Babes Unleashed  | https://www.babes.com/scene/3108261/fill-her-up                       |
|   Babes | Elegant Anal     | https://www.babes.com/scene/4404812/racy-redhead                      |
|   Babes | Office Obsession | https://www.babes.com/scene/3101011/pussy-power                       |
|   Babes | Step Mom Lessons | https://www.babes.com/scene/3098571/like-stepmother-like-stepdaughter |

## Bang Bros

- 70 studios listed on StashDB, 54 scrapable from API

  Missing:

  - BangBros Worldwide
  - Big Ass Adventure
  - BrandiBelle.com
  - Busty Adventures
  - CFNM Show
  - College Rules
  - Dancing Bear
  - Fart Hammer
  - Filthy Family
  - Mia Khalifa
  - Mom's Anal Adventure
  - My Dirty Vault
  - MyGF
  - Public Invasion
  - Sex Busters
  - XXX Pawn

- All scene URLs use `video` instead of `scene` between domain and scene ID but performer URLs are fine
- Should translate old-style URLs to new-style URLs by checking for redirects:
  - https://bangbros.com/video116453/eva-lovia
  - https://bangbros.com/video/9027421/eva-lovia
- Name adjustments:
  - AvaSpice -> Ava Spice
  - MomIsHorny -> Mom Is Horny

|  Network | Studio                | URL                                                                                   |
| -------: | :-------------------- | ------------------------------------------------------------------------------------- |
| BangBros | Ass Parade            | https://bangbros.com/video/9719651/big-poolside-booty                                 |
| BangBros | AvaSpice              | https://bangbros.com/video/9087751/cock-a-smile                                       |
| BangBros | Back Room Facials     | https://bangbros.com/video/8968901/sexy-latinas-good-dicking                          |
| BangBros | Backroom MILF         | https://bangbros.com/video/9092331/a-taste-of-vanilla                                 |
| BangBros | Ball Honeys           | https://bangbros.com/video/9115601/erika-vution-rocked-my-cock                        |
| BangBros | Bang Bus              | https://bangbros.com/video/9420961/zodiac-fuck                                        |
| BangBros | Bang Casting          | https://bangbros.com/video/8985221/sexy-selena                                        |
| BangBros | Bang POV              | https://bangbros.com/video/9214171/fuck-me-in-the-ass-please                          |
| BangBros | Bang Tryouts          | https://bangbros.com/video/9063991/sex-tape-5                                         |
| BangBros | BangBros 18           | https://bangbros.com/video/9580671/stepdad-gets-caught-in-action                      |
| BangBros | BangBros Angels       | https://bangbros.com/video/9027421/eva-lovia                                          |
| BangBros | Bangbros Clips        | https://bangbros.com/video/9428961/new-shower-new-pussy                               |
| BangBros | BangBros Remastered   | https://bangbros.com/video/9010721/big-ass-big-tits-gianna-works-out-that-juicy-pussy |
| BangBros | BangBros Vault        | https://bangbros.com/video/8863501/summer-getting-nasty                               |
| BangBros | Big Mouthfuls         | https://bangbros.com/video/9155231/asian-nympho-loves-to-get-fuck                     |
| BangBros | Big Tit Cream Pie     | https://bangbros.com/video/9297791/nikka-realy-needs-the-cream-                       |
| BangBros | Big Tits, Round Asses | https://bangbros.com/video/9429171/puerto-rican-pussy-loves-oil                       |
| BangBros | BlowJob Fridays       | https://bangbros.com/video/8906201/arietta-sucks-her-stepbrothers-dick                |
| BangBros | Blowjob Ninjas        | https://bangbros.com/video/9120031/jenaveve-gets-down-and-dirtty                      |
| BangBros | Boob Squad            | https://bangbros.com/video/9149391/black-gold                                         |
| BangBros | Brown Bunnies         | https://bangbros.com/video/9497411/stretching-out-august                              |
| BangBros | Can He Score          | https://bangbros.com/video/9032981/rachel-starr-and-the-hoagie-hero                   |
| BangBros | Casting               | https://bangbros.com/video/9124101/she-does-cook-anal                                 |
| BangBros | Chongas               | https://bangbros.com/video/9041131/doesnt-get-better-then-jynx-maze                   |
| BangBros | Colombia Fuck Fest    | https://bangbros.com/video/8968571/colombian-newbie-gets-slammed                      |
| BangBros | Dirty World Tour      | https://bangbros.com/video/9097911/pin-up-doll                                        |
| BangBros | Dorm Invasion         | https://bangbros.com/video/9034361/pornstars-raid-the-dorm-full-of-college-boys       |
| BangBros | Facial Fest           | https://bangbros.com/video/8992381/slutty-amateur-gets-a-facial                       |
| BangBros | Fuck Team Five        | https://bangbros.com/video/9027201/fuckteam-beach-time                                |
| BangBros | Glory Hole Loads      | https://bangbros.com/video/8971801/thick-latina-deep-throats-in-the-gloryhole         |
| BangBros | Latina Rampage        | https://bangbros.com/video/9032011/puerto-rican-flavor-weve-evans                     |
| BangBros | Living With Anna      | https://bangbros.com/video/9083961/one-with-nature                                    |
| BangBros | MILF Lessons          | https://bangbros.com/video/9129461/anita-blues-anal-salute                            |
| BangBros | Milf Soup             | https://bangbros.com/video/9044481/milf-takes-a-pounding                              |
| BangBros | Magical Feet          | https://bangbros.com/video/9059841/feet-that-will-make-you-squirt                     |
| BangBros | MomIsHorny            | https://bangbros.com/video/9401771/step-mom-gives-blu-balls                           |
| BangBros | Monsters of Cock      | https://bangbros.com/video/8852571/tiny-pussy-gets-fucked                             |
| BangBros | Mr CamelToe           | https://bangbros.com/video/9139961/alexis-malone                                      |
| BangBros | Mr. Anal              | https://bangbros.com/video/8986901/cristi-ann-gets-an-anal-pounding                   |
| BangBros | My Dirty Maid         | https://bangbros.com/video/8838251/anal-gymnastics                                    |
| BangBros | My Life In Brazil     | https://bangbros.com/video/9088421/suzanny-the-dog-rescuer                            |
| BangBros | Newbie Black          | https://bangbros.com/video/9100111/pussy-on-wheels                                    |
| BangBros | Pawg                  | https://bangbros.com/video/8996361/keisha-grey-fucked-by-black-cock                   |
| BangBros | Party of 3            | https://bangbros.com/video/9035831/amateur-lesbians-fuck                              |
| BangBros | Penny Show            | https://bangbros.com/video/9119001/olivia-olovely-and-from-one-million-to-billion     |
| BangBros | Porn Star Spa         | https://bangbros.com/video/9041761/sexy-brunette-massaged-and-fucked-hardcore         |
| BangBros | Power Munch           | https://bangbros.com/video/9097431/freaky-slumber-munch                               |
| BangBros | Public Bang           | https://bangbros.com/video/8935091/selva-gets-public-anal                             |
| BangBros | Slutty White Girls    | https://bangbros.com/video/9026281/amateur-blonde-slut-gang-banged                    |
| BangBros | Stepmom Videos        | https://bangbros.com/video/9007731/my-stepmom-teaches-me-how-to-fuck-my-bf            |
| BangBros | Street Ranger         | https://bangbros.com/video/9133631/tour-d-fuck                                        |
| BangBros | Tugjobs               | https://bangbros.com/video/9015181/hot-latina-pornstar-jerks-off-a-dick               |
| BangBros | Virtual Porn          | https://virtualporn.com/video/9359281/too-horny-to-fail                               |
| BangBros | Working Latinas       | https://bangbros.com/video/9123731/latin-fever                                        |

## Brazzers

- 49 studios listed on StashDB, 28 scrapable from API

  Missing:

  - Brazzers en Español
  - Butts & Blacks
  - Charles Dera
  - Desiree Dulce
  - Emily Willis
  - Euro Babes
  - Jizz On My Jugs
  - Jordi
  - Kendra Lust
  - Lacy Lennon
  - Lil D
  - Luna Star
  - Pornstars Punishment
  - Rachel Starr
  - Racks & Blacks
  - SexPro Adventures
  - Sofia Rose
  - Sophie Dee
  - Teens Like It Black
  - VRT
  - Xander Corvus

- All scene URLs use `video` instead of `scene` between domain and scene ID
- All performer URLs use `pornstar` instead of `model` between domain and scene ID
- If scene has tag "Brazzers Live" then studio should be "Brazzers Live"

- Name adjustments:
  - JugFuckers -> Jug Fuckers
  - Shes Gonna Squirt -> She's Gonna Squirt

|  Network | Studio                | URL                                                                       |
| -------: | :-------------------- | ------------------------------------------------------------------------- |
| Brazzers | Asses in Public       | https://www.brazzers.com/video/3788751/from-russia-with-lust              |
| Brazzers | Baby Got Boobs        | https://www.brazzers.com/video/4423671/chores-suck-and-so-do-i            |
| Brazzers | Big Butts Like It Big | https://www.brazzers.com/video/4445271/big-ass-anal-for-a-heavy-load      |
| Brazzers | Big Tits at School    | https://www.brazzers.com/video/3831901/principal-photography              |
| Brazzers | Big Tits at Work      | https://www.brazzers.com/video/4658471/virtual-fuckfest                   |
| Brazzers | Big Tits In Sports    | https://www.brazzers.com/video/3847871/kortney-s-slutty-circuit-training  |
| Brazzers | Big Tits In Uniform   | https://www.brazzers.com/video/3851201/dinners-on-me                      |
| Brazzers | Big Wet Butts         | https://www.brazzers.com/video/4404989/britney-s-jeans                    |
| Brazzers | BrazzersExxtra        | https://www.brazzers.com/video/9311401/medical-ass-istance-required       |
| Brazzers | Brazzers Vault        | https://www.brazzers.com/video/3873921/i-gotta-have-my-moms-boyfriend     |
| Brazzers | Busty & Real          | https://www.brazzers.com/video/3793201/big-natural-round-boobs            |
| Brazzers | Bustyz                | https://www.brazzers.com/video/3882961/pretty-face-with-big-tits          |
| Brazzers | CFNM                  | https://www.brazzers.com/video/3899601/you-want-us-to-clean-your-dick     |
| Brazzers | Day With A Pornstar   | https://www.brazzers.com/video/4415556/siouxsie-q-s-anal-kitchen-cleaning |
| Brazzers | Dirty Masseur         | https://www.brazzers.com/video/4393739/im-sensitive                       |
| Brazzers | Doctor Adventures     | https://www.brazzers.com/video/3912371/psycho-anal-ysis                   |
| Brazzers | Hot And Mean          | https://www.brazzers.com/video/4505171/anal-workout-with-bestie           |
| Brazzers | Hot Chicks Big Asses  | https://www.brazzers.com/video/3924151/everything-is-bigger-in-texas      |
| Brazzers | JugFuckers            | https://www.brazzers.com/video/3936411/big-natural-juggs                  |
| Brazzers | Milfs Like It Big     | https://www.brazzers.com/video/4395708/i-m-over-it                        |
| Brazzers | Mommy Got Boobs       | https://www.brazzers.com/video/3940591/ninas-chapel-of-lust-part-1        |
| Brazzers | Moms in control       | https://www.brazzers.com/video/3963591/you-need-mums-approval             |
| Brazzers | Pornstars Like it Big | https://www.brazzers.com/video/4445561/the-garden-of-demi-s-delights      |
| Brazzers | Real Wife Stories     | https://www.brazzers.com/video/4410374/sex-with-the-therapist             |
| Brazzers | Shes Gonna Squirt     | https://www.brazzers.com/video/4015911/wheres-my-valentine                |
| Brazzers | Teens Like It Big     | https://www.brazzers.com/video/4327711/mc2-ass                            |
| Brazzers | ZZ Series             | https://www.brazzers.com/video/3789801/the-exxxceptions-episode-1         |

## Bromo

- Single studio but has some substudio elements? Will flatten to just "Bromo" with no parent

| Network | Studio            | URL                                                      |
| ------: | :---------------- | -------------------------------------------------------- |
|   Bromo | Bromo US          | https://www.bromo.com/scene/4412747/tattoo-fuck          |
|   Bromo | Bromo BlackMaleMe | https://www.bromo.com/scene/3227341/breaking-him-scene-1 |

## BigStr

- 3 studios listed on StashDB, all 3 scrapable from API
- Seems to be actively restructuring: during development of this scraper several scenes vanished from public site
- All studios have their own domain

| Network | Studio       | URL                                                        |
| ------: | :----------- | ---------------------------------------------------------- |
|  BigStr | Debt Dandy   | https://www.debtdandy.com/scene/4300191/debt-dandy-160     |
|  BigStr | Dirty Scout  | https://www.dirtyscout.com/scene/4508331/dirty-scout-283   |
|  BigStr | Czech Hunter | https://www.czechhunter.com/scene/9575711/czech-hunter-718 |

## Deviante

- 5 studios listed on StashDB, all 5 scrapable from API
- All scenes use `video` instead of `scene` between domain and scene ID
- All studios have their own domain
- Name adjustments:
  - es -> Erotic Spice
  - fmf -> Forgive Me Father
  - lha -> Love Her Ass
  - pdt -> Pretty Dirty Teens
  - sw -> Sex Working

|  Network | Studio | URL                                                                             |
| -------: | :----- | ------------------------------------------------------------------------------- |
| Deviante | es     | https://www.eroticspice.com/video/4422220/busty-japanese-milf-fucks-shy-guy     |
| Deviante | fmf    | https://www.forgivemefather.com/video/4493281/father-s-righteous-ritual         |
| Deviante | lha    | https://www.loveherass.com/video/4424461/playful-roomie-loves-anal              |
| Deviante | pdt    | https://www.prettydirtyteens.com/video/7939981/creampie-for-sneaky-college-teen |
| Deviante | sw     | https://www.deviante.com/video/4647241/cash-for-happy-ending-with-masseuse      |
| Deviante | sw     | https://www.sexworking.com/video/4474711/brazilian-escort-summoned-to-please    |

## Digital Playground

- 6 studios listed on StashDB, all 6 scrapable from API
- Name adjustments:
  - dpw -> DP World
  - Dpstar Episodes -> Episodes
  - Dpstar Sex Challenges -> Sex Challenges

|            Network | Studio                | URL                                                                                |
| -----------------: | :-------------------- | ---------------------------------------------------------------------------------- |
|                    | Digital Playground    | https://www.digitalplayground.com/scene/4410802/sleepless-nights-scene-1           |
| Digital Playground | dpw                   | https://www.digitalplayground.com/scene/8353721/tourist-trap-episode-4             |
| Digital Playground | dpw                   | https://www.digitalplaygroundnetwork.com/scene/8353721/tourist-trap-episode-4      |
| Digital Playground | Blockbuster           | https://www.digitalplayground.com/scene/4132651/body-heat-scene-1                  |
| Digital Playground | DP Parody             | https://www.digitalplayground.com/scene/4176641/ass-effect-a-xxx-parody            |
| Digital Playground | Dpstar Episodes       | https://www.digitalplayground.com/scene/4416872/auditions-part-1                   |
| Digital Playground | Episodes              | https://www.digitalplayground.com/scene/4187051/bad-babysitter-episode-1           |
| Digital Playground | Dpstar Sex Challenges | https://www.digitalplayground.com/scene/4416848/luna-star-in-dp-star-sex-challenge |
| Digital Playground | Flixxx                | https://www.digitalplayground.com/scene/4489851/bouncer-bitch                      |
| Digital Playground | Rawcut                | https://www.digitalplayground.com/scene/4186511/ghost-of-blowjobs-past             |

## Erito

- No special handling required

| Network | Studio | URL                                                         |
| ------: | :----- | ----------------------------------------------------------- |
|         | Erito  | https://www.erito.com/scene/4653021/nonstop-sticky-creampie |

## FakeHub

- 11 studios listed on StashDB, all 11 scrapable from API
- All performer profiles have `modelprofile` instead of `model` between domain and scene ID
- Some studios have their own domain

| Network | Studio              | URL                                                                             |
| ------: | :------------------ | ------------------------------------------------------------------------------- |
| FakeHub | Fake Agent          | https://www.fakehub.com/scene/4411255/punk-rocker-loves-rough-sex               |
| FakeHub | Fake Agent UK       | https://www.fakehub.com/scene/4083631/cum-splattered-face-for-petite-teen       |
| FakeHub | Fake Cop            | https://www.fakehub.com/scene/4087511/unregistered-driver-creampied-by-cop      |
| FakeHub | Fake Driving School | https://www.fakehub.com/scene/4474671/students-accidental-tik-tok-bag-challenge |
| FakeHub | Fake Hospital       | https://www.fakehub.com/scene/4084801/holiday-maker-strikes-a-sexual-deal       |
| FakeHub | Fake Hostel         | https://www.fakehostel.com/scene/9352861/sudden-threesome-for-new-lovers        |
| FakeHub | Fake Taxi           | https://www.faketaxi.com/scene/9642961/cute-brazilian-gives-xmas-tip            |
| FakeHub | Fakehub Originals   | https://www.fakehub.com/scene/9642841/free-use-mail-order-e-girl                |
| FakeHub | Female Agent        | https://www.fakehub.com/scene/4079471/sexy-lesbian-christmas-casting            |
| FakeHub | Female Fake Taxi    | https://www.fakehub.com/scene/4485911/curvy-driver-gets-a-hard-dicking          |
| FakeHub | Public Agent        | https://www.publicagent.com/scene/4498351/what-is-the-spanish-for-blowjob       |

## Gay Wire

- 18 studios listed on StashDB, 13 scrapable from API

  Missing:

  - Bigdaddy
  - Gay Patrol
  - Gay Pawn
  - Grab Ass
  - Project City Bus
  - Gay Selector (Doesn't seem to belong to Gay Wire? Available to members, redistribution deal perhaps)

- BangBros needs to be replaced with Gay Wire in all studio objects
- bangbros.com needs to be replaced with gaywire.com in all URLs
- Should translate old-style URLs to new-style URLs by checking for redirects:
  - https://gaywire.com/h1/video487/cock-sucking-galore
  - https://gaywire.com/scene/9322311/cock-sucking-galore
- Name adjustments:
  - Its Gonna Hurt -> It's Gonna Hurt
  - Poundhisass -> Pound His Ass

|  Network | Studio           | URL                                                                |
| -------: | :--------------- | ------------------------------------------------------------------ |
| BangBros | Bait Bus         | https://gaywire.com/scene/9315611/double-ginger                    |
| BangBros | Bareback Attack  | https://gaywire.com/scene/9321281/virgin-anal-sex-with-a-big-dick  |
| BangBros | Bareback Casting | https://gaywire.com/scene/9320721/georgio-fucks-like-an-animal     |
| BangBros | ExBF             | https://gaywire.com/scene/9322311/cock-sucking-galore              |
| BangBros | Haze Him         | https://gaywire.com/scene/9326111/slosh-balls                      |
| BangBros | Its Gonna Hurt   | https://gaywire.com/scene/9325601/shockingly-painful               |
| BangBros | Out In Public    | https://gaywire.com/scene/9329621/public-anal-sex-in-europe        |
| BangBros | Poundhisass      | https://gaywire.com/scene/8942881/aaron-trainer-trains-his-cock    |
| BangBros | Rub Him          | https://gaywire.com/scene/9335691/oil-massaged-anal-sex            |
| BangBros | Sausage Party    | https://gaywire.com/scene/9332131/crazy-in-the-club                |
| BangBros | Thug Hunter      | https://gaywire.com/scene/9332821/hunting-in-the-heart-of-darkness |
| BangBros | UngloryHole      | https://gaywire.com/scene/9336331/cock-surprise                    |
| BangBros | Urban Invasion   | https://gaywire.com/scene/9333241/two-hot-jocks                    |

## Hentai Pros

- No special handling required

| Network | Studio      | URL                                                                        |
| ------: | :---------- | -------------------------------------------------------------------------- |
|         | Hentai Pros | https://www.hentaipros.com/scene/8359071/girlfriend-stealing-app           |
|         | Hentai Pros | https://www.hentaiprosnetwork.com/scene/2686971/boin-babes-at-the-resort-2 |

## Men.com

- 10 studios listed on StashDB, all 10 scrapable from API
- Consolidated most studios URLs into men.com: old URLs should be supported, but only men.com should be output

  Exception: TwinkPop still has a separate domain

- All scene URLs use `sceneid` instead of `scene` between domain and scene ID

  Exception: TwinkPop uses `scene` or `video`: we'll stick with `scene` for consistency

- All performer URLs use `modelprofile` instead of `model` between domain and scene ID

  Exception: TwinkPop uses `pornstar`

- Name adjustments:
  - tp -> TwinkPop
  - Men -> Men.com

| Network | Studio              | URL                                                                    |
| ------: | :------------------ | ---------------------------------------------------------------------- |
|     Men | Big Dicks At School | https://www.bigdicksatschool.com/sceneid/4405350/more-spice-than-sugar |
|     Men | Drill My Hole       | https://www.men.com/sceneid/4481271/the-rookie-lifeguard               |
|     Men | Gods of Men         | https://www.godsofmen.com/scene/4392307/tied-to-you                    |
|     Men | Jizz Orgy           | https://www.jizzorgy.com/scene/3707561/the-calendar-shoot              |
|     Men | Men of UK           | https://www.menofuk.com/scene/3711691/men-in-crack                     |
|         | Men                 | https://www.men.com/sceneid/9736131/ex-con-hard-on                     |
|     Men | Str8 to Gay         | https://www.str8togay.com/scene/4357781/rodeo-romeo                    |
|     Men | The Gay Office      | https://www.thegayoffice.com/scene/3712041/unexpected-revenge          |
|     Men | Top to Bottom       | https://www.toptobottom.com/scene/3716161/the-cleaner                  |
|     Men | tp                  | https://www.twinkpop.com/video/9634991/sweet-twink-sweat               |

## Metro HD

- 5 studios listed on StashDB, all 5 scrapable from API
- All studios have their own domain
- metro.com needs to be replaced with metrohd.com as a fallback
- Name adjustments:
  Metro -> Metro HD

| Network | Studio           | URL                                                                                                             |
| ------: | :--------------- | --------------------------------------------------------------------------------------------------------------- |
|   Metro | Deviant Hardcore | https://www.devianthardcore.com/scene/4414757/sexy-domme-abigail-mac-uses-her-good-submissive-maddy-o-reilly    |
|   Metro | Family Hook Ups  | https://www.familyhookups.com/scene/9670731/aidra-fox-and-aubree-valentine                                      |
|   Metro | Girl Grind       | https://www.girlgrind.com/scene/4471381/latina-babe-daisy-marie-gets-d-pd-with-toys-by-hot-blonde-sammie-rhodes |
|   Metro | Kinky Spa        | https://www.kinkyspa.com/scene/9638571/nicole-doshi-gets-a-spa-day-for-her-anniversary                          |
|   Metro | She Will Cheat   | https://www.shewillcheat.com/scene/9670841/hot-blonde-lilly-bell-gets-fucked-by-her-marriage-counselor          |

## Mile High Media

- 16 studio listed on StashDB, 12 scrapable from API

  Missing:

  - Cherry Pop
  - Couples Seeking Teens (folded into Reality Junkies?)
  - Gilfed
  - Mile High Xtreme (movie studio, not in modern API)

- Appear to segregate their bi / gay / trans content across domains, but according to the API they're all MHM

  Have split them across 3 scrapers but could undergo consolidation or further splitting at a later date

- milehigh.com needs to be replaced with milehighmedia.com in all URLs
- milehigh.com can be replaced by studio domain

### Mile High Media (Straight)

- Name adjustments:
  - dlf -> Dilfed
  - DogHouseDigital -> Doghouse Digital
  - LesbianOlderYounger -> Lesbian Older Younger
  - RealityJunkies -> Reality Junkies
  - SweetSinner -> Sweet Sinner
  - SweetHeartVideo -> Sweetheart Video

|         Network | Studio              | URL                                                                                   |
| --------------: | :------------------ | ------------------------------------------------------------------------------------- |
| Mile High Media | dlf                 | https://www.dilfed.com/scene/9292051/cheating-bbq                                     |
| Mile High Media | DogHouseDigital     | https://www.doghousedigital.com/scene/9393951/amazing-tits-14-scene-2-titty-action    |
| Mile High Media | Family Sinners      | https://www.familysinners.com/scene/9381621/in-laws-2-episode-2-keep-it-in-the-family |
| Mile High Media | LesbianOlderYounger | https://www.milfed.com/scene/4365378/older-women-crave-chicks-02-scene-1              |
| Mile High Media | Milfed              | https://www.milfed.com/scene/9497251/fun-at-the-physio                                |
| Mile High Media | RealityJunkies      | https://www.realityjunkies.com/scene/9446181/free-use-families-2-scene-3-cant-resist  |
| Mile High Media | SweetSinner         | https://www.sweetsinner.com/scene/9585781/the-voyeur-6-scene-1-sneaky                 |
| Mile High Media | SweetHeartVideo     | https://www.sweetheartvideo.com/scene/4651721/lesbian-stepmother-7-scene-4            |

### Mile High Media (Trans and Bi)

- Name adjustments:
  BIEmpire -> Bi Empire

|         Network | Studio       | URL                                                                           |
| --------------: | :----------- | ----------------------------------------------------------------------------- |
| Mile High Media | BIEmpire     | https://www.biempire.com/scene/4421745/dirty-pictures                         |
| Mile High Media | Transsensual | https://www.transsensual.com/scene/4653681/sheer-panties-cumshot-gets-her-guy |

### Mile High Media (Gay)

|         Network | Studio    | URL                                                          |
| --------------: | :-------- | ------------------------------------------------------------ |
| Mile High Media | Icon Male | https://www.iconmale.com/scene/4653701/hot-daddies-3-scene-1 |
| Mile High Media | Icon Male | https://www.taboomale.com/scene/4373622/forgive-me-scene-1   |
| Mile High Media | Noir Male | https://www.noirmale.com/scene/9635521/christmas-proposal    |

## Why Not Bi

- Single studio but the parent studio comes back from the API as "WhyNotBy": flattening this into just "Why Not Bi"

|  Network | Studio     | URL                                                            |
| -------: | :--------- | -------------------------------------------------------------- |
| WhyNotBy | Why Not Bi | https://www.whynotbi.com/scene/4643151/glory-ous-wet-threesome |

## Mofos

- 28 studios listed on StashDB, 21 scrapable from API

  Missing:

  - Border Patrol Sex
  - Can She Take It
  - Ebony Sex Tapes (folded into Mofos B Sides)
  - Mofos Live
  - Mofos Old School
  - Teens At Work

- Some studios have their own domain

  Older domains like letstryanal.com, dontbreakme.com should still be supported URLs but not output

- Name adjustments:
  - lpi -> Let's Post It
  - Lets Try Anal -> Let's Try Anal

| Network | Studio              | URL                                                                                      |
| ------: | :------------------ | ---------------------------------------------------------------------------------------- |
|   Mofos | Busted Babysitters  | https://www.mofos.com/scene/2978471/webcamming-babysitter-learns-to-fuck                 |
|   Mofos | Don't Break Me      | https://www.dontbreakme.com/scene/4410806/dont-break-aria                                |
|   Mofos | Drone Hunter        | https://www.mofos.com/scene/2984901/country-riding                                       |
|   Mofos | Girls Gone Pink     | https://www.mofos.com/scene/2986081/breaking-entering-lesbian-couple                     |
|   Mofos | I Know That Girl    | https://www.iknowthatgirl.com/scene/9670091/influencer-coco-is-a-baddie                  |
|   Mofos | In Gang We Bang     | https://www.mofos.com/scene/2982821/gym-class-fuckers                                    |
|   Mofos | Latina Sex Tapes    | https://www.mofos.com/scene/2997891/public-flashing-in-the-street                        |
|   Mofos | lpi                 | https://www.mofos.com/scene/9659071/fuck-buddy-reunion                                   |
|   Mofos | Lets Try Anal       | https://www.letstryanal.com/scene/4620941/gf-loses-game-and-now-she-must-give-up-her-ass |
|   Mofos | Milfs Like It Black | https://www.mofos.com/scene/3014421/working-out-aint-working-out                         |
|   Mofos | Mofos B Sides       | https://www.mofos.com/scene/2982291/big-booty-nurse-heals-sick-bf                        |
|   Mofos | MOFOS Lab           | https://www.mofosnetwork.com/scene/3009491/sweet-naomi                                   |
|   Mofos | Mofos World Wide    | https://www.mofos.com/scene/3009451/euro-fuckdoll-takes-a-load                           |
|   Mofos | Pervs On Patrol     | https://www.mofos.com/scene/4358051/smokeshow                                            |
|   Mofos | Pornstar Vote       | https://www.mofos.com/scene/3027181/riley-reid-doesnt-wear-panties                       |
|   Mofos | Project RV          | https://www.mofos.com/scene/3027261/petite-teens-rv-fuck                                 |
|   Mofos | Pubic Pickups       | https://www.mofos.com/scene/4350950/cant-dickline-cash                                   |
|   Mofos | Real Slut Party     | https://www.mofos.com/scene/3037521/boats-n-hoes                                         |
|   Mofos | Share My BF         | https://www.mofos.com/scene/9483651/new-dick-to-forget-your-ex                           |
|   Mofos | She's A Freak       | https://www.mofos.com/scene/3046411/blondes-do-have-all-the-fun                          |
|   Mofos | Stranded Teens      | https://www.mofos.com/scene/3218041/stranded-in-my-feelings                              |
|   Mofos | The Sex Scout       | https://www.mofos.com/scene/3051541/hot-brunette-scouts-a-stranger                       |

## Property Sex

- 3 studios listed on StashDB (if we include the "network"), all 3 scrapable from API
- House Humpers has its own domain

|      Network | Studio          | URL                                                                |
| -----------: | :-------------- | ------------------------------------------------------------------ |
|              | Property Sex    | https://www.propertysex.com/scene/4437501/id-be-a-great-roommate   |
| Property Sex | Property Sex VR | https://www.propertysex.com/scene/4394526/going-that-extra-mile    |
| Property Sex | House Humpers   | https://www.househumpers.com/scene/9635471/we-work-better-together |

## Reality Dudes

- 5 studios listed on StashDB (if we include the "network"), 4 scrapable from API

  Missing:

  - Gay Revenge

- realitydudes.com does not show model pages, but URLs are still scrapable
- Papi has its own domain
- Papi uses `pornstar` instead of `model` between domain and scene ID
- Papi does not seem to be producing any scenes of their own, so most of their links are actually for Reality Dudes, Sean Cody, Men.com etc. The scraper does not account for this and some scenes may need to be rescraped with other Aylo scrapers to get fully correct metadata

|       Network | Studio        | URL                                                                                      |
| ------------: | :------------ | ---------------------------------------------------------------------------------------- |
|               | Reality Dudes | https://www.realitydudes.com/scene/4466271/bedroom-bukkake                               |
|               | Reality Dudes | https://www.realitydudesnetwork.com/scene/9509871/malik-delgaty-drills-enzo-mullers-hole |
| Reality Dudes | Dick Dorm     | https://www.realitydudes.com/scene/4475811/fitness-training                              |
| Reality Dudes | Papi          | https://www.realitydudes.com/scene/2834531/testicle-seduction                            |
| Reality Dudes | Str8 Chaser   | https://www.realitydudes.com/scene/2839091/cole                                          |

## Reality Kings

- 59 studios listed on StashDB, 45 scrapable from API

  Missing:

  - Bikini Crashers
  - Black GFs (folded into RK Prime)
  - Cum Girls
  - Dangerous Dongs
  - Flower Tucci
  - GF Revenge (folded into GF Leaks)
  - Project DTF
  - Real Orgasms
  - Round and Brown (folded into RK Prime)
  - Saturday Night Latinas
  - Team Squirt
  - Top Shelf Pussy
  - Tranny Surprise (folded into TransHarder?)
  - VIP Crew

- Look At Her Now seems to be in the process of being integrated:
  it still has its own domain and some of its scenes come back from the API without Reality Kings as a parent
- Older sites had their own domain and their URLs should be supported but not output
- Name adjustments:
  - rks -> RK Shorts

|       Network | Studio                | URL                                                                      |
| ------------: | :-------------------- | ------------------------------------------------------------------------ |
| Reality Kings | 40 Inch Plus          | https://www.realitykings.com/scene/27/double-bubbles                     |
| Reality Kings | 8th Street Latinas    | https://www.8thstreetlatinas.com/scene/2286648/my-secret-latina          |
| Reality Kings | Bad Tow Truck         | https://www.realitykings.com/scene/10255/cant-be-serious                 |
| Reality Kings | Big Naturals          | https://www.bignaturals.com/scene/4412702/second-thoughts                |
| Reality Kings | Big Tits Boss         | https://www.rk.com/scene/1110/career-woman                               |
| Reality Kings | Captain Stabbin       | https://www.realitykings.com/scene/4442371/semen-sirens-of-the-high-seas |
| Reality Kings | CFNM Secret           | https://www.realitykings.com/scene/1501/can-you-get-hard                 |
| Reality Kings | Crazy Asian GFs       | https://www.realitykings.com/scene/2959551/naughty-nyomi                 |
| Reality Kings | Crazy College GFs     | https://www.realitykings.com/scene/2957881/deuce-is-wild                 |
| Reality Kings | Cum Fiesta            | https://www.cumfiesta.com/scene/2483428/cooch-couture                    |
| Reality Kings | Dare Dorm             | https://www.daredorm.com/scene/2954551/high-stakes                       |
| Reality Kings | Euro Sex Parties      | https://www.eurosexparties.com/scene/10746/loving-to-fuck                |
| Reality Kings | Extreme Asses         | https://www.realitykings.com/scene/2603/teenie-bikini                    |
| Reality Kings | Extreme Naturals      | https://www.realitykings.com/scene/2667/redheaded-tit-youth              |
| Reality Kings | First Time Auditions  | https://www.realitykings.com/scene/10812/ease-into-elsa                  |
| Reality Kings | GF Leaks              | https://www.gfleaks.com/scene/2955251/sexy-stash                         |
| Reality Kings | Girls of Naked        | https://www.realitykings.com/scene/3086/the-soloist                      |
| Reality Kings | Happy Tugs            | https://www.happytugs.com/scene/3101/marvelous-mandi                     |
| Reality Kings | HD Love               | https://www.hdlove.com/scene/8376/rocking-remy                           |
| Reality Kings | Horny Birds           | https://www.hornybirds.com/scene/2957491/divorcees-revenge               |
| Reality Kings | Hot Bush              | https://www.realitykings.com/scene/3194/sweet-puss                       |
| Reality Kings | Hot Girls Game        | https://www.hotgirlsgame.com/scene/8805741/anal-obsessed-nerds           |
| Reality Kings | In the VIP            | https://www.realitykings.com/scene/3272/doing-doubles                    |
| Reality Kings | Lil Humpers           | https://www.lilhumpers.com/scene/4410213/pounding-the-prankster          |
|               | Look At Her Now       | https://www.lookathernow.com/scene/4413126/taste-tester                  |
| Reality Kings | Look At Her Now       | https://www.realitykings.com/scene/4416606/whos-the-boss-now             |
| Reality Kings | Mike in Brazil        | https://www.mikeinbrazil.com/scene/9776/sweet-caramel                    |
| Reality Kings | Mike's Apartment      | https://www.realitykings.com/scene/10808/sexy-zazie                      |
| Reality Kings | Milf Hunter           | https://www.milfhunter.com/scene/1853742/showering-her-with-cum          |
| Reality Kings | Milf Next Door        | https://www.realitykings.com/scene/5097/in-the-mood                      |
| Reality Kings | Moms Bang Teens       | https://www.momsbangteens.com/scene/2286917/anal-sex-education           |
| Reality Kings | Moms Lick Teens       | https://www.momslickteens.com/scene/2948131/vacation-sensation           |
| Reality Kings | Money Talks           | https://www.moneytalks.com/scene/8790/candy-cooch                        |
| Reality Kings | Monster Curves        | https://www.monstercurves.com/scene/4297681/choose-your-poison-2         |
| Reality Kings | No Faces              | https://www.realitykings.com/scene/5606/private-packers                  |
| Reality Kings | Pure 18               | https://www.pure18.com/scene/5708/horny-chloe                            |
| Reality Kings | Reckless in Miami     | https://www.recklessinmiami.com/scene/4393751/home-and-away              |
| Reality Kings | RK Prime              | https://www.realitykings.com/scene/4654441/mai-i-oil-you-up              |
| Reality Kings | rks                   | https://www.realitykings.com/scene/9735791/filling-the-gamer-girls-ass   |
| Reality Kings | See My Wife           | https://www.realitykings.com/scene/6477/my-lovely-lady                   |
| Reality Kings | Sneaky Sex            | https://www.sneakysex.com/scene/4410566/booty-camp                       |
| Reality Kings | Street BlowJobs       | https://www.realitykings.com/scene/10688/juicy-sweet                     |
| Reality Kings | Teens Love Huge Cocks | https://www.teenslovehugecocks.com/scene/4417629/amazing-avery           |
| Reality Kings | We Live Together      | https://www.welivetogether.com/scene/4414014/wlt-s01e02-new-arrivals     |
| Reality Kings | Wives in Pantyhose    | https://www.realitykings.com/scene/8283/perfect-ten                      |
| Reality Kings | Work Me Harder        | https://www.workmeharder.com/scene/4655221/fuck-truck                    |

## Sean Cody

- Single studio but has some substudio elements? Will flatten to just "Sean Cody" with no parent

|   Network | Studio         | URL                                                           |
| --------: | :------------- | ------------------------------------------------------------- |
|           | Sean Cody      | https://www.seancody.com/scene/4652961/devy-brock-bareback    |
| Sean Cody | SC BlackMaleMe | https://www.seancody.com/scene/2711231/daniel-philip-bareback |

## SexyHub

- 9 studios listed on StashDB, 6 scrapable from API

  Missing:

  - BDSM.xxx
  - HDPOV
  - Orgasms.XXX

- Some studios have their own domain
- All performer profiles have `modelprofile` instead of `model` between domain and scene ID

| Network | Studio        | URL                                                                      |
| ------: | :------------ | ------------------------------------------------------------------------ |
| SexyHub | Dane Jones    | https://www.danejones.com/scene/9585371/gamer-fucks-big-tits-italian-gf  |
| SexyHub | Fitness Rooms | https://www.sexyhub.com/scene/9585341/big-cock-gym-perv-fucks-redhead    |
| SexyHub | Girlfriends   | https://www.sexyhub.com/scene/4227051/bananas                            |
| SexyHub | Lesbea        | https://www.lesbea.com/scene/9289091/orgasms-in-beautiful-lingerie       |
| SexyHub | Massage Rooms | https://www.sexyhub.com/scene/4411925/deep-orgasms-for-petite-czech-babe |
| SexyHub | Mom XXX       | https://www.sexyhub.com/scene/9379531/long-legs-facesitting-with-stepmom |

## Squirted

- No special handling required

| Network | Studio   | URL                                                           |
| ------: | :------- | ------------------------------------------------------------- |
|         | Squirted | https://www.squirted.com/scene/4485941/tiffanys-back-for-more |

## TransAngels / TransHarder

- No special handling required

| Network | Studio      | URL                                                                        |
| ------: | :---------- | -------------------------------------------------------------------------- |
|         | TransAngels | https://www.transangels.com/scene/2682551/cocked-behind-bars               |
|         | TransAngels | https://www.transangelsnetwork.com/scene/9510091/strip-searched-and-fucked |
|         | TransHarder | https://www.transharder.com/scene/4420814/break-the-burglar                |

## True Amateurs

- No special handling required

| Network | Studio        | URL                                                                     |
| ------: | :------------ | ----------------------------------------------------------------------- |
|         | True Amateurs | https://www.trueamateurs.com/scene/4333351/footjob-with-black-stockings |

## Tube8Vip

- All scenes come back as belonging to the studio Elite, mostly under the parent studio Premium: flatten to just "Tube8Vip"

| Network | Studio | URL                                                                |
| ------: | :----- | ------------------------------------------------------------------ |
| Premium | Elite  | https://www.tube8vip.com/scene/2933481/why-everybody-loves-adriana |

## Twistys

- 13 studios listed on StashDB, 11 scrapable from API

  Missing:

  - Naughty Staff
  - Twistys Live

- Blue Fantasies, Busty Ones and Euro Foxes are all mixed up and have confusing metadata in the API

  This [scene with Louise Glover](https://www.twistys.com/scene/3474791/for-all-the-world-to-see) falls under all 3 channels:

  - Shows up on the [first page for Blue Fantasies](https://www.twistys.com/scenes?site=220)
  - Shows up on the [19th page for Busty Ones](https://www.twistys.com/scenes?page=19&site=229)
  - Shows up on the [13th page for Euro Foxes](https://www.twistys.com/scenes?page=13&site=226)

  If a scene is in any or all of these collections we will make its studio the first one that matches alphabetically: this particular scene would fall under Blue Fantasies

- Name adjustments:
  - anettedawn -> Anette Dawn
  - TwistysHard -> Twistys Hard
  - whengirlsplay -> When Girls Play

| Network | Studio          | URL                                                            |
| ------: | :-------------- | -------------------------------------------------------------- |
| Twistys | anettedawn      | https://www.twistys.com/scene/3468571/anette-gets-a-naughty    |
| Twistys | Feature Film    | https://www.twistys.com/scene/3413521/the-artist-within-part-1 |
| Twistys | Mom Knows Best  | https://www.twistys.com/scene/4281921/dads-new-girlfriend      |
| Twistys | Nicole Graves   | https://www.twistys.com/scene/3436211/wanna-play               |
| Twistys | Turning Twistys | https://www.twistys.com/scene/8366721/let-me-show-you          |
| Twistys | TwistysHard     | https://www.twistys.com/scene/3406841/fix-her-up-her           |
| Twistys | Twistys Teasers | https://www.twistys.com/scene/3430461/work-those-asses         |
| Twistys | whengirlsplay   | https://www.twistys.com/scene/9420281/lulus-lesbian-squirtfest |

## VOYR

- No special handling required

| Network | Studio | URL                                                  |
| ------: | :----- | ---------------------------------------------------- |
|         | Voyr   | https://www.voyr.com/scene/9729471/four-way-pleasure |
