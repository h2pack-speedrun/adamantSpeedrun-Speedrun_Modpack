# Speedrun Modpack

Unrelated Mod to the Hades 1 modpack. Just slightly inspired by it is all.

This is a modular Hades II modpack. Every module here can either be installed individually or part of the pack. It brings together first-hammer selection, boonless route controls, infinite Death Defiance practice, in-game LiveSplit-style timing, quality-of-life options, and gameplay-flow quality-of-life adjustments under one shared Speedrun settings window.

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

Adds native LiveSplit-like timing support to the game. Thanks to Museus for their original Timer mod. This is a big expansion on that.

#### Examples
The recording table can show biome splits with selected timing columns while a run is active.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-LiveSplit/main/assets/Timer1.png" width="60%"/>


<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-LiveSplit/main/assets/Timer2.png" width="60%"/>

LiveSplit records runs and shows selected timing information while you play. Its main feature is a compact recording table that tracks your route through a run.

Supported timing views include:

- Underworld routes: Erebus, Oceanus, Fields, and Tartarus
- Surface routes: Ephyra, Thessaly, Olympus, and The Summit
- Dream Dive routes, with biome order detected from the run
- Single-run split recording
- Multi-run batch recording for routing or practice sessions
- IGT, RTA, and LrT timing columns
- Recording continues until you stop recording

#### Options while doing single run repeated recording
Single-run mode keeps the next run ready for split recording and is aimed at repeated normal attempts.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-LiveSplit/main/assets/SingleRun.png" width="60%"/>

#### Options while doing multi run repeated recording
Multi-run mode records a batch of consecutive runs and keeps cumulative batch totals.

<img src="https://raw.githubusercontent.com/h2pack-speedrun/adamantSpeedrun-LiveSplit/main/assets/MultiRun.png" width="60%"/>

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


## How To Use

Install via r2modman. In game, open the Speedrun menu and configure the modules from the shared settings window.

The Quick Setup tab provides module-level enable toggles. Open a module tab for individual settings.

## More Information

- [Changelog](CHANGELOG.md)
- [Speedrun shell repo](https://github.com/h2pack-speedrun/speedrun-modpack)
