# Wolfie's Project Diablo 2 Loot Filters

To see images of my filters in action please visit the [Reddit thread](https://www.reddit.com/r/ProjectDiablo2/comments/kokwu0/wolfieeiflows_pd2_filters/).  
I have created a Discord so that you can be notified when I update my filter. Take a look [HERE](https://github.com/WolfieeifloW/pd2filter#discord) for more info!  
Looking for a LoD filter? Check it out [HERE](https://github.com/WolfieeifloW/lodfilter)!

**TOO MANY BLUE OR WHITE ITEMS?**  
Check the "Magic Items Master" and "Base Items Master" sections.  
Please also look at the instructions under the "Base Items" header.

# Table of Contents
1. [Installation](https://github.com/WolfieeifloW/pd2filter#installation)
1. [Loot Filters](https://github.com/WolfieeifloW/pd2filter#loot-filters)
   * [Detailed](https://github.com/WolfieeifloW/pd2filter#detailed)
   * [Revealed](https://github.com/WolfieeifloW/pd2filter#revealed)
   * [Compact](https://github.com/WolfieeifloW/pd2filter#compact)
   * [Wolfie](https://github.com/WolfieeifloW/pd2filter#wolfie)
   * [BTNeandertha1](https://github.com/WolfieeifloW/pd2filter#btneandertha1)
   * [Template](https://github.com/WolfieeifloW/pd2filter#template)
1. [Pictures](https://github.com/WolfieeifloW/pd2filter#pictures)
1. [Discord](https://github.com/WolfieeifloW/pd2filter#discord)
1. [Informative Links](https://github.com/WolfieeifloW/pd2filter#informative-links)
1. [Common Issues](https://github.com/WolfieeifloW/pd2filter#common-issues)
1. [FAQ](https://github.com/WolfieeifloW/pd2filter#faq)
1. [Donations](https://github.com/WolfieeifloW/pd2filter#donations)
1. [Disclaimer](https://github.com/WolfieeifloW/pd2filter#disclaimer)

# Installation
The launcher will automatically grab the newest version of your selected filter whenever you press Play!
1. In the Project Diablo 2 launcher click the "Item Filter Profiles" button:  
![01](https://user-images.githubusercontent.com/40577712/110861246-e0e37480-828b-11eb-99c9-1000149c7c43.jpg)
1. On the left-side column (1) select **Wolfie**
1. On the right-side column (2) select which version of my [Loot Filter](https://github.com/WolfieeifloW/pd2filter#loot-filters) you want to use:  
![02](https://user-images.githubusercontent.com/40577712/110861437-20aa5c00-828c-11eb-9e8d-bd04e3e01399.png)
1. Once you select a filter from the right side you will see "Config Saved"  
![03](https://user-images.githubusercontent.com/40577712/110861656-72eb7d00-828c-11eb-80f0-2d586bb2773c.png)
1. Click the **X** button in the top-right corner
1. Select **Play** in the launcher
1. Once in-game CTRL+click the Settings button (bottom-left corner by default)
1. Change your settings to match the image below:  
![InGameSettings](https://user-images.githubusercontent.com/40577712/112235704-8f38d380-8c15-11eb-9791-fddfe493d45b.png)
1. Close the Settings window by right-clicking in the title bar (anywhere along the bar that says "Settings")
1. Reload your filter using **Numpad 0**
   1. If you don't have a numpad change `Reload Config:          VK_NUMPAD0` in ProjectDiablo.cfg (in your PD2 folder) to one of these [Virtual Key Codes](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes)

If it worked a Minor Health Potion should now say *HP1*.

# Loot Filters
### [Detailed](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/detailed.filter)  
CTRL+click the above link for the raw code.  
**Select this version if you are uncomfortable with needing to write your own filter lines.** This version has lines for every single item in the game and is **massively** commented to make it very, very easy to edit to your liking. This is for ease-of-use and very quick editing as you should ideally only ever have to comment or uncomment a line (add or remove //). This version will show and notify a lot of items by default with the idea that you can slowly start to comment out things you don't need. The flip side is that since this filter contains lines for every item you can easily just uncomment a line for things you want to show that aren't currently showing.

### [Revealed](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/revealed.filter)  
CTRL+click the above link for the raw code.  
**Select this version if you want to know what Set and Unique item you've dropped without ID'ing it.** This version is based off of Detailed but will show you the name of Set and Unique items when they drop before you've ID'd them. For example if a Unique Shako drops it will say "Shako [Harlequin Crest]". Being based off of Detailed means it still has lines for every single item in the game and is **massively** commented to make it very, very easy to edit to your liking.

### [Compact](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/compact.filter)  
CTRL+click the above link for the raw code.  
**Select this version if you are comfortable with writing your own filter lines.** This version will contain only the lines that are already uncommented in the Detailed version. This version will still show and notify a lot of items that you can slowly start to comment out but you have to have knowledge of filters to add your own lines for items that are not already in the filter.

### [Wolfie](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/wolfie.filter)  
CTRL+click the above link for the raw code.  
**This version is a copy of my own personal filter.** It is semi-strict while still working while leveling. No support will be given for this filter. Please only report items that are completely wrong.

### [BTNeandertha1](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/btneandertha1.filter)  
CTRL+click the above link for the raw code.  
This is a custom-made version for [BTNeandertha1](https://www.twitch.tv/btneandertha1) which is quite strict. No support will be given for this version.

### [Template](https://raw.githubusercontent.com/WolfieeifloW/pd2filter/main/template.filter)  
CTRL+click the above link for the raw code.  
**Select this version if you want a template/base to start from for creating your own filter.** This filters purpose is to help people get a start on building their own filter. No support will be given for this filter, you assume all responsibility for creating and editing it to your liking.

# Pictures
Some things may have changed since these images were taken but these give a general idea of how things look. For even more images please visit my [Reddit thread](https://www.reddit.com/r/ProjectDiablo2/comments/kokwu0/wolfieeiflows_pd2_filters/)!

**Detailed:**  
![00_GroundDetailed](https://user-images.githubusercontent.com/40577712/110947461-31031b00-830e-11eb-8ea2-bfd0bf65613f.png)

**Wolfie:**  
![00_GroundWolfie](https://user-images.githubusercontent.com/40577712/110947471-3496a200-830e-11eb-988a-20c9d86049fb.png)

# Discord
Discord link: [WolfieeifloW's PD2 Filters](https://discord.gg/6bM8AtYGAq)  
I've created a Discord for my filter so that you can get pinged when there's an update so you can know when to grab the new update in the launcher!

# Informative Links
* **Reddit Thread:** <https://www.reddit.com/r/ProjectDiablo2/comments/kokwu0/wolfieeiflows_pd2_filters/>
* **Info for Filter:** <https://github.com/planqi/slashdiablo-maphack/wiki/Advanced-Item-Display>
* **Color Chart:** <https://raw.githubusercontent.com/planqi/slashdiablo-maphack/master/readme_gfx/color_palette.png>
* **Info for Notify:** <https://github.com/planqi/slashdiablo-maphack/wiki/Advanced-Item-Display#marking-items-on-the-map>
* **More Notify Info:** <https://github.com/planqi/slashdiablo-maphack#release-notes-for-bh-maphack-v18>
* **PD2 New Item & Skill Codes:** <https://docs.google.com/spreadsheets/d/15_JIFA5Wkx3sGQr_scLZz3l6Q8Ig687yUiz8DttaxtI/edit?usp=sharing>
* **PD2 Wiki (all item/skill codes):** <https://projectdiablo2.miraheze.org/wiki/Item_Filtering>
* **Automods Info:** <https://www.diabloii.net/forums/threads/the-staffmod-grail.740340/>

# Common Issues
These are the common problems that people seem to run into. Please check each of these before asking for help.
* In-game settings not matching what I have in [Installation](https://github.com/WolfieeifloW/pd2filter#installation)
* Having two PD2 installations and pasting your filter into the wrong one
* Saving the filter file with the wrong name, eg **default.filter.filter**, **default.txt**, or **default.filter.txt**
* Having a PD2 installation inside of a Diablo II folder which is inside another Diablo II folder (folderception!)
* Not saving and closing the filter file after pasting into it

# FAQ
**Read the [Common Issues](https://github.com/WolfieeifloW/pd2filter#common-issues) above if the FAQ does not help.**

1. **What is the (best / recommended / good for X / leveling) filter?**
   * "Best" / "recommended" is subjective. The best/recommended filter is the filter that suits your needs! Try a few out, it's easier than ever now to try different ones as it's only a few clicks in the launcher. [List of Public Filters](https://projectdiablo2.miraheze.org/wiki/Item_Filtering#List_of_Public_Filters) has a short description for each filter
1. **How do I turn off the filter / go back to original?**
   * Turn off `Advanced Item Display` in the in-game settings then close your game and launcher. Delete the `filters` folder, and delete `default.filter` and `loot.filter` in the ProjectD2 folder, and then reload the game
1. **My launcher still says "Coming soon!" for item filters?**
   * First back-up your ddraw.ini and ProjectDiablo.cfg files (these will be overwritten). Visit the [Project Diablo 2](https://www.projectdiablo2.com/) site and download the launcher and install the new launcher version
1. **My Settings button is gone?**
   * Close the game & the launcher, delete `UI.ini`, and then relaunch the game. Note you may have to redo your settings (look at the image in [Installation](https://github.com/WolfieeifloW/pd2filter#installation))
1. **But I've customized my filter, how do I save my changes?**
   * **NOTE:** Using a local filter will mean you miss out on updates from the creator whose filter you're using. You will have to manually input any future changes they make to acquire them. Put your customized filter into `ProjectD2\filters\local` as `default.filter` and choose "Local" in the launcher (look at my guide [here](https://github.com/Project-Diablo-2/LootFilters#using-a-local--customized-filter) too)
1. **I want to use a filter not in the launcher?**
   * **NOTE:** Using a local filter will mean you miss out on updates from the creator whose filter you're using. You will have to manually input any future changes they make to acquire them. Put your customized filter into `ProjectD2\filters\local` as `default.filter` and choose "Local" in the launcher (look at my guide [here](https://github.com/Project-Diablo-2/LootFilters#using-a-local--customized-filter) too)
1. **Will a loot filter from Season 1 work for Season 2?**
   * No. Season 2 added new items, changed all the map item codes, and more. You will most likely miss out on all of these things if you continue using a Season 1 filter
1. **My launcher shows no filters in the list?**
   * Close launcher and re-open, repeat if they still don't show *or* the server/GitHub is down. Also try adding the launcher and game to your antivirus and/or firewall
1. **Has anyone made a video or post about the differences between X and Y filter?**
   * No one here has made comparison videos or a post of "X vs Y filter", that would be an astronomical amount of work. What's not a lot of work is trying a few out and seeing what fits your style!
1. **How can I test my chosen loot filter?**
   * The easiest way to test your filter is by using [BetweenWall's FilterBird](https://betweenwalls.github.io/filterbird/?v=PD2)
1. **Are your filters updated for Season 2?**
   * Yes, all versions of my filters are updated and ready-to-go for Season 2!
1. **What is the difference between your filters?**
   * My Detailed/Revealed/Compact are less strict, Wolfie is stricter, and BT is strictest

# Donations
Donation link: [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=9JARHKMQ9UU3S&item_name=Project+Diablo+2+Loot+Filter&currency_code=CAD)  
Donations are not required in any way but I very much appreciate all who support me in this fashion!  
If you wish you can get the "Donator" role in my [Discord](https://github.com/WolfieeifloW/pd2filter#discord) as well!

# Disclaimer
For all versions of the filter I take no responsibility for any items that are accidentally hidden and/or do not notify. I do try my best to test these filters and ensure they are working properly but there's always room for error.
