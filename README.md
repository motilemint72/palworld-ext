<p align="center">
  <img width="686" height="386" alt="Palworld Mod Menu Banner" src="" />
</p>

<h1 align="center">🦄 Palworld External Mod Menu</h1>
<p align="center"><b>External cheat & customization menu for Palworld — resources, taming, exploration, and more.</b></p>

<p align="center">
  <img alt="platform" src="https://img.shields.io/badge/platform-Windows-blue">
  <img alt="build" src="https://img.shields.io/badge/build-x64-lightgrey">
  <img alt="status" src="https://img.shields.io/badge/status-active-brightgreen">
  <img alt="license" src="https://img.shields.io/badge/license-MIT-green">
</p>

---

## ⬇️ Download

> Replace this section with your own verified, first-party hosting (your own GitHub Releases page, your own domain, etc.). Avoid third-party "download portal" domains and password-protected archives — both are hallmarks of malware distribution and will get your project flagged, mistrusted, or reported.

**[your-project-releases-link-here]**
File: `PalworldModMenu_Setup.exe` (signed / checksum published)

---

## ⚠️ Disclaimer

- Intended for **personal, offline/single-player use** only.
- Using this in online co-op or multiplayer may violate Palworld's Terms of Service and can result in bans.
- This tool operates **externally** — it reads/writes to the running game process; it does not modify or redistribute any Palworld game files.
- The developer is not responsible for account bans, save corruption, or system instability. Use at your own risk.
- Not affiliated with Pocketpair, Inc. Palworld is a trademark of Pocketpair.

---

## 🧩 About

**Palworld External Mod Menu** is a lightweight Windows application that attaches to a running Palworld process and gives you an in-game overlay for adjusting resources, taming, movement, and world settings — without editing your save files directly.

Because it's external (not injected into the game's own code), it's easy to fully unload at any time, leaving the game exactly as it was.

---

## ✨ Features

| Feature | Description |
|---|---|
| 💰 Infinite Resources | Unlimited materials, coins, and crafting ingredients |
| ⚡ Auto-Farm Mode | Automates gathering and collection |
| 🏹 Instant Taming | Tame any Pal in one action |
| 🏃 Speed Boost | Adjustable movement speed |
| 🛡️ God Mode | Toggleable invulnerability |
| 🧭 Teleport | Jump to any point on the map |
| 💤 No Fatigue | Disable sleep/stamina drain |
| 🏗️ Structure Spawner | Instantly place structures from the build menu |
| 🎒 Inventory Editor | Add, remove, or duplicate items |
| 📈 XP Multiplier | Adjustable leveling rate for player and Pals |
| 🖼️ World Customizer | Change weather and time of day |
| 💾 Profile Backup | Back up and restore your settings/loadouts |

---

## 🖥️ OS Compatibility

| OS | Support | Notes |
|---|:---:|---|
| 🪟 Windows 11 | ✅ | Full support |
| 🪟 Windows 10 | ✅ | Full support |
| 🐧 Linux (Proton) | ⚠️ | Partial — overlay rendering may need extra config |
| 🍏 macOS | ⚠️ | Experimental, Apple Silicon only |
| 🎮 Steam Deck | ⚠️ | Desktop Mode only |

---

## 💻 System Requirements

| Component | Minimum |
|---|---|
| OS | Windows 10 (64-bit) |
| RAM | 4 GB |
| Runtime | .NET 6.0+ |
| Privileges | Administrator |

---

## 🏆 Why Choose This One

- **Fully external** — no DLL injection into the game binary, so it's easy to disable cleanly and doesn't touch your game files.
- **Transparent source** — no obfuscated installers, no lookalike download domains, no password-locked archives. What you download is what you get.
- **Single-player focused defaults** — safe-mode is on by default and clearly flags any feature that could affect an online session.
- **Actively maintained** — offset/version tracking against Palworld patches so the menu doesn't silently break.
- **No telemetry** — runs fully local; nothing is sent off your machine.

---

## 🔧 Installation

1. Download the installer from the link above.
2. Verify the checksum (published alongside the release) before running anything.
3. Run the installer and launch Palworld.
4. Start the mod menu **as Administrator** and attach to the running game process.
5. Open the overlay with the menu hotkey and adjust settings.

---

## ⚙️ Configuration

Stored in `config.json` at `%APPDATA%\PalworldModMenu\config.json`

| Parameter | Type | Default | Description |
|---|---|---|---|
| `menu_hotkey` | String | `"Insert"` | Toggles the overlay |
| `auto_attach` | Boolean | `true` | Attach on game launch |
| `process_name` | String | `"Palworld-Win64-Shipping.exe"` | Target process |
| `safe_mode` | Boolean | `true` | Restricts features flagged as online-unsafe |

---

## ⌨️ Hotkeys

| Key | Action |
|---|---|
| `Insert` | Toggle menu |
| `F1` | Apply selected feature |
| `F2` | Save loadout |
| `F3` | Load loadout |
| `F4` | Restore defaults |
| `End` | Unload tool |

---

## ❓ FAQ

**Will this get me banned?**
Palworld's anti-cheat is less aggressive than titles like Valorant, but using this in online/co-op sessions can still violate ToS and risk a ban. Single-player is the safe use case.

**Does it modify my save file?**
No — it changes runtime game state while running. Your save files aren't edited directly.

**Does it need updates after game patches?**
Yes — process offsets can shift between Palworld versions. Check release notes before use.

---

## 🤝 Contributing

Issues and PRs welcome. Please include your Palworld version when reporting a bug.

## 📄 License

MIT License.
