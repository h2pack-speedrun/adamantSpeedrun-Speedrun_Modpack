# Speedrun Modpack

Unrelated Mod to the Hades 1 modpack. Just slightly inspired by it is all.

This is a modular Hades II modpack. Every module here can either be installed individually or part of the pack. It brings together first-hammer selection, in-game LiveSplit-style timing, quality-of-life options, and gameplay-flow quality-of-life adjustments under one shared Speedrun settings window. Optional modules (Boonless, InfiniDD and Quick Pause) are installed separately and join the same window when present.

## How To Open The Settings

In game, open the mod menu from `Mods -> adamantSpeedrun-Speedrun_Modpack -> Show Modpack Menu`.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Speedrun_Modpack/main/assets/HowToOpen.png" width="70%"/>

## What the pack brings instead of individual installs

### Unified UI
Have a single unified UI panel to manage all module toggles, settings, and shared options.

The Quick Setup tab gives each included module a compact enable toggle so a profile can be configured without jumping between separate mod menus.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Speedrun_Modpack/main/assets/FullMenu.png" width="80%"/>

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Speedrun_Modpack/main/assets/QuickSetup.png" width="80%"/>

### Profiles
Save different configurations, such as Any Fear, High Fear, RTA, or multi-run practice, into profiles and load them with one click in game.

Profiles store the shared Speedrun settings state, making it easier to swap between routing, practice, and submission setups.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Speedrun_Modpack/main/assets/Profile.png" width="90%"/>

### Hashing
While the pack is installed, a unique fingerprint will be shown on the side. This is simply to confirm the uniqueness of the configuration in the pack.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Speedrun_Modpack/main/assets/Hashing.png" width="60%"/>

## Included Modules

### Select First Hammer

Choose the guaranteed first Daedalus Hammer for each weapon aspect.

Instead of taking a random first hammer, you can assign a specific opener to every aspect in the game. Leaving an aspect on None (Random) preserves vanilla behavior for that aspect.

The module provides a separate first-hammer selection for every aspect across the full weapon roster. UI layout is grouped by weapon, then by aspect.

#### Hammer Panel Options

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Select_First_Hammer/main/assets/Hammer.png" width="60%"/>

### LiveSplit

In-game splits and timers for Hades II. Built on Museus's Timer mod.

#### Timing

- **IGT**: the game's run timer.
- **RTA**: wall-clock time.
- **LrT**: RTA with map loads removed.

Show any combination. Splits are per biome on Underworld, Surface and Dream Dive routes.

#### Categories

| Category | Goal |
|---|---|
| Single Run | Splits for every run until you stop recording. |
| All Regions | Clear the Underworld and the Surface, either order, same aspect. |
| 3 Weapons | Clears with 3 different weapons. |
| One Weapon | Clears with all 4 aspects of one weapon. |
| All Weapons | Clears with all 6 weapons. |
| All Aspects | Clears with all 24 aspects. |
| Custom | Your own rules. |

Multi-run categories time the whole session: RTA runs from the first run's start, including time in
the Crossroads, and IGT is the sum of every run. Deaths are logged as failed runs and the session
keeps going. Repeats and rule breaks are shown but don't count.

**Custom** can reproduce any preset (Settings → Copy to Custom) and change it:
- up to 50 runs;
- which of region, weapon or aspect must be new or stay the same;
- which regions count;
- whether a death ends the session;
- whether to keep biome splits for every run.

#### Long sessions

- **Pause** (F6) between runs to take a break. The session clocks stop, and the break shows up as
  a Paused split, so the total stays honest.
- Sessions **survive a game exit or crash**. Time with the game closed isn't counted.
- The overlay pages through finished runs with **F7/F8**.

All keys can be rebound under Hotkeys & Advanced. Conflicts with other mods' keys are flagged
there.

### Quality of Life

Thanks to Pony for their QoL mod. This is a port of many of their features into my modpack for hashing/profiles, alongside my own QoL.

Adds practical speedrun quality-of-life options for cleaner menus, faster resets, and better keyboard-and-mouse handling.

#### Direct ports from PonyQoL

- **Always Show Location:** Always displays the current location in the UI.
- **Skip Death Cutscene:** Skips the death cutscene and returns you to the main menu faster while still showing the death screen.
- **Auto Skip Dialogue:** Automatically skips dialogue prompts during gameplay.
- **Skip Run End Cutscene:** Skips the end-of-run cutscene and returns you to the main menu faster while still showing the victory screen.
- **Spawn in Training Grounds:** Spawns you in the Training Grounds instead of next to Frinos pool.

#### Speedrun QoL additions

- **KBM Escape Fix:** Makes Escape work during boon and pom selection, Hex selection, Path of Stars, and death sequences.
- **Rerolling Saves the Game:** Saluting the Oath statue now triggers a game save.
- **Arcana & Fear on Victory Screen:** Displays Arcana and Fear on the victory screen.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-QoL/main/assets/victory2.jpg" width="80%"/>

### Gameplay QoL

Adds run-flow and routing helpers for speedrun routing and practice.

Current options:

- **Skip Gem Boss Reward:** Stops bosses from dropping gem rewards when using Grave Thirst.
- **Prevent Echo Scam:** Blocks both Fields minibosses from spawning in room 3 to prevent Echo scam.
- **No Selene in First Room:** Removes Selene from the reward roster of the first room of a run.
- **Disable Arachne Pity:** Disables Arachne pity entirely for Any Fear runs.
- **Force Arachne Spawn:** Forces Arachne to spawn to reduce death pity reset.
- **Force Medea Spawn:** Forces Medea to spawn to reduce death pity reset.
- **Incrementing Fig Leaf:** Dionysus skip chance starts at the default value (37%), increases by 13% after every encounter, and resets on biome start.
- **Disable Charybdis:** Prevents Charybdis from appearing on Thessaly.
- **Remove Thessaly Heracles:** Removes Heracles encounter from Thessaly.
- **Jeweled Pom Boon:** Chooses which Hades boon the Jeweled Pom grants. Falls back to a random Hades boon if the chosen one is not eligible (Last Gasp).
- **Fix Zagreus Timer Freeze:** Resumes the run timer when Zagreus is killed right after he rises again; vanilla leaves it paused for the rest of the run. On by default.
- **Disable Codex and Inventory when IGT is active:** The Codex, Inventory and trait Info screens pause the in-game timer, so during a run they can only be opened while the timer is already paused. On by default as a leaderboard rule.

## Optional Modules

These modules are not installed by the pack. Install them from Thunderstore when you want them: each works on its own, and when the Speedrun modpack is installed it adds them to its window.

- [Boonless](https://thunderstore.io/c/hades-ii/p/adamantSpeedrun/Boonless/)
- [InfiniDD](https://thunderstore.io/c/hades-ii/p/adamantSpeedrun/InfiniDD/)
- [Quick Pause](https://thunderstore.io/c/hades-ii/p/adamantSpeedrun/Quick_Pause/)

### Boonless

This module provides the option to transform all run rewards into onions of spare gold. It meant for challenge runs under a maybe Boonless category.

Current options:

- **Preset Dropdown:** Applies common Boonless checkbox configurations from the full module tab or Quick Setup.
- **Individual Reward Toggles:** Converts selected boons, NPC rewards, Chaos, Selene, or Daedalus Hammer offers into Shared Wealth.
- **Vow of Forfeit Toggles:** Lets Vow of Forfeit keep skipping selected boon, Selene, or hammer room rewards without consuming the biome skip count.

Individual checkboxes can target normal boons, hammers, Selene, each route NPC, and Chaos. Boon, hammer, and Selene controls each pair a Shared Wealth fallback with a matching Vow of Forfeit skip toggle.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Boonless/main/assets/options.png" width="60%"/>

Presets cover common route shapes:

- Removing normal boons only
- Removing Olympian gifts, including the core gods plus Athena, Artemis, Dionysus, and Hades
- Removing Olympian, NPC, and special gifts, including Medea, Circe, Icarus, Arachne, Narcissus, Echo, Chaos, and Selene
- Converting hammers as part of the full Shared Wealth preset

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-Boonless/main/assets/presets.png" width="60%"/>

### InfiniDD

Adds an infinite Death Defiance practice mode for testing recovery, survival, and late-run routing after all real Death Defiances are gone.

Current options:

- **Practice Recovery:** Configures how much health and magick a practice Death Defiance restores.
- **Death Counter Overlay:** Shows a right-side counter for practice Death Defiances used in the current run.
- **Practice Slowdown:** Optionally slows the player, enemies, projectiles, and world objects for a short duration after the base Death Defiance sequence finishes.

### Quick Pause

Freezes or slows the game with a hotkey, without opening the pause menu. It uses the game's own simulation-speed slowdown, so the world stops while the screen stays clear.

Current options:

- **Pause Hotkey:** The key that toggles the freeze (F5 to F12, F9 by default).
- **Speed While Paused:** How much of normal speed remains while paused. 0 is a full freeze.
- **Block Actions While Paused:** Stops attacks and dashes from queueing up.
- **PAUSED Indicator:** Shows a small badge in the corner while paused.


## How To Use

Install via r2modman. In game, open the Speedrun menu and configure the modules from the shared settings window. Optional modules you installed separately appear there too.

The Quick Setup tab provides module-level enable toggles. Open a module tab for individual settings.

## More Information

- [Changelog](CHANGELOG.md)
- [Speedrun shell repo](https://github.com/h2pack-speedrun/speedrun-modpack)
