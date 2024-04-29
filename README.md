# Custom Homemenu 3DS

## Notes
* Suported regions/versions: EUR/USA/JPN/KOR on Old/New 3DS/2DS between 9.6 and 11.17
* By using this, there is a rare chance to randomly crash when you go back to the homemenu from a game or applet. This is a known issue and **not caused by the custom homemenu itself**, but by layeredfs included in **luma3ds**. I'm unable to fix this as I wouldn't know how, it's complicated stuff.

## Installation tutorial:
* Go to [here](https://github.com/cooolgamer/Custom-Homemenu-3DS/blob/main/README.md#how-to-install).

## Making your own:
A guide is available on the [wiki of this repo](https://github.com/cooolgamer/Custom-Homemenu-3DS/wiki).

# What changed? What is modified?
## KOR region support:
* Theme support (with the help of [@ZeroSkill](https://github.com/ZeroSkill1))
* Unlocked and translated homemenu management (translated with Yandex translate, it can be not accurate),
* Badges section translated (you need to have badges and a NNID to see it),


## For all regions:
* Custom animations: Folders, Power on, Launch a software, Dialog (windows like "closing software"), Sleep mode screen and more!,
* Faster camera load when pressing L+R (removed 10 frames),
* Removed Y and LR buttons showing on top screen (pressing them show up to see what they does),
* New launcher! Inspired with old homemenu applets style (cursor will go 1 row more because I can't change it, it's the default position, sorry!),
* Changed cursors and buttons (inspired of old homemenu),
* Changed sleep screen, big button in the middle,
* Changed battery skin,
* Custom icons,
* Added transparency for windows,
* Changed HUD (the date/hour/play coins etc...),
* Changed banner/icons for applets (miiverse is now red and flash green for notifications),
* Theme menu and Homemenu layout menu is a bit darker.
* Loading icon is now the Wii U one.

# Screenshots
![main](/screenshots/main.png?raw=true "Launcher")
![downloading](/screenshots/downloading.png?raw=true "Downloading and Loading")

![homemenuLayout](/screenshots/homemenuLayout.png?raw=true "Homemenu Layout")
![sleep](/screenshots/sleep.png?raw=true "Power Menu")

![homemenuSettings](/screenshots/homemenuSettings.png?raw=true "Homemenu Settings")
![dialog](/screenshots/dialog.png?raw=true "Dialog Boxes")

[Outdated presentation video](https://youtu.be/zQe--Ni4vi8)


# How to install?
* Make sure your luma version is above or equal to 10.3, if not or you are not sure, you can get it on the [official luma3DS github repository](https://github.com/LumaTeam/Luma3DS/releases),
* Also make sure that game patching is enabled on your luma config (if not, hold the select button while booting and select (x) "Enable game patching" then press start.),
* Download the archive in the [releases page](https://github.com/cooolgamer/Custom-Homemenu-3DS/releases) and uncompress it,
* Choose your console region and copy/paste the "luma" folder on the root of your SDcard.
* Enjoy!   
## Cia method is no longer supported.
If you did this method in the past, please follow the uninstallation cia method below

# How to uninstall ?
## Luma patching method
* Simply remove the folder you copied in luma/titles (the one with the 0004003000(numbers corresponding to your region)).
* Or disable game pathing on luma config.
## Cia method (Please uninstall if you did and follow the new installation method.)
* Launch godmode9,
* Press HOME, go to scripts and select "Mod_HomeMenu",
* Select "restore" and follow instructions.
* Done! It's now uninstalled and you can boot on original Firmware!

# Need help? Or just want to see my other projects?
Join my discord server for help/report bugs or chat! https://discord.gg/hKgeSYqcsC

# Known issues
* Close button on homemenu settings press what is behind it (Z order problem, don't know how to fix)
