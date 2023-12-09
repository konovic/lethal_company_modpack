## Lethal Company Modpack
Personal modpack for Lethal Company update 44.  
All rights held by the respective mod authors.

## Mod List
| Mod/Plugin       | Version | Source                                                                                  |
| ---------------- |:-------:|:---------------------------------------------------------------------------------------:|
| BepInEx          | 5.4.22  | [github](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.22)                       |
| FlashlightToggle | 1.3.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Renegades/FlashlightToggle/)  |
| HelmetCamera     | 2.1.3   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RickArg/Helmet_Cameras/)      |
| HotbarTweaks     | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Straky/HotbarTweaks/)         |
| LC\_API          | 2.1.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API/)                 |
| LateCompany      | 1.0.4   | [thunderstore](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany/)     |
| LetMeLookDown    | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/LetMeLookDown/)      |
| Mimics           | 1.1.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/Mimics/)                 |
| MoreCompany      | 1.7.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany/) |
| MoreEmotes       | 1.1.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Sligili/More_Emotes/)         |
| MoreSuits        | 1.3.3   | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/)             |
| ShipLoot         | 1.0.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/tinyhoot/ShipLoot/)           |
| Skinwalkers      | 1.0.7   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RugbugRedfern/Skinwalkers/)   |

## Installation Instructions

#### LETHAL COMPANY:
Ensure you're running the [previous] branch on Steam (update 44).
1. Open Steam
2. Right click Lethal Company and select Properties
3. Under the `Betas` tab, select `previous - The previous version` and update the game

#### DOWNLOAD:
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `Source code (zip)`.

#### INSTALL:
This guide assumes you're using a fresh install of Lethal Company. If you have a previous set of mods installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder (default: `C:\Program Files (x86)\Steam\steamapps\common\Lethal Company`).  
Alternatively, open Steam, right click Lethal Company, go to Manage -> Browse local files)
2. Unzip/open `lethal_company_modpack-*.zip`.
3. Move the contents of the `modpack` folder into the `Lethal Company` folder from step 1.
4. (Optional) Configure each mod by editing the config files in `BepInEx/config`.

#### UPDATE:
1. Locate and open the Lethal Company installation folder (default: `C:\Program Files (x86)\Steam\steamapps\common\Lethal Company`).
2. Skip this step if you have not modified any files in `BepInEx\config`
    1. Backup your `BepInEx\config` folder to a temporary safe location e.g. the desktop (failing to do so will revert all configs to their default values).
3. Skip this step if you have not modified any files in `BepInEx\plugins`
    1. Backup any folders with manual modifications, for example `BepInEx\plugins\moresuits` if you added a `!less-suits.txt` file.
4. Delete the existing `BepInEx` folder and everything within it.
5. Follow the steps for `INSTALL` as above.
6. If you performed step 2, copy the `config` folder back into the `Lethal Company\BepInEx` folder.  
Note: I'll try to make a note in the `Releases` section if I notice that a mod config has new/updated values. In that case, you would want to manually edit the new config's updated values.
7. If you performed step 3, restore any additional files/folders. Take care when overwriting files from newer mod versions.
