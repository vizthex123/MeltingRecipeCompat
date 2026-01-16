# Datapack Changelog

A full changelog for every version (and sub-version) of the [Datapack](https://www.curseforge.com/minecraft/data-packs/melting-recipe-compatibility).

This one will be updated more often than the CurseForge and Modrinth changelogs.

I increment the version by X.1 whenever I add more mod support (so long as the addition has 8+ recipes), and X.X.1 for minor fixes and/or additions I missed in the last patch.

Lines appended with a version in brackets (e.g. Text Here [1.19]) denote changes that only apply to that version.

--------------------------------------------------

## 2.0

Ported to 1.19.2

Added a recipe to cast (and melt) Ender Fragments if Ender Zoology is installed

Mod support added:
- Create: New Age
- Forestry: Community Edition
- Fullblock Energistics
- Thermal Endergy


<br /> <br />

--------------------------------------------------

## 1.5

Updated all tag files to use the `required` field since conditions don't work on them<br />
Fixed the Fuel Canister using the `damagable_melting` recipe type when it shouldn't have
 
Mod support added:
- Bag of Holding (both Fuzs and xiaxin113's)
- Bigger Reactors
- Create: Diesel Generators
- Create Ore Excavation
- Create Sifting
- Extreme Reactors
- Intelligence: Quarry
- LaserIO


<br /> <br />

--------------------------------------------------

## 1.4.2

Fixed several clay melting recipes not loading in

Added a melting recipe for Ceramics' Cisterns<br />
Added support for Quark's Terracotta Shingle blocks<br />
Fixed Cyan Terracotta bricks missing my custom tags *[Clayworks]*


<br /> <br />

--------------------------------------------------

## 1.4.1

Removed Steam as a smeltery fuel<br />
Added support for Storage Drawers


<br /> <br />

--------------------------------------------------

## 1.4

All Brick melting recipes now use my custom tags (can't believe I forgot this in the previous release lol)
- This allows much better mod compatibility in the future, as well as removing duplicate recipes (e.g. Quark's vertical brick slab being separate from the regular slab recipes)

Fixed a few bricks from Create Deco not having tags added to them<br />
Fixed the Model Framework not giving Clay like it should *[Hostile Neural Networks]*<br />
Updated support for Netherific since I forgot most of the Obsidian stuff and all of the Quartz stuff lol

Added support for the following mods:
- Biome Makeover
- Ceramic Bucket
- Ceramic Shears
- Ender Magnet
- Mekanism Advanced Generators / Mekanism-MoreSolarPanels
- Tesseract


<br /> <br />

--------------------------------------------------

## 1.3

Added Steam as a Smeltery fuel<br />
Made my custom tags use the `required` field, that way all of them can load in properly

Fixed Crying Obsidian and Respawn Anchors having the wrong melting temperature<br />
Fixed Amethyst Throwing Daggers outputting Gold instead of Copper (and not working with the Tipped Variant) [Blood Magic]<br />
Fixed Vertical Brick and Quartz Slabs not having melting recipes *[Quark]*<br />
Fixed some issues with XNet's connector recipes

Updated Create Deco support with all the Brick Blocks I missed (even though that's like half of the mod lol)<br />
Removed several unecessary tags (recipes have been updated to use the standard input substitution method):
- The `cage_lamps` tag. Also vastly reduced the melting time.
- The `connectors` tag. Also vastly reduced the melting time.


Corrected several melting temperatures<br />
Reduced the melting temperature of Cast Iron to 800 (was 1,000) *[Create Deco]*<br />
Separated the Prospector's Pick and Sword Billet recipes *[Obscuria's Essentials]*<br />
Emeraldite and Pendorite ore now give bonus outputs based on configured smelting boost rates *[Biomes You'll Go]*

Added more recipes for some missing Blood Magic items<br />
Added a few missing Twilight Forest recipes (including one to melt Fiery Vials into Fiery Essence)<br />
Made Additional Additions' Rose Gold gear only melt into Gold and Copper

Added some Liquid Soul recipes I missed<br />
Added Gear and Dust melting recipes for most of the missing entries<br />
Added durability melting rates to all tool recipes (like base Tinkers' has)


Added support for the following mods:
- AE2 Things
- Applied Energistics 2
- Applied Energistics 2 Wireless Terminals
- Appied Botanics
- Appied Cooking
- Appied Mekanistics
- AdminShop Overhauled
- Aquamirae
- Biomes o' Plenty (flesh blocks)
- BluePower
- Botania
- Clayworks
- Cognition
- Cooking for Blockheads
- Create: Applied Kinetics
- Deep Resonance
- Ender Quarry Plus
- Enigmatic Legacy
- Enlightend
- Extended Crafting
- Functional Storage
- Hostile Neural Networks
- Immersive Engineering
- Iron Barrels
- Iron Bookshelves
- Iron Chests
- Iron Chests: Restocked
- Iron Jetpacks (only partial support since I can't use NBT data)
- ME Requester
- Malum
- Mekanism
- Mekanism Additions
- Mekanism Generators
- Mekanism Tools
- Nature's Aura
- Neapolitan
- Netherific
- Portality
- Quantum Quarry Plus
- Refined Pipes
- Reliquary Reincarnations
- Scannable
- Simple Quarry
- Simply Jetpacks
- Solar Cooker
- Solar Flux Reborn
- Staff of Travelling
- Thermal Extra (also add missing casting recipes and fluid tooltips)
- Thermal Series (all modules)
- Thermal Systeams
- Travel Anchors
- Woodworks
- Wormhole


<br /> <br />

--------------------------------------------------

## 1.2

Optimised a few recipes by combining them into a single entry
- Also fixed the incorrect melting temperatures in several recipes

Fixed all the melting times not using the proper time units
- For some reason, Tinkers uses a 4:1 time ratio (e.g. 12 time equals 3 seconds for the item to melt) instead of the standard 20:1 (20 ticks per second)

Fixed Bygone Nether's Gilded Netherite recipes not loading in<br />
Fixed the Obscuria's Essentials Paladin's Helmet using a Helmet instead<br />
Fixed the Oh The Biomes You'll Go recipe for Chainmail Boots using a Helmet instead<br />
Fixed the Oh The Biomes You'll Go recipe for Pendorite Horse Armour not loading in

Added a melting recipe for Crying Obsidian<br />
Added melting recipes for all of Blood Magic's anointments<br />
Added melting recipes for several other random items that I missed

Added support for the following mods:
- Additional Additions
- Bygone Nether
- Colds: Easy Paxel (and the Lite version)
- Oh the Biomes You'll Go
- Only Paxel
- Simple Paxels


<br /> <br />

--------------------------------------------------

## 1.1

Overhauled file structure so it's easier to add recipes
- This doesn't affect users, but is still worth noting

Added a melting recipe for Cast Iron Plates<br />
Fixed several Iron melting recipes using Cast Iron items<br />
Fixed the melting recipe for Cast Iron Nuggets not loading in<br />
Added Slime to several melting recipes that were missing it<br />
Datapack now fixes the incorrect melting amount for Emeraldite Shards if BYG & Tinkers Integrations and Tweaks are loaded


Added support for the following mods:
- Blood Magic
- ChickenChunks
- EnderStorage
- RFTools (all modules)
- XNet


<br /> <br />

--------------------------------------------------

## 1.0.2

Fixed the tag support recipe for Bricks not overriding the default one


<br /> <br />

--------------------------------------------------

## 1.0.1

Fixed Create's windows (and panes) loading in when they shouldn't.

Mod support added:

- Advancement Frames
- Fuel Canister
- Long Fall Boots
- Measurements


<br /> <br />

--------------------------------------------------

## 1.0

Initial release.

Supports the following mods:

- Create
- Create Crafts & Additions
- Create Deco
- Create Enchantment Industry
- Essentials
- Obscuria's Essentials (Legacy)
- Lightman's Currency
- Lightman's Currency Tech
- Quark
- Quark Oddities
- Twilight Forest's Iron Ladder (other materials already have recipes)