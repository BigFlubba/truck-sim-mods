<div align="center">
  
# Big Flubba's American Truck Simulator Mod Guide & List

</div>

> [!CAUTION]
> Modding any game comes with its own risks. Mods can, and sometimes will, break after a game update. It is best to prevent automatic updates to avoid mods breaking until they are patched.
>
> This guide is provided as-is. I will not provide support for game file corruption, game breakage, & performance issues.

> [!IMPORTANT]
> All mods and other tools listed in this guide belong to their respective owners. I'm not the creator of any of these mods or tools. Some save files and careers have been modified for my preferences.
> 
> If you want other mods supported, please create an issue, and if you can, a pull request too.

---

## Installation

> [!CAUTION]
> This guide has only been tested on ATS `v1.60` (64-bit DX11)
>
> This guide, careers, saves, & mods may work on earlier versions, but support for any other version will not be available (including VR). I tried to keep compatibility as broad as possible, but mod and career support for other versions are out of my control.

### Step 1: Download and import the mods (must download all) (required)
  1. Steam Workshop:
     1. Subscribe to the entire mod list [Flubba's Steam Workshop Mod List](https://steamcommunity.com/sharedfiles/filedetails?id=3797669251)

  2. Manual:
     1. Download the mods:
        - []()
        - []()
        - []()
        - []()
        - []()
     1. Import the mods:
        1. Navigate to your downloads folder
        2. Extract all of the mod `.zip` files
        3. Navigate to your documents folder `\American Truck Simulator\mods`
        4. Paste all of the `.scs` mod files into the mod folder
       
---

### Step 2: Career
To import the mod load order, there are a few methods. `profile.sii` & a save file are required to import the order. This, in turn, will create a new career.

- New Career (recommended):
  > Creates a new career that is separate from your main career. This method does not affect your current mods, XP, money, and progress in your current career. Useful for having a dedicated career for multiplayer.
  > If you want to start from the beginning, then delete the save files
  
  1. Download the repo in a zip format [main.zip](https://github.com/BigFlubba/truck-sim-mods/archive/refs/heads/main.zip)
  2. Navigate to your downloads folder
  3. Extract `truck-sim-mods-main.zip`
  4. Navigate to `\truck-sim-mods-main\truck-sim-mods-main\ATS\careers\new` 
  6. Copy the new career/profile folder from your downloads folder into your documents folder `\American Truck Simulator\profiles`
  7. From your existing career, take and copy the following files into the new career profile folder, replacing the existing files (optional, but converts all of your key-binds and game settings over to your new career)
     - `config.cfg`
     - `config_local.cfg`
     - `controls.sii`
     - `gearbox_layout_eaton_10.sii`
     - `gearbox_layout_eaton_13.sii`
     - `gearbox_layout_eaton_18.sii`

- Add to existing career:
[see add-to-existing career README]()

---

### Step 3: Edit your game settings

In order to take advantage of some of the mods, you will need to change some game and graphics settings. Changing some of these settings will impact performance, but allows the mods to work.

1. Graphics settings
   1. Disable SSAO (required by )
   2. Enable lighting distance
