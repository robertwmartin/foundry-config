---
category: audio
status: active
scope: all worlds
---

# Monk's Sound Enhancements

**Version:** 12.03
**Used In:** All Worlds  
**Purpose:** Adds sound-related features and cosmetic UI tweaks to enhance how playlists and sound effects are experienced and triggered in-game.

## Configuration Snapshot

![Sound Enhancements Settings](./MonksSoundEnhancements.png)

## Configuration Summary

- ✅ **Change Playlist Style** – improves UI feedback when a track is playing
- 🎭 **Actor Sound Effects:** `NPCs` – only NPC sheets show the SFX trigger button
- 🎵 **Item Sound Effects:** `Everyone` – all actors can trigger item-based sounds
- ☐ **Combat Sound:** disabled
- ✅ **Default Hide Names:** hides sound file names in hidden playlists
- ☐ **Show Playlist Description:** disabled (see explanation below)

---

## ❓ What is “Show Playlist Description”?

This option:
- Displays a tooltip (popup text) when you **hover over a playlist** in the sidebar
- The tooltip content comes from the `description` field of that playlist
- **Only visible to users with permission to view/edit playlists** (usually GMs)

### 📌 Use Case

You might enable this if:
- You use descriptive playlists (e.g., “Rainstorm – use for tense travel scene”)
- You share sound responsibilities with a co-GM or player during stream prep
- You want quick reminders or tagging without opening the playlist editor

### ✅ Verdict

Useful if you:
- Organize playlists with intentional scene-based use
- Want lightweight hover-to-reference behavior

Safe to leave off if:
- You don’t describe your playlists, or don’t want visual clutter

---

## Tasks

- [x] Capture config
- [ ] Decide whether to populate playlist descriptions to take advantage of tooltip
