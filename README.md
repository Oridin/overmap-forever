# Overmap Forever

> **ALPHA. Made for WoW Forever only.** It won't work on other World of Warcraft clients or servers. Expect rough edges, and back up your settings before updating.

Overmap Forever draws a see-through map over the game world around you, Diablo / Path of Exile style. It shows the way to where you're going, plus the quest you're on and its steps. A levelling guide suggests what's worth doing next.

## What it does

- **See-through map overlay** around your character: roads, paths, water, buildings, cliffs, zone borders, and icons for flight masters, innkeepers, trainers and mailboxes. You choose what shows.
- **Routes that walk like a player.** They follow the ground, stairs, bridges and floors, steer around dangerous mobs, and use flight paths, boats and the Deeprun Tram when that's quicker.
- **Quest steps on the map.** Pick a quest and the map shows every step without any clicking: walk to the flight master, fly, walk to the area, each objective with its progress (`Dustwind Savage slain: 4/12`), then the hand-in. It warns you when a hand-in sits in a camp full of mobs.
- **Levelling guide.** It ranks what to do next by XP a minute and shows its top three in the drawer beside the map. Quest givers on the map are marked by what it thinks of them.
- **Search.** `/om find` finds any mob, NPC, item or place.
- **Settings profiles.** Save your set-up, load it on any character, and share it with a friend as one line of text.

## Download

**[Latest release ->](https://github.com/Oridin/overmap-forever/releases/latest)**: download the `OvermapForever-<version>.zip` attached to it (about 85 MB).

## Install

1. Download `OvermapForever-<version>.zip` from [Releases](https://github.com/Oridin/overmap-forever/releases).
2. Unzip it into your WoW Forever `Interface\AddOns` folder. You should end up with four folders:
   - `Overmap`
   - `Overmap_Search`
   - `Overmap_Nav_EasternKingdoms`
   - `Overmap_Nav_Kalimdor`
3. Restart the game. A `/reload` doesn't pick up new files.

Keep all four enabled. The search and navmesh folders load themselves when they're needed.

## Getting started

- The map appears around your character. Move the mouse to its top edge to show its title bar, then drag or resize it there.
- Click a quest in your quest log to route to it. You can also Ctrl- or Shift-click the world map, or let the guide pick.
- Hold **Alt** and point at any icon to see what it is. Alt-click it to go there.
- Type **`/om`** for settings and **`/om help`** for the main commands.

## Settings and profiles

Overmap Forever starts with its standard set-up:

- Safest routes and the navmesh router.
- An outline-style map with water, building, cliff and contour layers.
- The levelling guide switched on.

Change anything in `/om`. To save it, open **Settings → Profiles...** or type `/om settings`. From there you can:

- **Save my settings as...**: keep your set-up under a name. Saving under the same name again updates it.
- **Load / Delete**: profiles are account-wide, so every character can load them.
- **Overmap's defaults**: go back to the standard set-up. **Undo** puts yours back.
- **Export mine / Import**: share a set-up as one line of text, copied with Ctrl-C and pasted with Ctrl-V. An imported line can only change settings, nothing else.

A profile never moves the window and never touches what you've learnt in play, such as your flight paths and quests.

## Commands

| Command | Does |
|---|---|
| `/om` | Settings |
| `/om help` | The main commands |
| `/om toggle` | Show / hide the map |
| `/om settings` | Profiles: save, load, share, defaults |
| `/om clear` | Clear the route |
| `/om guide`, `/om top`, `/om nearby` | The levelling guide, its best picks, what's worth doing here |
| `/om find <name>` | Find a mob, NPC, item or place |
| `/om profile safest` | Route style: `fastest`, `safest`, `roads`, `direct`, `explore` |
| `/om marks` | Show only the guide's recommended quest markers |
| `/om status`, `/om errors` | What it's doing, and anything that went wrong |

Key bindings are under **Key Bindings → AddOns → Overmap**.

## Known limits (alpha)

- Built and tested on WoW Forever's client only.
- Map data comes from the game files and can be wrong in places. A route can still try a wall or a cliff now and then.
- Dungeon and city interiors are rougher than the open world.
- The guide's quest choices still need tuning.

## Problems and ideas

Open an [issue](https://github.com/Oridin/overmap-forever/issues). If something broke, include:

- what `/om errors` shows;
- what you were doing, and where (zone, roughly where in it);
- a screenshot, if it's about the map or a route.

This repository holds the releases and this page. The addon is developed elsewhere.

---

Overmap Forever is a fan-made addon. It isn't affiliated with or endorsed by Blizzard Entertainment or the WoW Forever team. World of Warcraft is a trademark of Blizzard Entertainment.
