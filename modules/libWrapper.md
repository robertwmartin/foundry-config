---
category: library
status: active
scope: all worlds
---

# libWrapper

**Version:** 1.12.0  
**Used In:** All Worlds  
**Purpose:** Foundation library for safely overriding core Foundry VTT functions. Required by many modules to inject hooks or patch behaviors.

## Configuration Snapshot

![libWrapper Settings v1.12.0](./libWrapper-v1.12.0.png)

## Configuration Notes

- ✅ **Notify GM of Issues** – enabled (default, recommended)
- ☐ **Notify Players of Issues** – disabled
- ☐ **High-Performance Mode** – disabled (safer for detecting module conflicts)
- **Verbosity:** `Warning` – standard console feedback level

These defaults provide a healthy balance of awareness without unnecessary console noise or player confusion.

## Usage Notes

- Required by:
  - DFreds modules
  - Levels
  - Item Piles
  - Chat Portrait
- Present in nearly all module-rich Foundry setups
- Rarely interacted with directly unless troubleshooting or debugging

## Maintenance & Relevance

- ✅ Actively maintained and essential to the Foundry ecosystem
- 🔍 If conflicts occur, libWrapper provides detection and console logging
- 🧠 Safe to leave installed even when not directly used

## Tasks

- [x] Track config in case future versions add toggles or performance settings
