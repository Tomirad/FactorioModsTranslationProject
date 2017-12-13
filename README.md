# Factorio Mods Translations
Translations are available to modders, mainly for those who don't use the GitHub platform to distribute them.

The rules are simple:
- create a directory with the mod name (exactly as the creator uses it) and mod version
- inside create directory with locale name (e.g. `pl` for polish translation) 
- place translation files inside that directory

Template:
<b>{NameProject}_{version}/locale/{LngCode}/config.cfg</b>
Example:
Ruins_0.1.3/locale/pl/config.cfg

Sometimes author of the modification uses other names for localisation files ex. string.cfg or {LngCode}.cfg

NameProject - is name the mod with info.json
Version - is version with info.json, must be format _0.0.0 or _0.0
LngCode - language code your country e.g. polish - pl, english - en, russian - ru

And then we translate the mod from English into our own language.

Important:
If translation is incomplete, please add how many percent is already translated.
E.g. 90% (90 lines from 100 text lines )


# For Gamers
Download this localisation files and then copy only internal folders to /mods/ folder inside your game directory.

# Others
Project is for game <b>Factorio</b> [factorio.com](http://factorio.com)
You will find mods to our translations here: [mods.factorio.com](https://mods.factorio.com)
