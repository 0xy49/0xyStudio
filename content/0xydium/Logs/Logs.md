---
publish: true
created: 2026-10-22T13:06:02.826Z
modified: 2026-11-07T22:47:37.879Z
published: 2026-11-07T22:47:37.879Z
outgoing_links: "[[Mojang.base]]"
---

# 07/11/26

> [!note]- 0xydium
> Added :
>
> - Link's Hat now gives the Hero of the Village effect as long as you wear it (better trades with villagers)
> - Fisherman's Hat now gives +1 Luck while worn (better fishing loot)
> - Hylian Shield can now be enchanted (Unbreaking, Mending...)
> - Master Sword can now be enchanted (Sharpness, Smite, Looting, Fire Aspect, Sweeping Edge, Unbreaking, Mending...)
> - Class and level now show above players head for every other player (example: "Lvl.57 Assassin")
>   - Assassin in green, Warrior in blue, Mage in red
>   - Updates automatically when you level up / ==🔴change class (Not yet implemented)==
>   - Nothing is shown until class is chosen
> - Bank Terminal: new "Ranking" panel on the right showing the 10 richest players
>   - Shows each player's head, name and total balance
>   - Your own rank is shown at the bottom ("You: #N / total")
>   - Hover a line to see the exact amount
>   - Updates every time you open the terminal or make a deposit, withdrawal or transfer
> - Portable Drill: the drill head now spins much faster while you mine blocks or swing at the air, like a real drill at work
>   - It slows back down smoothly when you stop
>   - Hitting a mob keeps the normal animation
> - Mount Certificate: right-click your tamed mount or pet with paper to create a certificate
>   - Give it to another player: they right-click the animal with it to become its new owner
>   - Works on horses, donkeys, mules, llamas, camels, wolves, cats and parrots
>   - Only one certificate can exist per animal at a time: right-click the animal with your own certificate to cancel it
>   - Certificates expire after 7 days
>   - Hover over Paper and hold Shift or Ctrl to see how it works
> - Market Terminal (new block): a machine that opens the stock market when you right-click it (WIP feature)
>   - Can be moved with the Create wrench like the Bank Terminal
> - Market Remote (new item): opens the stock market from anywhere
> - Stock market screen with three tabs (WIP feature):
>   - Shops: lists every shop, with filters (mode, currency, items, owner, dimension) and favorites
>   - Market: average and lowest price per item, 24h change, volume, price graph and trend
>   - Top sellers: ranking of the best sellers, by sales or by number of shops
> - Table cloths you set up with Create are now listed automatically, with the real price shown (e.g. 12 Cogs) instead of a converted value
> - Buy orders: a table cloth that “sells” coins in exchange for an item is listed as a purchase (the owner buys that item and pays in coins)
>
> Fixed :
>
> - Zinc and Brass tools and weapons now show and use their real stats (attack damage and attack speed)
> - The Paxel now shows and uses its stats too (same as a Netherite Axe)
> - Portable Drill: the held drill no longer dips down and back up when mining or clicking in the air
> - Highlighted rows (favorites, best seller, selected filters) no longer hide the text
> - Text and columns no longer stick to the column separators
> - Various small visual overflows in the market screen (top border, search bar, sidebar edge)

> [!note]- Entity Texture Features 7.2.7
>
> - fixed the enchanted skin pixels feature not working properly in 1.21.9+
> - improved memory usage for 1.21.9+
> - translation updates

> [!note]- Aeronautics: Joy of Creation 1.2.1
> fixed crash with deep seas
> removed unfinished tag from gyro seat

> [!note]- Alex's Mobs Continued 2.3.0
> 27 reports from github, discord and curseforge. The 5 I couldn't fix are on the
> issue tracker.
>
> **New**
>
> - Minecraft 26.3 on Forge. 52 builds now, that was the last one missing. Server tested, not client
>   tested yet.
> - Terrain mod support. Tectonic, Terralith, Biomes O' Plenty, all of them. 5 mobs had their spawn
>   height hardcoded so they stopped spawning once a terrain mod moved the ground. New options:
>   `flutterSpawnHeight`, `cockroachSpawnHeight`, `flyMinSpawnHeight`, `orcaMinSpawnHeight`,
>   `hammerheadSharkMinSpawnHeight`. Defaults are the old values so nothing changes unless you want it to.
>
> **Fixed**
>
> - 26.3 NeoForge crashed on making a new world. Built against the wrong NeoForge, needs 26.3.0.101 now.
> - Anacondas didn't slither on 1.21.2+ and didn't move at all in water.
>   …

> [!note]- Amendments 2.2.7
>
> - added more mod compat for EBE on forge
> - more compat for thrown projectiles to render 3d like snowball (default off, includes environmental mudballs)

> [!note]- AzureLib 3.2.7
> v3.2.7
>
> **Additions**
>
> - Added Blockbench polygon mesh rendering. Meshes inside a bone render and animate with it, like cubes. Requires AzureLib Animator 2.4.0.
> - Added skinned meshes with smooth deformation. Meshes inside a Blockbench armature bend with the armature's bones using linear blend skinning (up to four weights per vertex), matching the Blockbench preview. Armature bones export as regular bones, so animations, procedural poses, IK, sockets and hitboxes work on them.
> - Bedrock `poly_mesh` geometry from other tools now loads and renders, including mixed triangle and quad polygons and the `tri_list` / `quad_list` shorthands.
> - Bone hitboxes that fit their bone's geometry now include rigid meshes.
>
> **Fixes**
> …

> [!note]- Balm 21.0.67
>
> - API: Backported support for `lootTableId` parameter in `BalmLootModifier`

> [!note]- Collective 8.83 neo
>
> - Added more options for dependent mods on the Create World screen.
> - Added shared functions for the spawn point mods.
> - Fixed the /collective config command accepting invalid weights.Updated Village Spawn Point and Biome Spawn Point translations.(Fabric) Fixed spawn mods placing an extra bonus chest.(26.1+) Fixed bonus chests and some packets using the wrong position.The complete changelog with detailed information about previous versions can be found on my website: >

> [!note]- Colorwheel 1.3.2
>
> - Fixed buffer overflow
>   This may fix issues with other mods, like Voxy

> [!note]- Create Aeronautics: Transmission & Linkage 0.2.9
> Fixed interference with Create’s built-in Ponder scenes.
>
> Removed the annoying Toolgun installation reminder.
>
> Fixed unintended interactions with hydraulic and pneumatic rods through physics structures.

> [!note]- Create: Pocket Sized 0.24.1
> **REQUIREMENTS**
>
> - Pehkui 3.8.3 or newer is required.
> - Pym 0.5.1 is my scaling library currently bundled inside the Pocket jar. No separate download needed.
> - Client and server must both be on 0.24.1.
>
> **Pocket Sized v0.24.1**
>
> - Aeroworks 1.5 fix
>
> **Collision & LOD Optimizations**
>
> - All entities now use LOD colliders for sublevels (based on relative scale) to prevent lag.
> - Very large or complex scaled colliders fall back safely instead of failing to build.
> - Large entities use a faster water check.
> - Scaled sublevels skip water checks in chunks with no water.
> - Simulated Coaster optimizations for tiny rollercoasters.
> - Pym's scaling no longer affects 1x sublevels & players.
>
> **Physics**
> …

> [!note]- CreativeCore 2.13.53
>
> - Added some more helpers to BoxCorner and ABB
> - Fixed potential cheating items by setting the hand in gui

> [!note]- DynamicRenderDistance 1.3.1
> **Added**
>
> - Forge 1.16.5 (Forge 36.2.42+, Java 8). Client-only, with the same settings screens, HUD, key binds, /drd commands and JSON config as the other versions. No additional mod required.
>
> **Changed**
>
> - Lower Fabric minimums: 1.3.0 asked for the Fabric Loader and Fabric API builds it was compiled against (for example Fabric Loader 0.18.4 and Fabric API 0.92.7 on 1.20.1). 1.3.1 asks only for the oldest build of each Minecraft line it works with.
> - Fabric 26.1.2 now requires Fabric Loader 0.19.5 or newer: Architectury API 20.1.14 crashes the game at startup on older loaders.
> - Forge now starts at the first recommended build of each line (43.1.0, 47.1.0, 61.1.0) instead of accepting every build, betas included.
>   …

> [!note]- Easy NPC 7.18.0
>
> - Fixed by keeping NPCs from getting lost on loading with mods like LetMeDespawn.
> - Fixed NPCs with melee and a ranged attack not shooting while holding a bow, crossbow or gun.
> - Fixed NPCs spinning between objectives and slime NPCs hopping the wrong way when attacking.
> - Fixed the boss bar staying on screen after teleporting away or changing dimensions.
> - Fixed creative pick block on an NPC not giving its spawn egg.
> - Fixed "Scoreboard" conditions adding a score of 0 for players without a score.
> - Fixed the Spartan Weaponry golden heavy crossbow and added the leather and copper ones.
> - Fixed overlapping hints, checkbox tooltips, and missing errors and log spam in the skin screens.
> - Fixed the "Custom" skin tab naming the folder `skins` instead of `config/easy_npc/skin`.
>   …

> [!note]- Easy NPC: Config UI 7.18.0
> Même changelog que Easy NPC.

> [!note]- Easy NPC: Core 7.18.0
> Même changelog que Easy NPC.

> [!note]- Enhanced Celestials 2: Core 2.0.3.4
>
> - Bump required Data Anchor version to prevent a race condition crash

> [!note]- Enhanced Celestials 2: Default Lunar Events 2.0.1.4
> Même changelog que Enhanced Celestials 2: Core.

> [!note]- Enhanced Celestials 2: Shader Support 2.0.0.4
>
> - Require Iris 1.8.14-beta.1 or newer and Sodium 0.8 or newer. Older Iris builds crash with Sodium 0.8, so the game now reports the bad combination at startup instead of crashing when joining a world.
> - Bump required Data Anchor version to prevent a race condition crash

> [!note]- Essential Mod 1.5.2
> **Forge and NeoForge support**
> Essential is now available on Forge and NeoForge for Minecraft 1.21.11, 26.1.2, 26.2, and 26.3.
>
> **Mod Compatibility**
>
> - Fixed FancyMenu player entity element not facing the mouse when hovering Essential buttons on Minecraft 26.1 and above
> - Fixed FancyMenu background and player entity element not parallaxing when hovering Essential buttons on Minecraft 26.1 and above
> - Fixed FancyMenu player entity element not facing the mouse when hovering Essential buttons with the "Render above vanilla" option enabled
> - Fixed the game crashing with ImmediatelyFast on Minecraft 26.2 and above

> [!note]- Fresh Animations 1.11.2
> Recommended with Entity Model Features & Entity Texture Features.
>
> ---
>
> **Changes**
>
> - fixed cave spider using normal spider animations in 26.1+
> - fixed inconsistent spider models across versions
> - fixed llama leash position
> - fixed allay leash position
> - tweaked bee animations
> - tweaked baby zombified piglin texture

> [!note]- Fresh Animations: Extensions 1.10.1
> **All Extensions 1.10.1 Includes:**
>
> - Details Add-on 2.4
> - Objects Add-on 2.1.3
> - Quivers Add-on 2.3
> - Emissive Add-on 1.7
> - Creeper Edit 2.2
> - Spiders Edit 2.3.1
>
> **Spiders Edit 2.3.1:**
>
> - fixed broken spider models with FA 1.11

> [!note]- Just Enough Items (JEI) 19.70.0.469
>
> - Close Close inventory on Escape during ingredient navigation - mezz
>   - Fix Preserve chat item link click actions - mezz
>   - Cache ingredient type visibility snapshots - mezz
>   - Remove redundant recipe category sorting - mezz
>   - Avoid retaining unsupported menus during recipe transfer lookup - mezz
>   - Implement sorting snapshots in ingredient filter tests - mezz
>   - Optimize recipe category visibility check - mezz
>   - Test item decorations in batched rendering - Reece Mackie
>   - Use single-use Gradle daemons in Jenkins - mezz
>   - Check API compatibility in final runtime jars - mezz
>   - Support Minecraft 26.1.2 instead of 26.2 - mezz

> [!note]- Keybind Atlas 2.3.0
> New features:
>
> - Added a trash button to each edit summary row to revert that individuall change
> - Forge/Neoforge only: Added initial compat with keybind bundles mod (Would appreciate feedback on this!)
> - Added QWERTY PT-PT support
>
> Bug fixes:
>
> - Fix 3 distinct crash causes (Please let me know if problems persist through the github issues :D)
> - Added a few safeguards to (hopefully) prevent future crashes

> [!note]- KeyBind Bundles 1.5.0
>
> - Add a config option for toggle mode (off by default) - this should when playing with controllers (katubug)
> - Improve readability of the radial menu by adding colours (katubug)
> - Add brazilian portugese translations (PrincessStellar)
> - Add japanese translations (Nia1111)

> [!note]- MezzConfig 0.6.11
>
> - Expose config description localization keys - mezz
>   - Expose immutable sorting snapshots - mezz
>   - Bump version to 0.6.9 - mezz
>   - Dispatch config listeners outside schema locks - mezz
>   - Add Simplified Chinese translation - jim139129
>   - Use AtomicFile for config file operations - mezz
>   - Bump version to 0.6.8 - mezz
>   - Fix Windows path and file replacement tests - mezz
>   - Quote the Minecraft version argument in Windows CI - mezz
>   - Retry Windows file sharing failures during config saves - mezz

> [!note]- MobSpawnController 1.4.0
> 中文：
>
> - 新增“未知来源”生成条件，支持白名单与黑名单。
> - 完善生成拦截；全部生成开关关闭时，也会阻止无法归类的生成。
> - 优化条件检查性能，避免重复概率判定。
>
> English:
>
> - Added "Unknown origin" spawn conditions with whitelist and blacklist support.
> - Improved spawn interception; disabling all spawn types now also blocks unclassified spawns.
> - Optimized condition checks and prevented duplicate chance rolls.

> [!note]- Moonlight Lib 3.8.2
>
> - Added plugin registration - Required by Every Compat

> [!note]- More Culling 1.0.11
>
> - fix incompat with regions unexplored
> - fix incompat with terrain slabs in by @manucherf
> - fix fence top not rendering with candles above it

> [!note]- Not Enough Animations 1.12.7
>
> - Fix lantern animation being choppy
> - Fix offhand hiding not taking priority over lantern/map holding
> - qol: increase max blocking angle limit
> - feat/fix: use MapItem instead of a predefined HashSet
> - feat: use more precise mixins for Rotation Angles
> - Improve Chinese localization for animation settings

> [!note]- Not Enough Recipe Book 0.6
>
> - Backported to 1.21.1

> [!note]- Oh The Trees You'll Grow 5.3.6
>
> - Clear oversized random tick tags.
> - Fix blocks generating above the nether roof.

> [!note]- Physics Mod 3.0.35
>
> - Fixed freeze with Prefab mod

> [!note]- Punchy! 3.1b
> **Fixes**
>
> - Hand Editor: Reset now puts a pose back to how your resource packs set it, even after you saved a change. Before, Reset only undid what you had changed since opening the editor or since your last save, so a saved pose could not be reset.
> - Hand Editor: a value you changed keeps its reset button after you save, until it matches your resource packs again.

> [!note]- Punchy! Studio 1.1.1
> **Punchy! Studio 1.1.1**
>
> - Works with the released **Punchy! Moves 1.0.0**: exported packs play in Moves, the Game view plays your clip in the game, Copy a pack from the game finds your Moves packs, and Punchy!'s classic F8 menu shows the Punchy! Moves button.
> - A pack you exported with Studio 1.1.0 is put right on its next export: its Moves files go where Moves reads them, and the old copies go to the pack's backups.
> - Typing in names, numbers and searches works on Minecraft 26.3 and 26.4.
> - Edit > Preferences: turn the camera the other way left and right or up and down, set how fast it orbits and zooms, invert zoom, hide the floor grid, pick your keys and turn tooltips off.
>   …

> [!note]- Reconnectible Chains 2.5.0
> **Added**
>
> - Walking along a chain or rope with chain collisions enabled now sways the camera, like Supplementaries ropes.

> [!note]- ShatterLib | OctoLib 0.6.3
>
> - Fixed config empty lists validation

> [!note]- Solas Shader 3.9
> Mostly small fixes, as well as added support for Iris on Vulkan (Thanks to IMS)

> [!note]- Sophisticated Backpacks 3.26.20.2244
> **Fixes**
>
> - Fixed upgrade settings being lost when migrating worlds from 1.20.1

> [!note]- Sophisticated Core 1.5.31.2460
> **Fixes**
>
> - Fixed multiple compression upgrades claiming extra inventory slots
> - Fixed cooking upgrades handling input-aware recipes incorrectly
> - Fixed JEI crafting transfers disconnecting players when JEI was missing on the server

> [!note]- SuperMartijn642's Core Lib 1.1.26a
> **SuperMartijn642's Core Library 1.1.26a**
>
> - Added z-axis rotation option for variants in `BlockStateGenerator`
> - Added block loaded check when handling `BlockEntityBasePacket`s
>
> **SuperMartijn642's Core Library 1.1.26**
>
> - Added `PlayerProfileCache` for looking up player names, uuids, and skins
> - Added `Teleporter` for handling teleporting entities
> - Added `StackedWidget` to layer multiple widgets and separate interaction between them
> - Added options to set size and position of `ScissorWidget`
> - Added more text styling option to `TextFieldWidget`
> - Fixed `WidgetScreen` not using widget cursor type
> - Fixed widget cursor type not being maintained whilst dragging
> - Fixed child widgets of `AbstractButtonWidget` not receiving `#mousePressed` call
>   …

> [!note]- Swinging Lanterns 2.1.0
>
> - new settings screen
> - improved performances
> - fixed Traveler's Lantern's belt lantern
> - fixed glowing player skin

> [!note]- Almanac 1.26.11.1
> **Changed**
>
> - Bundles Dungeon Config 1.26.11.1: sound playback for mods, sharper text at fractional GUI scales, FancyMenu support for every Dungeon Config screen (hiding or moving the Dungeon Configs title screen button now survives a restart), and font sizes that go unused are freed so long sessions don't build up GPU memory.
> - **For mod developers:** `ConfigManager.loadConfig` and `loadConfigFromFile` now take a `Supplier` that creates the default config, for example `loadConfig(file, MyConfig.class, MyConfig::new)`.

> [!note]- ChoiceTheorem's Overhauled Village 3.6.4
> **Optimization**
>
> - None for this patch
>   **New compatibility**
> - Rework domestication innovation building into Redomestication blocks.
> - New compatibility with More Villagers: Missing Buildings
> - Limit More Villagers: Missing Buildings houses to 1 per village
> - Limit More Villagers houses to 1 per village
>   **Technical changes**
> - Fix various kinks in the mods.
>   **Bug Fixes**
> - Fix references to legacy loot table

> [!note]- Let Me Despawn 1.26.11.1
> **Fixed**
>
> - Fixed a crash with Easy NPC and other mods that make their mobs persistent while the mob is still being created. Spawning an Easy NPC failed with a `NullPointerException`, and NPCs already in the world failed to load, so the next save dropped them. Let Me Despawn now checks a mob's name only for mobs that came from a spawner, so it never reads a mob that isn't finished yet.
>
> **Changed**
>
> - Requires Almanac 1.26.11.1 or newer, which bundles Dungeon Config 1.26.11.1.

## Configs

- Neoforge version : /
- Removed :
  - [Enchantment Outlines](https://modrinth.com/resourcepack/glowing-glints)
  - [Not Enough Animations](https://modrinth.com/mod/not-enough-animations)
- Added :
  - [Outline N' Stuff - Enchantments](https://modrinth.com/mod/outlinestuff)
  - [Punchy! Moves](https://modrinth.com/mod/punchymoves)
  - [Create: Magneutica](https://modrinth.com/mod/create-magneutica)
  - [Create: Pocket Factory](https://modrinth.com/mod/create-pocket-factory)
  - [Atlas Api](https://modrinth.com/mod/atlas-api)
  - [Iron's Gems 'n Jewelry](https://modrinth.com/mod/irons-jewelry)
  - [Create: Octo Arms](https://www.curseforge.com/minecraft/mc-mods/create-octo-arms)
