---
category: class-support
status: active
scope: dev only
---

# MCDM: Core Support Module

**Version:** 1.0.0  
**Used In:** Dev Servers Only  
**Purpose:** Enables key functionality for MCDM player classes like the Illrigger and Beastheart, including support for custom resources and subclass mechanics.

## Configuration Snapshot

![MCDM Core Support Settings v1.0.0](./MCDMCoreSupport-v1.0.0.png)

## Configuration Notes

- **Actor Resource for Ferocity**: `Resource 1 Value`  
  - Used by the Beastheart to sync Ferocity between actor and companion

## Usage Notes

- ✅ Required for:
  - **Illrigger class** (e.g., custom spellcasting for Architect of Ruin)
  - **Beastheart & Monstrous Companions** (Ferocity syncing)
- ❌ Not required for MCDM monsters, Strongholds, or Fleets modules
- 📂 Only enabled in dev servers so players can browse class options
- 🔁 If a player chooses one of these classes, the module will be activated in their assigned world

## Maintenance & Relevance

- ✅ Official support from MCDM
- ⚠️ Needs to remain synced with future MCDM class/module releases
- 🔍 May expand in scope if additional class mechanics are added to Foundry

## Related Modules

- [[Illrigger (MCDM)]] – requires this module for subclass automation
- [[Beastheart (MCDM)]] – uses Ferocity resource field mapping
