# Changelog

These are identical to those found [on GitHub](https://github.com/fins-mods/REnhanced/releases).
If you want notifications you can open that page then: Click the arrow next to "Watch" at the top → Custom → Releases → Apply, and you'll get GitHub notifications (configurable to be push and/or email) whenever the modpack updates.

## 1.1.0 Thank you for 1000 downloads! Here's our first minor version bump

- New companion modpack with mods that didn't quite make the cut! It's already on [Thunderstore](https://thunderstore.io/package/fin/REnhanced_Extras/) and [GitHub](https://github.com/fins-mods/REnhanced_Extras)
- The following changes mentioned in the 1.0.7 changelog:
  - `LICENSE.txt` will be omitted from the Thunderstore package.
  - `manifest.json` will be minified
  - `expanded-manifest.json` is available in the [GitHub repository](https://github.com/fins-mods/REnhanced).
- Added [HighItemVizability](https://thunderstore.io/package/VizMod/HighItemVizability/) by [VizMod](https://thunderstore.io/package/VizMod/) - "Shoots a tier colored beam to the sky at the location of a dropped item for visability across the map."
- Added [LookStraightDown](https://thunderstore.io/package/HIFU/LookStraightDown/) by [HIFU](https://thunderstore.io/package/HIFU/) - "Allows you to look straight down, and straight up. Configurable"
- Added [NoSelfPing](https://thunderstore.io/package/Xan/NoSelfPing/) by [Xan](https://thunderstore.io/package/Xan/) - "This mod fixes a bug that made it possible to ping yourself..."
- Updated [BetterGameplay](https://thunderstore.io/package/XoXFaby/BetterGameplay/) 1.1.2 → 1.1.3
  - Bugfix: Fixed bug that would apply the cooldown increase in the bazaar to only the first equipment instead of each equipment the character has.
- Removed config files for the following mods because they held default values:
  - RailCharges
  - PingItemDescription
- Removed dependency mods that will be installed automatically when installing their dependants.
- Updated note about StutterStunter and removed StutterStunter config
- Re-ordered "Better Explanation" section's bullet points to match the ordering in REnhanced_Extras
- The README note about the changelog being moved to CHANGELOG.md is now gone
- Changed README notes from H3 headers to bullet points
- Changed borderline mods from bullet points to H4 headers with their respective descriptions underneath instead of all being on giant single lines
- Updated downloads thank you message, we're over 1000!
- Reduced icon.png file size by 31%
- Fixed old GitHub Changelogs not matching the ones here (there have been a few typo fixes and the early ones didn't necessarily follow the same formatting schema used now)
- Fixed missing space between the Aerolt author's name and the mod description in the list of not-included mods.
- Fixed a handful of typos and weird grammar quirks in the README

## 1.0.7 Now using the Thunderstore changelog

- Moved Changelog from README.md to CHANGELOG.md since that's now supported by Thunderstore, there's a note about it in the README.md
- `manifest.json` is now formatted properly
- **<!>** Starting with 1.1.0 (which likely won't be the next release, but it could be):
  - `LICENSE.txt` will be omitted from the Thunderstore package.
  - `manifest.json` will be minified
- Starting with this release, `expanded-manifest.json` will be included in the [GitHub repository](https://github.com/fins-mods/REnhanced) (it will  **not** be included in the Thunderstore release).
  - Until 1.1.0 launches with a minified `manifest.json`, these two files will be identical.
- Fixed typos in previous changelogs
- Formatted JSON and Markdown files in the proper standard ways
- Updated thank you downloads number to 700!

## 1.0.6 Mod updates, README polish

- Updated [Engi_M1_Autofire](https://thunderstore.io/package/Moffein/Engi_M1_Autofire/) 1.1.4 → 1.2.0
  - Risk of Options support.
  - Fixed a bunch of config options being missing.
- Updated [R2API_Core](https://thunderstore.io/package/RiskofThunder/R2API_Core/) 5.0.3 → 5.0.4
  - Added SystemInitializerInjector class to the Utils namespace
- Updated [R2API_Elites](https://thunderstore.io/package/RiskofThunder/R2API_Elites/) 1.0.0 → 1.0.1
  - Fix some non working custom ramps (ramp index not properly set)
  - Always enable EliteAPI hooks (potential fix for a Spikestrip elite color bug)
- Appended `/`s to the end of Thunderstore links to avoid unnecessary redirects.
- Added a `#` after the `/` in the Thunderstore link to this Modpack's package page so that it doesn't reload when pressed from Thunderstore.
- Updated thank you downloads number to 500!
- Fixed typo in previous changelog.

## 1.0.5 Just README Updates

- Added "No deprecated mods!" to my list of ~~pseudo-requirements~~ preferences.
- Added note at the very bottom of README to like the modpack
- Updated thank you downloads number to 350!

## 1.0.4 More polish and a new mod- SeerPing

- Changed README ROR2 Modding Discord invite from `discord.gg/` to `discord.com/invite/`
- Fixed capitalization of 'Where I draw the "vanilla flavored" line' in README
- Fixed manifest.json modlist being incorrectly sorted
- Gave README consistent newlines
- Added [SeerPing](https://thunderstore.io/package/Moonlol/SeerPing/) by [Moonlol](https://thunderstore.io/package/Moonlol/) - "makes the lunar seers show you where they lead when pinged"
- Changed line endings to the unix style LF (\\n) instead of CRLF (\\r\\n). Will affect literally nothing in practice but it's my preference.
- Changed Changelog section text to use `→` instead of `->` since my editor's font ligatures obviously don't apply on Thunderstore.. oops

## 1.0.3 Configuration fix

- Fixed PingItemDescription misconfiguration

## 1.0.2 Polish

- Fix a typo in the README
- Updated mod description
- Add GitHub URL to manifest.json
- Add Changelog section to README
- Add currently empty "Known Issues" section to README
- Remove an accidentally included mod skin mod (oops)
- Sort manifest.json dependency strings alphabetically by mod name (with R2API and BepInEx ones sorted separately at the bottom)
- Somewhat heretically indented dependency strings to be centered around the `author`-`modname` dash delimiters

## 1.0.1 Remove an extra temp file

- Delete a missed temporary file 1.0.1 Remove an extra temp file

## 1.0.0 Initial release

- Initial Release
