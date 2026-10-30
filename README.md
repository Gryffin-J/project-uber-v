# project-uber-v

Converting a late-90s Cannondale Uber V into a 40+ MPH (target) electric vehicle powered by a custom 72V 20S10P battery pack built from salvaged lithium cells.

## Battery Pack Target Specs

| Spec | Theoretical (label rating) | Realistic target |
|---|---|---|
| Configuration | 20S10P (200 cells) | 20S10P (200 cells) |
| Cell capacity | 3,200 mAh | 2,400-2,800 mAh |
| Pack capacity | 32 Ah | 24-28 Ah |
| Nominal voltage | 72.0 V | 72.0 V |
| Full charge voltage | 84.0 V | 84.0 V |
| Energy | 2,304 Wh | 1,728-2,016 Wh |

*These are targets, not measured results. They'll be replaced with real data once the cells are tested.*

## Current Status

**10/30/26:** Received 500 salvaged 18650 cells from [Battery Hookup](https://batteryhookup.com), a salvaged-battery reseller. They arrive as 50 modem battery packs of 10 cells each ([listing](https://batteryhookup.com/products/modem-battery-with-10x-3200mah-18650?variant=43375176712354)). I have opened all 50 modem packs and removed the spot welds from 100 cells and tested their voltage and internal resistance. The data is now in [cell-log.csv](../data/cell-log.csv). The average internal resistance was around 38 mΩ, which should be fine for the battery pack. I have also tested the capacity of a batch of 6 cells using the tool I bought (cells 1–6). The capacity of these 6 sample cells ranged from 2,850 mAh to 2,950 mAh, exceeding my expectations (initial estimate was around 2,600 mAh), though I will test more cells to see if the trend holds.

**Next:** Continue removing spot welds and testing internal resistance of the remaining 400 cells.

## Safety Disclaimer

**Please do not use this project as a tutorial. I am learning as I go with this project and will probably make mistakes.**
