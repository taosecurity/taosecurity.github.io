# Richard Presents Development Hub

Richard Presents Development Hub is the starting page for my free Starfield sites and tools. Each card on it says what one site or tool does for you and links to it.

Open the site: https://taosecurity.github.io/

## Example

Start here if you are new. Say you want 100 rounds of 7.77mm ammo in your game on PC:

1. Open the hub and click **Starfield Item IDs** under "Console and reference lists".
2. Type `7.77` in the search box. The Ammo group shows **7.77mm Caseless**, with the FormID `0004AD3E`.
3. Type `100` in the Count box, then click the command `player.additem 0004AD3E 100` to copy it.
4. In the game, press **~** (the key under Esc) to open the console, paste the command and press Enter.

You get 100 rounds of 7.77mm Caseless ammo. Xbox and PlayStation have no console. Using the console turns off achievements for that save unless you use a mod that keeps them on.

What's new: see the top of the [live page](https://taosecurity.github.io/).

## What's on the hub

**Trends:**

- [Tracking Starfield on Nexus Mods](https://taosecurity.github.io/NexusModsMetrics/) compares Starfield's mod downloads, mod counts and mod types with the other top games on Nexus Mods, every day.
- [Xbox Top 40 Tracker](https://taosecurity.github.io/xbox-top40-tracker/) charts where Starfield and ten other games place each week in the TrueAchievements Xbox top 40.

**Console and reference lists**, read from the game files:

- [Starfield Console Commands](https://taosecurity.github.io/starfield-console-commands/) lists every console and script command, with examples you can copy.
- [Starfield Item IDs](https://taosecurity.github.io/starfield-item-ids/) gives the FormID of every item you can spawn, with copyable `player.additem` commands.
- [Starfield Locations](https://taosecurity.github.io/starfield-locations/) lists every place you can reach with the `coc` command.
- [Starfield Game Settings](https://taosecurity.github.io/starfield-game-settings/) lists every game setting and INI setting with its default value.
- [Starfield Globals and Quests](https://taosecurity.github.io/starfield-globals-quests/) lists every global variable and quest, with every quest stage.
- [Starfield Record Types](https://taosecurity.github.io/starfield-record-types/) is a plain-English guide to every record type in Starfield.esm.
- [Starfield Version History](https://taosecurity.github.io/starfield-version-history/) lists every Starfield version, with its date, highlights and patch notes.

**Worked examples:**

- [Scene Hunt: The Kneeling Mourner](https://taosecurity.github.io/starfield-scene-hunt/) traces a scene a player saw in the game to the mod that adds it, step by step.

**Modding tools**, each with its own GitHub page and download:

- [sf-mod-check](https://github.com/taosecurity/sf-mod-check) checks a plugin for problems that break it in the game.
- [papyrus-log-check](https://github.com/taosecurity/papyrus-log-check) checks a Papyrus log against the lines your mod should write.
- [BuildKit](https://github.com/taosecurity/BuildKit) is a C# library for writing Starfield plugins with Mutagen.
- [sf-cut-check](https://github.com/taosecurity/sf-cut-check) finds content the game never uses, in the game or in your own plugin.
- [sf-pex-tools](https://github.com/taosecurity/sf-pex-tools) compares compiled Papyrus scripts and the files inside `.ba2` archives.
- [sf-log-collector](https://github.com/taosecurity/sf-log-collector) gathers the logs a mod author asks for into one zip.
- [sf-mod-build](https://github.com/taosecurity/sf-mod-build) builds a mod from one project file with one command.
- [sf-load-order](https://github.com/taosecurity/sf-load-order) checks your load order before you play.
- [sf-save-reader](https://github.com/taosecurity/sf-save-reader) shows what is in a save: the character, its plugins and every quest's state.
- [sf-save-health](https://github.com/taosecurity/sf-save-health) checks a save against the mods you have installed now.
- [sf-test-plan](https://github.com/taosecurity/sf-test-plan) turns a Markdown test plan into an offline checklist page.
- [sf-papyrus-ref](https://github.com/taosecurity/sf-papyrus-ref) tells you offline whether a Papyrus function exists in Starfield, and checks your scripts.
- [sf-patch-day](https://github.com/taosecurity/sf-patch-day) tells you after a game update which of your SFSE plugins still load.
- [Starfield Voice Tool](https://github.com/taosecurity/StarfieldVoiceTool) lets you browse, play and save every voiced line and sound.

**General purpose tools:**

- [SquareSnap](https://github.com/taosecurity/SquareSnap) takes square screenshots on Windows, in WSL and on Linux.
- [BejView](https://github.com/taosecurity/BejView) opens and searches text files of many gigabytes in seconds.

Each tool's card shows its latest version and links to its download page.

## Words used here

- **Console:** the PC command line inside the game, opened with ~.
- **FormID:** a record's number, such as `0004AD3E`. The first two digits depend on the load order.
- **Plugin:** a mod's data file (`.esm`, `.esp` or `.esl`). It adds or changes records in the game.
- **Papyrus:** Starfield's scripting language. Scripts are written as `.psc` source files and compiled into `.pex` files that the game runs.
- **SFSE:** the Starfield Script Extender, which loads `.dll` plugins that add features the game lacks. Each game update can break them until they are updated.

## Found a mistake?

Open an issue in the repo of the site or tool it's about. The "About" section at the bottom of the hub links to each one's issue page. For the hub itself, open an issue: https://github.com/taosecurity/taosecurity.github.io/issues

## Credits and License

Richard Bejtlich of [Richard Presents Starfield Essentials](https://www.youtube.com/@RichardBejtlich) made these pages.

These are unofficial pages, not made or endorsed by Bethesda. Starfield is a trademark of ZeniMax Media.

The hub is a single self-contained `index.html` with no external dependencies. It is MIT licensed; see [LICENSE](LICENSE). Each site and tool has its own license, named in its repo.
