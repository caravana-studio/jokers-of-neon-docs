---
sidebar_position: 2
---

# Rounds and Map Flow

## Map Structure

Runs are divided into levels, and each level generates a procedural map.

- Total stages per level: `4 + level`
- Level 1 has 5 stages, Level 2 has 6, Level 3 has 7, and so on.
- The first stage is always a **Round**.
- The last stage is always a **boss Rage**.
- Maps can branch, and players choose their route through connected nodes.

## Node Distribution

- Base stage distribution is roughly **90% Round** and **10% Rage** before forced placements.
- Each map contains between **2 and 5 rage encounters**, not counting the final boss rage.
- Store nodes appear after progression nodes and act as the main upgrade checkpoints.
- A stage can contain up to 4 nodes.

## Rage Placement

- Rages are spread through the map instead of being front-loaded.
- The final rage of each level is always the strongest encounter of that map.
- Some rage effects cannot appear together in the same round.

## Rage Round Power System

Each rage node has a power budget that determines how many rage effects can be rolled.

- Non-final rages use `min(rage encounter count, 8)` as the budget.
- Final boss rages use `min(rage encounter count, 8) + 2`.
- Rage rarity also determines power cost:
  - `C = 1`
  - `B = 2`
  - `A = 3`
  - `S = 4`

The game keeps selecting unique rage cards until the budget is spent.

## Rage Round Configuration

- Initial random rage chance: **35%**
- Chance increase per round: **+15%**
- Maximum active rages in one encounter: **4**
- Minimum round level before rage activation: **3**
- Level cooldown: **1**

## Round Target Score Curve

The round counter is global across the whole run. It does not reset when a new level begins.

- Rounds 1-5: `300 * round`
- Rounds 6-11: `2,400 + (round - 6) * 900`
- Rounds 12-18: `10,500 + (round - 12) * 3,600`
- Rounds 19-26: `50,100 + (round - 19) * 18,000`
- Rounds 27-35: `284,100 + (round - 27) * 108,000`
- Rounds 36-45: `1,904,100 + (round - 36) * 756,000`
- Rounds 46-56: `14,756,100 + (round - 46) * 6,048,000`
- Rounds 57+: `178,052,100 + (round - 57) * 54,432,000`

The curve accelerates hard, so late-run consistency and scaling matter more than raw early tempo.
