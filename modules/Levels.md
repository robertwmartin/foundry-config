---
category: map-tools
status: active
scope: all worlds
---

# Levels

**Version:** 1.27.2  
**Used In:** All Worlds  
**Purpose:** Adds verticality, elevation-based visibility, and multilayer fog of war to scenes. Essential for advanced map layouts, buildings with multiple floors, and 3D navigation effects.

## Configuration Snapshot

![Levels Settings v1.27.2](./Levels-v1.27.2.png)

## Configuration Notes

- ✅ **Elevation Scale** – enabled
- ✅ **Elevation Scale Multiplier:** 1.0
- ✅ **Advanced Fog of War** – enabled
- ✅ **Reveal token in fog** – enabled
- ☐  **Lock Elevation** – players may still modify if they have permissions
- 🔽 **Hide Elevation:** Don't Hide
- ✅ **Precise token visibility** – enabled for better occlusion accuracy
- ☐  **Exact token visibility** – disabled (reserved for 3D Canvas or performance-sensitive setups)
- 📂 **Multilevel Fog Folder:** `LevelsMultiLevelFog`
- ☐ **Migrate settings on startup** – manual migration only

## Usage Notes

- Used for:
  - Multi-floor buildings and vertical scenes
  - Controlling line-of-sight with elevation and token positioning
- Not yet used for:
  - Complex elevation triggers
  - 3D canvas support
  - Exact token sighting and automated floor switching

## Maintenance & Relevance

- ✅ Active and highly maintained
- 🧠 Core to immersive scene layouts in your campaigns
- ⚡ Requires precision in walling, floors, and token placement for best results

## Related Modules

- [[Less Fog]] – previously used for fog adjustments, now removed
- [[FXMaster]] – works visually alongside layered scenes
- [[Scene Packer]] – can help with exporting multi-layered maps
- [[Automated Animations]] – needs coordinate precision when elevation is involved

## Tasks

- [x] Capture and commit current settings screenshot
- [ ] Explore 3D Canvas and Exact Visibility for more realism
- [ ] Consider using Levels Triggers (advanced feature) for automated floor switches
