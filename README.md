# Interrupt Bar addon for TBC Classic

This is an updated version of the once popular InterruptBar created by Kollektiv. The goal is to have this lightweight addon working for TBC Classic.

## Maintenance

Updating the addon's target version to the latest client.

Command for getting the current client version:

`/run print((select(4, GetBuildInfo())));`

Enable/Disable LUA errors in the client:

`/console scriptErrors 0/1`

## New Features

I've added a few features that were missing in the original version:

- Rank agnostic detection - the addon now tracks all ranks of the spells

## TODO Features

- Interface for adding, removing spells
- Default melee, caster presets