---
aliases:
  - Encounters
---
An encounter is a situation presented by the [[App]] that the player must resolve. Encounters have a few parts:
- Type
- Icon on [[Tiles]]
- Button on [[Encounter Selection Screen]] with Icon
- Encounter resolution screen

All encounter resolution screens should display one of the following when complete:
- [[Encounter Selection Screen]]
- [[Movement Timer Screen]]
- [[Setup Screen]]
- A different encounter resolution screen up to 2 times

| Icon                  | Encounter Name | Likely Encounter Resolution Screen                                       |
| --------------------- | -------------- | ------------------------------------------------------------------------ |
| ![[Stairs.png\|50]]   | Stairs         | [[Stairs Screen]]                                                        |
| ![[Loot.png\|50]]     | Loot           | [[Loot Screen]]                                                          |
| ![[Merchant.png\|50]] | Merchant       | [[Merchant Screen]]; might not be consumed                               |
| ![[Quest.png\|50]]    | Quest          | [[Quest Screen]]                                                         |
| ![[Puzzle.png\|50]]   | Puzzle         | [[Puzzle Screen]]; timed; might not be consumed                          |
| ![[Obstacle.png\|50]] | Obstacle       | [[Obstacle Screen]]; cannot explore new [[Tiles]]; might not be consumed |
| ![[Trap.png\|50]]     | Trap           | [[Trap Screen]]; stops movement                                          |
| ![[Combat.png\|50]]   | Combat         | [[Combat Screen]]; cannot explore new [[Tiles]]                          |
| ![[Ambush.png\|50]]   | Ambush         | [[Combat Screen]] at disadvantage; stops movement                        |
| ![[Boss.png\|50]]     | Boss           | [[Combat Screen]]; if players flee won't roam or be consumed             |
