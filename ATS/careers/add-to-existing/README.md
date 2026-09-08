> [!IMPORTANT]
> If you have existing mods in your current career, this will disable all of them and remove their order. You must either manually enable them and set their order, or edit your `profile.sii` file

## Add to existing career:
  > Adds the new mods to your existing career. This method will require manual tuning.
  
  1. Disable Steam Cloud (if enabled)
     1. Launch the game
     2. Click on your career (top right)
     3. Edit career
     4. Disable Steam Cloud Sync
     5. Confirm all of the prompts
     6. Close the game
  2. Back up your existing career (optional, but recommended)
     1. Navigate to your documents folder `\American Truck Simulator\profiles`
     2. Copy your current profile and save it to another directory of your choosing
  3. Navigate to your documents folder `\American Truck Simulator\profiles\YOUR PROFILE ID\profile.sii`
  4. Upload the sii file to [Sii Decode](https://sii-decode.github.io/) and decode it
  5. Download the decoded `profile.sii` file. I should download it as `profile-decoded.sii`; if not, it is fine
  6. Download or copy the raw text for [mod-load-order-profile.sii](https://github.com/BigFlubba/truck-sim-mods/main/ATS/careers/add-to-existing)
  7. In your preferred text editor, add the following lines and replace the ` active_mods: COUNT` line with the new one.
  8. Save the `profile.sii` file
  9. Rename the decoded `profile-decoded.sii` to `profile.sii`
  10. Rename the old original `profile.sii` file to `profile.sii.bak` to keep a backup of the original `profile.sii` file
  11. Add the new `profile.sii` file to your career's folder
