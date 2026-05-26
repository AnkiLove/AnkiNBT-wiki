# Feature Overview

AnkiNBT 1.2.4 focuses on item editing, potion editing, villager trades, text editing and cross-version compatibility. This page is written for players who want to know what the mod can do before opening the NBT tree.

## Two Editing Modes

| Mode | Best for | What it does |
|---|---|---|
| Simple Mode | Players who do not want to write NBT directly | Edit name, count, durability, enchantments, lore, attributes, potion effects and appearance from visual panels. |
| Advanced Mode | Map makers and technical users | Inspect and edit the NBT tree with search, add, delete, expand, collapse and type validation. |

You can switch modes from the editor header. Changes are not written back immediately. Press `Ctrl+S` when the edited item looks correct.

## Item Editing

- Edit the item in your main hand, or hover an item inside an inventory or container and open the editor.
- General fields include name, count, durability, max durability, max stack size, repair cost, unbreakable, fire resistant and rarity.
- Appearance fields include custom model data, enchantment glint, hidden tooltip, dye color and item name color.
- Tools include copy NBT, copy `/give` command, import NBT, export NBT and reset to the state from when the editor was opened.

## Lore And Text Editing

The 1.2.4 text editor behaves more like a normal editor:

- `Ctrl+A` selects all text.
- Arrow keys move the cursor.
- Holding `Shift` extends the selection.
- Mouse clicks move the cursor, and dragging can select text across multiple lines.
- Selected text can receive color or formatting codes.
- `&` color codes are supported, such as `&c` red, `&b` aqua, `&l` bold and `&r` reset.
- Lore supports multiple lines, reordering, deletion and per-line editing.

## Enchantments

- Enchantments use localized names. Chinese language shows Chinese names with namespaces, English language shows English names.
- The add list can search by translated name, English name or namespace.
- Existing enchantments can be edited by level or removed with `X`.
- A clear-all action removes every enchantment from the item.

## Attribute Modifiers

- Attribute modifiers have localized labels and optional notes.
- Supported attributes include attack damage, attack speed, armor, armor toughness, max health, movement speed, knockback resistance, luck and more.
- Three operations are available: add, multiply base and multiply total.
- Slot filters include any, main hand, off hand, head, chest, legs and feet.
- Existing modifiers can be removed with `X`.
- Attribute notes can be toggled in config. They are off by default for a cleaner list.

## Potion Effects

Potion items use a dedicated potion editor:

- Detects normal potions, splash potions, lingering potions and tipped arrows.
- Lets you choose the base potion.
- Supports a custom potion color.
- Allows multi-select when adding effects.
- Each selected effect can have its own duration, amplifier, ambient flag, particles flag and icon flag.
- The selected effect list is scrollable and can be selected for editing.
- Custom effects can be cleared at once.

## Item Picker And Villager Trades

- The item picker searches by item name and namespace.
- The villager trade editor can edit buy item, second buy item, sell item, counts, max uses, XP and price multiplier.
- Trade item selection uses the same searchable picker.
- It can edit existing villagers or write trade data into villager spawn eggs.

## Entities And Config

- The entity editor targets the entity you are looking at or an item that can store entity data.
- The config menu controls default mode, opacity, theme color, attribute notes, export directory and key binds.
- Theme color is applied across main buttons, selected rows, borders and sub-editors.

## NBT Import And Export

- Exported files are saved to `.minecraft/ankinbt-config/save-nbt/` by default.
- Files can be organized by category and given aliases.
- The import screen shows file name, alias, size and modification time.
- 1.2.4 fixes duplicate external file picker windows on some import entry points.

## Compatibility

1.2.4 covers Fabric and NeoForge:

- Minecraft 1.21 through 1.21.11
- Minecraft 26.1, 26.1.1 and 26.1.2

Use Java 21 for the 1.21 line and Java 25 for the 26.1 line. Fabric builds require Fabric API.
