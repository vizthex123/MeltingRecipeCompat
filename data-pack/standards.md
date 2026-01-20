# Recipe Standards

1) Recipe heat & time copies the primary material. Seems like there's no standard for melting times (it's probably generated automatically lol), so I can just add a few seconds whenever.

2) Molten amounts are equal to the total material cost (e.g. a Multi-Piston gives an extra iron ingot because of the Piston used to craft it), and are rounded down in the event of a decimal divison. The output order is determined by the amount (with the highest amount being the primary material), and are grouped by type (metal, gem, block, misc). Organised alphabetically if there's a tie.

3) Byproducts are calculated from left -> right, top -> bottom of the crafting grid - the first item found is the primary output.

4) Byproduct exception: If one material is used in a greater than 1:1 ratio, it becomes the primary material (e.g. using a Copper Block and Iron Plate with the Plate being on top of the Block).

5) Items in tag files are organised alphabetically by mod and then registry name

The `time` field doesn't use game ticks, instead using smeltery ticks (4:1 ratio - so 20 time = 5 seconds (since 1 time = 4 smeltery ticks)).