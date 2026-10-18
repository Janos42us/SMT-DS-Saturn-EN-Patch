<div align="center">

# Shin Megami Tensei: Devil Summoner
### English Translation Patch · Sega Saturn

![Version](https://img.shields.io/badge/version-0.10.0-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Sega_Saturn-black?style=for-the-badge)
![Disc Support](https://img.shields.io/badge/discs-Rev_A_%26_Rev_B-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/status-Community_Testing-orange?style=for-the-badge)

**Originally released by Atlus in Japan, 1995 · T-14403G**  
**Patch updated October 16, 2026**

[📥 Releases](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/releases) ·
[🐛 Report a Bug](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/issues/new/choose) ·
[💬 Suggest a Translation](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/issues/new/choose)

</div>

---

> [!IMPORTANT]
> ### 💬 Translation suggestions are now welcome!
> Found awkward dialogue, a questionable translation, or wording that could be better? **[Open a translation suggestion issue](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/issues/new/choose).**
>
> Include the current text, your proposed change, and where it appears. Screenshots and the original Japanese are especially helpful. Please check [existing issues](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/issues) before submitting.

A full English translation of **Shin Megami Tensei: Devil Summoner**, originally released exclusively in Japan for the Sega Saturn. Separate patches support **Rev A** and **Rev B**.

> [!NOTE]
> **You need your own copy of the game.** This repository contains patches only. No game data is included.

## 📖 Contents

- [Choose Your Patch](#-choose-your-patch)
- [Installation](#-installation)
- [Translation Coverage](#-translation-coverage)
- [Translation and Formatting Notes](#-translation-and-formatting-notes)
- [Known Issues](#-known-issues)
- [Bugs and Translation Suggestions](#-bugs-and-translation-suggestions)
- [Version Numbering](#-version-numbering)
- [Credits](#-credits)

## 💿 Choose Your Patch

**Rev B is recommended.** The 1996 reprint includes Atlus's fixes for original-release bugs, including agility not working past 25 and a quest softlock.

| Disc | Release | Disc Header | Patch |
|:---|:---:|:---:|:---|
| **⭐ Rev B — Recommended** | 1996 | `V3.000` | `DevilSummoner_EN_RevB_v0.10.0.ppf` |
| **Rev A** | 1995 | `V1.000` | `DevilSummoner_EN_RevA_v0.10.0.ppf` |

<details>
<summary><strong>🔎 Original Track 1 SHA-1 hashes</strong></summary>

Use these hashes to identify your **unpatched** Track 1 `.bin`.

| Disc | SHA-1 |
|:---|:---|
| **Rev B** | `f2bac79dd9b5885fe435d3d24293d4308dd26b4c` |
| **Rev A** | `046bab81be23acf48845ec566c8d42063b279698` |

</details>

> [!WARNING]
> **Match the patch to your disc revision.** Files occupy different locations on the two discs, so the patches are not interchangeable. Compatible PPF tools can detect a mismatch using the patch's verification data, but you should still verify your SHA-1 before patching.

**Save files work with both revisions.**

## 🛠️ Installation

1. **Back up** your original Track 1 `.bin`.
2. **Verify its SHA-1** against the hashes above.
3. **Apply the matching PPF** using a PPF 3.0-compatible tool, such as PPF-O-Matic or ApplyPPF.
4. **Load the original `.cue`** in your emulator, or burn the patched image for real hardware.

Track 2 contains music and is left untouched. Keep it alongside the patched Track 1 and continue using the original `.cue`.

File sizes and disc layout remain unchanged. Sector checksums are rebuilt for real-hardware compatibility.

> [!TIP]
> Your patch version appears at the **bottom right of the title screen**:
> `EN v0.10.0 Rev A` / `EN v0.10.0 Rev B`

## ✨ Translation Coverage

| Area | What's Translated |
|:---|:---|
| **📜 Story** | All dialogue, townspeople, shops, boss conversations, and all **15 demon negotiation personalities** |
| **⚗️ Gouma-Den** | Menus, fusion marks legend, fusion rules help, two-way and three-way fusion tables, and sorting options |
| **⚔️ Battle** | Battle text, labels, and results window |
| **💻 Menus and Data** | Help text; demon, item, spell, race, and location names; item and spell descriptions; COMP, EQUIP, STATUS, CONFIG, control pad, and save/load screens |
| **⌨️ DDS-NET Registration** | English keyboards for names, address, and code name |
| **🎨 Graphics** | Town and dungeon signs, banners, posters, backgrounds, and two movie scenes |
| **🎬 Movies** | Subtitles for the news report in the opening movie |
| **🏁 Credits** | Romanized staff names in Western order and an opening “Translated by Janos42us” page |

<details>
<summary><strong>⚗️ A note on Gouma-Den text</strong></summary>

These screens use the game's smaller 12-pixel font, with English letters drawn 6 pixels wide. Race names in fusion tables are abbreviated to **four letters** to fit the original layout.

</details>

<details>
<summary><strong>⌨️ Entering your name in DDS-NET</strong></summary>

First and last names support up to **eight letters each**.

- **Left box:** First name.
- **Right box:** Last name.

</details>

## 📝 Translation and Formatting Notes

- **Western name order:** Kyouji Kuzunoha.
- **Series terminology:** Official Atlus English demon names are used where available, alongside established item names such as *Life Stone* and *Bead*.
- **Location names:** The dungeon location box holds eight letters, so some names are shortened: `Chinatwn`, `Kitayama`, `Old Tomb`, and `Darkwood`, for example.
- **Small-font panels:** Battle panels and menu lists retain the original eight-character name limit.
- **Names in dialogue:** Inserted demon and item names use their full forms, up to 16 letters.

## 🚧 Known Issues

> [!NOTE]
> A complete start-to-finish playthrough on a real Saturn is still pending. Most testing has been performed in emulators.

| Issue | Details |
|:---|:---|
| **Magnetite requests** | Amounts appear as `M197`, using the game's original notation. |
| **Fusion marks legend** | Wider character spacing creates small gaps every two letters. |
| **Inserted names** | Odd-length names may leave a double space or a space before punctuation because each tile holds two letters. |
| **Battle damage label** | The original battle box clips the tail of the *g* in “Damage,” making it resemble “Damase.” |
| **Staff credits** | Where an official romanization could not be confirmed, the most common reading of the kanji is used. |
| **Decorative Japanese** | Title screen diamonds, spell effects, shrine charms, and a few illegible background signs are intentionally unchanged. |

## 🤝 Bugs and Translation Suggestions

Found something? **[Open an issue](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/issues/new/choose).**

Please check [existing issues](https://github.com/Janos42us/SMT-DS-Saturn-EN-Patch/issues) first so reports and discussion stay together.

### 🐛 Reporting a Bug

Include as much of the following as possible:

- **Screenshot** of the problem.
- **Location** and what you were doing when it happened.
- **Disc revision:** Rev A or Rev B.
- **Patch version:** As shown on the title screen.
- **Save backup (`.bup`):** If available, to help reproduce the issue.

### 💬 Suggesting a Translation Change

Suggestions are welcome for dialogue, grammar, terminology, tone, and possible mistranslations.

| Include | What Helps |
|:---|:---|
| **Current text** | The wording exactly as it appears in the patch |
| **Suggested text** | Your proposed replacement |
| **Reason** | Why you think the change improves the translation |
| **Context** | Who is speaking, where it happens, and what's going on |
| **Reference** | A screenshot and the original Japanese, if available |
| **Version** | Your disc revision and patch version |

One issue per distinct suggestion makes discussion and tracking easier. Related lines from the same scene can go together.

## 🔢 Version Numbering

**Finally, an un-jacked naming scheme.**

Versions follow `0.MINOR.PATCH` until the first full release, **`1.0.0`**.

| Component | When It Changes |
|:---|:---|
| **MINOR** | A new test build |
| **PATCH** | A quick fix to an existing build |

<details>
<summary><strong>Previous release candidate names</strong></summary>

Older names map directly to the new numbering:

| Previous Name | Current Equivalent |
|:---|:---|
| RC1–RC8 | `0.1.0`–`0.8.0` |
| `1.0.0-rc.9` | `0.9.0` |

</details>

## 🙏 Credits

| Contribution | Credit |
|:---|:---|
| **Translation and hacking** | [Janos42us](https://github.com/Janos42us) |
| **Credits-page artwork** | Kazuma Kaneko's illustration of Kyouji Kuzunoha — Atlus |

---

<div align="center">

*Shin Megami Tensei* and *Devil Summoner* are trademarks of Atlus.  
This is an unofficial fan translation, not affiliated with or endorsed by Atlus or Sega.

</div>
