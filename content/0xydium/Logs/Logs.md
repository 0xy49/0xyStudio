---
publish: true
created: 2026-10-22T13:06:02.826Z
modified: 2026-10-31T15:30:38.771Z
published: 2026-10-31T15:30:38.771Z
outgoing_links: "[[Mojang.base]]"
---

# 31/10/26

> [!note]- 0xydium
>
> - Update to NeoForge Version `21.1.265`
> - Remove Copper Armor & Tools
> - Remove Mushroom Scale system

> [!note]- Amendments 2.2.5
> more configs and compat code

> [!note]- AzureLib 3.2.4
> v3.2.4
>
> **Additions**
>
> - Added spring bone colliders. `AzSpringCollider` is a sphere or capsule attached to a bone, positioned in Blockbench pixels from the bone's pivot, that follows the bone's animated pose. Spring chains can't pass through them, so tails, ears and capes swing around the body instead of through it. One collider can be shared by several chains.
> - Added `AzSpringBone.Builder#collider` to give a chain its colliders, `#radius` for how thick the chain is, and `#ground` to keep the chain above the entity's feet (or the model's origin for items and block entities).
>
> **Changes**
> …

> [!note]- Collective 8.72 neo
>
> - Fixed issues related to Collective's player respawn function, used by dependent mods.(26.1.2 NeoForge) Removed the temporary fix for some dependent mods not showing their icon.The complete changelog with detailed information about previous versions can be found on my website: >

> [!note]- Concurrent Chunk Management Engine (NeoForge) 0.4.0-alpha.0.124
> This version is uploaded automatically by GitHub Actions.
>
> Changelog:
>
> - 88b41272 new: implement ChunkTicketLevelUpdatedEvent - ishland

> [!note]- Create Encased 1.10.0-fix1
> CreateEncased 1.10.0-fix1:
>
> **Translations**
>
> - Update zh\_cn translation
>
> **Bug Fixes**
>
> - Fix shafts and cogwheels recipe overriding
> - Fix chains can't be placed because of Chain conveyors

> [!note]- Create: Bits 'n' Dyes 1.1.3
>
> - Fix frogport goggle display
>   - Fix latest sound of steam incompatibility

> [!note]- Create: Cyber Goggles 8.7.0
>
> - Add expression input to quantity boxes
> - Add a multiplier field and an apply button to quantity screens to scale every value at once
> - Add an option to abbreviate large item counts
> - Optimize the force overlay: cluster arrows per force group and cap their count to reduce lag
> - Fix the filter preview typing an extra character into the opened screen
> - Make the filter preview read-only, and allow third-party mods to register their own preview screens

> [!note]- Create: Radars 5.0.3
>
> - Fixed Filterer rendering on Network Block
> - Fixed ghost Datalinks in some situations
> - Fixed Swivel accuracy when cannon mount is placed further from the swivel
> - Reworked Jammers config so that its more intuitive and works out of the box for more cases
> - Binocular obstruction checks removed except when targeting sable ships

> [!note]- Create: Sound of Steam 0.9.2.1
> 1.21.1-specific patch
> **Bugfixes**
>
> - Server crash upon trying to decode keyboard relay packets
> - Diapason and Prestant missing from the creative menu
> - Several issues with the MIDI config GUI

> [!note]- CreativeCore 2.13.52
>
> - Fixed origin pose not getting updated during collision

> [!note]- Cubes Without Borders 5.0.0+1.21.0.
> **Features**
>
> - Added a new Fullscreen Mode option, `Windowed`, to simplify access to secondary borderless fullscreen types that prioritize preserving the characteristics of a windowed application over performance
>   - Users who previously changed the `Borderless Fullscreen Type` option in the mod's settings for this exact reason are encouraged to revert those changes and use this new fullscreen mode instead
> - Added two new macOS-related config options, `autoHideDock` and `autoHideMenuBar`, which control whether the dock and the menu bar, respectively, can be revealed by moving the mouse to the edge of the screen when using borderless fullscreen, rather than being hidden entirely
>   …

> [!note]- Data Anchor 2.0.0.18
>
> - Fix race condition

> [!note]- Easy NPC 7.17.1
>
> - Refactored the build to no longer ship tests, which makes the mod files up to 20 % smaller.

> [!note]- Easy NPC: Config UI 7.17.1
> Même changelog que Easy NPC.

> [!note]- Easy NPC: Core 7.17.1
> Même changelog que Easy NPC.

> [!note]- Fresh Animations: Extensions 1.10.0
> **All Extensions 1.10 Includes:**
>
> - Details Add-on 2.4
> - Objects Add-on 2.1.3
> - Quivers Add-on 2.3
> - Emissive Add-on 1.7
> - Creeper Edit 2.2
> - Spiders Edit 2.3
>
> **Details Add-on 2.4:**
>
> - added baby textures and models for pigs, sheep, cows, mooshroom
> - added baby sheep texture variants
> - added tweaked baby villager and zombie villager textures
> - added tweaked baby armour models and textures
> - added baby muddy pig texture variants
> - added baby donkey and mule textures and models
> - improved llama and donkey chest textures
> - tweaked temperate and cold cow textures
> - tweaked llama models
> - tweaked models to use FA 1.11 format
> - fixed broken models
> - fixed iron golem brow and pupils sometimes z-fighting
> - fixed cold cow horns texture UVs
>
> **Emissive Add-on 1.7:**
>
> - added classic bat
>   …

> [!note]- Fzzy Config 0.7.7+fix1
> **Breaking changes in 0.7.x**
>
> - `ValidatedEnumMap` is removed
> - Removed all methods and properties marked as Deprecated and for removal 0.7.0
>   - `SmallSpriteDecoration#`
>   - `SpriteDecorated#textureSet` & `textures` is now a required override
>   - `SpriteDecoration#`
>   - `CustomButtonWidget#` & builder is now only non-override method for adding custom button
>   - Removed `ActiveButtonWidget`
>   - Removed `TextlessActionWidget`
>   - `DynamicListWidget.EntryPos` and implementations made `internal`
>   - `PopupWidget` position elements; `LayoutWidget` no longer inherits from the PopupWidget variant
>   - Removed deprecated overrides of `PopupController` from `PopupParentElement`
>   - `SuggestionWindowListener` and `SuggestionWindowProvider` moved out of `internal` sub-package
>     …

> [!note]- Hyper Punchy 2.8
> **Fix Update!!!**
>
> We’ve completely switched to Blender for the infrastructure.
>
> Many new animations have been created.
>
> Hand positioning bugs and tool animation loops have been fixed.
>
> We’ve completely dropped the Respackopts dependency.
>
> Mixpack bugs fixed.
>
> Camera animations are temporarily unavailable, they’ll be included in the next release.
>
> Curseforge now has an official same version good news for our friends there too :P

> [!note]- Iron's Lib 2.3.0
> **Additions**
>
> - Added Autumn Knight Transmog
> - Added Pumpkin Heads Transmog

> [!note]- Just Enough Items (JEI) 19.70.0.468
>
> - Fix IME input after search actions - mezz

> [!note]- Just Enough Resources (JER) 1.6.0.60
> \[6815e71] Update Russian localization (GitHub)

> [!note]- Keybind Atlas 2.1.1
>
> - Fix crash

> [!note]- MezzConfig 0.6.10
>
> - Expose immutable sorting snapshots - mezz
>   - Bump version to 0.6.9 - mezz
>   - Dispatch config listeners outside schema locks - mezz
>   - Add Simplified Chinese translation - jim139129
>   - Use AtomicFile for config file operations - mezz
>   - Bump version to 0.6.8 - mezz
>   - Fix Windows path and file replacement tests - mezz
>   - Quote the Minecraft version argument in Windows CI - mezz
>   - Retry Windows file sharing failures during config saves - mezz
>   - Separate staged and committed config file states - mezz

> [!note]- Punchy! 3.0
> **The new Punchy menu**
>
> - Punchy has a brand new menu, opened with F8, from Mod Menu or from the Forge and NeoForge config buttons. Settings, Mix Packs, profiles, the item blacklist and the Hand Editor are all in one place, with a new look.
> - If the new menu ever fails to open, Punchy falls back to the old settings screen until the game restarts.
> - Other mods can add their own tabs to Punchy's menu.
> - The Hand Editor now returns to the menu when you close it.
>
> **Mix Packs**
>
> - The Mix Packs page previews each item's animations live, with your own hand and the real 3D held item. Special items show their own moves: shield use and equip, fishing rod cast and reel in, trident attack, throw, Loyalty and Riptide, spear attack and charge, and bow and crossbow load and shot.
>   …

> [!note]- Puzzles Lib 21.1.66
> **Fixed**
>
> - Restore missing transitive access wideners

> [!note]- Sophisticated Backpacks 3.26.18.2235
> **Fixes**
>
> - Fixed forged requests bypassing inventory access restrictions

> [!note]- Sophisticated Core 1.5.21.2439
> **Fixes**
>
> - Fixed forged requests bypassing inventory access restrictions
> - Fixed storage overflow voiding being blocked by reserved empty slots

> [!note]- Sophisticated Item Actions 0.5.19.446
> Même changelog que Sophisticated Backpacks.

> [!note]- SuperMartijn642's Core Lib 1.1.26
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
> - Fixed widgets not being unfocused when removed
> - Fixed `ScrollbarWidget` accepting scroll input when not focused
> - Fixed `ClientUtils#closeScreen` not closing screens without a container
>   …

## Configs

- Neoforge version : `21.1.264` => `21.1.265`
- Removed [Loot Beams: Refork](https://modrinth.com/mod/loot-beams-refork)
- Added :
  - [Aeronautics: Joy of Creation](https://modrinth.com/mod/aeronautics-joy-of-creation)
  - [Copper Age Backport](https://modrinth.com/mod/backport-copper-age)
  - [Create: Pocket Sized](https://modrinth.com/mod/create-pocket-sized)
  - [Fancy Items](https://modrinth.com/mod/fancyitems)
  - [Pehkui](https://modrinth.com/mod/pehkui)
  - [Punchy! Studio](https://modrinth.com/mod/punchystudio)
