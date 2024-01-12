# Lethal Company Modpack
Personal modpack for Lethal Company v49.\
All rights held by the respective mod authors.

#### A note about r2modman
r2modman support has been dropped as it added extra complexity and stability issues between those installing manually and those using the mod manager.\
For stability purposes, it is highly recommended that everybody follow the manual installation.\
I apologize for any inconvenience, and thank you for you understanding.

---
## Installation Instructions
### LETHAL COMPANY
Ensure you have the latest version (v49) downloaded through Steam. 

#### Previous Version
If you want to opt-in to the previous version (v45) perform the following:
1. Open Steam.
2. Right click Lethal Company and select `Properties`.
3. In the `Betas` tab, click the `None` dropdown-menu item and select `previous - The previous version`, then allow the game to download.

You can then install the [last supported version](https://github.com/konovic/lethal_company_modpack/releases/tag/v2.7.0) of the modpack for v45.\
These steps can be performed again to select the `None` branch to update the game to v49.

<br>

### MODPACK

#### Download:
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `Source code (zip)`.

#### Install:
This guide assumes you're using a fresh install of Lethal Company. If you're updating this modpack, see the [**Update**](https://github.com/konovic/lethal_company_modpack#update) section below.\
If you have a different modpack installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Unzip/open `lethal_company_modpack-v3.1.0.zip`.
3. Move the contents of the `lethal_company_modpack-v3.1.0\modpack` folder into the `Lethal Company` folder from step 1.\
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
5. If you were performing an [Update](https://github.com/konovic/lethal_company_modpack#update), return to step 6.

#### Update:
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Perform the following if you have modified any files in `BepInEx\config`. **This includes any changes made using LethalConfig in the game menu.**
    1. Backup your `BepInEx\config` folder to a temporary safe location e.g. the desktop.
3. Perform the following if you have modified any files in `BepInEx\plugins`.
    1. Backup any folders with manual modifications (e.g. `BepInEx\plugins\More_Suits\moresuits` if you added a `!less-suits.txt` file).
4. **Delete the existing** `BepInEx` **folder.**
5. Follow the [installation steps](https://github.com/konovic/lethal_company_modpack#modpack) as above.
6. If you performed step 2.i, copy the `config` folder back into the `Lethal Company\BepInEx` folder. If you're not sure, you probably want to overwrite the modpack's default config files.
7. If you performed step 3.i, restore any additional files/folders. Take care when copying files from older mod versions to newer mod versions.

---
## Mod List
| Mod/Plugin                                                                                 | Version | Author          | Source                                                                                        |
| ------------------------------------------------------------------------------------------ | ------- | --------------- | --------------------------------------------------------------------------------------------- |
| [BepInEx](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.21)                         | v5.4.21 | Various         | [github](https://github.com/BepInEx/BepInEx)                                                  |
| [CirnoFumoScrap](https://github.com/Badhamknibbs/Cirno-Fumo-Scrap-mod_LC)                  | v2.0.1  | Badham_Mods     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Badham_Mods/CirnoFumoScrap)         |
| [Coroner](https://github.com/EliteMasterEric/Coroner)                                      | v1.5.3  | EliteMasterEric | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/Coroner)            |
| [FlashlightFix](https://github.com/Shaosil/LethalCompanyMods-FlashlightFix)                | v1.0.5  | ShaosilGaming   | [thunderstore](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/FlashlightFix)        |
| [FlashlightToggle](https://github.com/redassser/Lc-Flashlight)                             | v1.5.0  | Renegades       | [thunderstore](https://thunderstore.io/c/lethal-company/p/Renegades/FlashlightToggle)         |
| [Fuzzy_chaos_gang_Suits](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/)      | v2.0.5  | Degenerates     | [thunderstore](https://thunderstore.io/c/lethal-company/p/Degenerates/Fuzzy_chaos_gang_Suits) |
| [GeneralImprovements](https://github.com/Shaosil/LethalCompanyMods-GeneralImprovements)    | v1.0.15 | ShaosilGaming   | [thunderstore](https://thunderstore.io/c/lethal-company/p/ShaosilGaming/GeneralImprovements)  |
| [Groan_Tube_Scrap](https://github.com/ChrisFeline)                                         | v1.0.1  | Kittenji        | [thunderstore](https://thunderstore.io/c/lethal-company/p/Kittenji/Groan_Tube_Scrap)          |
| [Helmet_Cameras](https://github.com/The0therOne/Helmet_Cameras)                            | v2.1.5  | RickArg         | [thunderstore](https://thunderstore.io/c/lethal-company/p/RickArg/Helmet_Cameras)             |
| [HookGenPatcher](https://github.com/harbingerofme/Bepinex.Monomod.HookGenPatcher)          | v0.0.5  | Evaisa          | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/HookGenPatcher)              |
| HotbarPlus                                                                                 | v1.5.1  | FlipMods        | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/HotbarPlus)                |
| [JesterFree](https://github.com/AriDeve/JesterFree)                                        | v2.0.0  | AriDev          | [thunderstore](https://thunderstore.io/c/lethal-company/p/AriDev/JesterFree)                  |
| [JetpackWarning](https://github.com/Hamunii/JetpackWarning)                                | v2.2.0  | Hamunii         | [thunderstore](https://thunderstore.io/c/lethal-company/p/Hamunii/JetpackWarning)             |
| [LateCompany](https://github.com/ANormalTwig/LC-LateCompany)                               | v1.0.10 | anormaltwig     | [thunderstore](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany)            |
| [LC_API](https://github.com/steven4547466/LC-API)                                          | v3.3.2  | 2018            | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API)                        |
| [LCSoundTool](https://github.com/no00ob/LCSoundTool)                                       | v1.4.0  | no00ob          | [thunderstore](https://thunderstore.io/c/lethal-company/p/no00ob/LCSoundTool)                 |
| [LethalAutocomplete](https://github.com/IlyaChichkov/LethalAutocompleteMod)                | v0.4.1  | red_eye         | [thunderstore](https://thunderstore.io/c/lethal-company/p/red_eye/LethalAutocomplete)         |
| [LethalCompany_InputUtils](https://github.com/Rune580/LethalCompanyInputUtils)             | v0.4.4  | Rune580         | [thunderstore](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils)   |
| [LethalConfig](https://github.com/AinaVT/LethalConfig)                                     | v1.3.4  | AinaVT          | [thunderstore](https://thunderstore.io/c/lethal-company/p/AinaVT/LethalConfig)                |
| [LethalLib](https://github.com/EvaisaDev/LethalLib)                                        | v0.11.2 | Evaisa          | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalLib)                   |
| [LethalThings](https://github.com/EvaisaDev/LethalThings)                                  | v0.9.4  | Evaisa          | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalThings)                |
| LetMeLookDown                                                                              | v1.0.1  | FlipMods        | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/LetMeLookDown)             |
| MoreCompany                                                                                | v1.7.4  | notnotnotswipez | [thunderstore](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany)        |
| [More_Emotes](https://www.youtube.com/watch?v=GMgsFZ4rkEI)                                 | v1.3.3  | Sligili         | [thunderstore](https://thunderstore.io/c/lethal-company/p/Sligili/More_Emotes)                |
| MoreHead                                                                                   | v1.2.3  | Mhz             | [thunderstore](https://thunderstore.io/c/lethal-company/p/Mhz/MoreHead)                       |
| MoreItems                                                                                  | v1.0.2  | Drakorle        | [thunderstore](https://thunderstore.io/c/lethal-company/p/Drakorle/MoreItems)                 |
| [More_Suits](https://github.com/x753/Lethal-Company-More-Suits)                            | v1.4.1  | x753            | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/More_Suits)                    |
| [PersistentPurchases](https://github.com/NotSoEpic/PeristentPurchases)                     | v1.1.0  | TheBeeTeam      | [thunderstore](https://thunderstore.io/c/lethal-company/p/TheBeeTeam/PersistentPurchases)     |
| [Runtime_Netcode_Patcher](https://github.com/NicholasScott1337/RuntimeNetcodeRPCValidator) | v0.2.5  | Ozone           | [thunderstore](https://thunderstore.io/c/lethal-company/p/Ozone/Runtime_Netcode_Patcher)      |
| [ShipLoot](https://github.com/tinyhoot/ShipLoot)                                           | v1.0.0  | tinyhoot        | [thunderstore](https://thunderstore.io/c/lethal-company/p/tinyhoot/ShipLoot)                  |
| [Skinwalkers](https://rugbug.net/skinwalkers)                                              | v2.0.6  | RugbugRedfern   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RugbugRedfern/Skinwalkers)          |
| [SlimeTamingFix](https://github.com/EliteMasterEric/SlimeTamingFix)                        | v1.0.2  | EliteMasterEric | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/SlimeTamingFix)     |
| [SuitSaver](https://github.com/Hexnet111/SuitSaver)                                        | v1.1.4  | Hexnet111       | [thunderstore](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver)                |
| [TerminalApi](https://github.com/NotAtomicBomb/TerminalApi)                                | v1.5.0  | NotAtomicBomb   | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/TerminalApi)          |
| TooManySuits                                                                               | v1.0.5  | Verity          | [thunderstore](https://thunderstore.io/c/lethal-company/p/Verity/TooManySuits)                |
| YippeeMod                                                                                  | v1.2.3  | sunnobunno      | [thunderstore](https://thunderstore.io/c/lethal-company/p/sunnobunno/YippeeMod)               |
| YippeeScrap                                                                                | v1.0.5  | AinaVT          | [thunderstore](https://thunderstore.io/c/lethal-company/p/AinaVT/YippeeScrap)                 |

*Autogenerated using mod metadata downloaded via [thunderstore](https://thunderstore.io/c/lethal-company)*
