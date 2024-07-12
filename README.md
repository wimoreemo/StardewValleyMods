This repository contains all the SMAPI mods I've created for Stardew Valley. 

# General Information

- All of the mods in this repository require SMAPI. Ensure that SMAPI is functional before mod installation.
   
- Mods may have additional setup requirements. Read the mod description for all details. As a general rule of thumb, required frameworks are specified in the names. [CP]ExampleMod will require Content Patcher.
   
- All mods listed are equivalently available on NexusMods. Go to the mod description to find unique mod link. Or, find the listed mods on my [NexusMods profile](https://next.nexusmods.com/profile/wimoreemo/mods).

# Mod Descriptions

Mod descriptions provided below.

## Fish On Farm

Enables you to catch most standard location fish on your farm water bodies. That includes the little pond and the lake on the standard farm map. It also applies to all other water bodies (rivers, lakes, beaches) on your farm if your farm uses any of the other available farm maps. 

This mod helps you level up your fishing quickly without having to go to the in-game fishing locations.

The standard locations include the Beach, Mountain Lake, Cindersap Forest (river + lake), and the Town. Therefore, available fish categories are Beach Fish, Mountain Fish, Forest Fish and Town Fish. You can select which fish group to spawn by using the config file to change the default value for your relevant fish category to 'true' or 'false' (default 'true' for all categories).

Does not include legendary fish.

### Additional Details (Recommend for Non-Standard Farm Players)

Selected fish categories have priority over all default fish. In the case of the standard farm map, since there are no default fish, this has no relevance. For maps like the Beach Farm, selected fish groups will always have priority over default fish, in this case, that would mean priority over beach (ocean) fish. Example: If you select only 'Mountain Fish', you will only catch mountain fish even if you are fishing on the beach on a Beach Farm. You would have to select 'Beach Fish' if you still wish to fish for them.

All selected fish groups have equal probabilities of spawning. Example: If you have both 'Beach Fish' and 'Town Fish' selected, they are equally likely to spawn and one of them will be randomly selected for a catch (for a 'HIT!'). The same principle applies if more or all available fish categories are selected.

To revert to default fishing on your map, deselect all fish categories in the config file. 

### Necessary Requirements
- Must have SMAPI installed.
- Must have Content Patcher installed.

### Mod Installation
- Install this mod from NexusMods [here](https://www.nexusmods.com/stardewvalley/mods/25576?tab=description).
- (**Not Recommended**) Download the [CP]FishOnFarm folder from this repository into your mods folder.
