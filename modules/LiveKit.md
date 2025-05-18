---
category: a/v
status: active
scope: selected worlds
---

# LiveKit AVClient

**Version:** 1.2.0  
**Used In:** One world currently; planned for Monoclass Madness and others  
**Purpose:** Provides integrated A/V (audio and video) directly within Foundry using the LiveKit WebRTC service. Offers smoother video quality and more robust A/V stability compared to native WebRTC.

## Configuration Snapshot

![LiveKit AVClient Settings v1.2.0](./LiveKitAVClient-v1.2.0.png)

## Configuration Notes

- ✅ **Connection Quality Indicator** – enabled to help monitor user latency and connectivity
- ☐ **Audio Music Mode** – disabled (not suitable for speech)
- ☐ **Disable Receiving Audio/Video** – all incoming A/V is enabled by default
- ☐ **Separate Window for A/V** – not in use; A/V integrated in main window
- ☐ **Reset Meeting Room ID / Debug Logging** – not needed unless troubleshooting

## Usage Notes

- Used in one current game
- Will be used in **Monoclass Madness sessions**
- Offers a cleaner, higher-performance alternative to native Foundry WebRTC
- Especially beneficial for hybrid or remote-first groups

## Maintenance & Relevance

- ✅ Actively maintained
- 🧠 Useful for games where Discord is not the preferred option
- 🎯 Ideal for hosted sessions where visual presence or voice integration matters

## Related Modules

- [[Dice So Nice]] – integrates well visually during shared screens
- [[FXMaster]] – no known conflict; good parallel support
- [[Chat Portrait]] – complements visual player representation

## Tasks

- [x] Capture current settings screenshot
- [ ] Test A/V overlay and browser compatibility across devices
- [ ] Consider enabling in all public-facing campaigns
