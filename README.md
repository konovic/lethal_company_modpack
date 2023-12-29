# Lethal Company Modpack
Personal modpack for Lethal Company v45.\
All rights held by the respective mod authors.

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

#### r2modman
[r2modman](https://thunderstore.io/c/lethal-company/p/ebkr/r2modman/) is a mod manager that downloads and manages mods for you. It will automatically query thunderstore.io for mod updates and download them as they happen, keeping your mods up to date for you.
To install using r2modman:
1. If you haven't done so already: download r2modman above, install, and launch it.
2. Select Lethal Company from the game selection screen.
3. Import a new profile from a code, and paste the code below:\
`018cb734-451b-4a40-a148-2973ffa089b8`
4. Choose a name for your modpack profile and let it update.
You can now launch Lethal Company with mods directly from r2modman (requires owning the game on Steam).
##### Update:
r2modman will keep your mods up to date. If this modpack adds or removes mods, these changes can be updated in your existing profile.
1. Select Lethal Company from the game selection screen.
2. Click `Import/Update`, then `Update existing profile`, then `From code`.
3. Copy and paste the code above for most up-to-date version of this modpack.
4. Select the correct profile from the drop-down list and click `Update profile`.

---
#### Manual
##### Download:
Navigate to the [latest release](https://github.com/konovic/lethal_company_modpack/releases/latest) for this repository and download `Source code (zip)`.

<br>

##### Install:
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

##### Update:
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
## Mod List
```
BepInEx-BepInExPack-5.4.2100
EliteMasterEric-Coroner-1.5.0
Rune580-LethalCompany_InputUtils-0.4.4
Renegades-FlashlightToggle-1.5.0
Evaisa-HookGenPatcher-0.0.5
Evaisa-LethalLib-0.9.0
Badham_Mods-CirnoFumoScrap-1.2.1
RickArg-Helmet_Cameras-2.1.5
Straky-HotbarTweaks-1.0.1
no00ob-LCSoundTool-1.4.0
AriDev-JesterFree-2.0.0
anormaltwig-LateCompany-1.0.7
FlipMods-LetMeLookDown-1.0.1
x753-Mimics-2.3.0
notnotnotswipez-MoreCompany-1.7.2
Sligili-More_Emotes-1.2.2
x753-More_Suits-1.4.1
TheBeeTeam-PersistentPurchases-1.2.0
sunnobunno-ScalingStartCredits-1.0.1
tinyhoot-ShipLoot-1.0.0
RugbugRedfern-Skinwalkers-2.0.1
EliteMasterEric-SlimeTamingFix-1.0.2
Hexnet111-SuitSaver-1.1.2
NotAtomicBomb-TerminalApi-1.4.0
deemodev-TerminalHistory-1.0.0
sunnobunno-YippeeMod-1.2.2
AinaVT-YippeeScrap-1.0.0
2018-LC_API-3.1.0
Mhz-MoreHead-1.2.2
darmuh-ghostCodes-1.1.0
Badham_Mods-SCPFoundationDungeon-1.3.1
Clementinise-CustomSounds-2.2.0
JacuJ-Memetastic-1.0.4
```
