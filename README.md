# Shin Megami Tensei: Devil Summoner
### English Translation Patch — Sega Saturn

**Version 1.0 RC3** | October 13, 2026

![Status](https://img.shields.io/badge/Status-Release%20Candidate-orange)
![Version](https://img.shields.io/badge/Version-1.0%20RC3-blue)
![Platform](https://img.shields.io/badge/Platform-Sega%20Saturn-5865F2)
![Language](https://img.shields.io/badge/Language-English-brightgreen)

---

## About the Project

A complete English translation of **Shin Megami Tensei: Devil Summoner** for the Sega Saturn.

Originally released exclusively in Japan, *Devil Summoner* is now playable in English, including its story, demon negotiations, battle systems, menus, and in-game artwork.

This project aims to preserve the original Sega Saturn experience while making the game accessible to English-speaking players.

**Supported version:** Japan, Revision A (`T-14403G`)

> **Release Candidate:** The translation has been tested extensively in emulation. A complete start-to-finish playthrough on original Sega Saturn hardware has not yet been performed.

---

## Installation

### Requirements

You will need:

- An original **Shin Megami Tensei: Devil Summoner** Sega Saturn disc image (Japan, Rev A).
- The translation patch: `DevilSummoner_EN_v1.0rc3.ppf`
- A PPF 3.0-compatible patching utility, such as RomPatcher.js, PPF-O-Matic or ApplyPPF.
- A Sega Saturn emulator or compatible original hardware.

### Verify Your Disc Image

The patch requires the correct revision of the game.

| Property | Required Value |
|---|---|
| Game | Shin Megami Tensei: Devil Summoner |
| Region | Japan |
| Revision | Rev A |
| Serial | T-14403G |
| Target | Track 1 (Data) |
| Sector Format | MODE1/2352 |
| Sector Size | 2352 bytes |
| Hash Algorithm | SHA-1 |

**Required Track 1 SHA-1:**

```text
046bab81be23acf48845ec566c8d42063b279698
```

Make sure your Track 1 `.bin` matches this hash **before patching**.

### Apply the Patch

1. **Back up your original disc image.** Keep an untouched copy of Track 1.
2. **Open your PPF patching utility.** Select `DevilSummoner_EN_v1.0rc3.ppf` as the patch file.
3. **Select Track 1 as the target.** Apply the patch directly to the Track 1 `.bin` file.
4. **Leave Track 2 untouched.** Track 2 contains music and does not require modification.
5. **Launch the game.** Load the original `.cue` file in your emulator, or use the patched disc image with compatible original hardware.

> **Important:** Do not patch the `.cue` file or Track 2. Only the Track 1 data file should be modified.

The patch preserves the original file sizes and disc layout. Sector checksums are rebuilt to maintain compatibility with original Sega Saturn hardware.

---

## Translation Coverage

The goal of this release is to provide a complete English-language experience without compromising the game's original presentation.

| Category | Translation Status |
|---|---|
| Main Story & Dialogue | Complete |
| NPCs & Townspeople | Complete |
| Shops & Services | Complete |
| Boss Dialogue | Complete |
| Demon Negotiations | Complete — All 15 Personalities |
| Battle Text & Interface | Complete |
| Items, Spells & Descriptions | Complete |
| Demon Names & Races | Complete |
| Locations & Area Names | Complete |
| COMP, Equipment & Status Menus | Complete |
| Configuration & Controller Menus | Complete |
| Save / Load Screens | Complete |
| DDS-NET Registration | Complete |
| Environmental Signs & Posters | Translated |
| In-Game Movie Text | Translated |
| Opening & End Credits | Translated |

### Dialogue & Demon Negotiations

All story dialogue, NPC conversations, shop interactions, and boss encounters have been translated.

This includes all **15 demon negotiation personalities**, allowing players to experience the game's negotiation mechanics entirely in English.

### Menus & Battle Interface

The translation covers the game's core interface, including:

- COMP, EQUIP, STATUS, and CONFIG menus.
- Battle commands, labels, messages, and help text.
- Item, spell, and demon descriptions.
- Save/load screens and system messages.
- Controller configuration.

### DDS-NET Registration

The DDS-NET registration interface now supports an English-language keyboard for entering your character information.

**Name entry instructions:**

- **Left field:** Last name (maximum 8 letters).
- **Right field:** First name (maximum 8 letters).

Note: When entering your name use the capital letters for input, as you type it will auto lowercase from the second letter onward. We hacked in additional characters for English and haven't polished that yet.

Address and code-name entry also use an English keyboard, we prefilled it with the Romaji default. If you want to change it, same rules as with your name.

### Environmental Artwork & Movies

Translated visual elements include signs, banners, and posters appearing throughout dungeons and backgrounds, along with text in two in-game movie scenes.

### End Credits

The ending credits have been translated, with staff names romanized and presented in Western name order AND includes a custom **"Translated by Janos42us & Cai"** credit page.

---

## Translation & Localization Notes

Several localization decisions were made to preserve consistency with the broader *Shin Megami Tensei* series.

**Character Names**

Japanese names are presented in Western order.

Example: `Kyouji Kuzunoha`

**Demon Names**

Official Atlus English demon names are used wherever established translations exist.

**Character Limits**

Certain interface elements retain the original game's strict character limitations.

| Context | Character Limit |
|---|---|
| Small-font battle panels | 8 characters |
| Compact menu lists | 8 characters |
| Demon/item names in negotiation dialogue | Up to 16 characters |
| DDS-NET first/last name | 8 characters each |

Names may appear shortened in compact menus and battle panels while retaining their full forms in dialogue whenever space allows.

---

## Known Limitations

Although the translation is substantially complete, the following issues and limitations remain.

### Hardware Verification

The patch has been tested ONLY in emulation.

A complete start-to-finish playthrough on original Sega Saturn hardware is still pending. This is the primary reason for the **Release Candidate** designation.

### Magnetite Display

Demon requests display Magnetite amounts using the original game's notation.

Example: `M197`

This is intentional and reflects the original interface.

### Battle Results Screen

Two stone-counter labels in the battle results window remain in Japanese.

| Japanese | Meaning |
|---|---|
| ませき | Mana Stone |
| ほうぎょく | Orb |

### Staff Credits

Where an official romanization could not be confirmed, staff names use the most commonly accepted reading of their kanji.

### Untranslated Decorative Elements

A small number of decorative Japanese elements intentionally remain unchanged, including:

- Title-screen diamond decorations.
- Spell effects.
- Shrine charms.
- Certain illegible background signs.

These elements have been preserved as part of the game's original visual identity.

---

## Bug Reports & Feedback

Found a typo, broken text box, untranslated dialogue, or unexpected behavior?

Please report it using the repository's **GitHub Issues** section.

To help investigate the problem, include:

1. **Location:** Where in the game the issue occurred.
2. **Description:** What happened and what you expected to happen.
3. **Screenshot:** A screenshot clearly showing the problem.
4. **Environment:** Emulator and version, or original Sega Saturn hardware.
5. **Reproduction Steps:** How to trigger the issue, if known.

Feedback is especially welcome from anyone completing a full playthrough on original hardware.

---

## Credits

### Translation & ROM Hacking

**Janos42us & Cai**

### Artwork

The custom translation-credits page features Kazuma Kaneko's illustration of Kyouji Kuzunoha.

Original artwork by **Kazuma Kaneko / Atlus**.

---

## Disclaimer

This is an unofficial fan translation project.

*Shin Megami Tensei*, *Devil Summoner*, and associated characters, artwork, and intellectual property belong to Atlus and their respective rights holders.

This patch is intended for use with a legitimately obtained copy of the supported game. No original game disc image is included.

This project is not affiliated with, endorsed by, or sponsored by Atlus or Sega.

---

**Shin Megami Tensei: Devil Summoner — English Translation Patch**

*Version 1.0 RC3 · October 13, 2026*

**Translated by Janos42us & Cai**
