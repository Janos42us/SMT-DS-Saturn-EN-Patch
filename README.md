# Shin Megami Tensei: Devil Summoner — English Translation Patch

**Version 0.10.0** (2026-10-16) · Sega Saturn · Rev A & Rev B

A full English translation of the Sega Saturn game *Shin Megami Tensei: Devil Summoner* (Atlus, 1995, Japan only,
T-14403G). There are two patches, one for each version of the disc.

> **You need your own copy of the game.** This repository contains patches only, no game data.

## Which patch do I need?

**Rev B** is the 1996 reprint (disc header `V3.000`). Atlus fixed bugs in it, including agility not working past 25
and a quest softlock, so **use Rev B if you can**. **Rev A** is the 1995 original (`V1.000`).

| Disc | Patch | Original Track 1 SHA-1 |
|---|---|---|
| Rev B (recommended) | `DevilSummoner_EN_RevB_v0.10.0.ppf` | `f2bac79dd9b5885fe435d3d24293d4308dd26b4c` |
| Rev A | `DevilSummoner_EN_RevA_v0.10.0.ppf` | `046bab81be23acf48845ec566c8d42063b279698` |

Each patch checks the disc it is applied to, so a PPF tool will refuse the wrong one. (Files sit in different places
on the two discs, so a patch for one would break the other.) Saves work with both.

## How to apply

1. Back up your **Track 1** `.bin`.
2. Apply the matching PPF to it with any PPF 3.0 tool (PPF-O-Matic, ApplyPPF or similar).
3. Load the original `.cue` in your emulator, or burn the image for real hardware.

Track 2 is music and is left untouched; keep it next to the patched track. File sizes and disc layout are unchanged
and sector checksums are rebuilt, so the patched disc boots on a real Saturn.

Your version is shown at the **bottom right of the title screen** (`EN v0.10.0 Rev A` / `Rev B`).

## What is translated

- **Story:** all dialogue, townspeople, shops, boss talk and all 15 demon negotiation personalities.
- **Gouma-Den** (Victor's fusion lab): menus, fusion marks legend, fusion rules help, the 2-way / 3-way fusion tables
  and sort options. These screens use a smaller 12-pixel font, so the English there is drawn in a narrow 6-pixel
  letter; race names in the fusion tables are shortened to 4 letters.
- **Battle:** battle text, labels and the results window.
- **Menus and data:** help text, item / spell descriptions, demon / item / spell names, races, locations, menus (COMP,
  EQUIP, STATUS, CONFIG, control pad), save / load screens and messages.
- **DDS-NET sign-up:** names, address and code name use an English keyboard. First and last name each take up to
  8 letters. Type your **first** name in the left box and your **last** name in the right box.
- **Graphics:** signs, banners and posters in dungeons and town, backgrounds and two movie scenes.
- **Movies:** the news report in the opening movie is subtitled.
- **Credits:** staff names romanized in Western order, opening with a "Translated by Janos42us & Cai" page.

## Style notes

- Western name order (Kyouji Kuzunoha).
- Official Atlus English demon names where they exist, and the series' official item names (Life Stone, Bead...).
- The dungeon location box shows 8 letters, so some place names there are short forms (Chinatwn, Kitayama, Old Tomb,
  Darkwood...).
- Small-font boxes (battle panels, menu lists) show names cut to 8 letters, as the original layout allows only
  8 characters there. Dialogue that names a demon or item (negotiation) uses the full name, up to 16 letters.

## Known issues

- A complete start-to-finish playthrough on real hardware is still to be done; most testing is in emulators.
- Magnetite amounts in demon requests show as `M197` (the game's own notation).
- Fusion marks legend (Gouma-Den): the game draws it with wider character spacing, so its English has small gaps
  every two letters.
- Names inserted into dialogue can leave a double space or a space before punctuation, because two letters share one
  tile and odd-length names end with a blank half.
- Battle damage reads "Damase" at a glance: the battle box cuts off the tail of the *g* in the game's own English text.
- Some staff names in the credits use the most common reading of the kanji where no official romanization could be
  confirmed.
- Decorative kanji (title screen diamonds, spell effects, shrine charms and a few illegible background signs) are
  intentionally left as they are.

## Reporting bugs

Please open an issue with:

- a screenshot,
- where in the game it happened,
- your disc (**Rev A** or **Rev B**),
- the version from the title screen.

## Versions
Finally un-jacked naming scheme!

Versions are `0.MINOR.PATCH` until the first full release, `1.0.0`. MINOR goes up with every new test build, PATCH
for a quick fix to a build. Older names map straight across: RC8 = 0.8.0, 1.0.0-rc.9 = 0.9.0.


## Credits

- **Translation and hacking:** Janos42us
- **Credits-page artwork:** Kazuma Kaneko's illustration of Kyouji Kuzunoha (Atlus)

*Shin Megami Tensei* and *Devil Summoner* are trademarks of Atlus. This is an unofficial fan translation, not affiliated
with or endorsed by Atlus or Sega.
