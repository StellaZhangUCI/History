# Changelog

[← Back to main archive](README.md)

This file captures substantive changes to the archive. For per-commit detail, run `git log`.

## 2026-05-10

### Added

- **[`SPONSORS-AND-JUDGES.md`](SPONSORS-AND-JUDGES.md)**: institutional context document covering the Stella Zhang naming gift (with newly-documented **$750,000 March 2025 extension** that raised the announced pool from $100K to $150K+), recurring competition-level sponsors, judging panels for 2023 and 2024 (where named publicly), the Blum Center partnership with the Social Enterprise track, program staff (Jenn Huynh, Sara Heimann), and the seven-month workshop format.
- **[`TEAMS.md`](TEAMS.md)**: alphabetical master directory of all 112 teams across 2009 to 2026. One-line entry per team with year link, award abbreviations, members, and outcome status.
- **[`data/teams.json`](data/teams.json)**: slim machine-readable mirror of `TEAMS.md` (schema v1). Avoids duplication by referencing `data/nvc.json` for full member/project data and `OUTCOMES.md` anchors for outcome detail.
- **[`CHANGELOG.md`](CHANGELOG.md)** (this file): chronological iteration log.

### Changed (data canonicalization)

- **`data/nvc.json` `competition` object** substantially enriched with the institutional findings from `SPONSORS-AND-JUDGES.md`:
  - `naming_gift`: expanded from 3 fields (donor, affiliation, year) to a structured 12-field object covering primary donor, co-donor (John Shen), initial gift (2022, 5-year term, amount undisclosed), $750,000 March 2025 extension (5-year term to 2031, raised pool $100K -> $150K), the Zarina Bahadur / Long Beach Accelerator bridge, and source URLs.
  - New `sponsors` array: 12 named competition-level sponsors.
  - New `sponsors_note`: clarifies per-track corporate sponsorship does not exist.
  - New `track_partnerships` array: UCI Blum Center partnership with the Social Enterprise track (faculty judge Richard Matthew).
  - New `program_staff` array: Jenn Huynh (Program Manager), Sara Heimann (contact for archival data).
  - New `mentor_structure` object: documents that no standalone named program exists; mentors come from Beall Center and SCORE.
  - New `format` object: seven-month workshop series with sample workshop titles.
- **Per-year judges captured in `data/nvc.json`** where publicly named:
  - `years[2024]`: `judges_and_coaches` array (Stella Zhang, Elvin Kay, Ken & Carla Neeld, Jeff Freud, Shalabh Gupta, Fiza & Mansoor Shah, Dan Jenkins) with source.
  - `years[2023]`: `judges` array (Ken Neeld, Karin Koch, Isabelle Bart, Michelle Khine, Rodrigo C. Mahs) with Business Wire source.
  - `years[2025]`: `confirmed_judges_partial` and `judges_note` documenting the partial panel and the password-protected report gap.
- Each entry includes a source URL for traceability.

### Discovered

- Two previously-undocumented repeat finalists, surfaced by cross-checking the confirmed 2016 finalist roster against 2017+ team rosters:
  - **Simon Loo**: 2016 FunBand to 2017 Element: B2B2C (Business Products 1st)
  - **Pravin Surana**: 2016 Negocios & Etc. to 2017 APIC Diagnostics (Tech Surge 2nd)
- Both added to the Cross-Year Analytics repeat-finalists table and to `data/nvc.json`'s `cross_year_notes.repeat_finalists`.
- **Stella Zhang's second naming gift ($750,000, March 2025)** documented. Previously the archive noted only the January 2022 initial gift; this March 2025 extension is the proximate cause of the announced pool jump from $100K (2022 to 2024) to $150K+ (2025 onward).
- **2023 NVC judging panel:** Ken Neeld, Karin Koch, Isabelle Bart, Michelle Khine, Rodrigo C. Mahs (per Business Wire).
- **2024 NVC judges/coaches:** Stella Zhang, Elvin Kay, Ken & Carla Neeld, Jeff Freud, Shalabh Gupta, Fiza & Mansoor Shah, Dan Jenkins.
- **Per-track corporate sponsorship confirmed to not exist** in NVC's structure; sponsors fund the program collectively.

### Expanded

- **Pre-2017 section in README**: "Other 2016 finalist teams" upgraded from a flat team-name list to a full table with confirmed member rosters for all 10 named teams.
- **`data/nvc.json`**: `pre_2017_editions[2016].other_finalists_named` (string array) replaced with `other_finalists` (object array including members).
- **`BACKLOG.md`**: 2016 entry updated to reflect that members are now confirmed; track placements within 2016's category structure remain the open gap.

## 2026-05-09

### Added

- **[`OUTCOMES.md`](OUTCOMES.md)**: "Where Are They Now?" post-competition outcomes for ~30 finalists across 2009 to 2025. Outcome categories (`OPERATING`, `ACQUIRED`, `PIVOTED`, `DORMANT`, `SHUT DOWN`, `NO PUBLIC OUTCOME FOUND`) with confidence labels and inline source URLs.
- **[`data/outcomes.json`](data/outcomes.json)**: structured mirror of `OUTCOMES.md` with summary_stats.
- **[`BACKLOG.md`](BACKLOG.md)**: contributor-facing menu of gaps organized by 8 priorities (2026 results, password-protected reports, missing rosters, undisclosed prizes, pre-2017 track winners, outcome research extension, source citations, sponsors/judges).
- **Per-year outcome footnotes**: each `years/YYYY.md` (2017 to 2025) now ends with a "Post-competition outcomes (selected)" section linking to the matching `OUTCOMES.md` anchor.
- **Restructured into per-year files**: `years/2017.md` through `years/2026.md` (10 files). Each is self-contained with theme, full awards table, and notes.
- **Canonical structured data**: [`data/nvc.json`](data/nvc.json) (schema v1) covering competition metadata, all 9 completed years' awards, upcoming 2026, pre-2017 editions, and cross-year notes.
- **"Year-by-Year Index" in README**: clickable summary cards replacing the previous in-line per-year tables.
- **"Cross-Year Analytics" in README**: disclosed cash totals by year (~$760,000 across 2017 to 2025), theme evolution, repeat-finalist table, prize structure changes over time.
- **"2026 Competition (Upcoming)" section**: confirmed structure (5 tracks, $20K Grand Prize, $100,000+ pool), Grand Finale date (2026-05-21), and named semi-finalists (AegleBio, Billify, NeuroBoost, Grad2Go).
- **"Pre-2017 Editions (2009 to 2016)" section**: confirmed Grand Prize winners for 2009 (ZeroWatt Technologies), 2012 (Prescient Imaging), 2013 (Laser Associated Sciences), 2014 (iBesties), 2016 (EmbryLux). 2010, 2011, 2015 not preserved in indexed public sources.
- **"Sources & Notes" section in README**: primary source domains; note about password-protected annual NVC PDF reports being the canonical blocker for many `Not Listed` rosters.
- **`CONTRIBUTING.md`**: how to submit corrections, source-quality preferences, style notes.
- **`.gitignore`**: OS/editor/temp files.

### Changed

- **README title**: `(2017 to 2025)` updated to `(2009 to 2026)` reflecting expanded coverage.
- **About the Competition section**: added naming history (Merage Business Plan Competition → UCI New Venture Competition (2016-2017) → Stella Zhang New Venture Competition (2022 naming gift)).
- **Style rule established**: no em dash character anywhere in the archive. Existing em dashes removed; replacement chars are commas, periods, colons, or rephrased.
- **LICENSE copyright**: changed from "StellaZhangUCI" template leftover to "ImanM02 and contributors".

### Fixed

- 2025 PCOSitive Buddy team roster: was "Master of Innovation & Entrepreneurship Students", now "Ricianne 'Chi' Rey (MIE)".
- 2024 Sentinel roster spellings: `O'Carrol` to `O'Carroll`, `Natan` to `Natán`.
- 2021 prize amounts filled: MoodCloud `$5,000`, REMSYS `$5,000`, StyloSonic `$7,500` (previously all `Undisclosed`).
- 7 cross-reference rows in per-year tables: `(None)` placeholder replaced with `(See Grand Prize)` / `(See Grand Finale)` references.
- Disconfirmed "Ishita Gulati" (2017 APIC) and "Ishita" (2018 Mechanodontics) identity match: different academic levels and schools per research.

## Coverage at a glance

| Aspect                          | Status                                       |
|---------------------------------|----------------------------------------------|
| Years covered                   | 2009 to 2026 (2010, 2011, 2015 placeholder)  |
| Total teams indexed             | 112                                          |
| Teams with confirmed members    | 67 of 112                                    |
| Teams with `Not Listed` rosters | 43 (mostly 2019 to 2025)                     |
| Outcomes researched             | 35 teams                                     |
| Confirmed exits                 | 2 (LAS to Medtronic 2020; Mechanodontics rebranded to BRIUS, ~$46M raised) |
| Disclosed cash 2017 to 2025     | ~$760,000                                    |
