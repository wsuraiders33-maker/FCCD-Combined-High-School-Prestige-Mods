# FCCD Combined High School + Prestige Mods

Combined engine mods for **Football Coach: College Dynasty**, bringing together **High School Mods v1.1.5** and **Prestige-Based Dynasty v1.0.4**.

**Current release:** [High School v1.1.5 + Prestige v1.0.4](https://github.com/wsuraiders33-maker/FCCD-Combined-High-School-Prestige-Mods/releases/tag/combined-hs-v1.1.5-prestige-v1.0.4) — eight downloadable ZIPs.

**Fixed in Prestige v1.0.4:** AI-controlled teams can no longer issue scholarship offers during preseason, matching the restriction on human-controlled teams. Regular-season scholarship offers and recruiting commitments still operate normally. The earlier v1.0.3 combined packages contained the preseason-offer bug. Updating the game engine does **not** retroactively remove scholarship offers already recorded in saves.

This is a **separate project** from the standalone High School Mods and Prestige-Based Dynasty releases. Each combined package contains both systems. **Do not install standalone mods on top of a combined package.**

## Downloads

**[Download the current combined release — HS v1.1.5 + Prestige v1.0.4](https://github.com/wsuraiders33-maker/FCCD-Combined-High-School-Prestige-Mods/releases/tag/combined-hs-v1.1.5-prestige-v1.0.4)**

Choose one package:
- **Ohio Divisions I–VII:** One separately installable package for each division, matched to the corresponding Ohio Steam Workshop universe.
- **Generic High School:** One installer offering **Large, Medium or Small** school profiles.

Only one variant should be installed at a time.

## Release documentation

- [Current v1.1.5 + Prestige v1.0.4 release notes](RELEASE_NOTES_HS115_PRESTIGE104.md)
- [Current release SHA-256 checksums](SHA256SUMS_HS115_PRESTIGE104.txt)
- [Prior v1.1.5 + Prestige v1.0.3 release notes](RELEASE_NOTES_HS115_PRESTIGE103.md)
- [Historical combined v1.0.3 release notes](RELEASE_NOTES_ARCHIVED_COMBINED103.md)
- [Publishing and safe migration guide](PUBLISHING_GUIDE.md)

## Features

- High-school rules: **12-minute quarters**, kickoffs from the **40-yard line** and appropriate touchbacks
- High School v1.1.5 **missed-field-goal returns** with distance based on Kick Power, field visualization and clock accounting
- Four-year freshman–senior player progression with **no redshirts**
- Prestige-based roster caps of **34–85** players
- Prestige-scaled scholarship offers, recruiting limits and adaptive recruiting pools
- Improved AI recruiting, positional-depth safeguards and automatic walk-ons
- Division-specific or Generic-profile stadium and attendance calibration
- **Preseason scholarship-offer restriction**, fixed in Prestige v1.0.4

## Installation

1. Back up important dynasty saves and close the game completely.
2. Restore a **verified clean Windows Steam FCCD 1.6.5** installation before changing mods.
3. Download and **extract one** combined ZIP from its release.
4. Run its top-level `INSTALL.bat`, then `VERIFY.bat`.
5. Launch through Steam. To uninstall or switch versions, close the game and run the matching `RESTORE.bat` before installing another package.

**Compatibility:** Windows Steam FCCD 1.6.5 with the installers' verified original-file hashes. macOS is not verified. Do not stack combined or standalone patch installations.

## Other FCCD mods (separate repositories)

- [Standalone High School Mods](https://github.com/wsuraiders33-maker/FCCD-High-School-Mods)
- [Standalone Prestige-Based Dynasty](https://github.com/wsuraiders33-maker/FCCD-Prestige-Based-Dynasty)

## Release status and rights

**Gameplay tested:** Ohio Division III, Ohio Division V and one Generic High School configuration. Each had zero preseason scholarship offers through Summer 2 and normal recruiting offers and commitments by Week 5. The five other Ohio division packages passed archive and technical checks but were not individually gameplay-tested. All three Generic size profiles have not been individually gameplay-tested.

Before redistributing ZIPs containing modified commercial-game binaries, verify that redistribution is permitted by the rights holder.

Community project. Not affiliated with the developer of *Football Coach: College Dynasty*, Steam, Valve, the OHSAA or any represented school.
