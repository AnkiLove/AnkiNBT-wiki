# AnkiNBT 1.2.4 Changelog

1.2.4 focuses on stability, editor usability and complete 26.1 line support. The documentation was also moved into the standalone AnkiNBT-wiki project.

## Added And Improved

### Version Support

- Added Fabric builds for 26.1, 26.1.1 and 26.1.2.
- Added NeoForge builds for 26.1, 26.1.1 and 26.1.2.
- The 1.21 line continues to use Java 21.
- The 26.1 line uses Java 25.

### Text Editing

- Name and lore editors support `Ctrl+A`.
- Arrow keys move the cursor.
- Holding `Shift` extends the selection.
- Mouse clicks move the cursor, and dragging can select text across multiple lines.
- Selected text can receive color or formatting codes.
- Minecraft-style `&` formatting is supported, such as `&c`, `&b`, `&l` and `&r`.

### Simple Mode

- General, enchantment, lore, attribute, appearance, potion and tool categories are more complete.
- Enchantments and attributes use localized names. Chinese shows translated names with namespaces.
- Existing enchantments and attribute modifiers can be removed with `X`.
- Attribute notes were added and can be toggled in config.
- Theme color coverage was expanded across buttons, selected rows, borders and sub-editors.

### Potion Editing

- Potion-like items use a dedicated potion layout.
- Normal potions, splash potions, lingering potions and tipped arrows are supported.
- Base potion selection is supported.
- Custom potion color is supported.
- Adding potion effects supports multi-select.
- Each effect can have its own duration, amplifier, ambient flag, particles flag and icon flag.
- The selected effect list can be selected and scrolled.

### Advanced Mode

- The NBT tree supports search, expand, collapse, add, delete and type validation.
- Value editors now include basic text-editor behavior.
- Search focus issues were fixed on 1.21.9 through 1.21.11 and the 26.1 line.

### Item Picker And Villager Trades

- The item picker searches by item name and namespace.
- Villager trade item selection uses the searchable picker.
- Trades can edit buy item, second buy item, sell item, counts, max uses, XP and price multiplier.
- Existing villagers and villager spawn eggs are supported.

### NBT Files

- Import and export support categories, aliases and a configurable directory.
- Fixed duplicate external file picker windows from some import entry points.

## Fixes

- Fixed the startup module export conflict on NeoForge 26.1, 26.1.1 and 26.1.2.
- The 26.x builds no longer package Minecraft-owned `net.minecraft` classes into the mod JAR.
- Fixed mouse and keyboard focus issues in editors, item pickers and search boxes across several versions.
- Fixed missing Chinese text and incomplete theme color coverage in several editor panels.

## Documentation

- Documentation moved to the standalone `AnkiNBT-wiki` repository.
- The documentation root now opens directly to Quick Start.
- Added a feature overview page.
- The header GitHub link now points to the main `AnkiLove/AnkiNBT` project.

## Verification

- All 30 release builds were rebuilt locally with clean build tasks.
- Result: 30 successful, 0 failed.
- The fixed 26.x JARs were checked to ensure they do not contain `net/minecraft` entries.

Note: this release uploads 1.2.4 binaries only. The 1.2.4 source snapshot is not synced.
