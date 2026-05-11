# Changelog

[← Back to main archive](README.md)

This file captures substantive changes to the archive. For per-commit detail, run `git log`.

## 2026-05-11

### Fixed (verification pass against cited sources)

A systematic verification of high-stakes claims against their cited sources surfaced one fabricated connection by a research agent plus two minor data errors. All corrected:

- **First Step Diagnostics -> NeuroQure: REMOVED.** The connection was unsupported. Verification (WebFetch of both ocbj.com and innovation.uci.edu sources) confirmed NeuroQure was independently founded by Dave Justus in 2023 based on Prof. John "Jay" Gargus's research at UCI's Center for Autism Research and Translation (CART), with no documented relationship to First Step Diagnostics. First Step's 2018 NVC team (Max Lechner, Hannah Mylabathula, Dr. Elizabeth Chao, Dave Ferguson) is not mentioned in any NeuroQure source. The First Step Diagnostics outcome is now `NO_PUBLIC_OUTCOME_FOUND`. Affected files: OUTCOMES.md, data/outcomes.json, data/teams.json, TEAMS.md, years/2018.md, README.md (Where Are They Now? and Outcome distribution).
- **LAS acquisition date precision relaxed**: was "2020-04-14"; OC Business Journal reported the news on 2020-04-14 but UCI Innovation announcement is dated 2020-04-29. Updated to "2020-04" with a date_note in data/outcomes.json.
- **123 Baby Box investor name corrected**: "Sunstone Management" -> "Sunstone Fund" (the correct fund name per the Merage announcement). Investor list expanded to include the named angel investors (Mark Friedman, Demos Parneros, Sanjay Malhotra, Naren Parihar) from the Merage source.
- **Outcome distribution table** in README updated: PIVOTED 4 -> 3, NO_PUBLIC_OUTCOME_FOUND 14 -> 15.
- **Pattern summary** in OUTCOMES.md updated: "Three documented exits" -> "Three documented major outcomes" (acknowledging Mechanodontics/BRIUS is a rebrand, not an exit in the M&A sense); "Two real pivots" -> "One real pivot" (Wing -> Wing Assistant remains; First Step -> NeuroQure removed).
- **Mechanodontics/BRIUS funding caveat added**: rebrand confirmed via Crunchbase + CB Insights; $46M total funding figure (per PitchBook) flagged as not-independently-verified.

## 2026-05-10

### Added (judging-panel research, third pass)

- **Full judging panels added for 2021 and 2022:**
  - 2021: Gina Heitkamp, Pam Moellenhoff, Ken Neeld, Carrie Reynolds, Hicham Semaan
  - 2022: Isabelle Bart, Rodrigo Mahs, Lori Mazan, Debbie Lin
- **Partial judging info added for 2018, 2019, 2020:**
  - 2018: Chris Halliwell (Beall Center Board Member)
  - 2019: Ken & Carla Neeld, Mansoor & Fiza Shah, Dr. Emanuel Shaoulian, Matt Bailey, Johnson Chuang (named partners/sponsors); David Ochi (financial-modeling judge)
  - 2020: Ken Neeld (only confirmed name)
- **First documented finalist-to-judge transition: Gina Heitkamp** (2014 iBesties Grand Prize co-founder) returned in 2021 as a final-round judge. Added to README's repeat-finalists analytics section and to `data/nvc.json` years[2021].judges_note.
- **2018.notes** corrected: 2018 final round had 54 finalist teams (only the winners are in the awards array).
- **`data/nvc.json` years[2018-2022]** now have edition_number and judges / confirmed_judges_partial fields where data exists.
- **`SPONSORS-AND-JUDGES.md`**: new sub-sections for 2018, 2019, 2020, 2021, 2022.
- **`BACKLOG.md`** Priority 8 status updated: full panels for 2021/2022/2023/2024 now documented; only 2018, 2019, 2020 (full), 2025 (full), 2026 (upcoming), and 2017-earlier remain as gaps.
- Pre-2017 missing years (2010, 2011, 2015) still NOT FOUND after a third search angle; Wayback Machine inaccessibility blocks deeper search.
- "Not Listed" rosters for PZ Nanopure, CleanHydro, GlowGuard also NOT FOUND.

### Changed (propagation of outcome data into README and human-readable surfaces)

- **README "Where Are They Now?" teaser refreshed**: now reflects three documented exits (was two), names the two pivots-to-going-concern (First Step -> NeuroQure, Wing -> Wing Assistant), adds TeamMade's LuminOCity social-impact outcome, and reports the 54-of-112 research progress.
- **README Cross-Year Analytics**: new "Outcome distribution (researched teams)" sub-section with the category breakdown (50.0% OPERATING, 25.9% NO_PUBLIC_OUTCOME_FOUND, 9.3% DORMANT, 7.4% PIVOTED, 3.7% ACQUIRED, 1.9% SHUT DOWN).
- **TEAMS.md**: 18 entries gained inline italic outcome notes corresponding to the second-pass research findings.
- **years/2018.md through years/2025.md**: each year's "Post-competition outcomes (selected)" section updated with new bullets where applicable (10 new outcome bullets total across the 8 year files).

### Added (outcome research, second pass)

- **18 new confirmed-status outcomes** added to [`OUTCOMES.md`](OUTCOMES.md) and [`data/outcomes.json`](data/outcomes.json) from a second research pass on previously-unresearched track winners. Highlights:
  - **First Step Diagnostics -> NeuroQure** (PIVOTED 2018, confirmed): CLIA-certified ASD Insight autism test, UCI patent acquired 2024.
  - **No Decaf Allowed -> Moongoat Coffee Roasters** (ACQUIRED 2022, confirmed): the third documented exit in the archive after Laser Associated Sciences and the Mechanodontics rebrand.
  - **Wing -> Wing Assistant** (OPERATING 2018, confirmed): $2.1M seed in 2021, still operating in 2025-2026.
  - **Sayenza Biosciences** (OPERATING 2022, confirmed): ~$1.16M raised; joined California Life Sciences FAST Spring 2024.
  - **Nutripair** (OPERATING 2022, confirmed): $25K Verizon grant 2025; UCI Social Sciences profile March 2025.
  - **CarDana, Steth 'n Go, Omni Pet Club, TeamMade, Quiver** (OPERATING, confirmed): all with active product or project footprints.
  - **DermaVision Technologies** (OPERATING 2024, likely): student-team stage; placed 3rd at 2024 BMES Medtronic Design Competition.
  - **PCOSitive Buddy, ServEasy, Oslo** (OPERATING 2025, likely finalist stage).
  - **Poo Pal, REMSYS, SnapHealth, Crafty Palate** (DORMANT, likely): real websites or listings but no recent activity.
- **OUTCOMES.md pattern summary updated**: three documented exits now (was two); two real pivots that became going concerns (First Step -> NeuroQure, Wing -> Wing Assistant); TeamMade's LuminOCity unit donated for at-risk youth housing in July 2025 added as a social-impact highlight.
- **[`data/teams.json`](data/teams.json)**: outcome field populated for 18 newly-researched teams.
- **[`BACKLOG.md`](BACKLOG.md) Priority 5**: marked partially addressed; remaining unresearched list updated; pattern note added.
- **summary_stats in [`data/outcomes.json`](data/outcomes.json)** updated: teams_researched grew from 35 to 54; by_category breakdown adjusted; `notable_pivots` block added.

### Added

- **[`SPONSORS-AND-JUDGES.md`](SPONSORS-AND-JUDGES.md)**: institutional context document covering the Stella Zhang naming gift (with newly-documented **$750,000 March 2025 extension** that raised the announced pool from $100K to $150K+), recurring competition-level sponsors, judging panels for 2023 and 2024 (where named publicly), the Blum Center partnership with the Social Enterprise track, program staff (Jenn Huynh, Sara Heimann), and the seven-month workshop format.
- **[`TEAMS.md`](TEAMS.md)**: alphabetical master directory of all 112 teams across 2009 to 2026. One-line entry per team with year link, award abbreviations, members, and outcome status.
- **[`data/teams.json`](data/teams.json)**: slim machine-readable mirror of `TEAMS.md` (schema v1). Avoids duplication by referencing `data/nvc.json` for full member/project data and `OUTCOMES.md` anchors for outcome detail.
- **[`CHANGELOG.md`](CHANGELOG.md)** (this file): chronological iteration log.

### Infrastructure

- **JSON Schemas (draft-07)** added for the three data files:
  - [`data/nvc.schema.json`](data/nvc.schema.json): canonical archive schema (competition, years, awards, pre-2017 editions, cross-year notes).
  - [`data/outcomes.schema.json`](data/outcomes.schema.json): outcome entries with enum-typed `category` field constraining values to `OPERATING`, `ACQUIRED`, `EXITED_OTHER`, `PIVOTED`, `DORMANT`, `SHUT_DOWN`, `NO_PUBLIC_OUTCOME_FOUND`.
  - [`data/teams.schema.json`](data/teams.schema.json): team-index schema; `outcome.category` enum matches outcomes.schema.json.
- All three data files validated against their schemas via `npx ajv-cli@5 validate -s data/X.schema.json -d data/X.json` and pass.
- Contributors can run the same command to validate their changes before opening a PR.

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
