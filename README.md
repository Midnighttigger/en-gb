People are fine to make contributions via pull requests to this mod!
# en-gb for Factorio
 English, UK for Factorio https://mods.factorio.com/mod/en-gb
 mod support here https://mods.factorio.com/mod/mods-en-gb
---
#IMPORTANT! If you still want achievements on steam please install through the method that doesn't require running the mod
#Important Summary (ish)
- This mod doesn't overwrite the existing `en` locale and instead uses a different unsupported locale `en-gb`
- Mod support is on a separate mod called [mods-en-gb](https://mods.factorio.com/mod/mods-en-gb)
- Includes Space Age, Quality and Elevated Rails DLC support inside as of version mod 0.2.0
---
#How to Install (because of how the game manages unsupported languages)
##via editing config.ini but when you switch language once you'll have to do again
- Find config.ini in [User data directory](https://wiki.factorio.com/Application_directory#User_data_directory)
- Head to section `[general]` and put the setting as: `locale=en-gb` as seen in the image
##via adding a dedicated selector for en-gb
- Find mods folder in [User data directory](https://wiki.factorio.com/Application_directory#User_data_directory)
- open the .zip (mod itself) and navigate to a folder called "basegame" which this folder is next to other files including info.json
- Navigate down it through basegame -> core -> locale -> en-gb -> info.json & copy this file
- Find your Factorio [Application Directory](https://wiki.factorio.com/Application_directory#Application_directory)
- navigate down data -> core -> locale & make a folder en-gb, in this folder paste the file you copied
- when you boot up the game it should now be select-able, this should not override unless you change  your game install location
##via complete install (with this you can actually run en-gb whilst not running the mod)
- Find mods folder in [User data directory](https://wiki.factorio.com/Application_directory#User_data_directory)
- open the .zip (mod itself) and navigate to a folder called "basegame" which this folder is next to other files including info.json
- Copy `base` & `core` from the `basegame` folder (If you have the DLC copy over `elevated-rails` , `quality` and `space-age` as well)
- Find your Factorio [Application Directory](https://wiki.factorio.com/Application_directory#Application_directory)
- go into the `data` folder
- paste
- This should run, whenever this mod updates though I would recommend reinstalling to install en-gb updates if you use this way
---
#More info:
Inspired but not a derivative of https://mods.factorio.com/mod/BritishEnglishLocale but the thumbnail.png is from there
with file editing you may corrupt your game even though I wouldnt want it to currupt on your side, I do not take responsibility
if you know, can you tell me how to add it as a selectable in the language gui via just the mod
---
