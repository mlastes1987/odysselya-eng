# Shinseiki Odysselya — English Fan Translation

![Coming Soon — English translation preview](assets/coming-soon.png)

An English fan translation of **Shinseiki Odysselya**, the 1993 Super Famicom RPG from VIC TOKAI.

## The story

A mysterious traveler awakens in an unfamiliar world with no memory of her past. Her search for answers becomes a journey across ages, where ancient civilizations, strange creatures, and the legends of the gods are closer than they seem.

## Project status

**English v0.9 beta is in playtesting.** The current test checkpoint is
**R16 (November 20, 2026)**. It includes the English opening, all 5,301
extracted dialogue entries, and translations for many battle, inventory,
equipment, shop, and save/load screens.

Recent playtest fixes keep long item and weapon names inside their menus,
add English location signs such as the Kali Temple entrance, and improve
Rasetsu's party header and the Battle Mode layout. The opening and those
affected screens have been checked in the emulator. Later chapters still
need broader playtesting, and some title, chapter, and credits graphics
remain to be translated. A public release date has yet to be announced.

This repository carries project updates and will host public patch releases.
The project-specific development tools are private.

## Community

Follow development and ask about playtesting on Discord. If you spot
untranslated, clipped, or overlapping text, include the build version,
location or menu, and a screenshot if you have one. [Join our Discord](https://discord.gg/DwR2jxj5b)

## Public tools & acknowledgments

This project uses [translate-retro-game](https://github.com/minhnhattonthat/translate-retro-game) by [minhnhattonthat](https://github.com/minhnhattonthat), a public toolkit and workflow for retro-game translation.

It includes ROM and text utilities, emulator-based testing, screenshot tools, and patch creation. Visit the repository to get the tools and read the setup instructions and license.

## Required base ROM

The English patch requires an **unmodified, unheadered Japanese ROM** matching these details:

| Detail | Required value |
| --- | --- |
| Game | Shinseiki Odysselya (Japan) |
| Platform | Super Famicom / SNES |
| File size | 1,572,864 bytes (1.5 MiB) |
| Copier header | None |

**SHA-1:**

```text
581de180568d85e4fd6f06c800caeff0e74d43fe
```

When the patch is released, apply the **BPS patch** to a base ROM matching the hash above. ROM files are not included.

Original game © 1993 VIC TOKAI. English translation is an unofficial fan project.
