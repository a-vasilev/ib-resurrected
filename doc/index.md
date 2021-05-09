# Interrupt Bar addon for TBC Classic

Lightweight cooldown tracking addon for TBC Classic. Build ontop of the once popular InterruptBar by Kollektiv. The core functionality is the same as it used to be.

I've always been a fan of this addon, so when I got into the TBC Beta I got nostalgic and decided to resurrect it for personal use. I found an old version from WOTLK or Cata and updated it for the TBC client. I also fixed a few bugs that were always present and added a few more configuration options.

I intend to keep it up to date through TBC Classic and add some QoL features.

## Commands usage

Use `/ib` for printing all commands in the chat window.

- `/ib scale <number>` - Scales the size of the whole bar, 1 is for the default size
- `/ib columns <number>` - How many icons will be displayed per row. The default is 0 and it means everything is displayed on 1 row
- `/ib alpha <number>` - Sets the transparency of the whole bar. The values must be between 0 and 1, where 0 is invisible and 1 is completely opaque
- `/ib add <spellid> <cooldown>` - Adds a new ability for tracking, take the spellid from wowhead. The rank of the ability doesn't matter, the addon will track all ranks.
- `/ib hidden` - This is a toggle. When enabled the icons will be hidden until a spell has been used, so you only see the ones that are currently on cooldown
- `/ib lock` - This is a toggle
- `/ib test` - Triggers the cooldown of all tracked spells
- `/ib reset` - Resets all configuration, removes all added spells. Run a /reload after this command to make sure everything works ok.