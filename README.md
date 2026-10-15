# Shin Megami Tensei: Devil Summoner — English Patch (Sega Saturn)

**Version 1.0 RC5** · October 14, 2026 · by **Janos42us**

Devil Summoner never came out in English. Now it's playable in English on the Saturn: story, demon negotiations, battles, menus, and most of the in-game art.

It's a Release Candidate because we're still testing. Parts of it have been played on real hardware and it's been tested a lot in emulators.
TRANSLATED WITH AI

Work on human translation in progress.
---

## What you need

- Your own copy of the game: **Japan, Rev A, T-14403G**
- The patch: `DevilSummoner_EN_v1.0rc6.ppf`
- A PPF patcher (RomPatcher.js, PPF-O-Matic or ApplyPPF)
- An emulator or a real Saturn

Your **Track 1** `.bin` has to match this SHA-1 before you patch, or it won't work:

```
046bab81be23acf48845ec566c8d42063b279698
```

## How to patch

1. Make a backup of Track 1 first.
2. Open your PPF patcher, pick the `.ppf` file, and patch **Track 1 only**.
3. Don't touch Track 2 (that's the music) or the `.cue`.
4. Load the `.cue` like normal and play.

File sizes and disc layout stay the same, and sector checksums are rebuilt, so it should work on real hardware.

---

## What's translated

Basically everything:

- All story dialogue, townspeople, shops and bosses
- All 15 demon negotiation personalities
- Battle text, menus (COMP, EQUIP, STATUS, CONFIG), save/load
- Items, spells, demons, races, places, and their descriptions
- Gouma-Den fusion screens (Victor) -- in RC6
- Signs, posters and banners in dungeons and backgrounds, plus text in two movie scenes
- End credits (names romanized, Western order) and a "Translated by" page with Kaneko's Kyouji art

Names are in Western order (Kyouji Kuzunoha), and we use the official Atlus English demon names wherever they exist.

## Entering your name (DDS-NET sign-up)

- **Left box** is your last name, **right box** is your first name. 8 letters max each.
- Type with the capital letters. After the first letter it switches to lowercase on its own. We hacked in the English letters and haven't polished it yet.
- Address and code name are prefilled with the romaji defaults. If you want to change them, same rules.

---

## Known issues

- **Names get cut to 8 letters** in small menus and battle panels. In dialogue they show up to 16.
- **Magnetite requests show as `M197`.** That's how the original game does it.
- **Two labels on the battle results screen are still Japanese:** ませき (Mana Stone) and ほうぎょく (Orb). We haven't found where they're stored yet.
- **Fusion legend** has small gaps between letter pairs. Just cosmetic.
- **Clover's Gym heal shop** wasn't tested in an emulator. If it looks wrong on your end, let us know.
- Some decorations stay Japanese on purpose: title screen diamonds, spell effects, shrine charms, and a few signs you can't read anyway.
- Staff names we couldn't confirm use the most common reading.

## What's new since RC3

- Fixed a freeze on real hardware at the first Pisaca fight
- Fixed a freeze right after a demon joins you in negotiation
- Fusion menus and the gym heal shop are in English now --RC6
- Negotiation choices no longer spill into the next line
- Dungeon search/ambush messages, basement floors (B1F), and missing place names translated
- Demon name fixes (Pishacha → Pisaca, Kaiti → Kaichi, Shisa → Shiisaa, and more)

---

## Found a bug?

Open an issue on GitHub and tell us:

1. Where you were in the game
2. What happened
3. A screenshot
4. Emulator (and version) or real Saturn
5. How to make it happen again, if you know

Reports from anyone playing all the way through on a real Saturn are especially welcome.

---

## Credits and disclaimer

Translation and hacking: **Janos42us**
"Translated by" page art: Kyouji Kuzunoha by **Kazuma Kaneko / Atlus**

This is an unofficial fan translation. Shin Megami Tensei, Devil Summoner and everything in it belong to Atlus. Not affiliated with Atlus or Sega. No game files are included, use your own copy.
