# Quick Start

Pick the jar that matches your loader and Minecraft version, then place it in your `mods` folder. In game, hold an item or hover one in your inventory, then press `N` to open AnkiNBT.

## Choose A Build

| Loader | Minecraft | Java |
|---|---|---|
| Fabric | 1.21 through 1.21.11, 26.1 through 26.1.2 | Java 21 for 1.21 builds, Java 25 for 26.1 builds |
| NeoForge | 1.21 through 1.21.11, 26.1 through 26.1.2 | Java 21 for 1.21 builds, Java 25 for 26.1 builds |

Fabric builds also require Fabric API.

[Installation](installation-guide.md){ .md-button .md-button--primary }
[Compatibility Matrix](compat-matrix.md){ .md-button }

## Open The Editor

### Main Hand Item

1. Hold an item in your main hand.
2. Press `N`.
3. The editor opens for that item.

### Inventory Hover

1. Open your inventory or a container.
2. Hover the item you want to edit.
3. Press `N`.
4. The editor opens for the hovered item.

If there is no held or hovered item, AnkiNBT shows a message that no editable item was found.

## Editing Modes

| Mode | Best For | Description |
|---|---|---|
| Simple Mode | Common edits | Visual editing for names, lore, enchantments, attributes, appearance and potion effects. |
| Advanced Mode | Precise edits | Inspect, search and edit NBT nodes directly. |

[Simple Mode](simple-mode.md){ .md-button }
[Advanced Mode](advanced-mode.md){ .md-button }

## Save And Close

- Press `Ctrl+S` to save changes to the item.
- Saving is only available in Creative Mode.
- Press `Esc` to close the editor.
- Unsaved changes trigger a confirmation prompt.

## Configuration

The config file is stored at `.minecraft/config/ankinbt.json`. Common options include the open key, default mode, UI opacity, NBT export directory and close confirmation.

[Shortcuts](keyboard-shortcuts.md){ .md-button }
[FAQ](faq.md){ .md-button }
