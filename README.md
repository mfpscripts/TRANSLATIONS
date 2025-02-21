# MFPSCRIPTS Translations
To contribute, fork the repository and make a new pull request with your changes. You can submit new locale files, or update an existing one with improvements.
Before contributing, you MUST read our guidelines here: https://docs.maxifaxipaxi.com/translations
Feel free to add a credits comment to the top of the file with your name. Using the credits to advertise is not allowed.


## Setting the language in our scripts

Every script from MFPSCRIPTS is fully translatable out of the box. Simply head to config.lua, and update the Config.Translation option. You can find a list of available translations. Just add one language per file.

The name of the file (without the .lua extension) is the value you set Config.Locale to. For example, if you see a locale file called de.lua, update the config to Config.Locale = "de"

## Contributing
All translations for all our scripts are handled from the translations repository, found on GitHub:
https://github.com/maxifaxipaxi-new/TRANSLATIONS

Before each new release, all the latest translations are automatically pulled from this repository to ensure our scripts are up to date with the best translations available.

We would love for you to contribute! If you want to contribute a new locale file, or improve an existing one, simply make a new Pull Request with your changes, and one of the team will review it.

## Guidelines:

    The name of the locale file must be named with the language code, and be a lua file. For example en.lua, fr.lua, de.lua and so on.

    When creating a new locale file, simply copy an existing one (recommended to use English as it's the original file created by us), and replace the translations with the ones there.

    The start of the file must keep the variable declaration, and you must replace the existing language code to match the name of the file.

    Test the file before submitting your Pull Request to ensure that there are no syntax errors.
