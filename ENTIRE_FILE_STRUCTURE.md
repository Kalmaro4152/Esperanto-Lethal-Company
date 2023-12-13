Below is a breakdown of the files in the original Latin language mod.

## Top Level Files (Required for mod)
1. [CHANGELOG.md](CHANGELOG.md) - the changes to your mod over time
2. [README.md](README.md) - a description of your mod
3. [icon.png](icon.png) - a 256x256 image for your mod
4. [manifest.json](manifest.json) - metadata about the mod

## AutoTranslatorConfig.ini

[AutoTranslatorConfig.ini](BepInEx/Translation/eo/Text/AutoTranslatorConfig.ini) is where you set the language code like `la-VA` or whatever you choose. (Ex. Language=eo)

## The Translation Files (config folder)

The config folder contains the translations. There are 2 kinds of translations.

### Terminal Translations
The NewTerminal translations, used to translate the terminal itself.

1. [Verbs](BepInEx/config/NewTerminal-Verbs.cfg)
2. [Special](BepInEx/config/NewTerminal-Special.cfg)
3. [Other](BepInEx/config/NewTerminal-Other.cfg)

### EO Translations
The Esperanto translations used for everything besides the terminal.

1. [Creature](BepInEx/Translation/eo/Text/Creature.txt)
1. [Interactive](BepInEx/Translation/eo/Text/Interactive.txt)
1. [Location](BepInEx/Translation/eo/Text/Location.txt)
1. [MainMenu](BepInEx/Translation/eo/Text/MainMenu.txt)
1. [Scrap&items](BepInEx/Translation/eo/Text/Scrap&items.txt)
1. [UI](BepInEx/Translation/eo/Text/UI.txt)
