# AnkiNBT 2.0.0 Changelog

2.0.0 is the major stable release of AnkiNBT. Its primary change is a systematic redesign of the interface structure, editing workflows and interaction model. This release also replaces the earlier 2.0.0 artifacts, adds Minecraft 1.21 and completes real-client validation for every supported Fabric and NeoForge target.

## Rebuilt Editors

- Rebuilt the item editor for general fields, enchantments, lore, attributes, appearance, potions and tools.
- Added spawn-egg and live-entity editing for name, health, common state flags, undo and server readback.
- Rebuilt the villager trade editor with add, copy, move, delete, undo, two buy items, sell items and complete trade fields.
- Added villager profession, level, type and live offer saving.
- Added independent width, height, scale, live preview and resize reconstruction.

## Display And Input

- Updated the in-game AnkiNBT mark.
- Switched to Mynaui bitmap icons to fix private-use glyphs rendering as boxes.
- Fixed duplicate fallback icon rendering when a compatibility method returns `void`.
- Improved Chinese IME focus, mouse selection and text shortcuts.

## Cross-Version Fixes

- De-duplicated enchantment registry IDs and ensured `minecraft:lunge` appears at most once.
- Fixed scissor-state leaks and background flicker in low-version Fabric entity and trade editors.
- Supported the legacy fire-resistant `Unit` component on Fabric 1.21/1.21.1.
- Supported the unbreakable `Unit` component on Fabric 1.21.5/1.21.6.
- Fixed version differences in holders, item components, entity tags, villager offers and MerchantOffer serialization.

## Release Targets

- Minecraft 1.21 through 1.21.11.
- Minecraft 26.1, 26.1.1, 26.1.2 and 26.2.
- Fabric and NeoForge, for 32 dedicated jars.
- Java 21 for the 1.21 line and Java 25 for the 26.x line.
- Fabric builds require the matching Fabric API.

## Validation

- 64/64 loader, version and language combinations passed.
- 3648/3648 item, entity, trade and display checks passed.
- Tests ran in exclusive fullscreen, GUI scale 4, Chinese and English.
- 1984 final screenshots and zero runtime log issues.
- QA automation code is not included in release jars.

Download: [GitHub Release 2.0.0](https://github.com/AnkiLove/AnkiNBT/releases/tag/2.0.0)
