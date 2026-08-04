---
{"dg-publish":true,"permalink":"/portfolio/5th-cataclysm/","tags":["portfolio"],"dg-note-properties":{"tags":["portfolio"]}}
---

5th Cataclysm is a JRPG-style Deck builder hybrid featuring randomly generated loot, enemies, and a dungeon to explore.

- [Steam](https://store.steampowered.com/app/3515750/5th_Cataclysm_Demo/)
- [Landing Page](https://5thcataclysm.com/)
- [Itch.io](https://strfried.itch.io/5th-cataclysm)

# System Design / Wiki
## Cards List
Cards are the bread and butter of the game. They represent all possible actions in combat. Each character in the game that the player can fight against has a deck of cards. A core pillar of the game is that every card should be playable by the player and by all enemies. Cards also have effects on the overworld. This can be initiating combat or affecting the environment in different ways. For example, keys can be used on doors to unlock them.

```base
filters: file.folder == "5th Cataclysm/Cards List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Card Name
      - AP Cost
      - Description
      - Is Repairable
      - Price
      - Targets
      - Stocked by Item Merchant
      - Stocked by Weapon Merchant
      - tags
      - dg-publish

```


## Enemies List
Each enemy is represented by a character in game. Enemies are contained within Encounters, and themselves have a deck of cards and a possible reward pool.

```base
filters: file.folder == "5th Cataclysm/Enemies List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Name
      - HP
      - Hand Draw Size
      - Deck
      - Rewards
      - Links
      - tags
      - dg-publish

```


## Rewards List
Rewards can be environmental pickups, or drops from enemies after combat.

```base
filters: file.folder == "5th Cataclysm/Rewards List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Filename
      - Cards Count
      - Chance for Another Card
      - Possible Base Cards
      - Possible Modifiers
      - Money
      - Mod Count
      - Rewards All Listed Cards
      - Links
      - tags
      - dg-publish

```


## Enemy Mods List
Mods are randomly applied to enemies when combat is initiated.  They can affect health, add cards to the character's deck, and alter their reward drops.

```base
filters: file.folder == "5th Cataclysm/Enemy Mods List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Mod Name
      - Cards Added to Deck
      - HP% Change
      - Additional Rewards
      - Filename
      - Links
      - tags
      - dg-publish

```


## Card Mods List
Card Mods can be randomly applied to cards when they are rewarded (or perhaps through other means as well?). They can affect how much the card sells for, it's AP cost to play, and add effects to it.

```base
filters: file.folder == "5th Cataclysm/Card Mods List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Name
      - Prefix
      - Suffix
      - Price Modifier
      - AP Modifier
      - Effects
      - Links
      - tags
      - dg-publish

```


## Encounter Data List
Encounters determine which enemies can spawn, what the environment looks like, and how far the enemy party can wander on the Overworld.

```base
filters: file.folder == "5th Cataclysm/Encounter Data List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Filename
      - Enemies
      - Possible Enemy Modifiers
      - Environment
      - Links
      - tags
      - dg-publish

```


# Challenges
In the new roguelike version, challenges are intended to be the primary form of meta progression.

```base
filters: file.folder == "5th Cataclysm/Challenges List"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Challenge Name
      - Description
      - Links
      - tags
      - Filename
      - dg-publish

```
