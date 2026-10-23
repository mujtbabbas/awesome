# Changelog

All notable changes to this standalone edition of awesome are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `readme.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow; upstream's awesome-lint workflow kept as-is); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Set the repository About description and homepage (the main upstream repository).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [sindresorhus/awesome](https://github.com/sindresorhus/awesome) at upstream commit `bc98e517ddca672f55f9857d714fc3ea3c3540b2` (upstream HEAD dated 2026-09-02).
- Fork history severed; all files, media and the CC0 licence preserved as-is.
