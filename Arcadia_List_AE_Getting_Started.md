# The Arcadia List AE: Getting Started Guide

A beginner-friendly walkthrough for installing, launching, and enjoying **The Arcadia List AE**, a Fallout 4 Anniversary Edition modlist for Wabbajack and Mod Organizer 2 (MO2).

---

## Table of Contents

1. [What Is The Arcadia List?](#what-is-the-arcadia-list)
2. [Before You Install](#before-you-install)
3. [Installing the List](#installing-the-list)
4. [Choosing a Profile: Normal vs. Survival](#choosing-a-profile-normal-vs-survival)
5. [Your First Launch](#your-first-launch)
6. [What's in the List](#whats-in-the-list)
7. [Sim Settlements 2 Warnings (Read This!)](#sim-settlements-2-warnings-read-this)
8. [Gameplay Tips for New Players](#gameplay-tips-for-new-players)
9. [Performance and Stability Tips](#performance-and-stability-tips)
10. [Troubleshooting](#troubleshooting)
11. [Updating and Adding Your Own Mods](#updating-and-adding-your-own-mods)
12. [Getting Help](#getting-help)

---

## What Is The Arcadia List?

The Arcadia List AE is a large Fallout 4 modlist by **SkyAurelia**, built for the Anniversary Edition and installed through Wabbajack. It contains roughly **400 enabled mods**, plus the Creation Club content and DLC that ship with the AE update.

At a glance, it focuses on:

- **Settlement building** with Sim Settlements 2 (SS2), Chapter 3, and a very large set of addon packs
- **Visuals**: HD retextures, an ENB, new weather and lighting, and a full UI overhaul
- **Combat and gear**: many new weapons and armors, tactical reloads, locational damage, and improved faction AI
- **New quests and locations**: Fourville, Gun For Hire, America Rising 2, and more
- **Stability fixes** and performance tools

The list ships as **two profiles** (Normal and Survival). See [Choosing a Profile](#choosing-a-profile-normal-vs-survival).

---

## Before You Install

### Requirements

- **Fallout 4 on Steam**, with a **clean install**
- **All DLC and Creation Club content** that comes with the Anniversary Edition update. The list needs these files, and Wabbajack will report them as missing if you do not own them.
- **Wabbajack** and a **Nexus Mods account**. A Nexus Premium membership makes large lists much faster to download. Without it, you have to click through each download manually.
- **Lots of free disk space** and a capable PC. This list includes many 2K and 4K textures plus an ENB, so a weaker system should plan on lowering settings.

### Do a clean install of Fallout 4

Old mods and leftover settings are the number one cause of broken modlist installs. To start fresh:

1. **Uninstall** Fallout 4 from Steam.
2. **Delete the game folder** manually, for example `Steam\steamapps\common\Fallout 4`.
3. **Delete your documents folder for the game**: `C:\Users\<you>\Documents\My Games\Fallout4`. This removes old saves and INI files.
4. *(Optional but recommended)* Delete `C:\Users\<you>\AppData\Local\Fallout4`.
5. **Reinstall** Fallout 4 from Steam.
6. **Launch the game once** and let it reach the main menu, then close it. This creates fresh INI files and lets Wabbajack find your game.

> **Tip:** Open Fallout 4 from Steam and make sure every AE DLC and Creation Club item has finished downloading before you start Wabbajack.

---

## Installing the List

1. **Download Wabbajack** from the official site and place `Wabbajack.exe` in its own folder in a simple location, such as `C:\Wabbajack`. Avoid protected folders like `Program Files` and `Desktop`.
2. **Download The Arcadia List** `.wabbajack` file from its Nexus Mods page (Nexus mod ID 101471, uploaded by SkyAurelia).
3. Open Wabbajack and choose **Load a Modlist from Disk**.
4. Select the `.wabbajack` file you downloaded.
5. Choose **install** and **download** locations on a drive with plenty of space. Use short, simple paths such as `C:\Modlists\Arcadia`, and keep them outside protected folders.
6. Click **Install** and wait. This can take a long time, especially without Premium.
7. If Wabbajack reports **missing files or failed downloads** at the end, download them manually into your downloads folder and **run the install again**.
8. When it finishes, open the install folder and run **the Arcadia List MO2 executable** (the `.exe` named after the list).

---

## Choosing a Profile: Normal vs. Survival

Arcadia includes two MO2 profiles. Select one in the profile drop-down at the top left of MO2 **before you start a new game**.

| | **Normal profile** | **Survival profile** |
|---|---|---|
| Intended for | Standard Fallout 4 difficulties | Playing on Survival difficulty |
| Mod count | About 399 enabled mods | About 404 enabled mods |
| Extra mods | n/a | Disk Cache Enabler, Achievements Enabler AE (F4SE), Sprint Stuttering Fix, Faster Workshop AE (F4SE), Enhanced Vanilla Water |

Everything else is shared between the two profiles. The load order differs slightly in a few places (some patches and the Survival separator sit in different spots), but the main content is the same.

### Pick one and stay with it

Saves, settings, and mod states belong to the profile you were using. **Do not switch profiles in the middle of a playthrough.** If you want to try the other one, start a new game.

### What Survival difficulty means in vanilla Fallout 4

If Survival is new to you, expect a harder game:

- You **cannot save freely**. Saving happens when you sleep in a bed.
- **Fast travel is disabled.** You walk, or use vertibirds and other in-game travel options.
- You must manage **hunger, thirst, and tiredness**, and you can catch **diseases**.
- **Damage is higher** for both you and your enemies.
- **Ammo has weight**, so carry capacity matters more.

If this is your first time in the Commonwealth, the **Normal profile** is the gentler start.

---

## Your First Launch

1. In MO2, choose your profile (Normal or Survival).
2. In the executable drop-down next to the **Run** button, select **F4SE** (Fallout 4 Script Extender). **Always launch the game this way**, never directly from Steam.
3. Click **Run**.
4. The list uses **custom main menus** (RandomMainMenu and Immersive Main Menus), so the menu may not look like vanilla. That is expected.
5. Open the **MCM** (Mod Configuration Menu) from the game's settings or pause menu to adjust mod options.
6. Create your character. The list includes **LooksMenu**, so you will have a much more detailed character creator.
7. The list includes **MS Fast Start - Skip Sanctuary Prologue**. Check that mod's Nexus page for exactly what it skips and what it changes at the start of the game.

> **Reminder:** For your first session, change as little as possible. Play for a while and learn the defaults before you start tweaking.

---

## What's in the List

A quick tour of the main categories. This is not every mod, only the ones you are most likely to notice. The full load order is visible in MO2's left pane, organized by separator.

### Core fixes and frameworks

F4SE, Unofficial Fallout 4 Patch (UFO4P), Previsibines Repair Pack (PRP), Addictol and Addictol Crash Logger, Address Library, Baka Framework, RobCo Patcher, Community Fixes Merged, Weapon Debris Crash Fix, Long Loading Times Fix, and many more. These work in the background to keep the game stable.

### Weapons and ammo

Munitions (ammo expansion), Tactical Reload, and Bullet Counted Reload (BCR), plus a very large selection of weapon mods: Commonwealth Weaponry, Fallout New Vegas ports, the Lavish Laser Collection, and many more. A big set of patches ties these together.

### Armor and power armor

Eli's Armour Compendium, Combat Armor Remanufacture, and many power armor variants (T-45, T-51, T-60, X-01, Ultracite, Hellcat, Tribal, and others), all with HD textures.

### Combat and AI

Better Locational Damage, Armor-Upgrade Overhaul, and AI tweaks. Enemy factions are improved by the **[Faction] Improved** series (Guards, BoS, Institute, Minutemen, Railroad, Nuka Raiders), plus Rags Pirates, Toms Bruisers, Grizzled Security, Random Encounter Framework, and Institute Technology Overhaul.

### Visuals and lighting

HD Retexture Project, FlaconOil's Complete Retexture Project, Luxor's HD LOD, True Grass, Vivid Waters, True Storms, Lightweight Lighting, Project Luminescence Commonwealth (PLC), and the **Visceral ENB**.

### User interface

The **FallUI** suite (HUD, map, workbench, item sorter, and more), Better Console, MCM Booster, and LooksMenu.

### Quests and locations

Fourville, Gun For Hire (Commonwealth Mercenary Jobs), The Fens Sheriff's Department, America Rising 2 (Legacy of the Enclave), Modding for Charity quests (Trunk's Malfunction and Shady Motives), The Wild Key Chase, and Ashland Station.

### Companions

Dogmeat - A True Companion, Heather Casdin, Deeper Thoughts - Curie, Loving Cait, Ellen the Cartographer, and Simple Everyone's Best Friend, among others.

### Quality of life and gameplay

Lootable Crates, Immersive Settlers, Settler Sandbox Expansion, Pip-Boy Flashlight, Power Armor HUD Enhanced, Reinforcements and Retribution, Realistic Death Physics, Explosion Reactions, Project Black Bird, Detailed Bunkers, and more.

### Settlements

Sim Settlements 2 with a large library of addon packs. This is important enough to have its own section, next.

---

## Sim Settlements 2 Warnings (Read This!)

Arcadia includes **Sim Settlements 2 (SS2) Chapter 3**, the Previsibines Expansion Pack, and a huge collection of addon packs. SS2 is a great way to build, but it can cause crashes if you ignore the points below.

### Do not pre-build with Zimonja

> **When pre-building, do not include Zimonja.** It can cause a bug with the Minutemen quest line.

### The "Triangle of Death"

This is a zone in Fallout 4 between **Sanctuary Hills**, **Abernathy Farm**, and the **Red Rocket Truck Stop**. In this area, the game can load the cells for **all three locations at the same time**. With SS2, your settlements can grow so large that loading all three at once **crashes the game** when you enter the zone.

### How to avoid it

1. **Prioritize one settlement.** Pick only one of the three to become a massive, high-level city (for example, Sanctuary).
2. **Keep the others small.** Use Red Rocket and Abernathy for small operations (a player home, small farms), or leave them at lower-level city plans.
3. **Use lighter city plans.** In SS2, use the City Planner's Desk to choose performance-friendly or low-poly city plans if you plan to build up all three.
4. **Avoid fast traveling directly into one of these locations.** Fast traveling straight in makes the crash more likely, because the game tries to load everything instantly. Walking in from outside the zone loads things more gradually. *(On the Survival profile, fast travel is already off, so this one mostly takes care of itself.)*
5. **Do not pre-build all three locations** with the pre-build system. Adjust the settings and pre-build only one or two of them.

### Author's preference (not a requirement)

> The following is a personal preference, not a rule. The list author prefers to **skip auto-build** and **set each city plan by hand as settlements are claimed**, and **never sets up a city plan at Red Rocket**. Use whatever approach you like.

### SS2 resources

For more help with SS2, visit the official site: <https://simsettlements2.com/>

---

## Gameplay Tips for New Players

- **Learn one system at a time.** Do not try to master SS2, the weapons, the UI, and the quests on day one.
- **Check the MCM.** Many mods have options in the Mod Configuration Menu. This is the best way to change settings safely, and it is usually safer than editing INI files.
- **Make multiple save files.** Rotate through several saves instead of overwriting one. Corrupted saves are much easier to recover from if you have older ones. *(Survival profile: you save by sleeping, so sleep regularly.)*
- **Do not rush at low level.** The faction, AI, and locational damage mods make enemies noticeably tougher and smarter than vanilla. Be prepared to use cover and retreat.
- **Expect many new weapons and armors.** Visit the workbenches and read the item names. Many weapons have different ammo types because of Munitions.
- **Read the notes on quest mods.** Quest mods like Fourville, Gun For Hire, and America Rising 2 each have their own start conditions. Check each mod's Nexus page if you cannot find where a quest begins.
- **Take your time on settlements.** SS2 is a long-term system. Claim a settlement, set it up properly, and let it develop instead of building everywhere at once.

---

## Performance and Stability Tips

- **Always launch through F4SE in MO2**, never through Steam.
- **Do not change graphics settings blindly.** The list ships with tuned INI settings and an ENB.
- **Keep your big settlements to a minimum.** Large settlements are the most common cause of slowdowns and crashes. See [the Triangle of Death](#the-triangle-of-death).
- **Lower the ENB or textures if you struggle.** If your PC cannot handle the list, reducing ENB effects is the first thing to try.
- **Close other heavy programs.** Browsers with many tabs, overlays, and recording software all eat memory the game needs.
- **Use the crash logger.** The list includes **Addictol Crash Logger**. If the game crashes, a crash log is created that helps others diagnose the problem. Keep it handy when asking for help.
- **Do not enable or disable mods mid-save.** This can break scripts and saves. Make changes only before starting a new game.

---

## Troubleshooting

| Problem | What to try |
|---|---|
| Wabbajack cannot find the game | Launch Fallout 4 once from Steam and make sure it is installed cleanly. Re-run Wabbajack. |
| Wabbajack says AE files are missing | Confirm all AE DLC and Creation Club content is installed and fully downloaded in Steam, then re-run the install. |
| Downloads failed at the end of install | Download the listed files manually into your downloads folder and run the install again. |
| Wabbajack will not launch or fails to run | Place it in a simple folder such as `C:\Wabbajack`, outside protected folders. |
| Game will not start | Make sure you are launching **F4SE** from MO2 and not the regular game executable. |
| Crash when entering Sanctuary, Abernathy, or Red Rocket | See [the Triangle of Death](#the-triangle-of-death). |
| Minutemen quest line broken after pre-building | You may have included Zimonja. See [the SS2 warnings](#do-not-pre-build-with-zimonja). |
| Random crashes | Read the Addictol crash log and share it when asking for help. Also check that you did not install extra mods or change the load order. |

---

## Updating and Adding Your Own Mods

- **Check the changelog first.** Before updating the list, read the changelog on the Nexus page.
- **Updating can remove files that are not part of the list.** Wabbajack may delete anything that is not part of the modlist, so **do not rely on extra mods surviving an update**. Back up anything you added.
- **Start new characters after major updates.** Mid-playthrough updates can break saves, especially when they touch SS2 or other script-heavy mods.
- **Adding mods is at your own risk.** The list is a carefully balanced load order. If you add something and run into problems, remove it first before asking for support.

---

## Getting Help

- **The Arcadia List page on Nexus Mods**: read the description, changelog, and posts, and ask questions in the comments. The list's page is mod ID 101471.
- **Sim Settlements 2**: <https://simsettlements2.com/>
- **Wabbajack documentation**: <https://wiki.wabbajack.org/>

When asking for help, include:

1. Which profile you are using (Normal or Survival)
2. What you were doing when the problem happened
3. Your Addictol crash log, if the game crashed

---

*This guide is a community-written starting point for new players. Check the list's Nexus page for the most current install requirements.*
