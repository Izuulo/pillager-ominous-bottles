# Pillager Ominous Bottles

A Minecraft **26.3** data pack that makes regular (non-banner) pillagers drop an Ominous Bottle.

| Level | Chance |
|-------|--------|
| Bad Omen IV | 50% |
| Bad Omen I, II, III, V | 12.5% each |

Banner-carrying pillagers (captains) keep their vanilla drop (uniform I–V).

## Install
Copy this folder (or the release zip) into `<world>/datapacks/` and run `/reload`.

## Tweaking
Edit `data/minecraft/loot_table/entities/pillager.json`. The second pool holds the weights
(amplifier `3` = level IV, weight 4 out of 8). To add an overall drop chance, put a
`minecraft:random_chance` condition on that pool.

Note: this overrides the vanilla `entities/pillager` loot table and may conflict with other packs that do the same.
