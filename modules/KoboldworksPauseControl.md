---
category: utility
status: active
scope: select worlds
---

# Koboldworks - Pause Control

**Version:** 1.3.0  
**Used In:** Selected Worlds (for auto-unpausing at load)  
**Purpose:** Automates pause/unpause behavior when the world loads or when combat starts. Useful for streamlining session transitions and improving player self-service.

## Configuration Snapshot

![Koboldworks Pause Control Settings v1.3.0](./KoboldworksPauseControl-v1.3.0.png)

## Configuration Notes

- ✅ **Unpause on Ready** – enabled  
  - Game automatically unpauses when Foundry is ready — ideal for early player access
- ☐ **Unpause on Combat** – not enabled
- ☐ **Combat Pause Control** – disabled
- ☐ **Restore Pause State** – disabled

## Usage Notes

- Used in one active game where players may arrive early
- Likely to be rolled out to other campaigns for similar convenience
- No use of dynamic combat-based pause control at this time

## Maintenance & Relevance

- ✅ Lightweight and stable
- 🧭 Adds passive quality-of-life improvement with minimal configuration
- ⚡ Can be safely ignored unless deeper pause control is needed

## Related Modules

- [[FXMaster]] – pause/unpause doesn’t affect FX directly but works well alongside
- [[Scene Packer]] – may interact with startup triggers but not directly related

## Tasks

- [x] Capture screenshot
- [ ] Consider enabling in more campaigns for player-led session entry
