# Quick Start

AnkiNBT is a client-side editor for item data, entity data and Minecraft data components. Pick the right jar, place it in your `mods` folder, then hold an item or hover one in an inventory and press `N`.

## Pick The Right File

| Loader | Download file | Java |
|---|---|---|
| Fabric | `AnkiNBT-Fabric-mcVersion-1.2.4.jar` | Java 21 for the 1.21 line, Java 25 for the 26.1 line |
| NeoForge | `AnkiNBT-NeoForge-mcVersion-1.2.4.jar` | Java 21 for the 1.21 line, Java 25 for the 26.1 line |

Fabric builds also require Fabric API. When downloading, match `Fabric` or `NeoForge` first, then match the Minecraft version after `mc`.

[Installation](installation-guide.md){ .md-button .md-button--primary }
[Compatibility Matrix](compat-matrix.md){ .md-button }

## What 1.2.4 Includes

- Fabric and NeoForge builds for Minecraft 1.21 through 1.21.11, plus 26.1, 26.1.1 and 26.1.2.
- Simple Mode for general fields, enchantments, lore, attributes, appearance, potion effects and NBT import/export.
- Advanced Mode for NBT tree search, add, delete, edit, expand, collapse and type validation.
- Name and lore editing with `Ctrl+A`, arrow keys, `Shift` selection, mouse drag selection and coloring selected text.
- Potion editing with base potion, custom color, multi-select effects and per-effect duration, amplifier, particles and icon settings.
- Localized enchantment and attribute names, search, notes and single-item removal.
- Villager trade editing with searchable item picking, buy/sell items, max uses, XP and price multiplier.
- NBT import/export with categories, aliases and a configurable output directory.

[Feature Overview](feature-overview.md){ .md-button .md-button--primary }
[Simple Mode](simple-mode.md){ .md-button }
[Advanced Mode](advanced-mode.md){ .md-button }

## Open The Editor

### Main Hand Item

1. Hold the item you want to edit.
2. Press `N`.
3. The editor opens for that item.

### Inventory Hover

1. Open an inventory, chest or other container.
2. Hover the target item.
3. Press `N`.
4. The editor reads the hovered item.

If no held or hovered item is found, AnkiNBT shows a message instead of opening an empty editor.

## Save Rules

- Press `Ctrl+S` to save changes.
- Saving is only available in Creative Mode. Other game modes can inspect data but cannot write it back.
- Press `Esc` to close the editor.
- Unsaved changes trigger a confirmation prompt.

## Common Paths

| Goal | Page |
|---|---|
| Install or update | [Installation](installation-guide.md) |
| Check supported versions | [Compatibility Matrix](compat-matrix.md) |
| Check shortcuts | [Shortcuts](keyboard-shortcuts.md) |
| Read what changed in 1.2.4 | [Changelog 1.2.4](changelog-1.2.4.md) |
| Prepare a Modrinth description | [Modrinth Copy](modrinth.md) |

## Configuration

The config file is stored at `.minecraft/config/ankinbt.json`. Common options include the open key, default mode, UI opacity, theme color, attribute notes, NBT export directory and close confirmation.
