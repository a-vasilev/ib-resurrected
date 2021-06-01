# Interrupt Bar addon for TBC Classic

Lightweight cooldown tracking addon for TBC Classic. Build ontop of the once popular InterruptBar by Kollektiv.

[Curseforge Project](https://www.curseforge.com/wow/addons/interruptbar-resurrected-tbc)

## Maintenance

Updating the addon's target version to the latest client.

Command for getting the current client version:

`/run print((select(4, GetBuildInfo())));`

Enable/Disable LUA errors in the client for debugging:

`/console scriptErrors 0/1`

`/run SetCVar("nameplateMaxDistance", "41")`

## New Features

I've added a few features that were missing in the original version:

- Rank agnostic detection - the addon now tracks all ranks of the spells
- Configuration for number of icons per row       - `/ib columns <number>`
- Configuration for transparency of the whole bar - `/ib alpha <number>`
- More robust input validation, there was none
- Added a lot of spells by default
- Command for adding abilities through the game, no need to edit the lua anymore (but you still can)

## TODO Features

- Interface for adding/removing spells
- Default melee, caster presets