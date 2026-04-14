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


