![](https://img.shields.io/badge/Foundry-v12-informational)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/Syrious/foundryvtt-mobile-companion/total?label=Downloads+Total)
![GitHub Downloads (all assets, latest release)](https://img.shields.io/github/downloads/Syrious/foundryvtt-mobile-companion/latest/total?label=Downloads+Latest)
[![Support me on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3DSyriousWorkshop%26type%3Dpatrons&style=flat)](https://patreon.com/SyriousWorkshop)

[Discord](https://discord.gg/VMqndcyUGS)

# Introduction
Mobile-Companion is designed for in-person gaming sessions, catering to players who prefer not to micromanage their inventory. This module provides a streamlined, clean user interface that displays all relevant information for items, and will soon include spells and other features. With Mobile-Companion, players will never need to look up items in the rulebook again.

### Wait!.. Isn't that what [Sheet-Only](https://github.com/Syrious/foundryvtt-sheet-only) should be used for?
Well... no. [Sheet-Only](https://github.com/Syrious/foundryvtt-sheet-only) is intended to provide the whole character sheet and developed quite fast to a semi-interactive experience where player can do things to in-game token.

Furthermore, [Sheet-Only](https://github.com/Syrious/foundryvtt-sheet-only) uses the system's own character sheet implementation (and modifies it if necessary) and therefore is quite system-agnostic. Mobile-Companion on the other hand only uses the underlying data model and foundry functions, but the UI is made from scratch. Therefore, Mobile-Companion is **not system agnostic**.

Also, system sheets do not provide all the data necessary for in-person sessions. Most of them don't show the roll formula. Mobile-Companion adds all the information a player needs.

And last but not least: Mobile-Companion is intended to work on smaller displays like smartphones!

## Setup
1. Enable the module
2. Go to game settings and add the users who want to use Mobile-Companion. You can enter a number in the field to only activate that user's Mobile-Companion when the screen size is smaller than the entered value (Leave it at 0 to always activate Mobile-Companion for that user).
3. Make sure the user is the owner of an actor

## Supported Systems
### [Level Up: Advanced 5th Edition](https://foundryvtt.com/packages/a5e)
- Inventory
  - [![A5e](https://img.youtube.com/vi/KJzjQq46G20/0.jpg)](https://www.youtube.com/watch?v=KJzjQq46G20)

### [Dungeons & Dragons Fifth Edition](https://foundryvtt.com/packages/dnd5e)
- Inventory
  - [![Dnd5e](https://img.youtube.com/vi/DOKYq5_ZelQ/0.jpg)](https://www.youtube.com/watch?v=DOKYq5_ZelQ)
- Spells
  - [![Dnd5e](https://img.youtube.com/vi/t_cIfB1KSWg/0.jpg)](https://youtu.be/t_cIfB1KSWg)

### [Pathfinder 2e](https://foundryvtt.com/packages/pf2e)
- Inventory

### More to follow... 

## Notes
- Mobile Companion is still in active development and in a very early state
- Some of the footage and information in this document might show an early-access version 

## Future plans
I will at least do the aforementioned systems as well as adding spells. If everything goes smoothly I'll also add additional information, useful to the players like feats, combat maneuvers etc.
