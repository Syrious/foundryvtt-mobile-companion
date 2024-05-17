![](https://img.shields.io/badge/Foundry-v11-informational) ![GitHub All Releases](https://img.shields.io/github/downloads/Syrious/foundryvtt-mobile-companion/total?label=Downloads+latest+release) [![Support me on Patreon](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3DSyriousWorkshop%26type%3Dpatrons&style=flat)](https://patreon.com/SyriousWorkshop)

[Join the Discord Community](https://discord.gg/VMqndcyUGS)

Still in alpha!

# Introduction
Mobile-Companion is designed for in-person gaming sessions, catering to players who prefer not to micromanage their inventory. This module provides a streamlined, clean user interface that displays all relevant information for items, and will soon include spells and other features. With Mobile-Companion, players will never need to look up items in the rulebook again.

### Wait!.. Isn't that what [Sheet-Only](https://github.com/Syrious/foundryvtt-sheet-only) should be used for?
Well... no. [Sheet-Only](https://github.com/Syrious/foundryvtt-sheet-only) is intended to provide the whole character sheet and developed quite fast to a semi-interactive experience where player can do things to in-game token.

Furthermore, [Sheet-Only](https://github.com/Syrious/foundryvtt-sheet-only) uses the system's own character sheet implementation (and modifies it if necessary) and therefore is quite system-agnostic. Mobile-Companion on the other hand only uses the underlying data model and foundry functions, but the UI is made from scratch. Therefore, Mobile-Companion is **not system agnostic**.

Also, system sheets do not provide all the data necessary for in-person sessions. Most of them don't show the roll formula. Mobile-Companion adds all the information a player needs.

And last but not least: Mobile-Companion is intended to work on smaller displays like smartphones!

[example.mp4](assets/example.mp4.mov)
https://github.com/Syrious/foundryvtt-mobile-companion/blob/main/assets/example.mp4.mov

## Setup
1. Enable the module
2. Go to game settings and add the users who want to use Mobile-Companion. You can enter a number in the field to only activate that user's Mobile-Companion when the screen size is smaller than the entered value (Leave it at 0 to always activate Mobile-Companion for that user).
3. Make sure the user is the owner of an actor

## Supported Systems
Currently, I am working on DND5e and A5e. When this is done I probably go to Pf2e. Additional systems will follow.

## Future plans
I will at least do the aforementioned systems as well as adding spells. If everything goes smoothly I'll also add additional information, useful to the players like feats, combat maneuvers etc.
