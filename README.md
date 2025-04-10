<div align="center">

![Logo](https://i.imgur.com/JiIb8K3.png)

[![Guild Recruiter on Discord](https://img.shields.io/badge/discord-Always%20Be%20Convoking-7289DA?style=flat)](https://discord.gg/ZtS6Q2sKRH) [![Buy Me a Cofee](https://img.shields.io/badge/Buy-orange?style=flat&label=Buy%20Me%20a%20Coffee)](https://bmc.link/alwaysbeconvoking)

</div>

Guild Recruiter is now, the official replacement for FGI.  It is a guild recruitment addon that allows you to send messages to players that are not in a guild.  It also has a scanner that will scan the area around you for players that are not in a guild.  You can then invite them to your guild.

## Warning: Utilization of a guild recruitment addon can lead to a player being flagged for spamming.  Please use this addon responsibly.
<div align="center">This goes for any guild recruitment addon, not just Guild Recruiter.</div>

## Features

* Guild Master can force certain options to be use by other officers/recruiters.
* Sync your lists, messages, and settings with other guild recruiters.
* Custom messages with ability to embed your guild link.
* Guild greeting message when a player joins, that you invited.
* Whispered message to player when they join.
* Anti Spam Features:
    - Ignore players in zones that are PVP or current seasonal raid/dungeon.
    - Once invite is sent will not invite that player again for 7 to 180 days.
    - Able to add players to a black list, so they do not get future invites.
* Much more!

## Documentation
* Use /gr or /recruiter to access the addon outside the minimap icon.
* /gr help or /recruiter help to see a list of options you can use.
* Make sure you go into the settings to add a message, custom filters etc.
* To move the screen, click the lock next to the X button.  When it is green,
    you can move the screen.  Click the lock again to lock it in place.

There is a filter by class and another by race that is included with the addon.

## Miscellaneous
This is a new addon and while I have been working hard to debug it, I am sure there will be issues.

## Changes and Improvements by JSON

**New Features:**
- Added a **Custom Race/Class Filter**, allowing you to choose exactly which races and/or classes to search for. When the custom race/class filter is selected from the dropdown on the home screen, the scanner will search based on the classes and races you have selected in the addon settings or the quick filters menu on the scanner screen.
- Added a **Show/Hide Quick Filters** button to the bottom-right corner of the scanner interface, opening a streamlined quick menu to adjust filters on the fly.

**Improvements:**
- Quick Filters and the main Filter Settings menu are now synchronized — changes made in one will reflect in the other.
- Changing any filter setting for a race or class will now **automatically rebuild the search query**.
- Users can now search for **specific race and class combinations**.
- **Demon Hunters** are now properly excluded from **Hunter** class searches.
- Repositioned the **Scan** button and query input field for a cleaner layout.

**Scanner Logic Updates:**
- The scanner now searches in **20-level brackets**, dynamically adjusting based on the selected level range.
- If a player search returns the maximum of 50 results, the scanner will **split the search queries** and continue searching.
- When a level range is selected, the scanner will **loop back** to the start of the bracket once the search is completed to ensure full coverage.


## Known issues by JSON 
* Search progress percentage may not be accurate or goes above 100%, this is due to how the query splitting works, and i cant be bothered to fix it more then i already tried.
