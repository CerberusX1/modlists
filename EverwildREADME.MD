
<div align="center">
  <img src="https://github.com/CerberusX1/modlists/blob/main/Arcadia%20Everwild_%20Epic%20Mountain%20Realm.webp" alt="Modlist Banner" width="800"
</div>



# Everwild Table of Contents

- [**How to Clean Instal - Section 1**](#CleanInstall)
- [**How to Configure PageFile - Section 1**](#PageFile)
- [**How to Configure PageFile - Section 1**](#PageFile)


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

