# American Truck Simulator Mod List

> [!WARNING]
> **Disclaimer:** Modding any game comes with its own risks. I am not the creator of any of these mods. Mods can and sometimes will break on a game update. It is best to prevent automatic updates to avoid mods breaking until they are patched.
>
> This guide is provided as-is. I will not provide support for game file corruption, game breakage, & performance issues.
>
> If you want other mods supported, please create an issue, and if you can, a pull request too.

## Installation

### Step 1: Download and import the mods (must download all)
  1. Steam workshop:
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
        3. Navigate to `C:\Users\<YOUR USER>\Documents\American Truck Simulator\mods`
        4. Paste all of the `.scs` mod files into the mod folder

### Step 2: Career
To import the mod load order there are 2 methods.

- New Career (recommended):
  > Creates a new career that is separate from your main career. This method does not affect your current mods, XP, money, and progress in your current career. Useful for having a dedicated career for multiplayer.
  > If you want to start from the beginning then delete the save files
  1. Download the repo in a zip format [main.zip](https://github.com/BigFlubba/truck-sim-mods/archive/refs/heads/main.zip)
  2. Navigate to your downloads folder
  3. Extract `truck-sim-mods-main.zip`
  4. Navigate to `\truck-sim-mods-main\truck-sim-mods-main\career`
  5. Copy the new career/profile folder from your downloads folder into `C:\Users\<YOUR USER>\Documents\American Truck Simulator\profiles`
  6. From your existing career, take and copy the following files into the new careers profile folder, replacing the existing files (optional, but converts all of your key-binds and game settings over to your new career)
     - `config.cfg`
     - `config_local.cfg`
     - `controls.sii`
     - `gearbox_layout_eaton_10.sii`
     - `gearbox_layout_eaton_13.sii`
     - `gearbox_layout_eaton_18.sii`

- Add to existing career:
  > Adds the new mods to your existing career. This method will require manual tuning.
  1. Backup your existing career (optional, but recommended)
     1. Navigate to `C:\Users\<YOUR USER>\Documents\American Truck Simulator\profiles`
     2. Copy your current profile and save it to `C:\Users\<YOUR USER>\Desktop\American Truck Simulator Profile Backup`
  2. Disable Steam Cloud (if enabled)
     1. Launch the game
     2. Click on your career
     3. Edit career
     4. Disable Steam cloud
     5. Confirm all of the prompts
     6. Close the game
  3. Navigate to `C:\Users\<YOUR USER>\Documents\American Truck Simulator\profiles\YOUR PROFILE ID\profile.sii`
  4. Upload the sii file to [Sii Decode](https://sii-decode.github.io/) and decode it
  5. Download the decoded `profile.sii` file
  6. In your preferred text editor add these following lines and replacing ` active_mods: COUNT` line with the new one.

     ##### Note: If you have existing mods in your current career, this will disable all of them and remove their order. You must either manually enable them and set their order, or edit your `profile.sii` file
     
     ```sii
      active_mods: 57
      active_mods[0]: "mod_workshop_package.0000000084D9C438|Tempest Night Background Mod v1.3 (by Frkn64)"
      active_mods[1]: "mod_workshop_package.0000000036A08487|BigT Britax LED Beacons Pack"
      active_mods[2]: "mod_workshop_package.000000008A17812D|Real companies, gas stations & billboards"
      active_mods[3]: "mod_workshop_package.000000009F8E1B98|Interior Rotate Camera"
      active_mods[4]: "mod_workshop_package.0000000026E9432E|Realistic Mirror FOV (1.43)"
      active_mods[5]: "mod_workshop_package.000000004851687F|500k HP Engine Plus 9 Gear High Speed Transmisson"
      active_mods[6]: "mod_workshop_package.00000000A809C6A6|Icons!"
      active_mods[7]: "mod_workshop_package.000000003165AFBA|Camera Range Enhancement"
      active_mods[8]: "mod_workshop_package.000000004A5BD438|Actual Day-/Night times"
      active_mods[9]: "mod_workshop_package.000000006A66C1A1|Realistic short sound when refueling"
      active_mods[10]: "mod_workshop_package.0000000099EF81C2|Tire Whine & Gravel Sound Mod"
      active_mods[11]: "mod_workshop_package.000000009E4430C1|Reefer trailer sound addon for ATS"
      active_mods[12]: "mod_workshop_package.000000003182EB0E|Sound Fixes Pack v22.50 - ATS"
      active_mods[13]: "mod_workshop_package.000000009CF6E110|JC Amateur Sound Effects Pack"
      active_mods[14]: "mod_workshop_package.00000000882A41B1|Real Sound Peterbilt 389 1998 Detroit Series 60"
      active_mods[15]: "mod_workshop_package.00000000AA1C4059|Road Train - Big Edition [1.9.2]"
      active_mods[16]: "mod_workshop_package.000000002C52864A|No Damage v1.49"
      active_mods[17]: "mod_workshop_package.000000009A76B105|Red pulsating road barriers"
      active_mods[18]: "military_cargo_pack_by_Jazzycat_v1.5.6_ats|Military Cargo Pack by Jazzycat v1.5.6"
      active_mods[19]: "Oshkosh_HEMTT_ATS_1.49|Oshkosh Defense HEMTT A4"
      active_mods[20]: "New_Road_Textures_v3.2.2|New Road Textures"
      active_mods[21]: "overweight_trailers_and_cargo_pack_by_Jazzycat_v6.1.5_ats|Overweight Trailers & Cargo Pack by Jazzycat v6.1.5"
      active_mods[22]: "trailers_and_cargo_pack_by_Jazzycat_v616_ats_modland|Trailers & Cargo Pack by Jazzycat v6.1.6"
      active_mods[23]: "mod_workshop_package.00000000C7685763|Peterbilt 389 Add-ons"
      active_mods[24]: "naviATS|naviATS"
      active_mods[25]: "mod_workshop_package.000000009A0AF7CD|Super Engine & Transmission (Original ATS trucks)"
      active_mods[26]: "mod_workshop_package.0000000083C0C8C8|Runaway Demon"
      active_mods[27]: "mod_workshop_package.000000004D431C63|SiSL's Trailer Pack USA"
      active_mods[28]: "mod_workshop_package.0000000026E02B47|SiSL's Mega Pack"
      active_mods[29]: "mod_workshop_package.0000000026CE823E|[SCR] Smarty's Wheel Pack"
      active_mods[30]: "mod_workshop_package.00000000A4703EC4|[SCR] Timpte Super Seal"
      active_mods[31]: "mod_workshop_package.0000000060240815|[HIATUS] Multiple TPD Chassis+Axle Options"
      active_mods[32]: "mod_workshop_package.00000000737B7EBF|Yandex.Navigator - All voices"
      active_mods[33]: "mod_workshop_package.000000007D844B6A|Variable Message Sign Boards"
      active_mods[34]: "mod_workshop_package.00000000A11B98EF|Western Star and Freightliner Cascadia Improved Dashboards"
      active_mods[35]: "mod_workshop_package.0000000077B69781|Expanded Trailer Combinations"
      active_mods[36]: "mod_workshop_package.00000000A17C6DFD|Full Screen Map for ATS 16:9"
      active_mods[37]: "mod_workshop_package.000000009718F718|Engine Sound Pack"
      active_mods[38]: "mod_workshop_package.0000000037F2C35C|Accessory Parts for SCS Trucks"
      active_mods[39]: "mod_workshop_package.0000000098883E87|International HX520 2022"
      active_mods[40]: "mod_workshop_package.000000009FCB2B1B|Real Soundproofing"
      active_mods[41]: "mod_workshop_package.00000000817D43A0|No Limits Mod v1.4 for Special Transport DLC"
      active_mods[42]: "mod_workshop_package.0000000027E31B67|SiSL's Mega Pack Addon: Traffic"
      active_mods[43]: "mod_workshop_package.000000009AE08614|WorldMap Satellite Background"
      active_mods[44]: "mod_workshop_package.00000000268A2C89|Real Tires Mod"
      active_mods[45]: "mod_workshop_package.00000000B76D591A|Better Tire Grip"
      active_mods[46]: "mod_workshop_package.000000008AC03F98|Traffic Trucks Smoke"
      active_mods[47]: "mod_workshop_package.000000008AB08D33|Smoke in my Trucks"
      active_mods[48]: "mod_workshop_package.00000000DE9C7F52|Extra City Police Vehicles"
      active_mods[49]: "mod_workshop_package.00000000DF702AFD|Generic Police Removal (GPR)"
      active_mods[50]: "mod_workshop_package.0000000048513970|Real Traffic Density ATS"
      active_mods[51]: "mod_workshop_package.00000000624B58FF|Sisl CB Radio with better swing"
      active_mods[52]: "mod_workshop_package.0000000098F7ECA6|Interior Cabin Lights (ATS)"
      active_mods[53]: "better_flares_v4.5.2_base|Better Flares v4.5.2 - Base"
      active_mods[54]: "mod_workshop_package.00000000B34711E7|Realistic Graphics Mod"
      active_mods[55]: "mod_workshop_package.00000000865C8FDE|Realistic Truck Physics Mod v9.1.3 (by Frkn64)"
      active_mods[56]: "better_flares_v4.5.2_dot_n|Better Flares v4.5.2 - Headlights DOT Neutral"
     ```
   7. Save the `profile.sii` file

### Step 3: Edit your game settings

In order to take advantage of some of the mods you will need to change some game and graphics settings. Changing some of these settings will impact performance, but allows the mods to work.

1. Graphics settings
   1. Disable SSAO (required by )
   2. Enable lighting distance
