# ✨ xCT+ | Remastered for Wrath of the Lich King (3.3.5a)

![Version](https://img.shields.io/badge/version-3.8.0--remaster-blue)
![Game](https://img.shields.io/badge/game-3.3.5a-orange)
![Status](https://img.shields.io/badge/status-beta-yellow)

**xCT+** is a fully customizable combat text addon that replaces Blizzard's default floating combat text with a much more powerful system of scrolling frames, spell merging, and advanced filtering.

This **remaster** builds upon Barsoom's popular backport (based on Dandruff's original xCT+ for MoP 5.4.8) and has been carefully overhauled, enhanced, and localized for **Wrath of the Lich King (3.3.5a)**.

---

## 🚀 Core Features

- **9 independent, movable & resizable frames** – General, Outgoing, Criticals, Incoming Damage, Incoming Healing, Class Power, Combo Points, Special Effects (Procs), Loot/Money
- **Smart spell merging** – Combines spammy abilities into clean, aggregated messages
- **Extensive filtering** – Buffs, debuffs, outgoing spells, procs, and items can be whitelisted or hidden
- **Customizable appearance** – Font, size, justification, outline, icons, colors, and fading per frame
- **Number formatting** – Abbreviations (k, m) or thousands separators
- **Incoming healing with names** – Optionally class-colored, with realm name support
- **Spell icons on outgoing damage/healing**
- **Overkill and Overheal tracking** (toggleable)
- **Localization-ready** – Currently English, German, and Russian (more translations welcome)

---

## 🩸 New: Overkill Indicator

When a killing blow deals more damage than the target has remaining health, the excess damage is now shown directly in the combat text.

**Example:**  
`12.340 (overkill: 8.740)`

- Works for all outgoing damage types (melee swings, ranged attacks, spells, and periodic damage)
- Uses the active number formatting
- Displayed on the *Outgoing* and *Critical* frames (if not merged)

**Toggle it on/off:**  
`Frames` → `Outgoing` → `Special Tweaks` → **Show Overkill**  
(Enabled by default)

---

## 🔧 Changes & Fixed Issues

All previously reported issues from the original backport have been resolved, along with several additional improvements.

### ✅ Resolved GitHub Issues

| # | Issue | Status |
|---|-------|--------|
| 1 | Missing icons for incoming damage / healing | ✅ Fixed |
| 2 | Healing Stream Totem shows totem name instead of healer | ✅ Fixed |
| 3 | Fire totems (Magma, Searing, Fire Elemental) show no outgoing damage | ✅ Fixed |
| 4 | Incoming Icons for damage and healing (duplicate) | ✅ Fixed |

### 🔨 Additional Bugfixes & Enhancements

- **Duplicate combat text eliminated** when incoming icons are enabled
- **Periodic healing (HoTs)** correctly routed to its own periodic healing frame
- **Miss types, resist, block, absorb** no longer appear doubled
- **Guardian owner cache** now includes all player totems, fixing healer name display
- **Outgoing damage from all owned guardians/totems** correctly detected
- **Options UI** cleaned up (unique order values, locale linking)
- **LF/CRLF line endings** normalized for seamless cross-platform use

---

## 🌍 Localization (Work in Progress)

The entire configuration menu can be translated via `locales.lua`. Currently included:

| Language | Status |
|----------|--------|
| 🇬🇧 English | ✅ Complete |
| 🇩🇪 German | 🟡 ~90% (few texts remaining) |
| 🇷🇺 Russian | 🟠 ~70% (AI-generated, needs verification) |

> 💬 **Want to add or improve a language?**  
> Copy the English or German block in `locales.lua`, translate the values, and submit a pull request – you'll be credited!

---

## 📦 Installation

1. [Download](https://github.com/hypopheria2k/xCT_Plus_wotlk) the latest version
2. Extract the `xCT+` folder into `WoW/Interface/AddOns/`
3. Make sure the original `xCT` addon is disabled or removed
4. Launch WoW and type `/xct` to open the configuration

---

## 🧪 Beta Status & Roadmap

This remaster is currently in **beta**. While the known issues have been fixed and the addon is stable in most situations, some edge cases may still exist. Your feedback is invaluable!

**Planned / considered for future updates:**
- More options for incoming icons (size, position)
- Proper Russian translation verification
- Overheal display (similar to Overkill)
- Visual test mode improvements

Please report any problems or ideas on the [Issues page](https://github.com/hypopheria2k/xCT_Plus_wotlk/issues).

---

## 👏 Credits

- **Dandruff** – Original author of xCT+ (Pandaria 5.4.8)
- **Barsoom** – Initial backport to WotLK 3.3.5a
- **Hypopheria** – Remaster, bugfixes, localization & new features (2026)

Special thanks to everyone who tests, translates, or contributes.

---

## 🔗 Links

- 🐙 [GitHub Repository](https://github.com/hypopheria2k/xCT_Plus_wotlk)
- 🐛 [Report a Bug](https://github.com/hypopheria2k/xCT_Plus_wotlk/issues)

---

*"May your numbers always be visible and your icons always match."* ✌️