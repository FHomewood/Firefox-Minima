# Firefox-Minima

Firefox Minima is a userChrome profile for Firefox that reduces the amount of clutter and screenspace that comes with a modern browser, instead opting for heavy use of /vimium/ commands to navigate. As a result of this Minima has a very low profile, keyboard first style interface which uses the mouse only when it has to

## Captures

## Installation

Firstly from a fresh install of firefox you will need to prepare your browser for userChrome custom stylesheets
> Go to about:config in firefox and change the following settings:
> - toolkit.legacyUserProfileCustomizations.stylesheets = true
> - browser.proton.enabled = false

Then find the your profile directory in about:support.
Move the userChrome.css file from this repository to <profile-directory>/chrome/userChrome.css
This will add the Firefox Minima tab bar in place of the regular Firefox UI.

In order to make this minimalist browser more functional, a number of recommended AddOns will be described and configured here.

### Vimium-FF

This theme uses only a couple customisations to the standard Vimium-FF setup, install this extension then use <Ctrl-Shift-A> to go to the addon page where you can open the Vimium-FF options

> - Click 'Show Advanced Options' at the bottom of the window
> - Scroll to the bottom of the config menu and use the 'Backup and Restore' settings to import settings from the file vimium-minima.json in this repo

