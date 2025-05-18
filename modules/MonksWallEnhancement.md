---
title: "Monk's Wall Enhancements"
category: "Modules"
tags:
  - dev-only
  - monk
  - mapping
  - wall-tools
  - foundry-vtt
version: 1.0
lastReviewed: 2025-05-18
status: active
scope: dev
---

# Monk's Wall Enhancements

## Summary
This module provides enhanced tools for wall editing in Foundry VTT. It improves map preparation workflows by streamlining common actions like splitting, dragging, joining, and navigating wall elements.

## Why It's Used
Primarily used in **dev servers** when preparing complex Patreon maps (e.g., from CzePeku or Dr. Mapzo). It simplifies alignment, editing, and annotation of walls during map design. Not required in player-facing servers.

## Configuration

### Features Enabled

- ✅ **Show Drag Points Together**: Allows simultaneous dragging of overlapping wall points.
- ✅ **Allow double click split**: Double-click on a wall to split it at midpoint.
- ✅ **Alter wall icons**: Replaces default toolbar icons with more intuitive versions.
- ✅ **Remove Close Doors Tool**: Hides the rarely-used “Close All Doors” toolbar button to reduce clutter.
- ✅ **Allow One Way Doors**: Adds support for one-directional doors.
- ✅ **Allow Key Movement**: Enables wall movement using arrow keys.
- ✅ **Swap Wall Direction**: Allows double right-click to reverse wall direction.

### Features Disabled

- ❌ Condense Wall Types  
- ❌ Toggle Secret Door  
- ❌ Snap to Mid-point  
- ❌ Create Canvas Object

### Additional Notes

- **Toggle Walls Display** (new button in Wall Controls palette)  
  Temporarily hides all wall overlays to make aligning wall segments easier, especially on dense or pre-drawn maps.

## Screenshot

![Monk's Wall Enhancements Settings](./modules/MonksWallEnhancements.png)

