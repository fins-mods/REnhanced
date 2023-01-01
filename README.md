# REnhanced Modpack
TL;DR It's an "Enhanced Vanilla" experience with a lot of quality-of-life enhancement mods, minimal balance tweaks\*, and vanilla compatibility.

### Thank you for over 100 Downloads!



## Better explanation
First and foremost, this is a modpack made to pair my particular proceeding preferences:
- Overall vanilla flavored experience with some sprinkles :)
- Must maintain vanilla compatibility both when hosting **and** as a client
- Nothing should be too jarring to anyone coming from the unmodded base game
- Balance changes should be avoided or at most, imperceptible\*
- Performance over resource usage†
- Nothing "chocolate", nothing should *feel* modded. It should be conceivable that all of the mods could be added to the base game.


The way I see it, there's **a lot** of small tweaks (both flaw fixes and feature furtherance) that make considerable improvements to what it's like to just sit there and play the game. I much prefer a lot of very small independent tweaks that add up to a better experience instead of overhauling large/prominent parts of the game- I want to play Risk Of Rain 2, not a fan-made redesign and refactor.



## Where I draw the "vanilla flavored" line
This is of course a balancing act. So there are some mods I was on the fence about and chose to keep, and others that I decided not to. Since they're borderline and you might have different opinions, I'll list the iffy ones below.


### The ones I kept:
- [RespawnAfterBoss](https://thunderstore.io/package/neutrino-steak/RespawnAfterBoss) by [neutrino-steak](https://thunderstore.io/package/neutrino-steak) - Respawns all dead players once all bosses have been defeated. This means if 1 out of 4 players are alive at the end of the teleporter event, instead of all of the boss drops going to them, the other players can get their share so they don't fall behind (plus if they died, they could probably use the help from the extra items).
- [TooManyFriends](https://thunderstore.io/package/wildbook/TooManyFriends) by [wildbook](https://thunderstore.io/package/wildbook) - Allows you to play with more than just 4 players per lobby. The base game's player count-scaling wasn't designed with more than 4 player lobbies in mind, however since the mod only introduces that edge case perplexion once the mod becomes necessary, it's somewhat of a "necessary evil" with no better alternative.


### The ones I didn't
- [GoldChestForAll](https://thunderstore.io/package/DestroyedClone/GoldChestForAll) by [DestroyedClone](https://thunderstore.io/package/DestroyedClone) - While I do use this in my day-to-day and subjectively in my opinion it makes item distribution more fair, it does objectively affect balance in a meaningful way (4 reds on your team instead of 1 on Stage 4 can be pretty impactful).
- [Aerolt](https://thunderstore.io/package/Lodington/Aerolt) by [Lodington](https://thunderstore.io/package/Lodington)- A cheating mod menu that can serve as a helpful utility and very useful for testing, but it also is by nature a cheat which can be frowned upon by some (to each their own I suppose).
- [SillyItems](https://thunderstore.io/package/TheTimesweeper/SillyItems) by [TheTimesweeper](https://thunderstore.io/package/TheTimesweeper) - Even though you could argue being able to visually see how many items each player has does serve a purpose, if we're being realistic this mod is a much more "for fun" and not really a utility.
- [RiskOfRave](https://thunderstore.io/package/RuneFox237/RiskOfRave) by [RuneFox237](https://thunderstore.io/package/RuneFox237) - Plays the song Caramelldansen and adds rainbow post processing effects during teleporter events. The only utility it has is indirectly reminding you to stay inside the teleporter circle by muffling the music when you're outside of it. Also volume preferences will differ from setup to setup and it needs to be adjusted in the config which is a bit obtrusive.



## Known Issues
None currently, if you run into anything please contact me on Discord either by DMs ([Fin#1337](https://discord.com/users/386945522608373785)) or by @mentioning me in the [Risk Of Rain 2 Modding](https://discord.com/invite/5MbXZvd) Discord server.
Alternatively you can open an [Issue](https://github.com/fins-mods/REnhanced/issues/new) on GitHub but you'll definitely get a slower response.



## Changelog
These are identical to those found [on GitHub](https://github.com/fins-mods/REnhanced/releases).
If you want notifications you can open that page then: Click the arrow next to "Watch" at the top → Custom → Releases → Apply, and you'll get GitHub notifications (configurable to be push and/or email) whenever the modpack updates.


### 1.0.4 More polish and a new mod- SeerPing
- Changed README ROR2 Modding Discord invite from `discord.gg/` to `discord.com/invite/`
- Fixed capitalization of 'Where I draw the "vanilla flavored" line' in README
- Fixed manifest.json modlist being incorrectly sorted
- Gave README consistent newlines
- Added [SeerPing](https://thunderstore.io/package/Moonlol/SeerPing) by [Moonlol](https://thunderstore.io/package/Moonlol) - "makes the lunar seers show you where they lead when pinged"
- Changed line endings to the unix style LF (\\n) instead of CRLF (\\r\\n). Will affect literally nothing in practice but it's my preference.
- Changed Changelog section text to use `→` instead of `->` since my editor's font ligatures obviously don't apply on Thunderstore.. oops


### 1.0.3 Configuration fix
- Fixed PingItemDescription misconfiguration


### 1.0.2 Polish
- Fix a typo in the README
- Updated mod description
- Add GitHub URL to manifest.json
- Add Changelog section to README
- Add currently empty "Known Issues" section to README
- Remove an accidentally included mod skin mod (oops)
- Sort manifest.json dependency strings alphabetically by mod name (with R2API and BepInEx ones sorted separately at the bottom)
- Somewhat heretically indented dependency strings to be centered around the `author`-`modname` dash delimiters


### 1.0.1 Remove an extra temp file
- Delete a missed temporary file 1.0.1 Remove an extra temp file


### 1.0.0 Initial release
- Initial Release



## Notes

###### \* Balance tweaks that do exist should be imperceptible without a direct 1:1 comparison (you'd fail a blind test).

###### † I have a beefy computer, my friends have beefy computers. If you don't have 8GB of RAM free for the game to use, disable StutterStunterFork. If you have less than 32GB of RAM in your system, change the memory warning and max memory thresholds in the StutterStunterFork config file. If you don't follow these warnings, you will run into trouble. Do not complain to the StutterStunterFork maintainers.
