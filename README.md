# ✨ xCT+ | Remastered for Wrath of the Lich King (3.3.5a)

![Version](https://img.shields.io/badge/version-3.8.0--remaster-blue)
![Game](https://img.shields.io/badge/game-3.3.5a-orange)
![Status](https://img.shields.io/badge/status-beta-yellow)

**xCT+** is a highly sophisticated combat text addon that completely replaces and vastly improves upon Blizzard's default floating combat text.  
This version is a **remaster of Barsoom's popular backport**, itself based on Dandruff's original xCT+ (MoP 5.4.8). The addon has been carefully overhauled, enhanced, and localized for the **Wrath of the Lich King (3.3.5a)** environment.

---

## ⚙️ Changes & Fixed Bugs (since the original backport)

All of the following **issues from the original repository** have been successfully resolved.

### 🐛 Resolved Issues

| # | Issue | Status |
|---|-------|--------|
| 1 | **[Missing icons for incoming damage / healing](https://github.com/Barsoomx/xCT_Plus_wotlk/issues/1)** | ✅ Fixed |
| 2 | **[Healing Stream Totem shows totem name instead of owner (healer)](https://github.com/Barsoomx/xCT_Plus_wotlk/issues/2)** | ✅ Fixed |
| 3 | **[Fire totems (Magma, Searing, Fire Elemental) show no outgoing damage](https://github.com/Barsoomx/xCT_Plus_wotlk/issues/3)** | ✅ Fixed |
| 4 | **[Incoming Icons for damage and healing (duplicate)](https://github.com/Barsoomx/xCT_Plus_wotlk/issues/4)** | ✅ Fixed |

### 🔧 Additional Bugfixes & Improvements

- **Duplicate display of incoming damage/healing** eliminated when the new icons are enabled.
- **Periodic healing (HoTs)** is now correctly routed to its own periodic healing frame (instead of the normal healing frame).
- **Miss types (Dodge, Parry, Immune, etc.) and Resist/Block/Absorb** no longer appear doubled and are handled correctly.
- **Guardian cache (totems, pets)** now stores owners for **all** player totems, not just your own – healer names are displayed correctly.
- **Outgoing damage from all owned totems/guardians** is now correctly detected and displayed.
- Various **UI and options corrections** (e.g. unique `order` values, correct locale linking).

### 🌍 Localization (NEW – in progress)

xCT+ has been extended with a new **(not finished - WiP!)** localization system. 
Currently supported languages:

- 🇬🇧 **English** (complete)
- 🇩🇪 **German**  (mostly finished 90%) few texts need to be translated.
- 🇷🇺 **Russian** (partially ??%) with AI needs to be checked!

The translations covers partially the **entire configuration menu**. Additional languages can be easily added via the `locales.lua` file – this file also serves as a **template for new translations**.

> 💬 **Interested in contributing another language?**  
> Simply copy the English or German block in `locales.lua` and replace the values. Pull requests are always welcome!

---

## 📦 Installation

1. Download the latest version as a ZIP file.
2. Extract the `xCT+` folder into your `WoW/Interface/AddOns/` directory.
3. Make sure the original xCT is either disabled or deleted.
4. Launch WoW and configure the addon using `/xct`.

---

## 🧪 Beta Status & Testing

This remaster is currently in a **beta phase**.  
While the issues listed above have been fixed and many hours of work went into stabilization, undiscovered problems may still exist.

> ⚠️ **Please test thoroughly and provide feedback!**  
> Bug reports, ideas, or suggestions are very welcome on the [Issues page](https://github.com/hypopheria2k/xCT_Plus_wotlk/issues).

---

## 👏 Credits & Acknowledgements

- **Dandruff** – Original author of xCT+ (Pandaria 5.4.8)
- **Barsoom** – Initial backport to WotLK 3.3.5a
- **Hypopheria** – Remaster, bugfixes & localization (2026)

Special thanks also go to everyone who helped preserve and improve the original addon.

---

## 🔗 Links

- 🐙 GitHub Repository: [https://github.com/hypopheria2k/xCT_Plus_wotlk](https://github.com/hypopheria2k/xCT_Plus_wotlk)
- 🐛 Report Bugs: [Issues](https://github.com/hypopheria2k/xCT_Plus_wotlk/issues)

---

*"May your numbers always be visible and your icons always match."* ✌️