---
category: chat
status: active
scope: all worlds
---

# Chat Portrait

**Version:** 1.50.1  
**Used In:** All Worlds  
**Purpose:** Adds visually distinct portraits and player-colored message styling to the chat window, improving readability and enhancing roleplay immersion.

## Configuration Snapshots

- ![ChatPortrait-v1.50.1-a](./ChatPortrait-v1.50.1-a.png)
- ![ChatPortrait-v1.50.1-b](./ChatPortrait-v1.50.1-b.png)
- ![ChatPortrait-v1.50.1-c](./ChatPortrait-v1.50.1-c.png)
- ![ChatPortrait-v1.50.1-d](./ChatPortrait-v1.50.1-d.png)
- ![ChatPortrait-v1.50.1-e](./ChatPortrait-v1.50.1-e.png)
- ![ChatPortrait-v1.50.1-f](./ChatPortrait-v1.50.1-f.png)
- ![ChatPortrait-v1.50.1-g](./ChatPortrait-v1.50.1-g.png)

## Configuration Notes

- ✅ **Disable Chat Portrait** – enabled, since other options configure the behavior
- ✅ **Use Token Name**, **Avatar Player Image**, and **Show Aliases** – enabled for clarity
- ✅ **Player Color Border & Background** – enabled, set to black border, 2px
- ✅ Most message types (IC, OOC, Emote, Whisper, Roll, Other) are customized
- ✅ CSS blocks are configured for layout consistency (`margin: auto`)
- ☐ GM-specific features (like alias image overrides) are disabled
- ☐ Integration with "Speaking As" is disabled

These settings aim to **maximize readability and clarity**, especially in games with mixed in-character and out-of-character chat.

Two additional screenshots are inclued in the repo to show of applying the config changes to this module. These are used in the "Did You Know #1" documentation
	- ./ChatCardClean.png
    - ./ChatCardDefault.png

## Maintenance & Relevance

- ⚠️ **Not yet updated for Foundry V13** — monitor closely before upgrading
- ✅ Fully functional in Foundry V12
- 🧭 A core part of your chat visibility and roleplay system
- 💬 Offers a much-improved experience over the default chat layout

## Related Modules

- [[Actually Private Messages]] – works well alongside for structured whisper visibility
- [[Autocomplete Whisper]] – complementary to improving typed chat flow
- [[Illandril’s Chat Enhancements]] – may conflict or overlap, currently not in use

## Tasks

- [x] Capture and commit all config screenshots
- [ ] Monitor V13 compatibility news and issue tracker
- [ ] Export or backup CSS snippets if major update changes format
