---
publish: true
created: 2026-10-22T13:06:02.826Z
modified: 2026-10-24T13:57:10.079Z
---

# 24/10/26

> [!note]- \[EMF] Entity Model Features 3.3.12
>
> - Several optimizations to ASM animations, resulting in a notable fps increase with larger animations. Thanks to Wyvest on GitHub

> [!note]- \[ETF] Entity Texture Features 7.2.6
>
> - improved performance of NBT property testing, also applies to the EMF NBT animation function

> [!note]- 3D Skin Layers 1.11.4
>
> - Fix EMF resource packs not working on Forge, especially 1.20.1. Fix Fix
> - Keep track of Resource loaded textures to not leak them. Related to
> - Added ms\_my.json
> - Fixed existing Italian Localization file
> - Update libs fixing leak issues in combination with Fabric API
> - Update libs fixing a rare crash happening on Forge when loading many of my mods at once

> [!note]- Alex's Mobs Continued 2.2.4
> **Fixes**
>
> - Minecraft 26.3: the enchantment shine was drawn as a solid block with the missing texture. That put a purple blob on enchanted modded armour (such as the frontiersman's cap), made comb jellies look untextured, and covered mobs given rainbow jelly. Fixed.
>
> Needs CodxLib 1.6.0 or newer. Fabric also needs Fabric API.

> [!note]- AmbientSounds 6.3.11
>
> - Added better differentiation between grass and grass blocks to support custom biomes with different ground materials
> - Fixed not playing crickets near rivers

> [!note]- Amendments 2.2.0
>
> - added smooth animated hotbar slot animation
> - added a feature that makes walls, fence and panes all connect to eachother
> - Enhanced Block Entities now leaves signs and bells alone when amendments changes them, removed the chat warning
> - added some iris compat code since iris broke held candle holder particles

> [!note]- Aquamirae 7.2.13
>
> - Fixed armor items not having their durability set

> [!note]- AzureLib 3.2.0
> v3.2.0
>
> **Additions**
>
> - Added bone hitboxes. Entities can now define hitboxes that follow bones in their model, rotate with them, and stay in sync with whatever animation is playing. Implement `AzHitboxHolder` and return an `AzHitboxSet` to use them.
> - Hitboxes can fit a bone's cubes automatically or use an explicit size, offset and inflate in Blockbench pixels, and several hitboxes can share one bone.
> - Hitboxes have three roles.
>   - `COMBAT` hitboxes take crosshair targeting, projectiles and damage.
>   - `INTERACT` hitboxes can be right-clicked to trigger custom logic without affecting combat.
>   - `ANCHOR` hitboxes can't be hit and exist only to track a bone's position.
>     …

> [!note]- Climbable Ropes for Create Aeronautics 2.2.0
> **Changed**
>
> - Replaced the pre-made climbing animations with a procedural climbing pose that adapts to any rope angle: hands grip the rope, feet lock around it and the legs push while climbing
> - Players now crawl along flat and sagging ropes with the new climbing pose instead of Create's hanging pose
> - The mod no longer requires the Player Animator library

> [!note]- Collective 8.65 neo
>
> - (1.20.1) Backported Collective to work with NeoForge 47.1.(1.21.1 Forge) Backported Collective to work with the older Forge versions.The complete changelog with detailed information about previous versions can be found on my website: >

> [!note]- Corpse 1.1.22
>
> - Updated Ukrainian translation

> [!note]- Create Encased 1.10.0
> CreateEncased 1.10.0 - The In-World Update:
>
> **Gameplay Changes**
>
> - Add Industrial Iron, Weathered Iron, Shadow Steel, Refined Radiance and Chorium Sheets for crafting
> - Encased Blocks are no longer changeable in-world with the casing or the ingot.
> - Add the Recaser, a new item that allows you to change the casing/material of encased blocks in-world. It uses the plate of the material you want to change to, and can be used on any encased block.
> - Recipes for encased blocks have been changed to only use the plates. Encased blocks no longer uses the recipe from the original Create block, but instead uses the plate of the material you want to use.
> - Encased blocks can now be crafted by using a deployer with the associated plate.
> - Add Zinc stuff + New Zinc casing texture
>   …

> [!note]- Create: Factory Controller 1.2.3
> Bugfixes:
>
> - Fixed dedicated server crash on load
> - Fixed repackager not properly merge fluid & item packages ordered from stock keeper again

> [!note]- Create: Filters Anywhere 2.7.0
> Quite a few new things!
>
> New Mod Support: Pipez, adds support for all supported Filter items to Pipez's item pipes. Also adds Pipez Upgrade cards as a supported filter item.
>
> New Mod Support: Railcraft Reborn, adds support for all supported Filter items to the Item Loader and Item Unloader.
>
> New Mod Support: Ars Nouveau, adds support for all supported Filter items to the Storage Lectern system (using item frames to filter inventories). Also adds item allow and deny scrolls as supported filter items.
>
> New Mod Support: FTB Quests, adds support for all supported Filter items to be used as you would use the filters from FTB Filter system. For example, if you put in a Create filter with "can be washed", the quest will accept all items that match that criteria.
> …

> [!note]- Easy NPC 7.17.0
>
> - Fixed by no longer rewriting NPC files on every chunk unload when nothing changed.
> - Fixed following NPCs walking or teleporting to coordinates of a target in another dimension.
> - Fixed equipment, name, inventory, dialog and objective changes not always being saved.
> - Fixed preset exports being left broken when the server stopped while writing them.
> - Fixed `/easy_npc scale`, `rotate` and `position` rejecting the `root` model part.
> - Fixed `/easy_npc name clear` leaving the name visible above the NPC.
> - Fixed the hat layer staying visible when the head of a humanoid NPC was hidden.
> - Fixed dead, riding, ridden or leashed NPCs being put on a shoulder by commands or the API.
> - Fixed shoulder NPC rendering comparing all NPC data every frame and leaking on disconnect.
>   …

> [!note]- Easy NPC: Config UI 7.17.0
> Même changelog que Easy NPC.

> [!note]- Easy NPC: Core 7.17.0
> Même changelog que Easy NPC.

> [!note]- Essential Mod 1.5.1
> **Analytics sharing is now disabled by default**
> Your data, your choice. When starting Essential for the first time, you will now be asked whether you'd like to share usage data or not. Sharing analytics helps our team make better decisions about the development of Essential. You can change your choice any time in the Essential settings.
> Learn more about data sharing
>
> **Bug fixes**
>
> - Fixed skin uploads failing in the Wardrobe
> - Fixed not being able to OP players when hosting a world on Minecraft 26.3
> - Fixed the world not pausing after stopping hosting on Minecraft 26.2 and above
> - Fixed incoming friend requests appearing as outgoing in the Essential social menu
> - Fixed command auto-completion not updating after toggling cheats on Minecraft 1.16 and above
>   …

> [!note]- Forgified Fabric API 0.116.15+2.3.6
>
> - Fix codec unwrapper mixin on new Neo build (Su5eD)
> - Dehardcode publish settings (Su5eD)

> ## \[!note]- Fragmentum 5.4.0
>
> - Added a **Lite** version under **Additional Files** without bundled dependencies, ideal for modpack creators who prefer to manage Fragmentum dependencies manually or already include them in their modpack

> [!note]- Fresh Animations 1.11.1
> Recommended with Entity Model Features & Entity Texture Features.
>
> ---
>
> **Changes**
>
> - fixed baby pigs 26.1+
> - fixed baby villager model 26.1+
> - removed unnecessary properties files
> - updated pack meta files

> [!note]- Item Zoomer 2.3.0
>
> - Added support for Minecraft 26.3;
> - Added item zoom in stonecutter and villager trading screens;
> - Added Simplified Chinese translation;
> - Other minor improvements.

> [!note]- Just Enough Items (JEI) 19.69.0.457
>
> - Check published jars for Java bytecode compatibility - mezz

> [!note]- Just Enough Resources (JER) 1.6.0.54
> \[cd328c2] add missing enviroment for CF upload to Forge - hopefuly this fixes backport 1.21.1 release (way2muchnoise)

> [!note]- Keybind Atlas 2.0.0
> Included multiple suggestions from user feedback, including:
>
> - **Edit mode overhaul**: Improved flow of editing keybinds, making it faster and more intuitive. Added per-binding restore controls, strikethrough and color-coded feedback for removed/reassigned keys, and a better summary of changes before applying.
> - **Added search bar** for main UI, filter list, and edit mode. Filter by mod or action.
> - **Keybind sets feature**: The user can now save and load keybind sets, allowing them to switch between different configurations easily. Users can save the current keybinds as a new set, delete or rename existing sets, and create new sets that are copies of the current keybinds. The sets are saved in a JSON file in the config folder.
>   …

> [!note]- MakeUp - Ultra Fast 9.6
> **Changes**
>
> - Added selective temporal supersampling as an alternative to reduce or eliminate the ghosting effect caused by entities. Contributed by Dantar.
> - Fixed a previously introduced bug that prevented the shader from running on Minecraft 1.12.2 (OptiFine).
> - Updated some strings in the Russian translation. Contributed by ShallIMove.
> - Reorganized the options on the settings screen.

> [!note]- oÏo (owo-lib) 0.12.15.6-beta.1
> **Fixes**
>
> - ConfigureHotReloadScreen error due to parsing ResourceLocation as string
> - Resolve issue with latest neoforge update due to changes to internal network code
> - Fix issues where null EdmElements within EdmOPs may exist due to reliance on such by other mods

> [!note]- Photon Shaders v1.4
> This update contains lots of improvements and fixes made by the community!
>
> - Added support for Photonics (by Essentuan)
> - Added support for Colorwheel (by xuanplus and djefrey)
> - Added more settings for atmosphere saturation, blocky clouds, vanilla AO and colored lights vanilla lightmap contribution (by PatataNL)
> - Added Korean translation (by shihyeon)
> - Added vertical cutoff to border fog (by Candymanmax)
> - Added simplylights blocks to Colored Lights (by rockett1)
> - Many misc. bug fixes by:
>   - Lassebq
>   - rrtt2217
>   - 3DpCode
>   - yqs112358
>   - jspaterson000
>   - IMS
> - Improved bloom upsampling
> - Fixed some MC 26.3 rendering

> [!note]- Punchy! 2.8g
> **Animation fixes**
>
> - Fixed a brief offhand flash during inspect animations and restored missing inspect sounds across affected versions. Thanks to shbashi for reporting these issues!
> - Fixed throwable use animations when consuming the last item in a stack and when interrupting a two-handed equip animation.
> - Custom animation movement settings now apply correctly during actions and item equip transitions, with smooth transitions back to idle.
> - Fixed movement influence for two-handed animations so it applies to both arms while keeping single-arm actions isolated.
> - Fixed custom item idle poses being applied twice through the locomotion layer.
> - Preserved global arm position and rotation offsets during attacks and item equip transitions.
>   …

> [!note]- Puzzles Lib 21.1.65
> **Fixed**
>
> - Ensure the enchanted loot bonus callback only runs once on NeoForge

> [!note]- Regions Unexplored 0.6.3
>
> - Redstone Bulbs and Prismarite Clusters can now be placed facing any direction.
> - Refreshed a handful of existing block textures.
>   - Blackwood Planks
>   - Short Dry Grass (+ Red variant)
>   - Frozen Grass
>   - Glistering Sprout
>   - Flowering Leaves
>   - Salmonberry
>   - Hanging Earlight Fruit
>   - Icicle
> - Fixed RU's boats acting weird if there was a second player or chest inside.
> - Fixed the Prismachasm and Redstone Caves biomes not generating if certain other biome mods were installed.
> - Fixed spruce saplings sometimes growing Pine trees.

> [!note]- Solas Shader 3.8
> Some bug fixes and 26.3 compatibility

> [!note]- Sophisticated Backpacks 3.26.14.2222
> **Features**
>
> - Updated Japanese translation (Thanks Nearpoin)

> [!note]- Sophisticated Core 1.5.17.2426
> **Fixes**
>
> - Fixed Pump Upgrades bypassing claims when accessing nearby tanks

> [!note]- Sophisticated Item Actions 0.5.18.441
> **Fixes**
>
> - Fixed item highlighting disconnects around large storage setups

> [!note]- Sound Physics Remastered 1.5.2
>
> - Applied a proper fix for OpenAL reference distance issue in affected versions
> - Restored old linear attenuation by distance behavior

> [!note]- Starter Kit 9.0 neo
>
> - Added Curios and Trinkets support! Kits now save and give items automatically in their slots.
> - Added kit commands, which run when a kit is given. They can be set in './config/serilum/starterkit/commands/'.
> - Added the 'giveStarterKitOnRespawn', 'giveStarterKitOnFirstJoin', 'lockKitChoiceScreen' and 'randomKitWeights' config options.
> - Kits can now be ordered by starting their name with a number, such as '1\_Warrior'.
> - Kit names, descriptions and the choose kit text can now be translation keys.
> - Fixed players joining a hosted singleplayer world, such as via Essential, not receiving a starter kit.
> - Fixed kit tracking being incorrect or undone after a server restart.
> - Fixed some cases where items could be duplicated, lost or shown incorrectly when receiving a kit.
>   …

> [!note]- Villager Names 8.9 neo
>
> - Added the 'extraEntityTypesToName' and 'entityTypesToIgnore' config options.
> - Improved the modded villager detection, which finds more villagers and traders to name that aren't on the list.
> - Added compatibility with Visiting Villagers, Villager Workers, Villager Golem Healer and Millager.The complete changelog with detailed information about previous versions can be found on my website: >

> [!note]- Wavey Capes 1.11.3
>
> - feat: Support for MoreBannerFeatures by @DomiIRL in  (needs a future release of MoreBannerFeatures)
> - Improve performance of cape rendering
> - Update libs fixing leak issues in combination with Fabric API
> - Update libs fixing a rare crash happening on Forge when loading many of my mods at once

> [!note]- Almanac 1.26.10.3
>
> - **Fixed**
> - Bundles Dungeon Config 1.26.10.3: opening **Options > Controls > Key Binds** no longer crashes. The Dungeon Configs key (Ctrl + K) used a key category Minecraft did not know about, so sorting the key list failed.

> [!note]- Let Me Despawn 1.26.10.2
> **Fixed**
>
> - Trial spawner rewards can no longer be earned by waiting for the trial's mobs to despawn. Vanilla counts a mob that despawned the same as one that was killed, so standing nearby until the mobs despawned completed the trial and ejected its rewards without a fight. A trial spawner mob now never despawns while its spawner still counts it towards the trial. It can despawn once the spawner lets it go: it wandered more than 47 blocks away, the trial ended or reset, or the spawner was broken. Leftover trial mobs still despawn, so they don't pile up.
> - Trial spawner mobs saved before this update are matched to their spawner automatically.

> [!note]- Ore Harvester 2.1 neo
>
> - The 'oreBlockWhitelist', 'oreBlockBlacklist' and 'pickaxeWhitelist' lists can now be picked from a list in the in-game config.The complete changelog with detailed information about previous versions can be found on my website: >

## Configs

- Removed [Create: Blueprinted](https://modrinth.com/mod/create-blueprinted)
