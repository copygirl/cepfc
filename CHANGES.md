# Configuration Changes

This is a list of **ALL** the configuration changes made to mods in this pack. This is in case you're interested in the pack and want to see what we modified, or creating something similar for yourself. The modified config files can be found in the [`cepfc/src/config/`](cepfc/src/config/) folder. Both initial changes and ones made as the modpack is being developed can be seen in the [commit history](https://github.com/copygirl/cepfc/commits/master) of this repository.

## Quark
- Disable "q" button
### Automation
- Disable *Chute*
- Disable *Iron Rod*
- Disable "Chains Connect Blocks"
- Disable "Color Slimes"
- Disable "Dispensers Place Blocks"
- Disable "Pistons Move Tile Entities"
- Disable "Redstone Circuit"
### Building
- Disable *Beetroot Crate*
- Disable *Carrot Crate*
- Disable *Potato Crate*
### Tools
- Add *Backstabbing* as valid *Ancient Tome* enchantment
### World
- Disable *Limestone*
### Client
- Disable "Food Tooltips"
- Show that *Backstabbing* can be applied to knives
### Oddities
- Disable *Pipes*
- Disable *Magnet*
- Disable "Matrix Enchanting"
- Disable "Dark Souls Mode" for *Totem of Holding*

## Charm
- Add Quark's *Ancient Tomes* to *Bookcases'* valid books
### Items / Blocks
- Disable *Candles*
- Disable *Crates*
- Disable *Gold Bars*
- Disable *Netherite Nuggets*
- Disable variant *Bookshelves*, *Chests* and *Ladders*
### Enchantments
- Disable *Acquisition*
- Disable *Tinted*
### Features
- Disable "AutoRestock"
- Disable "DecreaseRepairCost"
- Disable "ExtendNetherite"
- Disable "ExtraRecipes"
- Disable "FeatherFallingCrops"
- Disable "InventoryTidying"
- Disable "MineshaftImprovements"
- Disable "MorePortalFrames"
- Disable "Show item repair cost"

## Cooking for Blockheads
- Disable *Cow in a Jar*
- Enable "sinkRequiresWater"

## Carry On
- Enable "dropCarriedWhenHit"
- Blacklist *Lectern* and all *Tetra* blocks

## Forgery / Fabrication
- Set profile to "Dark"
### Utility
- Disable "Books Show Enchants"
- Disable "Hide Armor" commands
- Disable "Tools Show Important Enchant"
### Tweaks
- Disable "Creepers Explode When On Fire"
### Minor Mechanics
- Disable "Feather Falling V"
### Mechanics
- Disable "Broken Gear Drops Components"
- Disable "Grindstone Disenchanting"
### Balance
- Enable "Bedrock-Like Impaling"
- Enable "Drop More Experience On Death"
- Enable "Food Always Edible"
- Enable "Soul Speed Doesn't Damage Boots"
- Enable "Tridents Accept Power"
- Enable "Tridents Accept Sharpness"
### Weird Tweaks
- Enable "Instant Pickup"
- Enable "Déjà Void"

## Mouse Tweaks
- Disable "RMB Tweak"
- Set "WheelScrollDirection" to 2 (position aware scrolling)

## InvMove
- Disable hiding the UI Background


# Datapack Changes

In addition to configuration changes, cEPfC also comes with its own data pack, adding and modifying recipes, and similar things controlled by data packs. Feel free to browse [`cepfc/src/global_data_packs/cepfc/`](cepfc/src/global_data_packs/cepfc/) yourself, as well.

## Cooking for Blockheads
The following changes allow these items to be made at the *Cooking Table*.
- Add *Dough* from *Create* to ingredients
- Add pies and cakes from *Farmer's Delight* to food items
- Add *Milk Bottle* from *Farmer's Delight* to ingredients
- Add *Pancake* from *Supplementaries* to food items

## Recipes
- *Milk Bottle* can be filled using Create's *Spout*
- Remove *Milk Bucket* recipe from 3x *Milk Bottles*
- Remove Vanilla *Cake* recipe in favor of the one accepting any `forge:milk` item
- Remove *Wheat Dough* recipes (duplicate with *Create*)
- All *Rope* recipes now craft / use Supplementaries' *Rope*
- Remove Vanilla *Barrel* recipe (conflict with *Charm*)

## Tags
- `supplementaries:ropes` now only has Supplementaries' *Rope*
