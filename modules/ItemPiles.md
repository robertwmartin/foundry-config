---
category: inventory
status: active
scope: all worlds
---

# Item Piles

**Version:** 1.8.4  
**Used In:** All Worlds  
**Purpose:** Adds interactive containers (e.g., chests, corpses, loot drops) and merchant functionality to the game. Supports trading, inventory inspection, and drop-based item creation.

## Configuration Snapshots

- ![ItemPiles-v1.8.4-a](./ItemPiles-v1.8.4-a.png)
- ![ItemPiles-v1.8.4-b](./ItemPiles-v1.8.4-b.png)
- ![ItemPiles-v1.8.4-c](./ItemPiles-v1.8.4-c.png)
- ![ItemPiles-v1.8.4-d](./ItemPiles-v1.8.4-d.png)

## Configuration Notes

### ✅ Local Settings
- ☐ Optional UI toggles left off
- ✅ Preload Files – improves performance for effects/images

### ✅ Module Settings
- ✅ Enable Dropping Items, Giving Items, and Trading
- ✅ Trade Button and Inspecting Items during Trades enabled
- 🗨️ Output to Chat: Public
- ☐ Auto-delete Empty Piles – disabled for safety

### 🎨 Style Settings
- Presets available, not actively customized yet

### ⚙️ System-Specific (D&D 5e)
- Actor & item classes mapped to: `character`, `loot`, `weapon`, `equipment`
- Quantity & price attributes: `system.quantity`, `system.price.value`
- Currency config available but unmodified

## Maintenance & Relevance

- ✅ Maintained and compatible with Foundry V12
- 🧠 Essential for immersive loot containers, trade interactions, and scene-based inventory
- 🔍 No current Foundry v13 core replacement — this module is still required
- 💬 Players enjoy the visual and mechanical clarity it adds to looting

## Related Modules

- [[DFreds Pocket Change]] – optional addon for random coin loot
- [[Item Macro]] – works with merchants or custom behaviors
- [[FXMaster]] – can enhance visual feedback during loot interactions

## Tasks

- [x] Capture and commit screenshots (Local, Module, Style, System tabs)
- [ ] Monitor v13 updates for native container support (none yet)
- [ ] Optional: Configure Currencies and Vault Styles for extended flavor
