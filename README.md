# Lethal Company Modpack
Personal modpack for Lethal Company v45.\
All rights held by the respective mod authors.

#### A note about r2modman
r2modman support has been dropped as it added extra complexity and stability issues between those installing manually and those using the mod manager.\
For stability purposes, it is highly recommended that everybody follow the manual installation.\
I apologize for any inconvenience, and thank you for you understanding.

#### A note about CustomSounds
A minor technical detail is that r2modman was previously installing CustomSounds mods into legacy locations rather than the correct CustomSounds mod folder.\
Despite being installed in the correct location now, there appears to be an occasional bug that requires the game to be loaded twice before the sounds start working.\
This will not have any real impact on gameplay.

---
## Installation Instructions
### LETHAL COMPANY
Now updated for v45.\
If you previously opted into the `previous - The previous version` beta branch, you'll need to update to the `None` branch to be on the latest version:
1. Open Steam.
2. Right click Lethal Company and select `Properties`.
3. Under the `Betas` tab, select `None` and update the game.

These steps can be performed again to select the `previous - The previous version` branch for [playing on v40](https://github.com/konovic/lethal_company_modpack/releases/tag/v1.1.0).

<br>

### INSTALL

#### Download:
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `Source code (zip)`.

<br>

#### Install:
This guide assumes you're using a fresh install of Lethal Company (or updating this modpack). If you have a previous set of mods installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Unzip/open `lethal_company_modpack-<version>.zip`.
3. Move the contents of the `lethal_company_modpack-<version>\modpack` folder into the `Lethal Company` folder from step 1.\
Your `Lethal Company` folder should look like this:
```
Lethal Company\BepInEx
Lethal Company\doorstop_config.ini
Lethal Company\winhttp.dll
Lethal Company\<all other base game files>
```
4. (Optional) Configure each mod by launching the game once, then editing the config files in `BepInEx\config`.
5. For Proton/Steamdeck users only: BepInEx works with Proton by adding\
`WINEDLLOVERRIDES="winhttp.dll=n,b" %command%`\
to Lethal Company's Steam launch options.

<br>

#### Update:
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Skip this step if you have not modified any files in `BepInEx\config`.
    1. Backup your `BepInEx\config` folder to a temporary safe location e.g. the desktop.
3. Skip this step if you have not modified any files in `BepInEx\plugins`.
    1. Backup any folders with manual modifications (e.g. `BepInEx\plugins\x753-More_Suits\moresuits` if you added a `!less-suits.txt` file).
4. Delete the existing `BepInEx` folder.
5. Follow the steps for `INSTALL` as above.
6. If you performed step 2, copy the `config` folder back into the `Lethal Company\BepInEx` folder.
7. If you performed step 3, restore any additional files/folders. Take care when copying files from older mod versions to newer mod versions.

---
| Mod/Plugin                                                                                 | Version | Author          |
| ------------------------------------------------------------------------------------------ | ------- | --------------- |
| [BepInEx](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.21)                         | v5.4.21 | Various         |
| [CirnoFumoScrap](https://github.com/Badhamknibbs/Cirno-Fumo-Scrap-mod_LC)                  | v1.2.1  | Badham_Mods     |
| [Coroner](https://github.com/EliteMasterEric/Coroner)                                      | v1.5.3  | EliteMasterEric |
| [CustomSounds](https://github.com/clementinise/CustomSounds)                               | v2.2.0  | Clementinise    |
| DraculaFlowBug                                                                             | v1.2.0  | KlippKlubben    |
| [FastSwitchPlayerViewInRadar](https://github.com/kRYstall9/FastSwitchPlayerViewInRadarMOD) | v1.3.2  | kRYstall9       |
| [FlashlightToggle](https://github.com/redassser/Lc-Flashlight)                             | v1.5.0  | Renegades       |
| [ghostCodes](https://github.com/darmuh/ghostcodes)                                         | v1.1.0  | darmuh          |
| [Helmet_Cameras](https://github.com/The0therOne/Helmet_Cameras)                            | v2.1.5  | RickArg         |
| [HookGenPatcher](https://github.com/harbingerofme/Bepinex.Monomod.HookGenPatcher)          | v0.0.5  | Evaisa          |
| [HotbarTweaks](https://straky.fr)                                                          | v1.0.1  | Straky          |
| [JesterFree](https://github.com/AriDeve/JesterFree)                                        | v2.0.0  | AriDev          |
| [JetpackWarning](https://github.com/Hamunii/JetpackWarning)                                | v2.2.0  | Hamunii         |
| [LateCompany](https://github.com/ANormalTwig/LC-LateCompany)                               | v1.0.9  | anormaltwig     |
| [LC_API](https://github.com/steven4547466/LC-API)                                          | v3.2.4  | 2018            |
| [LCSoundTool](https://github.com/no00ob/LCSoundTool)                                       | v1.4.0  | no00ob          |
| [LethalAutocomplete](https://github.com/IlyaChichkov/LethalAutocompleteMod)                | v0.4.0  | red_eye         |
| [LethalCompany_InputUtils](https://github.com/Rune580/LethalCompanyInputUtils)             | v0.4.4  | Rune580         |
| [LethalLib](https://github.com/EvaisaDev/LethalLib)                                        | v0.10.1 | Evaisa          |
| LetMeLookDown                                                                              | v1.0.1  | FlipMods        |
| [Mimics](https://github.com/x753/Lethal-Company-Mimics)                                    | v2.3.0  | x753            |
| MoreCompany                                                                                | v1.7.2  | notnotnotswipez |
| [More_Emotes](https://www.youtube.com/watch?v=nugrbr8dvvk)                                 | v1.2.2  | Sligili         |
| MoreHead                                                                                   | v1.2.2  | Mhz             |
| MoreItems                                                                                  | v1.0.1  | Drakorle        |
| [More_Suits](https://github.com/x753/Lethal-Company-More-Suits)                            | v1.4.1  | x753            |
| [PersistentPurchases](https://github.com/NotSoEpic/PeristentPurchases)                     | v1.2.0  | TheBeeTeam      |
| [ScalingStartCredits](https://github.com/sunnobunno/ScalingStartCredits)                   | v1.0.1  | sunnobunno      |
| [SCPFoundationDungeon](https://github.com/Badhamknibbs/SCPCB_DunGen_LC/)                   | v1.4.1  | Badham_Mods     |
| [ShipLoot](https://github.com/tinyhoot/ShipLoot)                                           | v1.0.0  | tinyhoot        |
| [Skinwalkers](https://rugbug.net/skinwalkers)                                              | v2.0.1  | RugbugRedfern   |
| SkipToMultiplayerMenu                                                                      | v1.0.0  | FlipMods        |
| [SlimeTamingFix](https://github.com/EliteMasterEric/SlimeTamingFix)                        | v1.0.2  | EliteMasterEric |
| [SuitSaver](https://github.com/Hexnet111/SuitSaver)                                        | v1.1.2  | Hexnet111       |
| [TerminalApi](https://github.com/NotAtomicBomb/TerminalApi)                                | v1.5.0  | NotAtomicBomb   |
| YippeeScrap                                                                                | v1.0.4  | AinaVT          |

*Autogenerated using mod metadata downloaded via [thunderstore](https://thunderstore.io/c/lethal-company)*
