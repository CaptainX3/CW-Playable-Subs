# IMPORTANT MESSAGE ABOUT THE NEW INSTALLER

* The PBS mod now has its own installation program that is packaged along with the mod. This program will automatically install the core mod files and allow the player to choose which additional submarines they'd like to install, and then the program will update all mission and campaign files to allow the optional subs to be played. The installation instructions on this page have been updated for using this new installer. **It is important that you use the installer program if you want to choose any of the optional submarines - they will not appear in your game if you manually install the override folder.**


# TABLE OF CONTENTS

* [Welcome to the New Playable Subs Mod](#welcome-to-the-new-playable-subs-mod)
* [Submitting Bug Reports and Suggestions](#submitting-bug-reports-and-suggestions)
* [Current List of Core Playable Submarines](#current-list-of-core-playable-submarines)
* [Optional Addon Submarines](#optional-addon-submarines)
* [Other Important Changes (MAKE SURE YOU READ THIS)](#other-important-changes)
* [**First Time Installation - Release Version**](#first-time-installation-release-version)
* [**First Time Installation - Development Version**](#first-time-installation-development-version)
* [**Updating the Mod**](#updating-the-mod)
* [How To Customize the UI Toolbars](#how-to-customize-the-ui-toolbars)
* [Donations](#donations)
* [Info For Mod Developers](#information-for-mod-developers)

---
## Welcome to the New Playable Subs Mod

* This Github repository is the official development center for the New Playable Subs & More mod for Cold Waters. In this repository, we have two versions of the mod - the official stable release version and the development version.

* [Click here](https://github.com/CaptainX3/CW-Playable-Subs/releases) to download the latest official, stable public release of the mod. This is the release that most users need to download. It will be updated periodically to reflect the latest major changes after they have been completed and are verified working.

* The development version of the mod is what you're seeing on the main page. **The development version of the mod is a constantly changing work in progress between mutiple developers, and is not guaranteed to be completely working or bug free. For most users, we recommend that you stick to the latest official release version linked above.** If you would like to try the latest development version of the mod, you can scroll down to the First Time Installation (Development Version) instructions below.

* If you have a bug report, the best place to let us know about it is to [open a new Issue](https://github.com/CaptainX3/CW-Playable-Subs/issues) here on Github and we'll see it and respond. You can also let us know directly in the [official CW Discord](https://discord.gg/mMvpzSV), in the **pbs_mod** channel. This Discord is also a fast way to ask for tech support for the mod as well.

---
## Submitting Bug Reports and Suggestions

* Everyone is welcome to use the Github Issues system to submit issues, bug reports, and suggestions. We have a system set up to handle and respond to these issues from our end.
* We have created a label system to tag all issues. All issues will initially be assigned a Category label, which will have a white background (except for bug reports, which will have a red background). Once the mod developers review an issue, they'll assign a Status label to it. This label indicates the current status of the issue and if any further comments are needed.
* Keep an eye on issues you submit, so you can respond to developer requests if needed. Issues that require further input but do not receive it within 7 days will be closed.

---
## Current List of Core Playable Submarines
*(These subs are automatically included in the core mod and are not optional.)*

* **United States**
  * Los Angeles (Flight I) Class SSN
  * Los Angeles (Flight II) Class SSN
  * Los Angeles (Flight III 688i) Class SSN
  * Narwhal Class SSN
  * Permit Class SSN (Early)
  * Permit Class SSN
  * Seawolf Class SSN
  * Skipjack Class SSN (Early)
  * Skipjack Class SSN
  * Sturgeon Class SSN (Early)
  * Sturgeon Class SSN
  * Virginia Class SSN
  * Improved Virginia Class SSN
  * Stingray Class SS
  * Ohio Class SSGN (Conversion)
  * Jive Turkey Class SSN

* **United Kingdom**
  * Astute Class SSN
  * Trafalgar Class SSN
  * Upholder Class SS
  * Vanguard Class SSBN

* **China (PLAN)**
  * Han Class SSN
  * Shang Class SSN
  * Ming Class SS
  * Kilo Class SS
  * Romeo Class SS
  * Song Class SS
  * Xia Class SSBN

* **Vietnam**
  * Kilo Class SS

* **North Korea**
  * Romeo Class SS

* **Japan**
  * Yushio Class SS
  * Oyashio Class SS

* **Russia**
  * Akula I Class SSN
  * Akula II Class SSN
  * Alfa Class SSN
  * Alfa II Class SSN
  * Mike Class SSN
  * November Class SSN
  * November II Class SSN
  * Sierra Class SSN
  * Victor I Class SSN
  * Victor II Class SSN
  * Victor III Class SSN
  * Foxtrot Class SS
  * Kilo Class SS
  * Kilo II Class SS
  * Lada Class SS
  * Romeo Class SS
  * Tango Class SS
  * Whiskey Class SS
  * Borei Class SSBN
  * Delta III Class SSBN
  * Delta IV Class SSBN
  * Golf Class SSB
  * Typhoon Class SSBN
  * Typhoon Class SSGN (Conversion)
  * Experimental Typhoon Class SSBN "Red October" (Conventional Drive)
  * Experimental Typhoon Class SSBN "Red October" (Silent Drive)
  * Yankee Class SSBN
  * Charlie I Class SSGN
  * Charlie II Class SSGN
  * Echo II Class SSGN
  * Juliet Class SSG
  * Oscar II Class SSGN
  * Yasen Class SSGN


## Optional Addon Submarines
*(These subs can be manually chosen for installation in the PBS Installer)*

* **Australia**
  * Collins Class SS
  * Oberon Class SS

* **Germany**
  * Type 209 Class SS
  * Type 212a Class SSN

* **Netherlands**
  * Walrus Class SS

* **Sweden**
  * Gotland Class SS

* **United States**
  * Nautilus Class SSN

* **Special Submarines**
  * Jive Turkey Class SSN


## Other Important Changes

* The Red Storm Rising (Free Roam) campaign has returned! This campaign is set up so that the player is tasked with a SEAL insertion mission with an extremely long timeframe (2400-3600 hours) to allow the player to roam the map and sink enemies as their leisure. Once the player is ready, they can insert the SEAL team at the designated location and trigger the final SSBN hunting mission. The time frame of this campaign has been changed to 2000 to allow for all of the older and modern Russian subs to be added as possible opponents.
* Player home base in SCS campaign changed to Okinawa, since it is a much more likely location for a US sub base in this theater of operations, and hopefully will somewhat ease the issue of automatically failing your mission whenever you need to rearm.
* Minimum aircraft distance to allow exiting a mission (NearbyAircraftMinDistance) changed from 10000 to 3500, so you're not stuck waiting forever for aircraft to disappear after you sink their mothership.
* Sonar signatures have been reworked. You will see the entire vessel list when playing single missions, but the campaign singature libraries have been left as they were in vanilla, since none of the new subs in this mod will appear in the campaigns.
* In this version of the mod, there is only ONE version of each sub instead of separate vanilla and playable versions like before. (This means that the playable Yasen you love will also be the Yasen you face in the campaigns and single missions.)

## Single Missions List Color Coding

* Single missions in the mod are color coded as follows:
  * White - Vanilla missions from Killerfish, modified to allow all playable subs to be used.
  * Orange - New missions sent to us by mod users, already designed with the mod's playable subs.
  * Green - These are custom missions that are unique in some way, usually featuring only certain playable subs and/or a unique objective.
  * Red - These are custom missions for the Red side (Russia, China, etc) (Note: All playable subs will be available for the player to choose from, but the enemies will be from the opposite side.)
  * Blue - These are custom missions for the Blue side (USA, UK, etc) (Note: All playable subs will be available for the player to choose from, but the enemies will be from the opposite side.)

---
## First Time Installation (Release Version)

* STEP 1: [Click here](https://github.com/CaptainX3/CW-Playable-Subs/releases) to open the Releases page.

* STEP 2: Click on the **Source code (zip)** link to initiate the download. Save the ZIP file to your desktop or wherever you can access it easily.

* STEP 3: Double click on the ZIP file to open it. Inside you'll see a single folder called **CW-Playable-Subs** with the release date and version number. Click on this folder to open it.

* STEP 4: Now you'll see two files in the window - Readme.md and a **PBS Installer** folder. You want to extract **ONLY the PBS Installer folder** to your desktop or wherever you can easily access it.

* STEP 5: Open the **PBS Installer** folder and double click on the **PBS_Installer.exe** file. The installer program should open.

* STEP 6: Follow the instructions in the Installer on each tab until you reach the Install/Uninstall tab.

* STEP 7: If you're using a Steam copy of Cold Waters and **did not change the default install directory,** click Install Mod and proceed to the next step. **If you're using the GOG games version of Cold Waters, or you changed the default install directory,** then choose the correct directory (wherever the ColdWaters.exe file is located) on this screen and then click Install Mod.

* STEP 8: You're done. Run the game and enjoy all of the new stuff!

---
## First Time Installation (Development Version)

* STEP 1: Click the green "Clone or Download" button that you see at the top of this page.

* STEP 2: Click the "Download ZIP" option.

* STEP 3: Double click on the ZIP file to open it. Inside you'll see a single folder called **CW-Playable-Subs-0-master-release**. Click on this folder to open it.

* STEP 4: Now you'll see two files in the window - Readme.md and a **PBS Installer** folder. You want to extract **ONLY the PBS Installer folder** to your desktop or wherever you can easily access it.

* STEP 5: Open the **PBS Installer** folder and double click on the **PBS_Installer.exe** file. The installer program should open.

* STEP 6: Follow the instructions in the Installer on each tab until you reach the Install/Uninstall tab.

* STEP 7: If you're using a Steam copy of Cold Waters and **did not change the default install directory,** click Install Mod and proceed to the next step. **If you're using the GOG games version of Cold Waters, or you changed the default install directory,** then choose the correct directory (wherever the ColdWaters.exe file is located) on this screen and then click Install Mod.

* STEP 8: You're done. Run the game and enjoy all of the new stuff!

---
## Updating The Mod

* STEP 1: Follow STEPS 1 thru 4 for whichever version you want to download (Development or Release).

* STEP 2: Double click on the **PBS_Installer.exe** file. The installer program should open.

* STEP 3: Click on the **Install/Uninstall** tab at the top. If you're using a Steam copy of Cold Waters and **did not change the default install directory,** click Uninstall Mod to completely remove the old version and proceed to the next step. **If you're using the GOG games version of Cold Waters, or you changed the default install directory,** then choose the correct directory (wherever the ColdWaters.exe file is located) on this screen and then click Uninstall Mod.

* STEP 4: Once the old version is uninstalled, click on the **Select Additional Submarines** tab and choose whatever optional submarines you wish to install. Pay attention to the list, we might have added new subs!

* STEP 5: Click on the Install/Uninstall tab, verify that the directory is correct, and then click Install Mod.

* STEP 6: You're done. Run the game and enjoy all of the new stuff!

---
## How To Customize The UI Toolbars
The positions of the UI toolbars for helm, depth, and sensors can be customized via the HUD text files if you don't like how we have them by default. In order to change their positions, you want to open the "override" folder and then open the "hud" folder. In here, you want to open the 3 text files - default.txt, russian.txt, and uk.txt.

In the default.txt file, scroll down to Line 231 (or, alternatively, scroll down and look for [HUD LAYOUT] in the file, the code blocks are a bit below that). Starting at line 231, you'll see three blocks of code. Each block is a specific option for how the toolbars will be placed, each with a description above the block for what it does. Here is what the text blocks look like:

```
//Toolbar position 0,0, (1 to anchor to minimap or 0 for no anchor)
//Default toolbars overlap and enabled via tabs/keys
//ToolbarsPos=0,0,0
//ForceAllToolbarsOn=FALSE
//HelmToolbarOffset=0,0
//DiveToolbarOffset=0,0
//SensorToolbarOffset=0,0

//Force all toolbars on in bottom horizontal row
//ToolbarsPos=0,0,0
//ForceAllToolbarsOn=TRUE
//HelmToolbarOffset=361,-346
//DiveToolbarOffset=700,-346
//SensorToolbarOffset=1039,-346

//Force all toolbars on in vertical stack to the right of the mini-map
ToolbarsPos=0,0,0
ForceAllToolbarsOn=TRUE
HelmToolbarOffset=331,-200
DiveToolbarOffset=331,-270
SensorToolbarOffset=331,-340
```

By default, the bottom block is the one that is active and forces the toolbars to appear stacked just to the right of the minimap. If you'd like to change this option to one of the other available options, then simply remove the // in front of each of the 5 code lines of your choice (DO NOT remove the // from the description text). Then, add // in front of the 5 code lines on the middle block so that you're commenting it out. Do the same thing for the other two text files, and you're done. Be aware that you'll need to do this each time the mod is updated.


---
## Donations

I've been asked several times if I have anything set up to receive donations for those who wish to say thank you for the mod. I don't have a donation page specifically set up for this mod, but I do have one set up for another mod I created for the 4x game Stellaris called "New Ship Clases & More". If you'd like to send a donation, follow the Paypal link below. The page will say "Donations for New Ship Classes & More", but that mod is mine also, so I'll still receive whatever you choose to send.

NOTE: Donations are always appreciated but never required. The content of the mod will never change based on donations, and work on the mod will continue whether I receive donations or not.

Donation Link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FYRBMQMX9CMQJ

---
---
# Information For Mod Developers
---
## Developer Announcements
_Important & urgent information for the mod developers will appear in this section._

* **IMPORTANT: When submitting a final pull request for your latest changes to be merged into the master branch, please list all of the changes you made in the comments, as this will become the official change log for each public release.**

---
## Developer Rules & Guidelines For New Content
* **All new subs must be personally approved by CaptainX3.** The new goal of the mod is not to provide as many units as possible, but instead to provide a smaller number of high quality units.
* New subs must be unique and not similar to existing subs. We're generally not looking for multiple revisions of the same sub class. (Example: We don't need an Oscar I, we have an Oscar II that works fine)
* New subs must fall within the standard time frame of the game, 1984 to present day. We will not be including old WWII subs and such.
* When creating a new sub, you may only add the **latest** weapons and sonar that was used on that class. We will not be adding dozens of obscure weapons and sonar models that are not needed.
* When creating weapons, sonar, radar, and other components for a sub, you **must** use the official name that the system is called in its origin country. (Example: The SS-N-19 Shipwreck missile is officially named the P-700 Granit in Russia, so it should be referred to as the P-700 Granit in the files and in the game.)
* When creating new units for the game, we use Wikipedia as our first choice for stats. If Wikipedia does not have stats available for your chosen unit, then you may seek alternative sources, however they must be at least credible enough to cite to the general public. **If Wikipedia has stats on your chosen unit, you are expected to use those unless you have a disputing credible source that you believe to be more correct than Wikipedia. Do not create units with stats "pulled out of the air."**
* Avoid placing excessive comments in the mod files. Comments with the author name is fine, and notations that are needed are fine, but we don't need files full of unnecessary comments.
* Respect each other's work. If you didn't create something in the mod but you'd like to change it, talk to the original creator first if possible. It's rude to change others' work without asking.

---
### Want To Be A Developer?
* If you'd like to become a mod developer, please contact CaptainX3 on the pbs-mod Discord channel located here: https://discord.gg/mMvpzSV
* Being a developer requires you to be on the Discord server. This is our primary method of communication.
* We'd like to keep this mod at the highest quality, so we ask and expect that all developers contribute work that is close to or equal to the original vanilla quality of the game. Substandard work will be rejected, and repeated issues will result in you being removed as a mod developer.
