## Lethal Company Modpack
Personal modpack for Lethal Company v45.  
All rights held by the respective mod authors.

## Installation Instructions

#### LETHAL COMPANY:
Now updated for v45. If you previously opted into the `previous - The previous version` beta branch, you'll need to update to the `None` branch to be on the latest version.
1. Open Steam
2. Right click Lethal Company and select `Properties`
3. Under the `Betas` tab, select `None` and update the game
These steps can be performed again to select the `previous - The previous version` branch for [playing on v40](https://github.com/konovic/lethal_company_modpack/releases/tag/v1.1.0)  
See the [release notes](https://github.com/konovic/lethal_company_modpack/releases/latest) for information about changes to mod configurations when updating this pack.

#### DOWNLOAD:
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `Source code (zip)`.

#### INSTALL:
This guide assumes you're using a fresh install of Lethal Company (or updating this modpack). If you have a previous set of mods installed, backup your `BepInEx` folder somewhere else and remove it from the `Lethal Company` folder.
1. Locate and open the Lethal Company installation folder (default: `C:\Program Files (x86)\Steam\steamapps\common\Lethal Company`).  
This can also be located by opening Steam, right clicking on Lethal Company, scrolling over `Manage` and clicking on `Browse Local Files`
2. Unzip/open `lethal_company_modpack-<version>.zip`.
3. Move the contents of the `lethal_company_mods-<version>\modpack` folder into the `Lethal Company` folder from step 1.  
This should only be the folder `BepInEx` and the two files `doorstop_config.ini` and `winhttp.dll`. These go directly into the `Lethal Company` folder, not a subfolder.  
Your `Lethal Company` folder should look like this:  
```
Lethal Company\BepInEx
Lethal Company\doorstop_config.ini
Lethal Company\winhttp.dll
Lethal Company\<all other base game files>
```
4. (Optional) Configure each mod by editing the config files in `BepInEx\config`.
5. For Proton/Steamdeck users only: BepInEx works with Proton by adding  
`WINEDLLOVERRIDES="winhttp.dll=n,b" %command%`  
to Lethal Company's Steam launch options

#### UPDATE:
1. Locate and open the Lethal Company installation folder (default: `C:\Program Files (x86)\Steam\steamapps\common\Lethal Company`).  
This can also be located by opening Steam, right clicking on Lethal Company, scrolling over `Manage` and clicking on `Browse Local Files`
2. Skip this step if you have not modified any files in `BepInEx\config`
    1. Backup your `BepInEx\config` folder to a temporary safe location e.g. the desktop (failing to do so will revert all configs to their default values).
3. Skip this step if you have not modified any files in `BepInEx\plugins`
    1. Backup any folders with manual modifications, for example `BepInEx\plugins\moresuits` if you added a `!less-suits.txt` file.
4. Delete the existing `BepInEx` folder and everything within it.
5. Follow the steps for `INSTALL` as above.
6. If you performed step 2, copy the `config` folder back into the `Lethal Company\BepInEx` folder.  
Note: I'll try to make a note in the `Releases` section if I notice that a mod config has new/updated values. In that case, follow those instructions for updating the new config.
7. If you performed step 3, restore any additional files/folders. Take care when copying files from older mod versions to newer mod versions.

## Mod List
| Mod/Plugin       | Version | Source                                                                                  |
| ---------------- |:-------:|:---------------------------------------------------------------------------------------:|
| BepInEx          | 5.4.22  | [github](https://github.com/BepInEx/BepInEx/releases/tag/v5.4.22)                       |
| FlashlightToggle | 1.4.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Renegades/FlashlightToggle/)  |
| HelmetCamera     | 2.1.5   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RickArg/Helmet_Cameras/)      |
| HotbarTweaks     | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Straky/HotbarTweaks/)         |
| LC\_API          | 2.2.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/2018/LC_API/)                 |
| LateCompany      | 1.0.6   | [thunderstore](https://thunderstore.io/c/lethal-company/p/anormaltwig/LateCompany/)     |
| LetMeLookDown    | 1.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/FlipMods/LetMeLookDown/)      |
| Mimics           | 2.2.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/Mimics/)                 |
| MoreCompany      | 1.7.2   | [thunderstore](https://thunderstore.io/c/lethal-company/p/notnotnotswipez/MoreCompany/) |
| MoreEmotes       | 1.2.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/Sligili/More_Emotes/)         |
| MoreSuits        | 1.4.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/x753/More_Suits/)             |
| ShipLoot         | 1.0.0   | [thunderstore](https://thunderstore.io/c/lethal-company/p/tinyhoot/ShipLoot/)           |
| Skinwalkers      | 2.0.1   | [thunderstore](https://thunderstore.io/c/lethal-company/p/RugbugRedfern/Skinwalkers/)   |
