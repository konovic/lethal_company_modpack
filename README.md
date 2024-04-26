## Table of Contents

- [Lethal Company Modpack](#lethal-company-modpack)
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
Personal modpack for Lethal Company v50.\
All rights held by the respective mod authors.

<br>

# Installation Instructions
## LETHAL COMPANY
Ensure you have the latest version (v50) downloaded through Steam. 

### Previous Version
If you want to opt-in to the previous version (v49) perform the following:
1. Open Steam.
2. Right click Lethal Company and select `Properties`.
3. In the `Betas` tab, click the `None` dropdown-menu item and select `previous - The previous version`, then allow the game to download.

You can then install the [last supported version](https://github.com/konovic/lethal_company_modpack/releases/tag/v2.7.0) of the modpack for v49.\
These steps can be performed again to select the `None` branch to update the game to v50.

## MODPACK

### Download
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `lethal_company_modpack-v4.0.0.zip`.

### Install
This guide assumes you're using a fresh install of Lethal Company. If you're updating this modpack, see the [**Update**](#update) section below.\
If you have a different modpack installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Unzip/open `lethal_company_modpack-v4.0.0.zip`.
3. Move the contents of the `lethal_company_modpack-v4.0.0\modpack` folder into the `Lethal Company` folder from step 1.\
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
| Mod/Plugin                                                                              | Version | Author           | Source                                                                                             |
| --------------------------------------------------------------------------------------- | ------- | ---------------- | -------------------------------------------------------------------------------------------------- |
| BadGojoSuit                                                                             | v1.0.2  | Vibrant          | [thunderstore](https://thunderstore.io/c/lethal-company/p/Vibrant/BadGojoSuit)                     |
| [BetterItemScan](https://github.com/PopleZoo/BetterItemScan)                            | v3.0.2  | PopleZoo         | [thunderstore](https://thunderstore.io/c/lethal-company/p/PopleZoo/BetterItemScan)                 |
| [Clown_Suit](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/)               | v1.0.0  | Crabford         | [thunderstore](https://thunderstore.io/c/lethal-company/p/Crabford/Clown_Suit)                     |
| [Coroner](https://github.com/EliteMasterEric/Coroner)                                   | v1.6.2  | EliteMasterEric  | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/Coroner)                 |
| [CustomFunSuits](https://www.google.com)                                                | v1.8.3  | GhostbustingTrio | [thunderstore](https://thunderstore.io/c/lethal-company/p/GhostbustingTrio/CustomFunSuits)         |
| [FrogSkins](https://twitter.com/mythicfroggo)                                           | v1.0.12 | MythicFrog       | [thunderstore](https://thunderstore.io/c/lethal-company/p/MythicFrog/FrogSkins)                    |
| [GeneralImprovements](https://github.com/Shaosil/LethalCompanyMods-GeneralImprovements) | v1.2.3  | ShaosilGaming    | [thunderstore](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/GeneralImprovements)       |
| [Helmet_Cameras](https://github.com/The0therOne/Helmet_Cameras)                         | v2.1.5  | RickArg          | [thunderstore](https://thunderstore.io/c/lethal-company/p/RickArg/Helmet_Cameras)                  |
| HotbarPlus                                                                              | v1.6.3  | FlipMods         | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/HotbarPlus)                     |
| [LateCompany](https://github.com/ANormalTwig/LC-LateCompany)                            | v1.0.13 | anormaltwig      | [thunderstore](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany)                 |
| [LC_API](https://github.com/steven4547466/LC-API)                                       | v3.4.5  | 2018             | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API)                             |
| [LethalAutocomplete](https://github.com/IlyaChichkov/LethalAutocompleteMod)             | v0.4.5  | red_eye          | [thunderstore](https://thunderstore.io/c/lethal-company/p/red_eye/LethalAutocomplete)              |
| [LethalConfig](https://github.com/AinaVT/LethalConfig)                                  | v1.4.2  | AinaVT           | [thunderstore](https://thunderstore.io/c/lethal-company/p/AinaVT/LethalConfig)                     |
| [Lidl_Suit](https://www.lidl.de)                                                        | v1.0.4  | QuFix            | [thunderstore](https://thunderstore.io/c/lethal-company/p/QuFix/Lidl_Suit)                         |
| MoreCompany                                                                             | v1.9.1  | notnotnotswipez  | [thunderstore](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany)             |
| [More_Suits](https://github.com/x753/Lethal-Company-More-Suits)                         | v1.4.3  | x753             | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/More_Suits)                         |
| RandomSuits                                                                             | v1.0.1  | JordinB          | [thunderstore](https://thunderstore.io/c/lethal-company/p/JordinB/RandomSuits)                     |
| Silly_Little_Company_Suits                                                              | v4.2.0  | DiaryOfTruth     | [thunderstore](https://thunderstore.io/c/lethal-company/p/DiaryOfTruth/Silly_Little_Company_Suits) |
| [SuitSaver](https://github.com/Hexnet111/SuitSaver)                                     | v1.2.0  | Hexnet111        | [thunderstore](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver)                     |
| [TimeCommand](https://github.com/Jax-Drummond/TimeCommand)                              | v1.1.1  | NotAtomicBomb    | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/TimeCommand)               |
| [TooManySuits](https://github.com/VerityIncorporated/TooManySuits)                      | v1.0.9  | Verity           | [thunderstore](https://thunderstore.io/c/lethal-company/p/Verity/TooManySuits)                     |
| [WackyCosmetics](https://github.com/EliteMasterEric/Wacky-Cosmetics)                    | v2.0.0  | EliteMasterEric  | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/WackyCosmetics)          |
| WaluigiSuit                                                                             | v0.0.3  | Team_Waluigi     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Team_Waluigi/WaluigiSuit)                |

| Dependency                                                                     | Version | Author        | Source                                                                                      |
| ------------------------------------------------------------------------------ | ------- | ------------- | ------------------------------------------------------------------------------------------- |
| [BepInEx](https://github.com/BepInEx/BepInEx)                                  | v5.4.21 | Various       | [github](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.21)                           |
| [LethalCompany_InputUtils](https://github.com/Rune580/LethalCompanyInputUtils) | v0.7.4  | Rune580       | [thunderstore](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils) |
| [TerminalApi](https://github.com/Jax-Drummond/TerminalApi)                     | v1.5.3  | NotAtomicBomb | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/TerminalApi)        |

*Autogenerated using mod metadata downloaded via [thunderstore](https://thunderstore.io/c/lethal-company)*
