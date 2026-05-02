---
{"dg-publish":true,"permalink":"/portfolio/5th-cataclysm/","tags":["portfolio"],"dg-note-properties":{"tags":["portfolio"]}}
---

# Overview
5th Cataclysm is a JRPG-style Deck builder hybrid featuring randomly generated loot, enemies, and a dungeon to explore.

- [Landing Page](https://5thcataclysm.com/)
- [Itch Link](https://strfried.itch.io/5th-cataclysm)
- [Steam Link](https://store.steampowered.com/app/3515750/5th_Cataclysm_Demo/)

Below is all of the content designed for the combat system.

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
      - AP
      - Uses
      - Description
      - Is Temp
      - Is Repairable
      - Price
      - Stocked by Moonman
      - Stocked by Starman
    columnSize:
      note.AP: 74
      note.Uses: 81
      note.Description: 562
      note.Price: 72

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
      - HP
      - Hand Draw Size
      - Deck
      - Rewards
      - tags
    sort:
      - property: file.name
        direction: ASC
      - property: Deck
        direction: ASC
    columnSize:
      note.HP: 57
      note.Hand Draw Size: 130
      note.Deck: 841

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
      - Cards Count
      - Chance for Another Card
      - Possible Base Cards
      - Possible Modifiers
      - Money
      - Mod Count
      - Rewards All Listed Cards
    sort:
      - property: file.name
        direction: ASC
      - property: Cards Count
        direction: DESC

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
      - HP Change
      - Additional Rewards

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
      - Prefix
      - Suffix
      - Price Mod
      - AP Mod
      - Effects

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
      - Enemies
      - Possible Enemy Modifiers
      - Environment
      - Wander Range
      - Stay on Map
    sort:
      - property: Stay on Map
        direction: ASC

```

