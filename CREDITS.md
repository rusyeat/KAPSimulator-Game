# KAP Simulator — дыбыстар мен дауыстар авторлары / Credits

Ойындағы жазылған дыбыстар тегін лицензиялы пакеттерден алынған. Төмендегі CC-BY дыбыстары үшін авторды көрсету міндетті.

## CC-BY 3.0 (авторды көрсету міндетті)

| Дыбыс | Автор | Дереккөз | Ойында |
|---|---|---|---|
| Helmut Scream | creativeheroes | https://freesound.org/people/creativeheroes/sounds/84353/ | `Scream_0` |
| Male_Thijs_loud_scream | thanvannispen | https://freesound.org/people/thanvannispen/sounds/9432/ | `Scream_1`, `Scream_2` |
| Gunshot sounds (cz, sks, mosin, shotty) | Vincent Sevedge (© 2009) | https://opengameart.org/content/gunshot-sounds | `GunPM`, `GunAK`, `GunSniper`, `GunShotgun` |

Лицензия: https://creativecommons.org/licenses/by/3.0/ — дыбыстар кесілген, қатты-баяулығы мен биіктігі ойында өзгертіледі.

## CC0 (қоғамдық игілік, авторды көрсету міндетті емес — алғыс ретінде)

| Пакет | Автор | Дереккөз | Ойында |
|---|---|---|---|
| Impact Sounds | Kenney | https://kenney.nl/assets/impact-sounds | қадамдар, соққылар |
| RPG Audio | Kenney | https://kenney.nl/assets/rpg-audio | есік, сықыр, мата, металл |
| human male scream multi | JohnsonBrandEditing | https://freesound.org/people/JohnsonBrandEditing/sounds/173944/ | `Scream_3`…`Scream_7` |
| Racing car engine sound loops | domasx2 | https://opengameart.org/content/racing-car-engine-sound-loops | `Engine_*` |
| Zombie moans | Darsycho | https://opengameart.org/content/zombie-moans | `Moan_0` |
| Hungry ghoul | OpenGameArt | https://opengameart.org/content/hungry-ghoul | `Moan_1` |
| Male grunt/yelling sounds (CC0 нұсқасы) | HaelDB | https://opengameart.org/content/male-gruntyelling-sounds | `Yell_*`, `Grunt_*` |
| Ambience Pack 1 – Sci-Fi Horror | Joth | https://opengameart.org/content/ambience-pack-1-sci-fi-horror | `Ambient_*` (фон музыкасы) |
| Insistent (background loop) | yd | https://opengameart.org/content/insistent-background-loop | `Danger_0` (қауіп музыкасы) |
| Abandoned passages / freezer (horror ambience loop) | congusbongus | https://opengameart.org/content/abandoned-passages-horror-ambience-loop | `Indoor_0` |
| Footsteps_Mountain_Boots_Wet_Sand_Sequence_Mono | Nox_Sound | https://freesound.org/s/564893/ | `StepSand_*` (жүру), `StepSandRun_*`, `LandSand_*` |
| Small Diesel Generator | jameswrowles | https://freesound.org/s/516759/ | `Generator_0/1` (цикл), `GenStart_0`, `GenStop_0` |
| shooting_1 (firing a rifle outdoors) | mchrpt | https://freesound.org/s/660978/ | `GunRifle_*` (снайпер, алыстағы атыс) |
| Geiger Counter Hotspot (Sweeping) | cookies+policy | https://freesound.org/s/555934/ | дозиметр шертпелері (`KAPGeigerClicks.inl`) |

## Музыка

| Трек | Авторы | Ойында |
|---|---|---|
| «Бос үміт» (KazAtomProm_Bos_Umit_FL_Menu) | жоба авторы (ChatGPT + FL Studio көмегімен) | `Menu_0` — басты мәзір (тұйық цикл) |

Мылтық жазбалары (Vincent Sevedge, CC-BY 3.0) жеке атыстарға кесілген: `GunPM_0…3`, `GunAK_0…13`, `GunSniper_0…4`, `GunShotgun_0`.

## Дауыстар (TTS)

Кейіпкерлердің сөздері Windows-тың кіріктірілген сөйлеу синтезімен (Microsoft Pavel — ер, Microsoft Irina — әйел, ru-RU)
`Scripts/gen_vo.ps1` арқылы жазылды. Қазақ әріптері синтезге дейін жуық орыс әріптеріне ауыстырылады (ә→а, қ→к, ө→ё, ...).

## Қалғаны

Модельдер (көліктер, ғимараттар, кейіпкерлер, қарулар), материалдар мен процедуралық дыбыстар (жел, найзағай, Гейгер, жүрек, сирена) —
жобаның өз коды: `Source/KAPSimulatorEditor` (генераторлар) және `Source/KAPSimulator/KAP/Audio` (синтез).

## KAP Creatures V1

Mutant and canine models, rig/animation edits and shaders: original KAP authoring. Mutant base uses the existing CC0 MakeHuman system data. 21 creature FX derive from the CC0 HaelDB grunts credited above (pitch, filtering, layering, envelopes and short reflection). Exact per-file sources: SourceArt/CreaturesV1/Audio/audio_report.json. Editable models and attribution: SourceArt/CreaturesV1/README.md. No S.T.A.L.K.E.R. assets used.

## Fab trader outfit

Trader model, coat, equipment and PBR textures: Oleg Ushenok, “Free sample Squad Of Surviving Stalkers”, https://www.fab.com/listings/7044a9d9-8f0d-4810-abbd-6a73f8bd413e . Fab Standard License accepted with the project owner's approval. KAP adaptation adds optimization, a pose-preserving skeleton, idle/walk/run clips and three LODs. Source and license notes: SourceArt/FabStalker/README.md. This is a separately licensed Fab asset, not an extracted S.T.A.L.K.E.R. game model.

## Original KAP weapon art — V3 (2026-10-25)

The V3 firearm and hand-tool meshes and their generated surface maps are original project art, authored in Blender for KAP Simulator. Source: `SourceArt/WeaponsV3/KAP_Weapons_V3.blend`; generator: `Scripts/blender/build_weapons_v3.py`; Unreal import: `Scripts/import_weapons_v3.py`. Eleven models, 22 mesh parts, three LODs. No firearm meshes were copied from another game.

## Нақты қару жазбалары / Real firearm recordings (Sonniss GDC Game Audio Bundle, 2026-11-08)

Royalty-free, коммерциялық ойынға рұқсат, авторды көрсету міндетті емес (алғыс ретінде көрсетілген). Лицензия: https://sonniss.com/gdc-bundle-license/ — дыбыстарды жеке пакет ретінде таратуға болмайды, тек ойынның ішінде.
Түпнұсқалар 96 кГц / 24-бит; жүктелді: https://sonniss.com/gameaudiogdc/ (ресми айна ftpmirror.your.org), кесу: `Scripts/process_sonniss_guns.ps1`, импорт: `Scripts/import_sonniss_guns.py`.

| Жазба | Автор / кітапхана | Бума | Ойында |
|---|---|---|---|
| AKM 7.62x39mm (1 м, 55 м) | Pole Position Production | GDC 2016 | `GunAKClose_*`, `GunAKFar_*` |
| FN FAL 7.62x51mm (1.5 м, 25 м) | Pole Position Production | GDC 2016 | `GunAKClose_*`, `GunAKFar_*` |
| HK416 5.56mm, G36C 5.56mm (1 м, 50 м) | Pole Position Production | GDC 2016 | `GunCarbineClose_*`, `GunCarbineFar_*` |
| Glock 18 9mm (1 м, 75 м) | Pole Position Production | GDC 2016 | `GunPistolClose_*`, `GunPistolFar_*` (ПМ, автомат-пистолет) |
| Barrett M98B .338 Lapua | Pole Position Production | GDC 2016 | `GunSniperClose_*` |
| Remington 870 12g (London Warehouse Firearms) | Audiobeast | GDC 2016 | `GunShotgunClose_*` |
| bullet_flyby, bullet_impact (body, concrete, metal) | Gamemaster Audio — Bullet Impact Sounds | GDC 2017 | `BulletFlyby_0`, `BulletBody_0`, `BulletConcrete_0`, `BulletMetal_0` |
| gun_semi_auto_rifle_cock | Gamemaster Audio — Gun Sound Pack | GDC 2017 | `RifleCock_0` |

## Дауыстар (ElevenLabs)

Кейіпкерлердің бір бөлігі ElevenLabs (https://elevenlabs.io) синтезімен дыбысталды.

## Анимациялар

Кейбір қимыл анимациялары Adobe Mixamo (https://www.mixamo.com) кітапханасынан алынып, KAP қаңқасына бейімделді.

## Қозғалтқыш

Unreal® Engine, Copyright 1998–2026, Epic Games, Inc. Unreal® — Epic Games, Inc. тіркелген сауда белгісі.
