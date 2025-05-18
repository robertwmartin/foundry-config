---
category: combat-enhancement
status: active
scope: all worlds
---

# Monk's Combat Details

**Version:** 12.02
**Used In:** All Worlds  
**Purpose:** Expands Foundry's default combat tracker with audio/visual feedback, initiative rules enforcement, and enhanced player turn management.

## Configuration Snapshots

![Combat Details 1](./MonksCombatDetails-a.png)  
![Combat Details 2](./MonksCombatDetails-b.png)  
![Combat Details 3](./MonksCombatDetails-c.png)  
![Combat Details 4](./MonksCombatDetails-d.png)  
![Combat Details 5](./MonksCombatDetails-e.png)

## Configuration Summary

### 🔐 Rules Enforcement
- ✅ No Combat Without Initiative
- ✅ Prevent Token Removal
- ✅ Order Initiative by player
- ✅ Prevent Spell Changes (via chat message)

### 🎯 Placeholders
- ✅ Enabled via Sidebar
- ☐ No initiative formula or custom image set (defaults used)

### 📊 Display & Alerts
- ✅ CR display for encounter setup
- ☐ CR hidden during live combat
- ✅ Start of combat pop-up dialog (shown to everyone)
- ✅ Switch tabs and remember tracker position
- ✅ Visual turn alerts and round banners enabled

### 🔉 Sound Notifications
- ✅ “Next Up”, “Your Turn”, and “New Round” sounds enabled
- ✅ Volume: 60%
- 🎵 Sounds sourced from `monks-combat-details/sounds/`

## Optional Features (Currently Disabled)

You may wish to explore enabling the following based on your playstyle:

| Feature | Description | Why Enable |
|--------|-------------|------------|
| `Show CR in Combat` | Displays Encounter CR during live combat | Transparent challenge overview for GM |
| `Pan to Combatant` | Camera auto-focus on token at turn start | Helps players in large or zoomed-out maps |
| `Turn Dead Invisible` | Auto-hides dead tokens | Immersion boost if you want bodies to vanish |
| `Large Turn Notification` | Displays a larger, centered visual | Dramatic effect for stream-style games |
| `Add Combat Bars` | Adds separate HP bars for in-combat tokens | Useful in large-scale battles

## Maintenance & Relevance

- ✅ Actively maintained
- 🧠 Complements automation-focused setups and streaming overlays
- 🔊 Ideal for groups who respond well to audio/visual cues

## Tasks

- [x] Capture current settings and sound paths
- [ ] Consider testing `Pan to Combatant` or `CR in Combat` in next session
