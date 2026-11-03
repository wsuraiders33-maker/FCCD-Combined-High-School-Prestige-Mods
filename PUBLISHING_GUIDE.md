# Publish the Combined Mods releases

This repository is intentionally separate from the standalone High School Mods and Prestige-Based Dynasty repositories.

## First: publish the current combined version

1. Open the [new repository Releases page](https://github.com/wsuraiders33-maker/FCCD-Combined-High-School-Prestige-Mods/releases) and click **Draft a new release**.
2. New tag: `combined-hs-v1.1.5-prestige-v1.0.3`.
3. Title: `FCCD High School v1.1.5 + Prestige v1.0.3 — Combined Mods`.
4. Paste `RELEASE_NOTES_HS115_PRESTIGE103.md` into the description.
5. Upload the eight **public release** ZIPs (not the private test ZIPs), checking their filenames against `SHA256SUMS.txt`.
6. Confirm the assets are accessible after publishing.

## Second: archive the older combined version in this repository

1. In the old High School Mods repository, open the [combined-v1.0.3 release](https://github.com/wsuraiders33-maker/FCCD-High-School-Mods/releases/tag/combined-v1.0.3).
2. Download its eight original ZIP assets.
3. Create an independent release here with tag `combined-v1.0.3`, title `FCCD High School + Prestige v1.0.3 — Archived Combined Mods`, using `RELEASE_NOTES_ARCHIVED_COMBINED103.md`.
4. Upload those **exact** eight historical assets without renaming or replacing them.
5. Verify each download works from the new repository.

## Last: clean the standalone High School repository

**Only after verifying both releases and their assets in this new repository:** delete the old combined release from High School Mods and remove its combined-specific root README section and `COMBINED_PRESTIGE_V1.0.3_RELEASE_NOTES.md`. Leave standalone High School releases and standalone Prestige-Based Dynasty untouched.

GitHub release assets do not migrate across repositories automatically and release ZIP uploads must be completed in GitHub's web interface with the available connected tools. Verify game-binary redistribution rights before publicly uploading archives.
