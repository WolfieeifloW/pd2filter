# Wolfie's Project Diablo 2 Loot Filters

# Table of Contents
1. [Installation](https://github.com/WolfieeifloW/pd2filter#installation)
1. [Loot Filters](https://github.com/WolfieeifloW/pd2filter#loot-filters)
   1. [Detailed](https://github.com/WolfieeifloW/pd2filter#detailed)
   1. [Compact](https://github.com/WolfieeifloW/pd2filter#compact)
   1. [Basic](https://github.com/WolfieeifloW/pd2filter#basic)
1. [Informative Links](https://github.com/WolfieeifloW/pd2filter#informative-links)
1. [Completely Hidden Items](https://github.com/WolfieeifloW/pd2filter#completely-hidden-items)
1. [Disclaimer](https://github.com/WolfieeifloW/pd2filter#disclaimer)

# Installation
1. Select which filter you want to use from [Loot Filters](https://github.com/WolfieeifloW/pd2filter#loot-filters) section
1. CTRL+Click (will open in a new tab) the link on that filter which will take you to the raw code for that version
1. Copy all of the code (press CTRL+A to select all than CTRL+C to copy)
1. Open your text editor (Notepad, Notepad++, etc) as Administrator
1. With your text editor open **default.filter** from your ProjectD2 folder
1. Paste the code you copied, overwriting everything in there
1. Save and close the file
1. Open Project Diablo 2
1. Once in-game CTRL+click the Settings button (bottom-left corner by default)
1. Change your settings to match the image below
1. Close the Settings window by right-clicking in the title bar (anywhere along the bar that says "Settings")
1. Reload your filter using **Numpad 0** (by default)

![In-Game Settings](https://i.imgur.com/y7vCGmq.png)

If you don't have a numpad change `Reload Config:          VK_NUMPAD0` in ProjectDiablo.cfg (in your PD2 folder) to one of these [Virtual Key Codes](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes).

# Loot Filters
### [Detailed](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/detailed.filter)
CTRL+click the above link for the raw code.

**Select this version if you are uncomfortable with needing to write your own filter lines.** This version has lines for every single item in the game and is **massively** commented to make it very, very easy to edit to your liking. This is for ease-of-use and very quick editing as you should ideally only ever have to comment or uncomment a line (add or remove //). This version will show and notify a lot of items by default with the idea that you can slowly start to comment out things you don't need. The flip side is that since this filter contains lines for every item you can easily just uncomment a line for things you want to show that aren't currently showing.

### [Compact](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/compact.filter)
CTRL+click the above link for the raw code.

**Select this version if you are comfortable with writing your own filter lines.** This version will contain only the lines that are already uncommented in the Detailed version. This version will still show and notify a lot of items that you can slowly start to comment out but you have to have knowledge of filters to add your own lines for items that are not already in the filter.

### [Basic](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/basic.filter)
CTRL+click the above link for the raw code.

**Select this version if you want a template/base to start from for creating your own filter.** This filters purpose is to help people get a start on building their own filter. No support will be given for this filter, you assume all responsibility for creating and editing it to your liking.

### Wolfie
**N/A yet.** This version is basically a copy of my own personal filter. Will most likely contain things you don't think are worth it and not contain things you think are worth it. No support will be given for this version.

# Informative Links
* **Info for Filter:** <https://github.com/planqi/slashdiablo-maphack/wiki/Advanced-Item-Display>
* **Color Chart:** <https://raw.githubusercontent.com/planqi/slashdiablo-maphack/master/readme_gfx/color_palette.png>
* **Info for Notify:** <https://github.com/planqi/slashdiablo-maphack/wiki/Advanced-Item-Display#marking-items-on-the-map>
* **More Notify Info:** <https://github.com/planqi/slashdiablo-maphack#release-notes-for-bh-maphack-v18>
* **Item Codes:** <http://www.gmstemple.com/Diablo2/itemcodes.html>
* **Automods Info:** <https://www.diabloii.net/forums/threads/the-staffmod-grail.740340/>
* **Skill Codes:** <https://user.xmission.com/~trevin/DiabloIIv1.09_Skills.html>
* **PD2 Item & Skill Codes:** <https://docs.google.com/spreadsheets/d/15_JIFA5Wkx3sGQr_scLZz3l6Q8Ig687yUiz8DttaxtI/edit?usp=sharing>

# Completely Hidden Items
The only items fully hidden in my filters (Detailed and Compact, at least) are:
* Horadric Scroll (completely useless item)
* Chipped, Flawed, and normal quality gems past certain character levels
* All ears
* All inferior (Broken, Crude, etc) items past certain character levels
* All quivers past a certain character level
* Low piles of gold past certain character levels
* Minor, Light, and normal quality Health and Mana Potions past certain character levels
* Rare items you don't specify past a certain character level
* Magic items you don't specify past a certain character level
* White items with 1 socket past a certain character level
* White Amazon Javelins past certain character levels (no sockets so no Runewords possible)
* White Amazon Javelins that are only +0-2 Jav skills past a certain character level
* White Belts, Boots, and Gloves past certain character levels
* White Bucklers (and Exceptional version) past certain character levels as they can only have 1 socket (no Runewords)
* White Daggers and Dirks (and Exceptional & Elite versions) pastcertain character levels as they can only have 1 socket (no Runewords)
* White Javelins past certain character levels (no sockets = no possible Runewords)
* White throwing weapons past certain character levels (no sockets = no possible Runewords)

# Disclaimer
For all versions of the filter I take no responsibility for any items that are accidentally hidden and/or do not notify. I do try my best to test these filters and ensure they are working properly but there's always room for error.
