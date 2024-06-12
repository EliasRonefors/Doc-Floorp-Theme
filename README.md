# Doc's Floorp Theme
A work in progress theme for the firefox-based browser Floorp.
![image](https://github.com/EliasRonefors/Doc-Floorp-Theme/assets/90244703/389e7085-bd6d-4c6e-a334-bebf9fd73ab8)
![image](https://github.com/EliasRonefors/Doc-Floorp-Theme/assets/90244703/62545bbc-2f24-46a8-940e-6462fea4025d)


## A quick warning
This theme for Floorp isn't very polished, there are small inconsistensies everywhere and it is very heavily targeted towards my personal use of Floorp which may not align with yours. Therefore I'm warning you that some things may break if you use Floorp in a different way from how I use it. 

If you encounter any issues or have any ideas for improvements, simply open an Issue in the Issues tab here on GitHub or contact me on Discord (username is "docdoozer").

This theme will not work properly on other browsers.

## Instructions
If you haven't already, [install Floorp](https://floorp.app/).

1. **Modify Floorp settings**
   * [In Floorp Settings in the "Design"-tab](about:preferences#design), set the Browser appearance to "Lepton UI". Then press the "Lepton Settings..."-button. In the settings page that pops up choose "Use tweaked Proton design" under "Lepton Settings".
   * [In Floorp Extensions & Themes page under the "Themes"-tab](about:addons), choose the Dark Theme, NOT System Theme.

2. **Install Sidebery Add-on** *(This add-on is what creates the fancy vertical tab bar)*
   * [Install Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) *(Make sure to allow it to run in private windows when prompted after installation)*
   * Download "SideberyData.json" from this GitHub repository.
   * Open Sidebery settings by pressing the cogwheel icon in the top right of the Sidebery side bar.
   * Scroll down to the bottom of the Settings page and press the "Import addon data" button, choose the "SideberyData.json"-file you just downloaded.

3. **Install Userchrome Toggle Add-on** *(This add-on will be used to toggle the vertical tab bar in a much nicer way than default)*
   * [Install Userchrome Toggle](https://addons.mozilla.org/en-US/firefox/addon/userchrome-toggle/) *(Make sure to allow it to run in private windows when prompted after installation)*
   * To begin configuring the add-on, right lick on it in the toolbar and press "Manage Extension" then open the "Options"-tab. Usually this opens itself after installing the add-on.
   * Disable option "Display a notification when toggling a style".
   * Rename the first Style Toggle 1 from "userchrome style" to "collapsed sidebar".
   * Make sure to press "Apply Changes" under both "General Settings" and under "Style toggle 1".

4. **Configure the Floorp Toolbar**
   * First enter the customization mode by right clicking on the Floorp toolbar and then press on "Customize Toolbar".
   * In the bottom left corner, press on "Toolbars" and in the dropdown-menu, hover over "Bookmarks Toolbar" and choose "Never Show". Later we will use a better way of accessing bookmarks.
   * Note that custom icons in this theme are currently only supported for the uBlock Origin- and Dark Reader add-ons. To achieve the same look as in the example images you would need to install them and pin them to the toolbar.
   * Now arrange the toolbar to look exactly like in the following image, including removing things from the tabs bar like the new-tab button. Failure to do so may cause things to look weird later. ![image](https://github.com/EliasRonefors/Doc-Floorp-Theme/assets/90244703/c7d26d94-b81b-4ddf-b95b-14fcff002484)

5. **Add the CSS customizations**
   * Press the alt-key on your keyboard to show the Floorp menu bar. Under the "CSS"-option, press "Open CSS-folder". A folder will open, go to its parent folder (should be titled "chrome").
   * Download the files in the folders titled "CSS" and "SVG" from this GitHub repository. Put the contents of the CSS folder you downloaded into the chrome\CSS folder you opened in the previous step. Put the contents of the SVG folder you downloaded just directly into the chrome folder.
   * If nothing changes after restarting Floorp, make sure to press alt and look at the CSS dropdown in the menu bar. There should now be options like "context-menu.css" in the list, make sure they're ticked.

6. **Celebration**
   * That should be it! Good job. If something isn't working or you need help do reach out to me. Continue reading to see some recommendations from me.

## Recommendations
* **My start page customization recommendations**
  * Navigate to the Home tab of Floorp settigs.
  * Here set "Floorp Home Background" to "Custom image..." to set a nice wallpaper.
  * I also like to turn off "Web Search", "Shortcuts" and "Recent activity" in the "Floorp Home Content" settings to make it extra clean.
  * Lastly download the "userContent.css" file from this GitHub repository and put it in the chrome folder you opened earlier when adding the other CSS customizations. This will remove some unneccessray icons from the home screen leaving it completely blank.

* **Adding a keybind for minimizing the left sidebar**
  * Open the Floorp extensions page. Press the settings icon in the top right, in the drop-down menu press "Manage Extension Shortcuts".
  * Change "Toggle userchrome style 1" under Userchrome Toggle to something like the f1-key.

* **Turn on sleeping tabs in Floorp Settings for improved memory usage when having many tabs open**

* **Modify right sidebar**
  * Modify pages pinned to the right sidebar by going to "Browser Manager Sidebar" in the Floorp Settings. Personally I've only got Google Translate, DeepL Translate, ChatGPT and Copilot pinned as of writing this.

* **Setting up Sidebery Panels**
  * Sidebery has a feature called "Panels", it gives your left sidebar another way to organize tabs. By default my "SideberyData.json"-file sets you up with two panels, one named "School" and one just named "Tabs". You can create more, remove them or rename them for more customization and flexibility
  * To customize the ones you have, simply right click on them and press "Configure Panel". This will take you to the Sidebery settings and open a pop-up where you can change the name, icon and color as well as some other settings for that panel.
  * To add a new panel navigate to the "Enabled elements" list under "Navigation bar" inside the Sidebery settings. Drag a "Tabs panel" into the list to add a new panel, then configure it like in the previous step.
  * To remove a panel just right click it and press "Remove panel".

## Credits
* [Shina Fox](https://github.com/Shina-SG/Shina-Fox) (Some code is taken from there since this project originally started as a modification of Shina Fox)
