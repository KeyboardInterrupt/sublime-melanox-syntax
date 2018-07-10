# Melanox syntax package for Sublime Text 2

Sublime Text 2 Syntax Definitition for Melanox router/switch/firewall configurations. This package will highlight Melanox configuration and commands within Sublime Text 2.

## Installing

**Using Package Control:** If you have [package control](https://packagecontrol.io/) installed then installing this is a snap. Simply open the command palette (Tools->Command Palette). Then type "install" then search for this plugin by typing "Melanox Syntax Highlighter". That's it. It should be installed.

**Without Git:** Download the zip from github, and extract the files to your Sublime Text "Packages" directory, into a new directory named `Melanox`. You can find the packages directy by going to Preferences -> Browse packages, within Sublime Text 2.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/KeyboardInterrupt/sublime-Melanox-syntax.git

## Usage
Once installed navigate to View->Syntax->Melanox to apply the Melanox syntax to the document.

This syntax definition will automatically be applied to .txt files and .cfg files.

## Customizing
Once Melanox syntax is turned on you can then try different color schemes by going to Preferences -> Color Schemes.

If you wish to customize this even further for your own needs navigate to the Melanox package (Preferences -> Browse Packages). Edit the `Melanox Definitions.json-tmlanguage` file within Sublime Text 2/3. Install AAAPackageDev. After your changes go to Tools -> Build, to rebuild the syntax definitions.
