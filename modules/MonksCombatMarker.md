---
category: combat-visuals
status: active
scope: all worlds
---

# Monk's Combat Marker

**Version:** 1.0.1  
**Used In:** All Worlds  
**Purpose:** Adds animated visual highlights to tokens in combat to improve visibility and focus for players and the GM.

## Configuration Snapshot

![Combat Marker Settings](./MonksCombatMarker.png)

## Configuration Notes

- ☐ **Clear Token Highlight** – disabled (markers remain throughout turn)
- 🎞️ **Animation Speed:** 100
- ✅ **Combat Highlight Size:** `1.1` (slightly larger than token)
- 🌀 **Animations:**
  - **Friendly:** Clockwise
  - **Hostile:** Counter-clockwise
  - **Neutral:** Clockwise
- 🖼️ **Images Used:** Default markers from `modules/monks-combat-marker/markers`

## Usage Notes

- Integrates well with:
  - [[Monk's Combat Details]] – timing and turn logic
  - [[Dice So Nice]] – synchronized with initiative cues
- Helps identify whose turn it is at a glance, even on crowded maps
- Can be customized with user-defined marker images if desired

## Maintenance & Relevance

- ✅ Actively maintained, lightweight
- 🔍 Optional aesthetic mod, but improves gameplay clarity
- 🎨 Marker customization possible via image folder replacement

## Tasks

- [x] Document settings and animation behavior
- [ ] Optionally add custom highlight images for themed campaigns
