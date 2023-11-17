# Animal Crossing:New Horizons
There are datasets of Animal Crossing: New Horizons contents, which is a game produced by Nintendo.
Researchers can do various investigations by using these datasets, like analyze the popularity of villagers.



##archive

###content
This dataset contains 30 csv files listing items in Animal Crossing: New Horizons, for example, clothing, music, art works, animals, villagers etc.

###source
This dataset comes from [Google Spreadsheet](https://docs.google.com/spreadsheets/d/13d_LAJPlxMa_DubPTuirkIV4DERBMXbrWQsmSh8ReK4/edit#gid=400375391),which is a large and comprehensive inventory of items in Animal Crossing: New Horizons。

###dress-up.csv
**Observations (Rows):** Each row represents an item and there features.
**Variables (Columns):**
| **Header**            | **Description**                                  |**Data Type**|
|-----------------------|--------------------------------------------------|-------------|
| Name                  | name of the item                                 | text        |
| Variation             | variation of the item                            | text        |
| DIY                   | whether it can be DIY                            | boolean     |
| Buy                   | price                                            | number      |
| Sell                  | price                                            | number      |
| Color1                | color1                                           | text        |
| Color2                | color2                                           | text        |
| Size                  | size of the item                                 | text        |
| Source                | where to buy this item in the game               | text        |
| Source Notes          | notes of source                                  | text        |
| Seasonal Availability | the season when this item is available           | text        |
| Mannequin Piece       | whether it is mannequin piece                    | boolean     |
| Version               | version of the game                              | number      |
| Style                 | clothing style                                   | text        |
| Label Themes          | label theme of clothing                          | number      |
| Villager Equippable   | whether villagers can wear this clothing         | boolean     |
| Catalog               | whether the item is for sale                     | boolean     |
| Primary Shape         | primary shape                                    | text        |
| Secondary Shape       | secondary shape                                  | text        |
| Filename              | unknown                                          | text        |
| Internal ID           | unknown                                          | number      |
| Unique Entry ID       | unknown                                          | text        |

##Animal Crossing Portal Villager Popularity

This is a dataset from [Animal Crossing Portal Villager Popularity](https://docs.google.com/spreadsheets/d/13d_LAJPlxMa_DubPTuirkIV4DERBMXbrWQsmSh8ReK4/edit#gid=400375391). It contains villager popularity tier and tier ranking of each villager in the game.

**Content**
Each villager belongs to a tier(1-6), and within each tier there are rankings. Each Tier has a different amount of rankings.
As of 2022, March:
The "Highest Popularity" tier contains 15 villagers
The "Very Popular" tier contains 25 villagers
The "Fairly Popular" tier contains 30 villagers
The "Middle Ground" tier contains 60 villagers
The "Less Popular" tier contains 120 villagers
The "Least Popular" tier contains 163 villagers



