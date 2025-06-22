# Cat Bot Packs

1. A pack starts with some specific rarity.
2. One of two random outcomes can happen at this step:
    - 70% chance: the current rarity becomes final rarity, go to step 3;
    - 30% chance: upgrade by one rarity and repeat step 2 (unless the pack is a Celestial).
3. Once a final pack rarity is chosen, get its Base Value, see table:

|  **Pack** | **Base Value** |
| --- | --- |
| Wooden | 65  |
| Stone | 90  |
| Bronze | 100 |
| Silver | 115 |
| Gold | 230 |
| Platinum | 630 |
| Diamond | 860 |
| Celestial | 2000 |

4. A random cat type is picked. Every cat type has the same chance of being chosen: 1/22.
5. Find out the result number of cats to reward: `Pack Base Value / Cat Type Value`. See table for cat type values:

| **Cat Type** | **Value** |
| --- | --- |
| Fine | 4.1 |
| Nice | 5.48 |
| Good | 8.22 |
| Rare | 11.74 |
| Wild | 14.94 |
| Baby | 17.86 |
| Epic | 20.54 |
| Sus | 23.47 |
| Brave | 27.39 |
| Rickroll | 32.86 |
| Reverse | 41.08 |
| Superior | 51.35 |
| Trash | 82.16 |
| Legendary | 117.37 |
| Mythic | 164.32 |
| 8bit | 205.4 |
| Corrupt | 273.87 |
| Professor | 410.8 |
| Divine | 513.5 |
| Real | 821.6 |
| Ultimate| 1369.33 |
| eGirl | 2054 |

6. The whole part of the result number is the guranteed reward.
7. For the fractional part, it represents the chance of getting another cat.
   - For example, `42.69` means you will get 43 cats in 69% of cases, and 42 in other 31%.
8. If the result reward is nothing, fall back to 1 Fine cat.
