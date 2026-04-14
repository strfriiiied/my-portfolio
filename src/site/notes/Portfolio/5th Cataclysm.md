---
{"dg-publish":true,"permalink":"/portfolio/5th-cataclysm/","tags":["portfolio"],"dg-note-properties":{"tags":["portfolio"]}}
---

# Links
- [Landing Page](https://5thcataclysm.com/)
- [Itch Link](https://strfried.itch.io/5th-cataclysm)
- [Steam Link](https://store.steampowered.com/app/3515750/5th_Cataclysm_Demo/)

# System Design / Wiki
## Cards List

```base
filters: file.folder == "5th Cataclysm/Cards List CSV"
views:
  - type: table
    name: Table
    order:
      - file.name
      - Description
      - AP
      - Uses
      - Is Temp
      - Is Repairable
      - Price
      - Stocked by Moonman
      - Stocked by Starman
    columnSize:
      note.Description: 494
      note.AP: 54
      note.Uses: 68
      note.Price: 73
      note.Stocked by Moonman: 178

```


## Enemies List

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

