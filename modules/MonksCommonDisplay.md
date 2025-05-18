---
category: player-ui
status: active
scope: all worlds
---

# Monk's Common Display

**Version:** 1.1.0  
**Used In:** All Worlds  
**Purpose:** Provides a GM-controlled shared view (the "Common Display") useful for streaming, local players, or group viewing of focused content.

## Configuration Snapshot

![Common Display Settings](./MonksCommonDisplay.png)

## Current Settings Summary

- ☐ Setting per scene – not stored uniquely per scene
- ✅ Hide UI – not hiding UI elements on common display
- ☐ Allow GM Players – not currently allowing GM-level users in the list
- ✅ Screen Padding: 10
- ✅ Show Chat Log – chat window is visible
- ☐ Show Camera Views – not enabled (see notes below)
- ✅ Show Combat – auto display when combat starts
- ☐ Show All Combatants – only active combatant shown
- ☐ Limit Combatants: `1`
- ☐ Auto-Close Popouts – closes popouts after 10 seconds

## Setting Notes

### ❓ Show Camera Views
- **What it does**: Displays webcam feeds (if enabled via Foundry’s LiveKit or other AV module) in the Common Display
- **Use case**: Only helpful for stream overlays or hybrid setups (e.g., players around a table watching a TV)
- ✅ Safe to leave off unless you plan to integrate webcam views visually on a shared display

### ✅ Useful Settings You’ve Enabled
- **Show Combat**: Makes shared view dynamic and responsive
- **Chat Log**: Helps passive viewers follow what's happening

### 🔄 Optional Tweaks to Consider
| Setting | Why Enable |
|--------|------------|
| `Show All Combatants` | Useful in large fights or for overview visibility |
| `Setting per Scene` | If you want per-map camera layout/overlay configs |

## Usage Examples

- Streaming overlay for Twitch (via OBS with this window captured)
- Display on secondary monitor or wall-mounted screen for in-person group
- Passive viewer mode for remote spectators or moderators

## Maintenance & Relevance

- ✅ Lightweight, works with most module setups
- 🎥 Potential future use with LiveKit for hybrid streaming + A/V overlay

## Tasks

- [x] Initial screenshot and baseline documentation
- [ ] Revisit after configuring full stream layout (Monoclass Madness?)
