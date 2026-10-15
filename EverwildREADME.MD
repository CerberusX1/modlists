
<div align="center">
  <img src="https://github.com/CerberusX1/modlists/blob/main/Arcadia%20Everwild_%20Epic%20Mountain%20Realm.webp" alt="Modlist Banner" width="800"
</div>



# Everwild Table of Contents

- [**How to Clean Instal1**](#CleanInstall)
- [**How to Configure PageFile**](#PageFile)
- [**How to Install**](#Installing)
- [**How to Keep your Save Stable**](#SafePlaying)

## CleanInstall

Step 1: Uninstall via Steam

1. Open your Steam Library.
2. Right-click The Elder Scrolls V: Skyrim (or Special Edition), hover over Manage, and click Uninstall.

Step 2: Delete Residual Game and Mod Folders

Even after uninstalling through Steam, leftover files and mod configurations remain and can cause bugs. Manually delete the following directories:
• Steam Game Folder: Navigate to ..\\Steam\\steamapps\\common and delete the Skyrim or Skyrim Special Edition folder.
• Documents Folder: Navigate to C:\\Users\\[Your User Account]\\Documents\\My Games and delete the Skyrim or Skyrim Special Edition folder.
• Local AppData: Press Windows Key + R, type appdata, hit Enter, open the Local folder, and delete the Skyrim or Skyrim Special Edition folder.
• Mod Managers: Delete any leftover mod manager folders (such as Vortex or Mod Organizer 2) in your AppData directories if you are resetting your setup.

Step 3: Reinstall the Game

1. Go back to your Steam Library and click Install on Skyrim.
2. Avoid installing the game into the C:\\Program Files or C:\\Program Files (x86) directories to prevent Windows permission issues with mods.
3. Launch the game once from Steam to let it generate fresh configuration files, then download all owned creations, then close it

### PageFile


To improve system stability (specially if you have only 16 gb of RAM) you need to setup the page file system for the drive you are running Everwild on.

To do this hit Windows keyboard key and R key simultaneously, type sysdm.cpl and click OK

Select Advanced tab and under Performance click on Settings

Select Advanced tab and click on Change

Uncheck Automatically manage page file size for all drives

Select the drive where Nolvus is installed and click on Custom size

Set the page file size from 20000 minimum to 40000 maximum and click on Set

Don't forget that the size you set will be taken as used space on your drive.

Click on OK (a reboot will be required)

#### Installing

Step 1 Launch Wabbajack

Step 2 Navigate to browse modlists, the select skyrim from the list of games.

step 3 locate Everwild and click on it, hit download.

step 4 set the location for the install, downloads should auto fill, hit install.

step 5 when finished downloading, launch mo2 from the specifiec folder and launch mo2 (optionaly right click send to desktop for shortcut)

step 6 make sure everwild is selected in the drop down and hit play.

#### SafePlaying

🔀 Avoid Alt+Tabbing
🚫 Avoid loading saves mid-session
📂 Practice safe saving (disable autosaves, save only during calm moments)
⚡ Quit other resource-hungry apps before launching your modlist
🖼️ Keep your graphics driver reasonably current, but test each update—if a new driver causes issues, roll back to the last stable version that worked well for you.
🔥 Return any overclocked hardware (usually excluding RAM using XMP or AMD EXPO) to stock speeds
👉 💾 Set your Windows Pagefile to 40,000 min and max (especially for 16GB of RAM or less).
😐 Averaging less than one crash in 4 hours usually isn't a major concern for any heavily modded Skyrim
