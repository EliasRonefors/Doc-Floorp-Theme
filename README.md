# Doc's Floorp Theme
A work in progress theme for the firefox-based browser Floorp.

## A quick warning
This theme for Floorp isn't very polished, there are small inconsistensies everywhere and it is very heavily targeted towards my personal use of Floorp which may not align with yours. Therefore I'm warning you that some things may break if you use Floorp in a different way from how I use it. 

If you encounter any issues or have any ideas for improvements, simply open an Issue in the Issues tab here on GitHub or contact me on Discord (username is "docdoozer").

This theme will not work properly on other browsers.

## Instructions
1. If you haven't already, [install Floorp](https://floorp.app/).

3. Modify Floorp settings
   * [In Floorp Settings in the "Design"-tab](about:preferences#design), set the Browser appearance to "Lepton UI". Then press the "Lepton Settings..."-button. In the settings page that pops up choose "Use tweaked Proton design" under "Lepton Settings".
   * [In Floorp Extensions & Themes page under the "Themes"-tab](about:addons), choose the Dark Theme, NOT System Theme.

4. Install SideBerry Add-on *(This add-on is what creates the fancy vertical tab bar)*
   * [Install SideBerry](https://addons.mozilla.org/en-US/firefox/addon/sidebery/) *(Make sure to allow it to run in private windows when prompted after installation)*
   * Download "SideBerryData.json" from this GitHub repository.
   * Open SideBerry settings by pressing the cogwheel icon in the top right of the SideBerry side bar.
   * Scroll down to the bottom of the Settings page and press the "Import addon data" button, choose the "SideBerryData.json"-file you just downloaded.

5. Install Userchrome Toggle Add-on *(This add-on will be used to toggle the vertical tab bar in a much nicer way than default)*
   * [Install Userchrome Toggle](https://addons.mozilla.org/en-US/firefox/addon/userchrome-toggle/) *(Make sure to allow it to run in private windows when prompted after installation)*
   * To begin configuring the add-on, right lick on it in the toolbar and press "Manage Extension" then open the "Options"-tab. Usually this opens itself after installing the add-on.
   * Disable option "Display a notification when toggling a style".
   * Rename the first Style Toggle 1 from "userchrome style" to "collapsed sidebar".
   * Make sure to press "Apply Changes" under both "General Settings" and under "Style toggle 1".

6. Configure the Floorp Toolbar
   * First enter the customization mode by right clicking on the Floorp toolbar and then press on "Customize Toolbar".
   * In the bottom left corner, press on "Toolbars" and in the dropdown-menu, hover over "Bookmarks Toolbar" and choose "Never Show". Later we will use a better way of accessing bookmarks.
   * temp, remove shit

7. Add the CSS customizations
   * Press the alt-key on your keyboard to show the Floorp menu bar. Under the "CSS"-option, press "Open CSS-folder".
   * Download the

## Notes, alternatives & recommendations
* start page changes
* sideberry containers?
* changing keybinds for userchrome/sideberry minimize
* choosing not to use userchrome toggle
* turning on sleeping tabs
* setting up the right sidebar

## Credits
* Shina Fox (Some code is taken from here since this project originally started as a modification of Shina Fox)
