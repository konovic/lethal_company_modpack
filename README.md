# Lethal Company Modpack
Personal modpack for Lethal Company v45.\
All rights held by the respective mod authors.

---
## Installation Instructions
### LETHAL COMPANY:
Now updated for v45.\
If you previously opted into the `previous - The previous version` beta branch, you'll need to update to the `None` branch to be on the latest version:
1. Open Steam.
2. Right click Lethal Company and select `Properties`.
3. Under the `Betas` tab, select `None` and update the game.

These steps can be performed again to select the `previous - The previous version` branch for [playing on v40](https://github.com/konovic/lethal_company_modpack/releases/tag/v1.1.0).

<br>

### DOWNLOAD:
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `Source code (zip)`.

<br>

### INSTALL:
This guide assumes you're using a fresh install of Lethal Company (or updating this modpack). If you have a previous set of mods installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Unzip/open `lethal_company_modpack-<version>.zip`.
3. Move the contents of the `lethal_company_modpack-<version>\modpack` folder into the `Lethal Company` folder from step 1.\
Your `Lethal Company` folder should look like this:\
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

### UPDATE:
1. Locate and open the Lethal Company installation folder by opening Steam, right clicking on `Lethal Company`, scrolling over `Manage` and clicking on `Browse Local Files`.
2. Skip this step if you have not modified any files in `BepInEx\config`.
    1. Backup your `BepInEx\config` folder to a temporary safe location e.g. the desktop.
3. Skip this step if you have not modified any files in `BepInEx\plugins`.
    1. Backup any folders with manual modifications (e.g. `BepInEx\plugins\moresuits` if you added a `!less-suits.txt` file).
4. Delete the existing `BepInEx` folder.
5. Follow the steps for `INSTALL` as above.
6. If you performed step 2, copy the `config` folder back into the `Lethal Company\BepInEx` folder.
7. If you performed step 3, restore any additional files/folders. Take care when copying files from older mod versions to newer mod versions.

---
## Mod List
### Mods
| Mod/Plugin              | Version | Source                                                                                       |
| ----------------------- |:-------:|:--------------------------------------------------------------------------------------------:|
| Coroner                 | 1.4.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/Coroner/)          |
| FlashlightToggle        | 1.4.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Renegades/FlashlightToggle/)       |
| CirnoFumoScrap          | 1.2.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Badham_Mods/CirnoFumoScrap/)       |
| HelmetCamera            | 2.1.5   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RickArg/Helmet_Cameras/)           |
| HotbarTweaks            | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Straky/HotbarTweaks/)              |
| JesterFree              | 2.0.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/AriDev/JesterFree/)                |
| LateCompany             | 1.0.6   | [thunderstore](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany/)          |
| LetMeLookDown           | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/LetMeLookDown/)           |
| Mimics                  | 2.2.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/Mimics/)                      |
| MoreCompany             | 1.7.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany/)      |
| MoreEmotes              | 1.2.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Sligili/More_Emotes/)              |
| MoreSuits               | 1.4.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/)                  |
| PersistentPurchases     | 1.2.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/TheBeeTeam/PersistentPurchases/)   |
| ScalingStartCredits     | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/sunnobunno/ScalingStartCredits/)   |
| ShipLoot                | 1.0.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/tinyhoot/ShipLoot/)                |
| Skinwalkers             | 2.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RugbugRedfern/Skinwalkers/)        |
| SlimeTamingFix          | 1.0.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/EliteMasterEric/SlimeTamingFix/)   |
| SuitSaver               | 1.1.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Hexnet111/SuitSaver/)              |
| TerminalHistory         | 1.0.4   | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/Terminal_History/)   |
| YippeeMod               | 1.2.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/sunnobunno/YippeeMod/)             |
| YippeeScrap             | 1.0.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/AinaVT/YippeeScrap/)               |

### Libraries
| Library                 | Version | Source                                                                                       |
| ----------------------- |:-------:|:--------------------------------------------------------------------------------------------:|
| BepInEx                 | 5.4.22  | [github](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.22)                            |
| HookGenPatcher          | 0.0.5   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/HookGenPatcher/)            |
| LC\_API                 | 2.2.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API/)                      |
| LCSoundTool             | 1.4.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/no00ob/LCSoundTool/)               |
| LethalCompanyInputUtils | 0.4.3   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Rune580/LethalCompany_InputUtils/) |
| LethalLib               | 0.7.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Evaisa/LethalLib/)                 |
| TerminalApi             | 1.4.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/NotAtomicBomb/TerminalApi/)        |
