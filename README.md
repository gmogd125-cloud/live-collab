# Live Collab

A Geode mod for Geometry Dash 2.2081 (Windows): build a level together with your friends, live, in the normal editor.

- Everything anyone places, moves, edits or deletes shows up for everyone right away
  (level settings, colour channels and the song too).
- Friends' selections glow in their colour with their name; their cursors move on your screen.
- Auto split: one part of the level per person, green lines around yours, red for the others.
  The host can slide the lines to resize parts, and Lock zones keeps everyone in their own part.
- Rooms stay up when the host leaves and are kept for 14 days, so you can come back with the code.
- Save and Play or leaving the editor keeps you in the room; start positions are personal.
- The host can kick or ban people, and unban them from the Banned list.

## Install

1. Install [Geode](https://geode-sdk.org).
2. Download `gmo12.live_collab.geode` from the [latest release](../../releases/latest).
3. Put it in `Geometry Dash\geode\mods` and start the game.

After that it updates itself: on the main menu it checks this repo for a newer release, downloads it,
checks it against GitHub's SHA-256 and asks you to restart (Later or Restart). You can turn this off
in the mod's settings (Auto-update).

## Use

Open a level in the editor and press **Collab** (top right). **Host this level** gives you a room code.
Friends open a new empty level, press **Collab**, type the code and press **Join**.
Everyone in a room needs the same version.
