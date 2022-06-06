# D2R Loot Filter

This is a D2R mod that modifies item labels and provides a psuedo loot filter.

### Common item labels
- Health Potions: `HP1` to `HP5`
- Mana Potions: `MP1` to `MP5`
- Rejuvination Potions: `+Rejuv` and `+Full Rejuv`
- Stamina Potion: `Stam!`
- Thawing Potion: `Thaw!`
- Antidote: `Anti!`
- Tome of Town Portal: `!TP!`
- Scroll of Town Portal: `TP!`
- Tome of Identify: `!ID!`
- Scroll of Identify: `ID!`
- Gold: `<Amount> g`

![common](https://user-images.githubusercontent.com/10291543/171337986-5cbd98a9-3268-478e-bdc7-749eefc91487.png)

### Colorful gem labels
- Flawless Gems: `+Flawless <Gem>`
- Perfect Gems: `+Perfect <Gem>`

![gems](https://user-images.githubusercontent.com/10291543/171337977-2d5fba39-8a2b-486d-9cd1-58d4151f801a.png)

### Big hitboxes
- High Runes
- Diablo Essence
- Baal Essence
- Diadem

![ber](https://user-images.githubusercontent.com/10291543/171337964-c67233fd-9217-41ce-aa57-f75593429bd2.png)

### Light beam effect
- High Runes
- Uber Keys

### Essence labels
- Twisted Essence of Suffering: `Andy Essence` (Duriel drops it too)
- Charged Essence of Hatred: `Meph Essence`
- Burning Essence of Terror: `Diablo Essence`
- Festering Essence of Destruction: `Baal Essence`

### Blank labels
- Arrows
- Bolts
- Strangling Gas Potion
- Fulminating Potion
- Choking Gas Potion
- Exploding Potion
- Rancid Gas Potion
- Oil Potion

![hidden](https://user-images.githubusercontent.com/10291543/171337953-9e7944ac-2ff2-4a2f-bf65-8ccea8e0e8f7.png)

# Disclaimer

Although this uses D2R's built-in modding system, Blizzard's stance on using mods online is not well defined. Use it online at your own risk.

# Download

https://github.com/admon84/d2r-loot-filter/archive/refs/heads/main.zip

# Install Mpq

Standard install method for most people.

1. [Download](#download) and extract the mod files (anywhere)
2. Create a "mods" folder in your D2R installation directory
3. Copy the extracted "lootfilter" folder into "mods"
    - If done correctly, the structure should match https://i.imgur.com/hZAvJI6.png
4. Edit game settings in your battle.net launcher and add `-mod lootfilter -txt` to your parameters, https://i.imgur.com/LG9Fpn2.png
    - If your parameters includes -direct, follow the "Install into Extracted Data" steps instead
5. Launch the game and enjoy

# Install into Extracted Data

If you are using `-direct -txt` in your launch parameters, follow these steps to add the mod files on top of the extracted data.

1. [Download](#download) and extract the mod files (anywhere)
2. Copy the "global", "hd" and "local" folders from lootfilter\lootfilter.mpq\Data into your D2R\Data folder. Select overwrite all when prompted
5. Launch the game and enjoy

# Development

If you want to make changes to the loot filter, you can extract data and perform a full installation.

1. Download CascView from http://www.zezula.net/en/casc/main.html
2. In CascView, Open Storage and select your D2R folder
3. Expand data/data on the left and extract "global", "hd" and "local" folders into your D2R\Data folder
4. [Download](#download) and extract the mod files (anywhere)
5. Copy the "global", "hd" and "local" folders from lootfilter\lootfilter.mpq\Data into your D2R\Data folder. Select overwrite all when prompted
6. Edit your game shortcut to add `-direct -txt` to the end. If using battle.net launcher, you can set this in game properties. https://i.imgur.com/kgP3VFZ.png

# Credits

Fork of original work in [AlexisEvo/d2r-loot-filter](https://github.com/AlexisEvo/d2r-loot-filter)
