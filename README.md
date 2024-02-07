## Table of Contents

- [Lethal Company Modpack](#lethal-company-modpack)
    - [A note about r2modman](#a-note-about-r2modman)
- [Installation Instructions](#installation-instructions)
  - [LETHAL COMPANY](#lethal-company)
    - [Previous Version](#previous-version)
  - [MODPACK](#modpack)
    - [Download](#download)
    - [Install](#install)
    - [Update](#update)
- [Mod List](#mod-list)

<br>

# Lethal Company Modpack
Personal modpack for Lethal Company v49.\
All rights held by the respective mod authors.

### A note about r2modman
r2modman support has been dropped as it added extra complexity and stability issues between those installing manually and those using the mod manager.\
For stability purposes, it is highly recommended that everybody follow the manual installation.\
I apologize for any inconvenience, and thank you for you understanding.

<br>

# Installation Instructions
## LETHAL COMPANY
Ensure you have the latest version (v49) downloaded through Steam. 

### Previous Version
If you want to opt-in to the previous version (v45) perform the following:
1. Open Steam.
2. Right click Lethal Company and select `Properties`.
3. In the `Betas` tab, click the `None` dropdown-menu item and select `previous - The previous version`, then allow the game to download.

You can then install the [last supported version](https://github.com/konovic/lethal_company_modpack/releases/tag/v2.7.0) of the modpack for v45.\
These steps can be performed again to select the `None` branch to update the game to v49.

## MODPACK

### Download
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `lethal_company_modpack-v3.5.0.zip`.

### Install
This guide assumes you're using a fresh install of Lethal Company. If you're updating this modpack, see the [**Update**](#update) section below.\
If you have a different modpack installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Unzip/open `lethal_company_modpack-v3.5.0.zip`.
3. Move the contents of the `lethal_company_modpack-v3.5.0\modpack` folder into the `Lethal Company` folder from step 1.\
Your `Lethal Company` folder should look like this:
```
Lethal Company\BepInEx\<plugins,config,etc>
Lethal Company\doorstop_config.ini
Lethal Company\winhttp.dll
Lethal Company\<all other base game files>
```
4. For Proton/Steamdeck users only: BepInEx works with Proton by adding\
`WINEDLLOVERRIDES="winhttp.dll=n,b" %command%`\
to Lethal Company's Steam launch options.
5. If you were performing an [Update](#update), return to step 6.

### Update
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Perform the following if you have modified any files in `BepInEx\config`. **This includes any changes made using LethalConfig in the game menu.**
    1. Backup your `BepInEx\config` folder to a temporary safe location e.g. the desktop.
3. Perform the following if you have modified any files in `BepInEx\plugins`.
    1. Backup any folders with manual modifications (e.g. `BepInEx\plugins\More_Suits\moresuits` if you added a `!less-suits.txt` file).
4. **Delete the existing** `BepInEx` **folder.**
5. Follow the [installation steps](#modpack) as above.
6. If you performed step 2.i, copy the `config` folder back into the `Lethal Company\BepInEx` folder. If you're not sure, you probably want to overwrite the modpack's default config files.
7. If you performed step 3.i, restore any additional files/folders. Take care when copying files from older mod versions to newer mod versions.

<br>

# Mod List
| Mod/Plugin                                                                              | Version | Author                     | Source                                                                                              |
| --------------------------------------------------------------------------------------- | ------- | -------------------------- | --------------------------------------------------------------------------------------------------- |
| BadGojoSuit                                                                             | v1.0.2  | Vibrant                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/Vibrant/BadGojoSuit)                      |
| [BetterItemScan](https://github.com/PopleZoo/BetterItemScan)                            | v3.0.1  | PopleZoo                   | [thunderstore](https://thunderstore.io/c/lethal-company/p/PopleZoo/BetterItemScan)                  |
| [BidenSoda](https://thunderstore.io/c/lethal-company/p/Spantle/BidenSoda)               | v1.1.2  | Spantle                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/Spantle/BidenSoda)                        |
| ChillaxSCRAPS                                                                           | v0.6.0  | CHILLAX                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/CHILLAX/ChillaxSCRAPS)                    |
| [CirnoFumoScrap](https://github.com/Badhamknibbs/Cirno-Fumo-Scrap-mod_LC)               | v2.0.1  | Badham_Mods                | [thunderstore](https://thunderstore.io/c/lethal-company/p/Badham_Mods/CirnoFumoScrap)               |
| [Clown_Suit](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/)               | v1.0.0  | Crabford                   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Crabford/Clown_Suit)                      |
| CoilHeadStare                                                                           | v1.0.6  | TwinDimensionalProductions | [thunderstore](https://thunderstore.io/c/lethal-company/p/TwinDimensionalProductions/CoilHeadStare) |
| [Coroner](https://github.com/EliteMasterEric/Coroner)                                   | v1.6.0  | EliteMasterEric            | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/Coroner)                  |
| [CozyImprovements](https://github.com/ricky-davis/CozyImprovements)                     | v1.2.2  | Spyci                      | [thunderstore](https://thunderstore.io/c/lethal-company/p/Spyci/CozyImprovements)                   |
| [CustomFunSuits](https://www.google.com)                                                | v1.8.2  | GhostbustingTrio           | [thunderstore](https://thunderstore.io/c/lethal-company/p/GhostbustingTrio/CustomFunSuits)          |
| [FlashlightFix](https://github.com/Shaosil/LethalCompanyMods-FlashlightFix)             | v1.0.7  | ShaosilGaming              | [thunderstore](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/FlashlightFix)              |
| [FrogSkins](https://twitter.com/mythicfroggo)                                           | v1.0.12 | MythicFrog                 | [thunderstore](https://thunderstore.io/c/lethal-company/p/MythicFrog/FrogSkins)                     |
| FumoCompany                                                                             | v1.2.3  | silhygames                 | [thunderstore](https://thunderstore.io/c/lethal-company/p/silhygames/FumoCompany)                   |
| [GeneralImprovements](https://github.com/Shaosil/LethalCompanyMods-GeneralImprovements) | v1.1.8  | ShaosilGaming              | [thunderstore](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/GeneralImprovements)        |
| [Groan_Tube_Scrap](https://github.com/ChrisFeline)                                      | v1.0.1  | Kittenji                   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Kittenji/Groan_Tube_Scrap)                |
| [Helmet_Cameras](https://github.com/The0therOne/Helmet_Cameras)                         | v2.1.5  | RickArg                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/RickArg/Helmet_Cameras)                   |
| HotbarPlus                                                                              | v1.5.7  | FlipMods                   | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/HotbarPlus)                      |
| [ImmersiveScraps](https://discord.com/channels/1168655651455639582/1195454016021340322) | v1.1.9  | Justice69                  | [thunderstore](https://thunderstore.io/c/lethal-company/p/Justice69/ImmersiveScraps)                |
| [JesterFree](https://github.com/AriDeve/JesterFree)                                     | v2.0.0  | AriDev                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/AriDev/JesterFree)                        |
| [JetpackWarning](https://github.com/Hamunii/JetpackWarning)                             | v2.2.0  | Hamunii                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/Hamunii/JetpackWarning)                   |
| LandMineFartReverb                                                                      | v1.0.3  | sunnobunno                 | [thunderstore](https://thunderstore.io/c/lethal-company/p/sunnobunno/LandMineFartReverb)            |
| [LateCompany](https://github.com/ANormalTwig/LC-LateCompany)                            | v1.0.11 | anormaltwig                | [thunderstore](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany)                  |
| [LC_API](https://github.com/steven4547466/LC-API)                                       | v3.4.5  | 2018                       | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API)                              |
| [LethalAutocomplete](https://github.com/IlyaChichkov/LethalAutocompleteMod)             | v0.4.3  | red_eye                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/red_eye/LethalAutocomplete)               |
| [LethalConfig](https://github.com/AinaVT/LethalConfig)                                  | v1.3.4  | AinaVT                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/AinaVT/LethalConfig)                      |
| [LethalPlushies](https://steamcommunity.com/id/Bohdie/)                                 | v1.7.1  | Nuts                       | [thunderstore](https://thunderstore.io/c/lethal-company/p/Nuts/LethalPlushies)                      |
| [LethalThings](https://github.com/EvaisaDev/LethalThings)                               | v0.9.4  | Evaisa                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalThings)                      |
| [LethalUtilities](https://discord.gg/rzQcgRDQw3)                                        | v1.2.21 | kyxino                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/kyxino/LethalUtilities)                   |
| [Lidl_Suit](https://www.lidl.de)                                                        | v1.0.4  | QuFix                      | [thunderstore](https://thunderstore.io/c/lethal-company/p/QuFix/Lidl_Suit)                          |
| [MirrorDecor](https://github.com/quackandcheese/MirrorDecor)                            | v1.3.2  | quackandcheese             | [thunderstore](https://thunderstore.io/c/lethal-company/p/quackandcheese/MirrorDecor)               |
| MoreCompany                                                                             | v1.7.6  | notnotnotswipez            | [thunderstore](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany)              |
| [MoreHead](https://space.bilibili.com/1542613)                                          | v1.2.5  | Mhz                        | [thunderstore](https://thunderstore.io/c/lethal-company/p/Mhz/MoreHead)                             |
| [More_Suits](https://github.com/x753/Lethal-Company-More-Suits)                         | v1.4.1  | x753                       | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/More_Suits)                          |
| [PathfindingLagFix](https://github.com/Zaggy1024/LC_PathfindingLagFix/)                 | v1.2.1  | Zaggy1024                  | [thunderstore](https://thunderstore.io/c/lethal-company/p/Zaggy1024/PathfindingLagFix)              |
| RandomSuits                                                                             | v1.0.1  | JordinB                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/JordinB/RandomSuits)                      |
| [Reptilian_Suit](https://github.com/x753/Lethal-Company-More-Suits)                     | v1.0.1  | Crab_imitation             | [thunderstore](https://thunderstore.io/c/lethal-company/p/Crab_imitation/Reptilian_Suit)            |
| Silly_Little_Company_Suits                                                              | v4.2.0  | DiaryOfTruth               | [thunderstore](https://thunderstore.io/c/lethal-company/p/DiaryOfTruth/Silly_Little_Company_Suits)  |
| [Skinwalkers](https://rugbug.net/skinwalkers)                                           | v4.0.1  | RugbugRedfern              | [thunderstore](https://thunderstore.io/c/lethal-company/p/RugbugRedfern/Skinwalkers)                |
| [SlimeTamingFix](https://github.com/EliteMasterEric/SlimeTamingFix)                     | v1.0.2  | EliteMasterEric            | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/SlimeTamingFix)           |
| [Space_Pajamas_Suit](https://github.com/x753/Lethal-Company-More-Suits)                 | v1.0.6  | Crab_imitation             | [thunderstore](https://thunderstore.io/c/lethal-company/p/Crab_imitation/Space_Pajamas_Suit)        |
| [SuitSaver](https://github.com/Hexnet111/SuitSaver)                                     | v1.1.4  | Hexnet111                  | [thunderstore](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver)                      |
| [Symbiosis](https://github.com/niceh26/Symbiosis)                                       | v1.0.5  | NiceHairs                  | [thunderstore](https://thunderstore.io/c/lethal-company/p/NiceHairs/Symbiosis)                      |
| [TimeCommand](https://github.com/NotAtomicBomb/TimeCommand)                             | v1.1.0  | NotAtomicBomb              | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/TimeCommand)                |
| [TooManyEmotes](https://github.com/cmooref17/Lethal-Company-TooManyEmotes)              | v1.8.6  | FlipMods                   | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/TooManyEmotes)                   |
| TooManySuits                                                                            | v1.0.5  | Verity                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Verity/TooManySuits)                      |
| [WackyCosmetics](https://github.com/EliteMasterEric/Wacky-Cosmetics)                    | v2.0.0  | EliteMasterEric            | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/WackyCosmetics)           |
| WaluigiSuit                                                                             | v0.0.3  | Team_Waluigi               | [thunderstore](https://thunderstore.io/c/lethal-company/p/Team_Waluigi/WaluigiSuit)                 |
| YippeeMod                                                                               | v1.2.3  | sunnobunno                 | [thunderstore](https://thunderstore.io/c/lethal-company/p/sunnobunno/YippeeMod)                     |
| YippeeScrap                                                                             | v1.0.7  | AinaVT                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/AinaVT/YippeeScrap)                       |

| Dependency                                                                              | Version | Author                     | Source                                                                                              |
| --------------------------------------------------------------------------------------- | ------- | -------------------------- | --------------------------------------------------------------------------------------------------- |
| [BepInEx](https://github.com/BepInEx/BepInEx)                                           | v5.4.21 | Various                    | [github](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.21)                                   |
| [HookGenPatcher](https://github.com/harbingerofme/Bepinex.Monomod.HookGenPatcher)       | v0.0.5  | Evaisa                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/HookGenPatcher)                    |
| JigglePhysicsPlugin                                                                     | v1.1.2  | HGG                        | [thunderstore](https://thunderstore.io/c/lethal-company/p/HGG/JigglePhysicsPlugin)                  |
| [LC_API](https://github.com/steven4547466/LC-API)                                       | v3.4.5  | 2018                       | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API)                              |
| [LCSoundTool](https://github.com/no00ob/LCSoundTool)                                    | v1.5.1  | no00ob                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/no00ob/LCSoundTool)                       |
| [LethalCompany_InputUtils](https://github.com/Rune580/LethalCompanyInputUtils)          | v0.6.3  | Rune580                    | [thunderstore](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils)         |
| [LethalExpansionCore](https://github.com/LethalMods/LethalExpansionCore)                | v1.3.15 | jockie                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/jockie/LethalExpansionCore)               |
| [LethalLib](https://github.com/EvaisaDev/LethalLib)                                     | v0.14.2 | Evaisa                     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalLib)                         |
| NuclearLib                                                                              | v1.0.4  | NiceHairs                  | [thunderstore](https://thunderstore.io/c/lethal-company/p/NiceHairs/NuclearLib)                     |
| [TerminalApi](https://github.com/NotAtomicBomb/TerminalApi)                             | v1.5.1  | NotAtomicBomb              | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/TerminalApi)                |

*Autogenerated using mod metadata downloaded via [thunderstore](https://thunderstore.io/c/lethal-company)*
