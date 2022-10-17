# DnD-Monsters
An exploration of different monsters in the world of Dungeons and Dragons (DnD), featuring **extensive data cleaning**, **visualization** and **machine learning** techniques to **predict** missing Challenge Ratings for monsters.

We use a dataset of $2,947$ monsters from the publicly available dataset on Kaggle by the user POKETCH : https://www.kaggle.com/datasets/poketch/dungeons-dragons-5e-monster-data

A brief description of its columns:
| Column | Description |
|--------|-------------|
|   id   | The id of each unique monster |
| name | The name of each unique monster |
| cr | Challenge Rating of a monster, a measure of how difficult it is to defeat in battle |
| hp, hp formula, hp special | Average health of a monster, the formula used to compute it's health, any special modifiers to a monster's health |
| ac, ac special | Armor Class of a monster, or how hard it is to damage a monster |
| str, str save | Strength of a monster, it's saving throw measures how well a monster can oppose a physical force |
| dex, dex save | Dexterity of a monster, it's saving throw measures how well a monster can make split-second movements to avoid attacks |
| con, con save | Constitution of a monster, it's saving throw measures how well a monster can resist physical pain or fatigue |
| int, int save | Intelligence of a monster, it's saving throw measures how well a monster can resist mental assualts or illusions |
| wis, wis save | Wisdom of a monster, it's saving throw measures how well a monster can remain vigilant or maintain mind control spells |
| cha, cha save | Charisma of a monster, it's saving throw measures how well a monster can resist physical altercations by the force of its personality |
| walk | The distance a monster can walk |
| fly | The amount a monster can fly |
| swim | The amount a monster can swim |
| burrow | The distance a monster can burrow |
| climb | The distance a monster can climb |
| hover | Whether a monster can hover above the ground |
| size | The size class of a monster |
| alignment | A monster's ethical and moral alignment |
| type | The type, category or class of monster (eg: Dragon) |
| source | Where data about this monster was obtained from |
