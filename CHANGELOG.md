# Changelog

[← Back to main archive](README.md)

This file captures substantive changes to the archive. For per-commit detail, run `git log`.

## Coverage at a glance (current, 2026-05-12)

| Aspect                          | Status                                                                                          |
|---------------------------------|-------------------------------------------------------------------------------------------------|
| Years covered                   | 2009 to 2026 (2010, 2011, 2015 confirmed structural gaps in indexed sources)                    |
| Total teams indexed             | 117 (113 across 2009-2025 + 4 named 2026 semi-finalists)                                        |
| Outcomes researched             | 114 teams                                                                                       |
| Outcome distribution            | 69 NO_PUBLIC_OUTCOME_FOUND / 31 OPERATING / 6 DORMANT / 5 PIVOTED / 2 ACQUIRED / 1 SHUT DOWN    |
| Confirmed acquisitions          | 2 (LAS to Medtronic Apr 2020; No Decaf Allowed to Moongoat Coffee Roasters Dec 2022)            |
| Notable rebrand                 | Mechanodontics to BRIUS Technologies; $46.2M total per Tracxn / Fundz / MergerLinks             |
| Notable pivots                  | Wing to Wing Assistant ($2.1M seed Oct 2021); COMPAS IP licensed to OpsGuru spin-out 2017 (stalled); Carbo into Prof. Krichmar's CARL research line at UCI |
| Disclosed cash 2017 to 2025     | ~$772,500 (corrected 2026-05-12 from $777,500 after MoodCloud/REMSYS tie-prize correction; prior 5th-pass adjustment took it from $760K to $777.5K)        |
| Disclosed cash pre-2017 partial | $67,500 (2013) + $82,500 (2016) = $150,000 confirmed; 2009/2012/2014/2015 partials remain      |
| Verification audit              | 38 passes against cited sources completed; 16 factual errors corrected + 6 stale derived figures caught and fixed; latest pass added full giv 2019 roster (Lucas Erb, Haven King, Ryan Luu, Nisarg Shah), expanded UniSafe 2019 to 3 named members (Upasana Mustafi + Praveen Ravisankar added), and DISCONFIRMED the prior "possible giv → Givsum" BACKLOG lead per UCI Beall and Butterworth 2019 winners page |

## 2026-05-12

### Added (thirty-eighth verification pass: giv 2019 full roster + UniSafe roster expansion + Givsum-link DISCONFIRMED)

Mined the UCI Beall and Butterworth 2019 winners page. Two roster fills plus a long-standing BACKLOG flag closed.

**giv 2019 (Social Enterprise 2nd, $5,000) - full team roster recovered**:
- Lucas Erb
- Haven King
- Ryan Luu
- Nisarg Shah

Project description refined: "Mobile-first online giving platform: curated, short-form video content from vetted nonprofits" (per the primary source). Replaces the earlier "Charitable giving platform similar to Instagram" wording.

**Cross-competition recognition**: giv also won the **Butterworth Software Competition 2019 2nd Place** ($6,500) - same year as the NVC appearance.

**Possible giv → Givsum lead DISCONFIRMED**: A prior pass had flagged a possible connection between the 2019 NVC "giv" team and the Givsum charitable-giving platform (founded by Shawn Wehan + Robert Kollar, joined UCI Wayfinder in 2017). With the giv UCI-team roster now confirmed as Lucas Erb / Haven King / Ryan Luu / Nisarg Shah, the two entities are demonstrably DIFFERENT. The BACKLOG flag is now closed. This continues the pattern of catching brand-confusion failure modes (similar to prior disconfirmations of First Step Diagnostics → NeuroQure, Sentinel → Spotter.ai, Help Belt → helpbelts.com, etc.).

**UniSafe 2019 (Business Products 1st, $10,000) - roster expanded** from 1 to 3 named members per the same primary source (where it is capitalized as "UniSAFE"):
- Rahul Sreedasyam (already in archive)
- **Upasana Mustafi** (new)
- **Praveen Ravisankar** (new)

**Cross-competition recognition**: UniSafe was also a Finalist at the **Butterworth Software Competition 2019** in the same year.

**bbcomp archive scope clarified**: A 2026-05-12 systematic check of `bbcomp.tech.uci.edu/past/past-{2016,2017,2018,2020,2025}` returned HTTP 404 for all five URLs, while 2019 and 2021-2024 returned data. The bbcomp past-winners archive only covers five years (2019, 2021, 2022, 2023, 2024 - and not 2020 or pre-2019). Worth noting in case future contributors look for those years.

**BACKLOG Priority 2 2019 list**: down to 1 remaining unresolved team (Jiffal). Poo Pal and SwappIt also still Not Listed (the 2019 NVC tied co-winner with Curbd remains unfindable).

**Files touched:**
- `data/nvc.json`: giv 2019 members + project description + `members_note` + `also_won`; UniSafe 2019 `team_aliases` ("UniSAFE") + roster expanded + `also_won`
- `years/2019.md`: giv + UniSafe rows updated with member detail; Notes section gained a cross-competition recognition paragraph and the Givsum-disconfirmation note
- `TEAMS.md`: giv + UniSafe entries upgraded from "Not Listed" / partial to full; 38th-pass date
- `BACKLOG.md`: Priority 2 2019 list updated (giv + UniSafe both resolved; "possible Givsum link" flag closed as DISCONFIRMED); last-reviewed bumped to 38th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 38 passes; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - no outcome changes, all enrichment), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Added (thirty-seventh verification pass: forMED roster expansion + 4 more cross-competition wins + Nutripair year correction)

Mined the UCI Beall and Butterworth past-winners pages (`bbcomp.tech.uci.edu/past/past-{2021,2022,2023}`) systematically. Four new cross-competition recognitions, a roster expansion, and a year correction.

**forMED Technologies 2022 (Life Sciences 1st, $10,000) - roster expanded from 3 to 5 members** per UCI Beall and Butterworth 2021 winners page:
- Aryan Agarwal (already in archive)
- Ruben Shakya (already in archive)
- **Raphael Francis Aguas** (first name expanded from "Francis Aguas")
- **Lily McGrale** (new)
- **Kamalesh Ananthakrishnan** (new)

Project description refined: "At-home **non-invasive intraocular-pressure** monitoring device to prevent blindness from glaucoma" (per the BSD 2021 description), replacing the bare "eye pressure monitoring system" wording.

**Four new cross-competition `also_won` recognitions:**
- **forMED Technologies 2022** (NVC LS 1st): won the **Beall Student Design Competition 2021 1st Place** with the same intraocular-pressure project the year before the NVC win
- **Nutripair 2022** (NVC BP 1st): won the **Butterworth Product Development Competition 2021 2nd Place** (Bing Mo + Catlin Tran; predates the 2022 NVC win)
- **ChewRank 2023** (NVC CS 2nd): won the **Butterworth Product Development Competition 2023 3rd Place** the same year
- **Leprendo 2023** (NVC RU + CS 1st): won the **Butterworth Product Development Competition 2022 1st Place** (3-member subset: Nina Nguyen, Dylan Riffle, Dan Ta; predates the 2023 NVC win)

**Nutripair Butterworth-year correction (16th factual error caught)**: Prior pass had recorded Nutripair as "2nd in 2022 Butterworth Product Development Competition" - the bbcomp 2022 winners page shows the 2022 Butterworth 2nd Place was actually **FoodPool** (Sanghyun Byun, Arthur Lafrance, Patrick Wang, Kevin Xu), and Nutripair's Butterworth 2nd Place was in **2021** (a year before the 2022 NVC win). The year was wrong in the prior pass and is now corrected in OUTCOMES.md, data/nvc.json, and TEAMS.md.

**Side observations (not added to archive pending stronger verification):**
- A "Michael Ross" appears on both the 2024 Sentinel NVC roster and the 2022 Thrust Aeronautics Beall Student Design Competition roster (3rd Place). Likely the same person given UCI engineering context, but Thrust Aeronautics is a Beall-only team (not an NVC finalist), so this isn't a "repeat NVC finalist" entry. Worth noting for future contributors interested in cross-competition trajectories.
- A "Rahul Sreedasyam" appears on both the 2019 NVC UniSafe team (co-founder) and the 2021 Phoraptor Beall Student Design Competition roster (2nd Place). Same person; same caveat (Phoraptor isn't an NVC team).

**Files touched:**
- `data/nvc.json`: forMED Technologies members + project description + `members_note` + `also_won`; Nutripair + ChewRank + Leprendo `also_won` fields added
- `OUTCOMES.md`: Nutripair entry's Butterworth year corrected from 2022 to 2021 with source citation
- `years/2022.md`: forMED Technologies row roster expanded; Notes section gained a cross-competition recognition paragraph for forMED + Nutripair
- `years/2023.md`: Notes section gained a cross-competition recognition paragraph for Leprendo + ChewRank
- `TEAMS.md`: forMED + ChewRank + Leprendo entries enriched with `also_won` annotations + 37th-pass date
- `BACKLOG.md`: last-reviewed bumped to 37th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 37 passes / 16 factual errors; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - no outcome category changes), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Added (thirty-sixth verification pass: 2024 cross-competition recognition + Sentinel-member spelling inconsistency note)

Three concrete enrichments to existing 2024 entries plus a source-quality observation.

**Cross-competition recognition added for three 2024 NVC teams** (per the Beall and Butterworth Competition 2024 winners page at bbcomp.tech.uci.edu/past/past-2024):
- **Sentinel** (NVC Grand Prize + BP 1st, $30K combined): also won **1st Place at the Butterworth Product Development Competition 2024**
- **Two Cube** (NVC Life Sciences 1st, $10K): also won **2nd Place at the Butterworth Product Development Competition 2024**
- **NeoMold** (NVC Runner-Up + LS 2nd, $10K combined): also won **1st Place at the Beall Student Design Competition 2024**

These cross-competition wins are added as `also_won` fields in `data/nvc.json` and called out in `years/2024.md` Notes. They round out the "what else did this team accomplish" picture for the strongest 2024 cohort without changing any outcome categorization.

**Two Cube project description refined**: Extended to match the Beall Butterworth primary source language ("autonomous research agents that streamline single-cell RNA analysis pipelines, enabling automatic code generation, result interpretation, and hypothesis development") rather than the bare "Autonomous bioinformatics platform streamlining single-cell RNA analysis" wording previously in the archive.

**Sentinel-member name-spelling inconsistency documented**: The Beall Butterworth 2024 winners page uses **"Nathan Ampudia"** and **"Spike O'Carroll"**, while the Business Wire / Merage 2024 press release (the higher-authority primary source) uses **"Natan Ampudia"** and **"Spike O'Carrol"**. The archive preserves the Business Wire / Merage spellings (which were specifically confirmed earlier in a prior pass after an incorrect "correction" to "Natán" / "O'Carroll" was reverted). The cross-source inconsistency is now explicitly noted in the Sentinel `members_note` field and in `years/2024.md` Notes section so future contributors don't accidentally "correct" the Business-Wire spellings to match the Beall Butterworth page (or vice versa) without checking both sources.

**Files touched:**
- `data/nvc.json`: Sentinel + NeoMold + Two Cube entries each gained an `also_won` field; Sentinel gained a `members_note` documenting the cross-source spelling inconsistency; Two Cube project description refined
- `years/2024.md`: Notes section gained a new paragraph documenting the three cross-competition wins and the Sentinel spelling-inconsistency observation
- `TEAMS.md`: date bumped to 36th pass (no per-team text changes - rosters unchanged, just adding cross-competition context which lives in the per-year file)
- `BACKLOG.md`: last-reviewed bumped to 36th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 36 passes; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - metadata enrichment only, no outcome category changes), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Fixed (thirty-fifth verification pass: MoodCloud/REMSYS 2021 tie-prize correction - 15th factual error caught + cash-total recalculation)

A meaningful factual correction plus a Shaka split-amount addition, both surfaced via the Merage 2021-06 primary source.

**MoodCloud + REMSYS 2021 (Consumer Services 1st, tied) - prize amounts corrected**: The Merage 2021-06 primary source explicitly states the two tied teams **split a single $5,000 prize** ($2,500 each), not that each team received $5,000 as the archive previously recorded. This is the 15th factual error corrected in the archive. Pattern matches the prior tie-prize confusion at 2019 Curbd/SwappIt, which was confirmed separately at $5,000 per team rather than a split.

**Shaka 2021 prize split clarified**: The Merage 2021-06 source confirms the $17,500 Shaka total, and the UCI Beall Wayfinder coverage from a 2026-05-12 search specifies Shaka's Grand Prize amount alone was $10,000 (the remaining $7,500 was the separate Business Products 1st award). Per-row amounts in `data/nvc.json` and `years/2021.md` updated from "Undisclosed" / null to the specific $10,000 GP + $7,500 BP 1st split. Total Shaka winnings ($17,500) remain unchanged. Augie Pimentel's full title ("Customer Success Specialist") also added to roster entries.

**Cascading derived-figure corrections:**
- 2021 disclosed cash total: **$46,000 → $41,000** (drop $5K from the over-counted tie prize)
- 2017-2025 cumulative disclosed: **$777,500 → $772,500**

**Files touched:**
- `data/nvc.json`: MoodCloud + REMSYS rows updated with corrected $2,500 amounts and a `prize_note` documenting the correction; 2021 entry in `disclosed_cash_totals_by_year_usd` corrected to $41,000 with an updated note; `total_2017_to_2025` corrected to $772,500 with a new note field
- `years/2021.md`: MoodCloud + REMSYS rows updated to $2,500 each; "Notes" section's disclosed-cash-total line corrected to $41,000 with the correction context
- `README.md`: Cross-Year Analytics cash table row for 2021 corrected to ~$41,000 with the correction context; Total row corrected to ~$772,500
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 35 passes / 15 factual errors / 6 stale derived figures; Disclosed-cash row refreshed to $772,500; this entry added

This pass also re-confirms a pattern observed multiple times: when a single sentence in the source ("each receiving half of a $5,000 prize") was reformatted into a per-team line in the archive table, the qualifier was dropped, producing a double-count. Future contributors should attend to "tied", "split", "each half" qualifiers in tie-prize coverage.

Cross-checks: outcomes.json by_category sums to 114 (unchanged - prize-amount correction is in nvc.json only), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Added (thirty-fourth verification pass: DermaVision 2024 post-competition recognition + Shaka 2021 roster verification + another password-protected PDF confirmed)

Small focused pass. One concrete enrichment plus two verifications-with-no-change.

**DermaVision 2024 (Social Enterprise 2nd, $5,000) - post-competition recognition added**: Samueli BME 2024 design-symposium materials document a **$3,000 grant from the Interdisciplinary Research Team program hosted by CALIT2 and UROP**. Also captured: Ashley Im's role detail (fourth-year biomedical engineer leading the algorithm and data-analysis side of the project). The existing Dean's Choice Award + BMES placement context preserved. Confidence on OPERATING (likely; student-team stage) unchanged.

**Shaka 2021 roster verification**: A 2026-05-12 search of UCI Beall + ocstartups coverage confirmed the existing Shaka team roster in `data/nvc.json` is complete and correct:
- Melanie Wertzberger (CEO)
- Austin Chauncey (CTO)
- Preston Le (Research Analyst)
- Agustine "Augie" Pimentel (Customer Success Specialist)

No change needed. The team description matches: "remote-work culture-building platform with automatic employee pairing, company-challenge tools (walking competitions, canned-food drives), and community spaces for groups like book clubs / working parents."

**Another password-protected PDF confirmed**: The 2021-NVC-Winners.pdf at `merage.uci.edu/_files/documents/beall-center/nvc/2021-NVC-Winners.pdf` is password-protected on direct download (1.7MB; confirmed 2026-05-12). This matches BACKLOG Priority 1 documentation. Would unlock the Hydroflow / MONI / HydroVasc / Health Libero prize amounts and rosters if access becomes available.

**Files touched:**
- `data/outcomes.json`: DermaVision summary extended with $3K CALIT2 / UROP grant + Ashley Im role detail; added Samueli BME design-symposium PDF source
- `OUTCOMES.md`: DermaVision narrative entry expanded similarly
- `TEAMS.md`: DermaVision entry annotated with Ashley Im role + the CALIT2 / UROP grant + Dean's Choice Award; date bumped to 34th pass
- `BACKLOG.md`: last-reviewed bumped to 34th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 34 passes; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - metadata-only enrichment of existing OPERATING entry), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Added (thirty-third verification pass: Nutripair co-founder + Sayenza founding-date enrichment + cross-file consistency audit)

Two concrete additions to existing OPERATING entries, plus a programmatic cross-file consistency audit.

**Nutripair 2022 (Business Products 1st, $10,000) - co-founder Bing Mo added**: UCI Social Sciences March 2025 profile names Bing Mo (UCI alum '21) as Catlin Tran's co-founder. Catlin Tran's role detail enriched: Founder & CEO; UCI Business Economics '23; 2022 UCI Beall Creativity & Entrepreneurship Scholarship recipient. Concept evolution captured: post-NVC, Nutripair pivoted from "clinical nutrition pairing" toward a restaurant-discovery platform for dietary restrictions. Also captured: 2nd place in 2022 Butterworth Product Development Competition (a sibling UCI competition track).

**Sayenza Biosciences 2022 (Life Sciences 2nd, $5,000) - founding-date and affiliations enriched**: 
- Founding date confirmed as **November 2019** (per UCI Beall coverage)
- Derek Banyard credentials expanded: Derek A. Banyard MD MS MBA, UCI MS 2017-2018
- Alan Widgerow's role outside Sayenza added: Plastic Surgeon, Professor & Director at the UCI Center for Tissue Engineering, also CMO at **Alastin Skincare** (acquired by **Galderma**) - the Alastin/Galderma connection is a meaningful exit-adjacent affiliation worth recording
- Funding context: ~$1.16M raised, aiming for a $3.5M seed round per UCI Samueli engineering coverage
- Two 2025 peer-reviewed publications added to OUTCOMES citations: *Bioengineering* paper and *Aesthetic Surgery Journal* paper on the underlying fluidic-device platform for lipoaspirate processing

**Cross-file consistency audit (no archive changes required)**:
Ran a programmatic cross-check across the three structured data files:
- All 114 outcomes in `data/outcomes.json` have matching entries in `data/teams.json` (including alias-mapping)
- All 114 teams in `data/teams.json` with non-null outcome match their `data/outcomes.json` entry
- All 117 teams in `data/teams.json` are represented in `data/nvc.json` across either `years.*.{grand_prize,runner_up,audience_favorite,specialty_awards,track_awards,tech_surge,awards,named_semifinalists}` or `pre_2017_editions.*.{grand_prize,undergraduate_winner,other_winners}`
- Zero category mismatches between teams.json outcome category and outcomes.json category
- Per-year markdown files in `years/` include every team listed in the corresponding nvc.json year entry

Confirms the archive's three structured data files and the per-year markdown narrative remain in sync after 33 verification passes.

**Files touched:**
- `data/nvc.json`: Sayenza Biosciences + Nutripair member fields enriched; Sayenza gained `company_founded: "2019-11"` and `members_note`
- `years/2022.md`: Sayenza Biosciences + Nutripair rows updated with the new member detail
- `OUTCOMES.md`: Sayenza + Nutripair narrative entries expanded with founding-date, role-detail, additional citations
- `TEAMS.md`: Sayenza + Nutripair entries upgraded; date bumped to 33rd pass
- `BACKLOG.md`: last-reviewed bumped to 33rd pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 33 passes; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - both updates were metadata enrichment of existing OPERATING entries), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Added (thirty-second verification pass: PCOSitive Buddy 2025 roster expansion)

Continued the Priority 2 roster sweep. One concrete addition.

**PCOSitive Buddy 2025 (MIE Specialty Award + Consumer Services 1st, $12,500 combined)** - roster expanded from a single name to four:
- **Ricianne "Chi" Rey** (MIE; co-founder & Marketing Lead) - directly verified via the ANTrepreneur Center January 2026 "Meet Chi Rey" profile and her RocketReach co-founder listing
- **Rafelia Angel** (core team) - sourced from WebSearch aggregation cross-referencing the 2025 Stella Zhang competition coverage
- **Varshini Vijay** (tech team) - LinkedIn-confirmed UCI student, Zotbotics Robotics Club co-president
- **Benson Manzano** (tech team) - LinkedIn-confirmed UCI ICS student, FUSION at UCI ICS project director

Project description refined: the AI wellness assistant is named "Chloe". A fifth team member referenced as "Kimberly" in indexed coverage is NOT added here pending a confirmed last name (deliberate caution around the name-fabrication failure mode previously caught with First Step Diagnostics / Help Belt / etc.).

**Files touched:**
- `data/nvc.json`: PCOSitive Buddy members field expanded (both the Specialty Award entry and the Track Award cross-listing); `members_note` documents the source-quality grading
- `OUTCOMES.md`: 2025 PCOSitive Buddy entry expanded with the four-member roster and source citations
- `years/2025.md`: Specialty Award row + CS 1st row updated; cross-listing now uses "(See Specialty Award)" for both project and members
- `TEAMS.md`: PCOSitive Buddy entry upgraded from single-name to full roster; date bumped to 32nd pass
- `BACKLOG.md`: last-reviewed bumped to 32nd pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 32 passes; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - metadata-only pass), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Fixed (thirty-first verification pass: Help Belt brand-disambiguation + Sentinel / VagAligna re-verifications)

A small, focused pass. One concrete archive change plus two negative-result re-verifications.

**Help Belt 2023 (Consumer Products 1st, $10,000) - brand-disambiguation note added**: A 2026-05-12 web search surfaced an unrelated commercial product, **Help Belts** at helpbelts.com (medical-alert seat-belt cover with information pocket, founded 2016 by a mother seeking a way to communicate her son's medical conditions to first responders). The UCI 2023 NVC Help Belt team is a distinct, separately-conceived seat-belt mobility-aid project, NOT the commercial Help Belts brand. Disambiguation note added to data/nvc.json and TEAMS.md to preempt the brand-confusion failure mode previously caught with First Step Diagnostics, Sentinel, Omni Pet Club, ZeroWatt Technologies, BrainCheck, Closed Loop Plastics, etc. (12th such disambiguation note in the archive.)

**Re-verifications (no archive change):**
- **Sentinel 2024 (Grand Prize)**: re-searched on 2026-05-12 for any post-September-2024 update. No public outcome data surfaced; OPERATING (MVP stage September 2024) categorization unchanged. BACKLOG Priority 6 still flags this for a future 2027 check.
- **VagAligna 2023 (Grand Finale Winner)**: re-searched on 2026-05-12 for any post-May-2023 FDA / clinical-trial update. Public coverage remains the original Business Wire / Merage 2023-05 announcements; no ClinicalTrials.gov entry surfaced. NO_FOUND categorization (with the contextual note that the project's path requires FDA clinical trials over multi-year timelines) unchanged.

**Files touched:**
- `data/nvc.json`: Help Belt 2023 entry gained a `naming_note` field disambiguating from helpbelts.com
- `TEAMS.md`: Help Belt entry annotated with the same disambiguation; date bumped to 31st pass
- `BACKLOG.md`: last-reviewed bumped to 31st pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 31 passes with the +1 disambiguation note recorded; this entry added

Cross-checks: outcomes.json by_category sums to 114 (unchanged - metadata-only pass), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Added (thirtieth verification pass: myHealth Today outcome upgrade + Embryologic 2019 roster + Hydroflow description refinement)

Continued the Priority 2 / Priority 6 sweep. Three concrete updates plus two negative-result verifications.

**myHealth Today 2019 (Consumer Services 1st, $10,000) - upgraded from NO_FOUND to OPERATING (likely)**: Merage 2020-12 coverage documents that CEO Kevin Wu (MBA '20) led the team, the company secured UCI Beall Applied Innovation funding, and officially incorporated in June 2020 (post-NVC). The app is `myHealthJournal`, a HIPAA-compliant patient-engagement service letting seniors record symptoms via phone voice services. `myhealthtoday.care` registered but returned ECONNREFUSED on 2026-05-12 fetch, so OPERATING is tagged "likely" rather than "confirmed" - incorporation is documented but current activity not independently verified. Outcome distribution shifts: 31 → 32 OPERATING, 69 → 68 NO_FOUND.

**Embryologic 2019 (Life Sciences 2nd, $5,000) - full team roster recovered** from Samueli engineering 2019-05 Rice Business Plan coverage:
- Prof. Michelle Digman (BME asst. professor, founder)
- Ning Ma (BME graduate student, Digman lab)
- Hongtao Chen (project scientist)
- Zhenghao Li (CS alumnus)

Source notes that the same team also placed 2nd in the 2019 Rice University Business Plan Competition semifinal round. The underlying FLIM-phasor IVF research published in *Scientific Reports* (2019) is the same line of work as the 2016 EmbryLux NVC entry - establishes the 2016 → 2019 continuity that was previously implicit.

**Hydroflow 2021 (Consumer Products 2nd) - project description refined**: "Smart water bottle cap tracking hydration levels" → "Smart water bottle cap that tracks water intake and monitors hydration levels" per UCI Beall 2021 primary-source language. Minor wording-level correction.

**Negative-result verifications (no archive change required):**
- **Closed Loop Plastics (2018 Tech Surge 2nd)**: re-verified on 2026-05-12 that `closedloopplastics.com/about-us` still serves a Sedo parking page. SHUT_DOWN (likely) status unchanged.
- **2024 NVC Report PDF** at `merage.uci.edu/_files/images/centers/innovation-entrepreneurship/NVC-2024-Report.pptx.pdf` is confirmed password-protected on direct download - matches BACKLOG Priority 1 documentation. Password not on file.

**Files touched:**
- `data/outcomes.json`: myHealth Today upgraded to OPERATING (likely); summary_stats refreshed (NO_FOUND 69→68, OPERATING 31→32)
- `data/nvc.json`: Hydroflow project description refined; myHealth Today + Embryologic member fields populated
- `data/teams.json`: myHealth Today outcome updated to OPERATING
- `years/2019.md`: myHealth Today + Embryologic rows updated with members; Post-competition outcomes section extended
- `years/2021.md`: Hydroflow description refined
- `OUTCOMES.md`: New myHealth Today + Embryologic entries added to 2019 section; header date / pass-count updated
- `TEAMS.md`: Embryologic + myHealth Today entries upgraded from "Not Listed"; date bumped to 30th pass
- `BACKLOG.md`: Priority 2 2019 list dropped from 4 to 2 remaining (myHealth Today + Embryologic both resolved); last-reviewed bumped to 30th pass
- `README.md`: Outcome-distribution table refreshed (NO_FOUND 69→68, OPERATING 31→32); narrative updated to reflect the 30th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 30 passes; this entry added

Cross-checks: outcomes.json by_category sums to 114 (still correct); teams.json 114/3 split unchanged; all three JSONs ajv-valid; em-dash sweep clean.

### Added (twenty-ninth verification pass: HAI 2022 full team + UniSafe 2019 co-founder + Hyperion post-comp grant)

Continued the Priority 2 "Not Listed" roster sweep across older years. Three concrete fills plus one possible-but-unconfirmed lead.

**HAI 2022 (Consumer Products 1st, $10,000) - full team roster recovered** from Samueli engineering 2022 NVC coverage:
- Yi-Ching (Wendy) Huang (CEO)
- Katrina Alberto (CMO)
- Ting-Ling (Tina) Kuo (CPO)
- Hsiao-Tung (Shelly) Liao (CFO)
- Tanaporn (Paul) Suwatnodom (COO)
- Pongthanit (Pong) Bisalputra
- Coach: Massoomeh Kazerouni

Project description refined to reflect primary source: "Sustainable jewelry made from recycled ocean waste; team pivoted from smartphone cases. 'HAI' means 'ocean' in Taiwanese." This is the largest single-team roster fill of the audit (6 members + coach).

**UniSafe 2019 (Business Products 1st, $10,000) - co-founder confirmed**: Rahul Sreedasyam (senior in Biomedical Engineering, UCI Henry Samueli School of Engineering). Other team members still Not Listed in indexed sources. Project description refined to capture the registered-sex-offender / crime-alert dimension noted in UCI Beall coverage.

**Hyperion Therapeutics 2023 (Life Sciences 1st) - post-competition grant added**: A $100,000 UCI Beall Applied Innovation Proof-of-Product grant in 2023 (Hyperion's first non-NVC funding milestone, surfaced in this pass). Already reflected in the OUTCOMES.md narrative from a prior pass; now propagated to `data/outcomes.json` summary field for consistency.

**Possible-but-unconfirmed: "giv" 2019 → Givsum**: A March 2020 UCI Beall "Where Are They Now?" feature on Givsum (founders Shawn Wehan CEO, Robert Kollar General Counsel; joined Wayfinder 2017) is consistent with the 2019 NVC "giv" team description ("charitable giving platform similar to Instagram"). However, none of the indexed sources explicitly state that Givsum competed at the 2019 NVC as "giv." Flagged as a possible link in BACKLOG with primary-source confirmation needed before adding to the archive - this is exactly the brand-confusion failure mode caught earlier with First Step Diagnostics, Sentinel, Omni Pet Club, etc.

**Files touched:**
- `data/nvc.json`: HAI 2022 members field populated (6 names + coach); UniSafe 2019 members partially populated; project descriptions refined for both
- `data/outcomes.json`: Hyperion Therapeutics summary extended with the $100K Proof-of-Product grant
- `years/2019.md`: UniSafe row updated with Rahul Sreedasyam
- `years/2022.md`: HAI row updated with full 6-member roster + coach
- `TEAMS.md`: HAI + UniSafe entries upgraded from "Not Listed"; date bumped to 29th pass
- `BACKLOG.md`: Priority 2 2022 list dropped HAI (from 4 to 3 remaining); 2019 list dropped UniSafe (from 5 to 4 remaining); "giv possible → Givsum" lead added with disclaimer; last-reviewed bumped to 29th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 29 passes; this entry added

Cross-checks: outcomes.json by_category sums unchanged (no new outcomes), teams.json 114/3 split unchanged, all three JSONs ajv-valid, em-dash sweep clean.

### Fixed (twenty-eighth verification pass: Prophet rename + Curbd roster + Steth 'n Go CEO)

Pursued Priority 2 "Not Listed" team-roster gaps where outcomes were already documented. Three concrete additions plus one factual correction.

**Prophet Modeling → Prophet Predictive Modeling (factual correction):** The Merage School 2020 press release primary source consistently uses "Prophet Predictive Modeling" with the project described as "AI-based money management services for accredited investors," not "predictive modeling for money management services" as previously recorded. Renamed across all five files (years/2020.md, data/nvc.json, data/outcomes.json, data/teams.json, TEAMS.md). `team_aliases` / `name_aliases` retain the old name for searchability. This is the 14th factual error caught across the audit.

**Curbd 2019 team roster:** Verified via `curbdparking.com/team.html` primary source on 2026-05-12:
- Farbod Rafezy (UCI Computer Science, Google Student Innovator; Lead Engineer)
- Iman Enayati (UCLA Psychobiology; Operations Manager)
- Ryan Dang (UCI Computer Science; Software Developer)

Curbd-side team page footer is 2019; consistent with the existing NO_FOUND outcome categorization. SwappIt (the tied co-winner) roster remains "Not Listed" - no primary source surfaced.

**Steth 'n Go 2019 CEO confirmed:** Omar Darwish (Associate Professor & Hospitalist at UC Irvine Health, Director of Point-of-Care Ultrasound for the Department of Medicine) confirmed as founder/CEO per his LinkedIn and the product origin story (residency frustration of losing six stethoscopes to inadequate hip-holders). Added to data/nvc.json members field, years/2019.md, TEAMS.md, and OUTCOMES.md entry.

**Curbd / SwappIt prize amount also clarified:** Each team received $5,000 per Orange County Startups Council 2019 coverage (previously the prize was recorded as "-" / undisclosed). 2019 Disclosed-cash narrative updated accordingly.

**Files touched:**
- `data/nvc.json`: 2019 Curbd / SwappIt + Steth 'n Go member fields; 2020 Prophet Modeling renamed + project description corrected
- `data/outcomes.json`: 2019 Curbd / SwappIt summary extended with Curbd roster + curbdparking.com source; 2020 Prophet Modeling renamed with team_aliases
- `data/teams.json`: Prophet Modeling renamed with name_aliases preserving old name
- `years/2019.md`: Curbd roster + Steth 'n Go CEO + prize text updated
- `years/2020.md`: Prophet Modeling → Prophet Predictive Modeling row updated
- `OUTCOMES.md`: Steth 'n Go entry gained Omar Darwish founder + product origin
- `TEAMS.md`: Three entries updated (Curbd / SwappIt, Prophet Predictive Modeling, Steth 'n Go); date bumped to 28th pass
- `BACKLOG.md`: Priority 2 2019 list - Curbd resolved (3 of 4 names) and Steth 'n Go resolved; subsection-header count updated from "(9 teams)" to "(5 teams remaining)"; last-reviewed bumped to 28th pass
- `CHANGELOG.md`: Coverage-at-a-glance verification-audit row bumped to 28 passes with the +1 factual error noted; this entry added

Cross-checks: all three JSONs still ajv-valid; em-dash sweep clean; outcomes.json by_category sums unchanged (no new outcomes added in this pass, only metadata corrections).

### Added (twenty-seventh verification pass: 2013 sub-winners full detail + 2016 full track placements + 2009 Happy Sleep)

Closed out almost all remaining unresearched teams in the archive. The 2016 finalist cohort, in particular, was a major BACKLOG Priority 4 unlock: the UCI News primary-source article from 2016-05-11 preserves complete track placements for all 12 finalist teams (placements were marked "not preserved in indexed sources" prior to this pass).

**New outcomes added (16 total) - by year:**

- **2009 (1):** Happy Sleep (Undergrad Division 1st, NO_FOUND)
- **2013 (5):** ValveStrong (DORMANT - founder moved to senior medtech roles, ValveStrong itself never incorporated), NoreGen (NO_FOUND), Nobles Medical Technology (NO_FOUND - disambiguated from Anthony Nobles' commercial NMT-II), MEGAL!NE (NO_FOUND), Bloom Diagnostics (NO_FOUND - disambiguated from unrelated Swiss medtech)
- **2016 (10):** Dental Insights, Negocios & Etc., Sher Biomedical, Jam, CeleriBio, Curaflow all NO_FOUND; FunBand DORMANT (Wayfinder incubator + OCBJ 2017 Innovator nomination, then no post-2018 footprint); Bottle Rocket DORMANT ($260K from MuckerLab + Dorm Room Fund, then no post-2018 footprint); Carbo PIVOTED (autism / ADHD therapy robot continued as Prof. Krichmar's CARL academic research at UCI); Maslow Construction Robots OPERATING (likely; Crunchbase profile exists)

**Researched-count now 114 of 117** (98 → 114). Only the 3 2026 semi-finalists (AegleBio, Billify, NeuroBoost) remain unresearched - they will be done after the 2026-05-21 Grand Finale. Effectively, this pass closes BACKLOG Priority 5 for the historical archive.

**Major findings beyond the team outcomes:**

- **NoreGen's $30,000 UCI School of Medicine Life Sciences Award** was previously unrecorded in this archive; recovered from the Samueli engineering primary source on 2026-05-12. This is the single largest specialty-prize line item in the pre-2017 archive and lifts the 2013 disclosed cash total from $31,000 (prior estimate) to $67,500.
- **ValveStrong's $6,000 TechPortal Orange Residency + $500 Best Concept Paper** were similarly unrecorded; ValveStrong's combined 2013 prize is now $14,000 rather than $7,500.
- **2016 disclosed cash total recovered**: $82,500 from line-item prizes (UCI News reports "more than $100,000 in cash and prizes" inclusive of legal-service and workspace in-kind credits not captured here).
- **Aaron Soto** was already added to the COMPAS team in the previous (26th) pass; the 27th pass adds **Andy Truong** (sole listed member of Maslow Construction Robots) and full member rosters + coaches for all five 2013 sub-winners, captured in data/nvc.json.
- **Two name-disambiguation notes** added to OUTCOMES.md: (1) UCI undergrad Nobles Medical Technology team is unrelated to Prof. Anthony Nobles' commercial NMT-II (NobleStitch); (2) UCI 2013 Bloom Diagnostics (environmental, algae-bloom detection) is unrelated to the Swiss medtech Bloom Diagnostics (CRP / iron-deficiency).
- **Repeat-finalist data enriched**: Simon Loo's 2016 FunBand award ("1st Consumer Products") and Pravin Surana's 2016 Negocios & Etc. award ("Blum Center for Poverty Alleviation Award") now appear in `cross_year_notes.repeat_finalists` rather than as empty `awards: []` arrays.

**Files touched:**

- `data/outcomes.json`: +16 outcomes; summary_stats updated (researched 98 → 114, NO_FOUND 58 → 69, OPERATING 30 → 31, PIVOTED 4 → 5, DORMANT 3 → 6)
- `data/nvc.json`: 2013 sub-winner rosters/coaches/expanded prize details; 2016 finalist track placements + prizes + descriptions; disclosed_cash_totals_by_year_usd extended with 2013 + 2016 + total_pre_2017_known; repeat-finalist awards arrays enriched for Simon Loo and Pravin Surana
- `data/teams.json`: 16 outcome fields populated; 10 2016 entries had top_award upgraded from "Finalist (track placement not preserved)" to specific placement; EmbryLux top_award noted as dual award; stats.teams_with_outcome_researched 98 → 114
- `OUTCOMES.md`: 16 new entries (Pre-2017 section); pattern summary gained two points (#11 about 2016 cohort pattern, #12 about 2013 cohort completion); header date / coverage line updated
- `README.md`: Pre-2017 Editions section gained a full 2013 sub-winners table (5 teams × 5 columns including coach) and a full 2016 placements table (10 teams × 4 columns); outcome distribution table refreshed (98 → 114, narrative rewritten to highlight 27th-pass coverage closure); "Where Are They Now?" teaser updated; name-disambiguation notes for Nobles Medical / Bloom Diagnostics added
- `BACKLOG.md`: Priority 4 strikethroughs for 2013 and 2016 (P4 now near-complete); Priority 5 reframed from "substantially completed" to "effectively complete" with only 3 2026 semi-finalists remaining; last-reviewed bumped to 27th pass
- `CHANGELOG.md`: Coverage-at-a-glance refreshed (researched count, distribution, disclosed cash, audit-pass count); this entry added

Primary sources newly cited in this pass: [Samueli engineering 2013 coverage](https://engineering.uci.edu/news/2013/6/engineering-students-achieve-strong-showing-merage-business-plan-competition), [UCI News 2016-05-11 coverage](https://news.uci.edu/2016/05/11/uci-student-entrepreneurs-do-battle-in-business-plan-competition/), [Samueli engineering 2009 coverage](https://sprocket.eng.uci.edu/news/2009/6/engineering-nabs-top-honors-2009-business-plan-competition-paul-merage-school-business), plus team-specific Gust/Crunchbase/UCI Beall/IGERT/Stanford-Zhao-Lab/ACM-DL citations per outcome entry.

Cross-checks passed: outcomes.json by_category sums to 114; teams.json has 114 with outcome / 3 null (3 2026 semi-finalists, as expected); all three JSONs ajv-valid; em-dash sweep clean.

### Added (twenty-sixth verification pass: 2017 track-winners cohort + COMPAS / OpsGuru trajectory)

Closed out the 2017 track-winners cohort that was the largest remaining concentration of unresearched teams. Seven new outcomes added to `data/outcomes.json`; six are NO_PUBLIC_OUTCOME_FOUND (Venom-Aid, Salux Diagnostics, Failsafe, Memorlane, Eater Zone, Element: B2B2C) and one is PIVOTED (COMPAS - the fourth PIVOTED entry in the archive).

**COMPAS / OpsGuru finding (verified against two primary sources, 2026-05-12):**

- COMPAS (Clinical Operations Management & Patient Analytics System) was developed inside UCI Health's Ops IT department to track patient flow in clinics; reported to have reduced patient cycle time from 86 to 62 minutes and won the 2016 CAPH/SNI Quality Leaders Awards top prize.
- In 2017 the IP was licensed to a new commercial spin-out, **OpsGuru**, founded as CEO by Jeff Greenberg, an Applied Innovation EiR (UC Tech News, 2018-06-06; UCI Beall Startup Spotlight, 2017-11).
- Curtis Hendrick (COMPAS lead, UCI Health director of Client Services and Innovation) on the licensing rationale: "UCI is not a software sales company. We figured we were best off licensing it to another company, and having that company take it to market."
- The OpsGuru commercialization vehicle has no public footprint after 2018. The current opsguru.com is an unrelated Canadian AWS consultancy (Carbon60 Operating Co LTD) - same brand-confusion failure mode previously caught with Sentinel/Spotter.ai, Omni Pet Club/OmniPet, BrainCheck/BrainCheck-Houston, ZeroWatt/Zerowatt-Energy. Explicitly disambiguated in the OUTCOMES entry.
- Underlying COMPAS technology continued at UCI Health as an internal tool (per UC Tech News coverage).

**Roster correction propagated across files**: UCI Informatics coverage identifies Aaron Soto (MHCID graduate student) as a fifth COMPAS team member alongside the four originally listed (Dr. Scott Ruskin, Don Magnuson, Curtis Hendrick, Michael Glover). Added to `years/2017.md`, `data/nvc.json`, and `TEAMS.md`.

**Memorlane signal-quality note**: The only post-2017 signal for Memorlane is a RocketReach profile that still associates founder Evan Schein with "Memorlane Founder." This is a stale-affiliation listing, not evidence of an active company - explicitly flagged as such in the OUTCOMES entry rather than upgraded to OPERATING.

**Files touched:**

- `data/outcomes.json`: +7 outcomes (Venom-Aid, Salux Diagnostics, Failsafe, Memorlane, Eater Zone, Element: B2B2C, COMPAS); summary_stats updated (teams_researched 91 -> 98, NO_PUBLIC_OUTCOME_FOUND 52 -> 58, PIVOTED 3 -> 4)
- `data/teams.json`: 7 outcome fields populated via `scratch/sync_teams_outcomes.js` + `scratch/recompact_teams.js`; stats.teams_with_outcome_researched 91 -> 98
- `data/nvc.json`: COMPAS member list extended by Aaron Soto
- `OUTCOMES.md`: 2017 section gained 7 new entries; pattern summary point #6 reworded; header date 2026-05-11 -> 2026-05-12
- `years/2017.md`: COMPAS members row updated; post-competition outcomes section gained two bullet groups; new "Roster note" section
- `TEAMS.md`: 7 entries gained status notes; COMPAS gained Aaron Soto; header date 2026-05-11 -> 2026-05-12
- `BACKLOG.md`: Priority 5 list cut from 26 to 19 unresearched teams; pattern narrative updated to "three outcomes-research passes"
- `README.md`: Outcome distribution table refreshed (91/52/30/3 -> 98/58/30/4); "Where Are They Now?" teaser updated; narrative paragraph reworded to call out the 26th-pass coverage closure
- `CHANGELOG.md`: Coverage-at-a-glance table refreshed; this entry added

Counts cross-check: 117 total teams - 98 researched = 19 unresearched. Matches teams.json `outcome === null` count.

## 2026-05-11

### Fixed (twenty-fifth verification pass: precise unresearched-team list)

Ran a programmatic cross-check to enumerate the exact remaining unresearched teams. BACKLOG Priority 5 had a generic prose description; now replaced with the precise list of 26 teams broken down by year / category:

- 3 × 2026 semi-finalists (AegleBio, Billify, NeuroBoost) - will be researched after the May 21, 2026 Grand Finale
- 7 × 2017 track winners (Venom-Aid, Salux Diagnostics, Failsafe, Memorlane, Eater Zone, Element: B2B2C, COMPAS)
- 5 × 2013 sub-winners (ValveStrong, NoreGen, Nobles Medical Technology, MEGAL!NE, Bloom Diagnostics)
- 10 × 2016 finalists with unknown track placements (CeleriBio, Dental Insights, Jam, FunBand, Curaflow, Carbo, Sher Biomedical, Negocios & Etc., Bottle Rocket, Maslow Construction Robots)
- 1 × 2009 Happy Sleep undergraduate winner

Total: 26. Counts match: 117 total teams - 91 researched = 26 unresearched. Cross-checked against teams.json `outcome === null` (also 26) and against teams not in outcomes.json (23, excluding the 3 2026 semi-finalists which are listed separately).

### Fixed (twenty-fourth verification pass: propagate NO_FOUND entries from outcomes.json to teams.json + BACKLOG)

After adding 37 NO_FOUND entries to data/outcomes.json in the previous pass, the corresponding teams.json entries still had outcome=null. Programmatic cross-file check identified all 37 inconsistencies. All now updated:

- **37 teams.json `outcome` fields** populated with `{category: "NO_PUBLIC_OUTCOME_FOUND", see: "OUTCOMES.md#<year>", note: "Researched 2026-05-10; no public outcome found"}`. Affected teams: Ardha Health, BagIt, CannTek, Celebrate in a Snap, ChewRank, CleanHydro, Curbd / SwappIt, Embryologic, EmpowerMi, Flare, GaleGauge, Gimme, giv, Graduate Data, HAI, Health Libero, Helios, Help Belt, Hydroflow, HydroVasc, Instinct, Jiffal, Lynne, MinuTax, MONI, MoodCloud, myHealth Today, NūCo, Orii.AI, P-FLAPs, Prophet Modeling, PZ Nanopure, SolarLab, Tooke Fabrics, TransMobile VR, UniSafe, Voltek.
- **teams.json compact format restored**: the propagation script used JSON.stringify with pretty-printing which expanded each team from one-line to multi-line. A custom serializer in `scratch/recompact_teams.js` restored the original one-line-per-team format for clean diffs.
- **BACKLOG.md Priority 5 reframed from "partially addressed" to "substantially completed"**. The list of 37 "still unresearched" teams was outdated since all those teams are now in data/outcomes.json with NO_FOUND status. New text shows the actual remaining 26 unresearched teams (mostly 2026 semi-finalists, pre-2017 sub-winners, and a few 2017-2018 track winners not in either pass).

### Added (twenty-third verification pass: 37 NO_PUBLIC_OUTCOME_FOUND entries propagated to data/outcomes.json)

The second outcomes-research pass (2026-05-10) attempted 56 previously-unresearched track winners; 18 yielded confirmed-status outcomes and were added to data/outcomes.json at the time. The remaining ~38 came up with no findable outcome but were never recorded as research-attempts, leading the BACKLOG to list them as "not yet researched."

This pass propagates those NO_PUBLIC_OUTCOME_FOUND entries to data/outcomes.json with brief summaries, year-specific source URLs to the original NVC announcement, and a confidence label of "researched 2026-05-10; no findable outcome."

37 new entries added (Curbd and SwappIt treated as one tied-row entry per archive convention):

- 2018 (4): Celebrate in a Snap, SolarLab, Gimme, Graduate Data
- 2019 (7): P-FLAPs, giv, UniSafe, Jiffal, myHealth Today, Curbd / SwappIt, Embryologic
- 2020 (5): Voltek, Prophet Modeling, Ardha Health, Instinct, CannTek
- 2021 (6): MONI, Health Libero, Hydroflow, MoodCloud, HydroVasc, Tooke Fabrics
- 2022 (3): EmpowerMi, HAI, GaleGauge
- 2023 (4): Helios, Orii.AI, Help Belt, ChewRank
- 2024 (4): BagIt, Flare, Lynne, PZ Nanopure
- 2025 (4): TransMobile VR, NūCo, MinuTax, CleanHydro

Propagated to derived figures:

- data/outcomes.json `summary_stats.teams_researched`: 54 -> 91; `by_category.NO_PUBLIC_OUTCOME_FOUND`: 15 -> 52.
- data/teams.json `stats.teams_with_outcome_researched`: 54 -> 91. `last_updated`: 2026-05-11 -> 2026-05-12.
- README "Where Are They Now?" teaser: "54 of 117" -> "91 of 117"; date 2026-05-11 -> 2026-05-12.
- README Outcome distribution table: 6-row distribution refreshed; NO_PUBLIC_OUTCOME_FOUND now the dominant category at 57.1% (was 27.8%). Pattern narrative rewritten to reflect this shift.
- CHANGELOG "Coverage at a glance (current)": outcomes-researched 54 -> 91; distribution refreshed.

Also fixed one stale propagation: LAS summary in data/outcomes.json still said "Acquired by Medtronic on April 14, 2020" even though the structured `acquisition_date` was updated to "2020-04" with a date_note. Summary now matches.

### Fixed (twenty-second verification pass: BACKLOG.md cleanup)

Audited BACKLOG.md for stale references after 21 passes of corrections.

- **"Last reviewed" date**: 2026-05-11 -> 2026-05-12.
- **"11 days from this review"**: was both wrong arithmetically (May 11 to May 21 is 10 days, not 11) AND now stale. Updated to "9 days from this review" (May 12 to May 21).
- **Priority 4 (Pre-2017 track winners) 2013 entry**: struck-through as resolved with a note about the five 2013 sub-winners (ValveStrong, NoreGen, Nobles Medical Technology, MEGAL!NE, Bloom Diagnostics) that were added in the 7th and 17th passes.

### Fixed (twenty-first verification pass: URL validity, sponsor consistency, Happy Sleep prize)

Ran 5 more programmatic checks: URL well-formedness, Pre-2017 README/JSON team-name consistency, TOC anchors, sponsor list cross-file, Happy Sleep teams.json prize info.

Real issues caught:
- **"Emanuel Shaoulian MD" -> "Emanuel Shaoulian, MD"**: nvc.json `competition.sponsors` had the form without comma; SPONSORS-AND-JUDGES.md has the comma form ("Emanuel Shaoulian, MD"). Standardized to the comma form in nvc.json so cross-file substring search finds the match.
- **Happy Sleep prize info in teams.json**: had "Undergraduate division winner" but the 9th pass added "$3,500 + Best Concept Paper" to nvc.json. Now propagated to teams.json `top_award` field.

Clean from these checks:
- URLs are all well-formed http(s):// across outcomes.json and naming_gift.sources.
- All 4 Pre-2017 named teams (ZeroWatt, Prescient, LAS, iBesties, EmbryLux) are present in the README Pre-2017 table.
- TOC anchor "Sources & Notes -> #sources--notes" was a false positive (GitHub's anchor rules produce double-dash for `&` between spaces; my slug logic was correct but the comparison logic had an edge case).

### Fixed (twentieth verification pass: members consistency between md and JSON)

Programmatic check on members and prize_text consistency between years/*.md tables and data/nvc.json. Found 1 real issue and 4 false positives (check-script artifacts):

Real issue:
- **TeamMade (2023 SE 2nd) members representation inconsistent.** MD had "UCI/OCC Partnership Team" in the members column; JSON had `members: []` with `members_note: "UCI/OCC Partnership Team"`. Two different structural representations of the same information. Normalized: JSON now has `members: ["UCI/OCC Partnership Team (individual roster not published)"]` matching the existing pattern used for other "team-label" entries like PCOSitive Buddy's "Ricianne 'Chi' Rey (MIE)".

False positives (data is correct, check has limitations):
- ELF Therapeutics LS 1st cross-listing entry has full members array in JSON (matching Tech Surge 1st canonical entry) but markdown uses "(See Tech Surge)" for the cross-listed row. This is the standard cross-listing convention in this archive (JSON entries are self-contained; markdown uses (See X) shortcuts). 4 of the 6 reported issues were these convention false positives.
- ELF Therapeutics prize-mismatch was a check-script ambiguous-match issue (two rows for the same team with place "1st"; Tech Surge 1st has "Funded" and LS 1st has "$10,000"; the check's first-match-wins logic returned the wrong pair).

### Fixed (nineteenth verification pass: more programmatic checks - found another stale by_category)

Ran additional programmatic checks: disclosed_cash sum vs total_2017_to_2025, year-file theme presence, teams_appearing_in_multiple_years count, outcomes by_category vs actual.

Real issue caught:
- **outcomes.json `summary_stats.by_category.OPERATING` was 29; actual count is 30.** Another off-by-one staleness. Earlier passes added Sentinel reclassification (PIVOTED -> OPERATING in 14th pass) and REMSYS reclassification (DORMANT -> OPERATING in 7th pass), but somewhere along the way the count was off. Now corrected: 30 OPERATING (55.6%). README outcome distribution and CHANGELOG "Coverage at a glance" updated to 30.

Also caught a structural inconsistency:
- **2019 Curbd / SwappIt "(Tie)" placement**: years/2019.md had "(Tie)" in the team column; data/nvc.json has "(Tie)" in the place field. Markdown updated to match JSON (place = "2nd (Tie)", team = "Curbd / SwappIt") for cross-file consistency. Verified all 9 year-file markdown tables now match data/nvc.json structurally.

All clean from these checks:
- disclosed_cash sum (777,500) matches stored total_2017_to_2025 OK
- Theme strings present in each year md file OK
- teams_appearing_in_multiple_years: stored 1 = actual 1 (Grad2Go) OK
- Other 5 by_category counts (ACQUIRED, PIVOTED, DORMANT, SHUT_DOWN, NO_PUBLIC_OUTCOME_FOUND) all match OK

### Fixed (eighteenth verification pass: more programmatic checks)

Ran 9 more programmatic checks (cross-listing validity, duplicate detection, anchor format, year ranges, year-vs-nvc consistency, prize text/usd consistency, repeat-finalist name verification, two-teams-same-year verification, 2026 semi-finalist consistency, empty-sources detection). Eight passed clean. One real issue caught:

- **First Step Diagnostics had empty `sources: []`** in data/outcomes.json. After the 1st-pass correction removed the (fabricated) NeuroQure link, the entry was left with no citations. Added the two URLs that document the disconfirmation, plus a `sources_note` clarifying that these sources document why the earlier NeuroQure link was wrong, not a positive outcome for First Step itself.
- **Two false-positive findings** logged: (1) Simon Loo / Pravin Surana repeat-finalist entries appear in pre_2017_editions[2016].other_finalists, not years[].awards; my check only looked at the latter (data is correct). (2) Don Magnuson "Don" vs "Donald" name-substring match failed due to my matching logic (data is correct).

The remaining six checks (cross-listing references, duplicates, anchor format, years range, outcome-year-vs-nvc-year, prize text/usd) all returned (none) - this is the first audit pass where most checks were clean.

### Fixed (seventeenth verification pass: programmatic cross-file consistency check)

This round ran a **programmatic cross-file check** (node script) between `data/nvc.json`, `data/outcomes.json`, and `data/teams.json` instead of grep sweeps. Found three categories of inconsistency:

- **"Laser Associated Sciences (LAS)" naming mismatch**: nvc.json had the team name as "Laser Associated Sciences (LAS)" (with the suffix), while outcomes.json and teams.json had it as plain "Laser Associated Sciences". Normalized to "Laser Associated Sciences" with `team_aliases: ["LAS"]` in nvc.json. Now consistent across all three files.
- **5 2013 sub-winners were missing from teams.json**: ValveStrong, NoreGen, Nobles Medical Technology, MEGAL!NE, Bloom Diagnostics were added to nvc.json's `pre_2017_editions[2013].other_winners` in the seventh pass but never added to teams.json. Now added with their 2013 placements / awards. teams.json `stats.total_unique_teams` updated 112 -> 117.
- **TEAMS.md header, README "Where Are They Now?", and CHANGELOG snapshot tables** all said "112 teams" - updated to 117. README clarified that the 5 new entries have not been outcome-researched (still 54 of 117).
- **3 false-positive mismatches** for 2026 semi-finalists (AegleBio, Billify, NeuroBoost) noted: they're in nvc.json under `years[2026].named_semifinalists` as a string array, intentionally separate from the `awards[]` structure since the finale hasn't occurred. teams.json captures them as full entries with `top_award: "Semi-finalist"`. The structural difference is correct.

Programmatic check pattern is far more thorough than grep sweeps. This was a different audit modality and caught issues the prior 6 grep-based consistency passes missed entirely. Worth running periodically.

### Fixed (sixteenth verification pass: more residual propagation)

Two more stale items found:

- **TEAMS.md ZeroWatt entry still said "Payam Heydari (faculty advisor)"** even though the 6th pass corrected this in README and data/nvc.json. Updated to "Associate Professor & co-founder" with the full team role detail.
- **DermaVision "available for licensing" + "placed third"** still in data/outcomes.json (line 582), years/2024.md (line 33), and TEAMS.md (line 53), even though the 5th pass clarified the UC Tech Transfer page now says "not available" AND noted the BMES placement discrepancy. All three locations now updated to match OUTCOMES.md.

Sixth consecutive consistency-audit pass to catch propagation failures. The empirical "every round finds something" pattern continues to hold.

### Fixed (fourteenth verification pass: more propagation cleanup)

Three more stale references found and corrected:

- **123 Baby Box "7-figure 2025 revenue"** STILL present in years/2020.md, TEAMS.md, and data/outcomes.json after the previous passes only updated OUTCOMES.md and README. Now cleaned up across all locations.
- **BRIUS funding precision $19.45M -> $19.5M and $46M -> $46.2M (Tracxn/Fundz/MergerLinks)** STILL present in data/outcomes.json BRIUS summary, TEAMS.md Mechanodontics entry, and years/2018.md after the previous pass only updated OUTCOMES.md. Now propagated.
- **123 Baby Box "seed" stage** unverified by TechCrunch source (which doesn't specify round stage); Merage source title says "oversubscribed round of $1.2 million." Changed "seed" -> "round" in OUTCOMES.md pattern summary point #5, README "Where Are They Now?", and TEAMS.md.

Four consecutive consistency-audit passes (11th + 12th + 13th + 14th) have each caught propagation failures. This empirically confirms that single-round corrections do not automatically propagate across all referencing locations; explicit consistency sweeps catch the leftover staleness reliably.

### Fixed (thirteenth verification pass: stale references in pattern summaries)

The pattern summaries at the top of OUTCOMES.md and the "Where Are They Now?" section in README still contained stale references from before earlier corrections:

- **Omni Pet Club "Chewy / Walmart / Amazon" retail mention** (from the 4th-pass brand-confusion correction) was still in the OUTCOMES.md pattern summary point #4. Updated to "operating via direct sales at omnipetclub.com."
- **123 Baby Box "7-figure 2025 revenue" claim** (from the 5th-pass correction) was still in BOTH the OUTCOMES.md pattern summary point #5 AND the README "Where Are They Now?" teaser. Replaced with the verified TechCrunch growth metrics (245% growth, tripled revenue, 5x MRR, target $100K MRR / $1M ARR).
- **LAS "April 14, 2020" date** (from the 1st-pass date-precision relaxation) was still in the OUTCOMES.md Pre-2017 LAS entry. Updated to "April 2020" with the OCBJ vs UCI Innovation date discrepancy noted. Also added 2013 NVC team detail (Charlene Ong, Tyler Rice, Sean White, Bruce Yang; coach Dale Sadlik) and the 2015 formal incorporation note.

These three were derived-prose staleness, similar to the 11th-pass disclosed-cash-total and 12th-pass teams.json stat. Three consecutive consistency-audit passes have now caught propagation failures.

### Fixed (twelfth verification pass: stale derived stats + last-updated dates)

After the eleventh pass caught one stale derived total, this pass audits all remaining derived stats and "last updated" dates for staleness:

- **`data/teams.json` `stats.teams_with_outcome_researched`: 35 -> 54** (was never updated after the second outcomes-research pass added 19 more entries to data/outcomes.json). Actual `outcomes.json` `summary_stats.teams_researched` is 54; teams.json stats now match.
- **`last_updated` / `Last updated` / `Last reviewed` dates refreshed to 2026-05-11** across data/nvc.json (was 2026-05-09), data/outcomes.json (was 2026-05-10), data/teams.json (was 2026-05-10), OUTCOMES.md (was 2026-05-09), TEAMS.md (was 2026-05-10), BACKLOG.md (was 2026-05-10), SPONSORS-AND-JUDGES.md (was 2026-05-10).
- **OUTCOMES.md header annotated** with "eleven verification passes against cited sources completed; thirteen factual errors corrected and one stale derived figure caught."

### Fixed (eleventh verification pass: consistency audit of derived totals)

After 13 corrections across the prior passes, the derived Cross-Year Analytics totals were re-audited for staleness. Found one stale figure:

- **2021 disclosed cash total updated $28,500 -> $46,000** to incorporate Shaka's previously-confirmed $17,500 (GP + BP 1st combined per Merage source). The Shaka prize was confirmed in the fifth pass (2026-05-11) but the Cross-Year Analytics table wasn't recalculated then. Now fixed.
- **Cumulative 2017-2025 disclosed total $760,000 -> $777,500** (same delta).
- **BACKLOG.md Priority 3**: Shaka GP and Shaka BP 1st rows struck-through with resolved note (other 2021 undisclosed amounts remain: Health Libero, MONI, Hydroflow, HydroVasc).
- **data/nvc.json `cross_year_notes.disclosed_cash_totals_by_year_usd`** updated with 2021_note documenting the change.
- **years/2021.md notes** updated to reflect the new total and the remaining undisclosed list.

### Confirmed (tenth verification pass: 2010/2011/2015 gap confirmed structural; Conshus Mahbub via PDF metadata)

- **2010, 2011, 2015 missing years: GENUINELY UNFINDABLE.** Confirmed conclusive after repeated targeted searches plus four direct WebSearch / WebFetch attempts on 2026-05-11. Wayback Machine returns ECONNREFUSED for archived merage.uci.edu pages. The competition was held each of those years (a 2010 3rd-place reference exists; 2015 was the kick-off for the 2016 cycle), but 1st-place winner announcements are not preserved in any indexed source. BACKLOG.md updated to reflect that this is a structural public-record gap, not a research effort failure.
- **Conshus Clothing (2020) founder Arneeb Mahbub** partially confirmed via PDF metadata of the concept paper hosted at merage.uci.edu (the PDF is titled "Conshus Exec Summary" created by Arneeb Mahbub). Co-founder "Parth" still not directly verifiable; left as-is per the original NVC archive entry.

### Added / Confirmed (ninth verification pass: more pre-2017 enrichment + Hyperion pipeline confirmed)

- **2009 Happy Sleep undergraduate winner**: $3,500 prize + Best Concept Paper for undergraduate division (NEW data; previously the archive had no prize amount). Both team members confirmed as Mechanical & Materials Science Engineering undergraduates. Updated in README + data/nvc.json `pre_2017_editions[2009].undergraduate_winner`.
- **2014 iBesties Heitkamp sisters enriched**: confirmed they were the first all-female team to win, the first sister team to make the finals, and the first toy idea in the (then) 11-year-old contest. Gina = MBA Merage + previous social-networking startup experience; Jenae = child therapist with 15 years of experience. Source: UCI News + universityofcalifornia.edu. Updated in README + data/nvc.json. (The specific Target / Nickelodeon claims about the post-2016 rebrand to Middle School Moguls remain unverifiable from primary sources.)
- **Hyperion Therapeutics pipeline confirmed**: SP3, SP4, SP5 are real named formulations in preclinical validation; 2023 PNAS publication referenced on hyperioneye.com/investors. No funding amounts disclosed publicly. Validates the earlier draft's claim about the SRED pipeline.
- **Conshus Clothing**: concept paper PDF exists at merage.uci.edu/_files/documents/beall-center/nvc/conshus-clothing-concept-paper.pdf; full content not searchable. Founder names (Arneeb Mahbub, Parth) from original NVC archive entry remain as-is.

### Fixed (eighth verification pass: pre-2017 team rosters)

- **Prescient Imaging (2012) founder dynamics clarified**. Merage source confirms Farhad Daghighian as Co-Founder and CEO (founded Prescient Imaging in 2008, four years before the NVC win). Ariel Beroukhim's role clarified: she originally developed the business model "for a class project," then joined Daghighian's NVC team. She is not described as a co-founder in the source. Updated in README's Pre-2017 Editions table and data/nvc.json.
- **EmbryLux (2016) verified**: team members confirmed (Tiffany Chien, Yingkai Su, Thai Nguyen, Shin Fukazawa, Daniel Tran) per news.uci.edu source. Awards confirmed: Life Sciences/CleanTech 1st ($10K) + UCI IP Award ($10K) = $20K total.
- **iBesties (2014) source returned 403**; couldn't re-verify in this pass (sources from previous pass already established the basics).
- **2010, 2011, 2015 missing winners** still not findable. The 2010 Don Beall Center awarded a 3rd-place prize at the 2010 competition per one search result, but the 1st-place winner for that year is not in any indexed source. **Confirmed structural gap** in the public record - not an archive failure.

### Fixed (seventh verification pass: REMSYS recategorization, 2013 NVC expansion, CarDana caveat)

- **REMSYS recategorized DORMANT -> OPERATING (BETA).** Verification on 2026-05-11 finds `remsys.app` in active BETA development as REMSYS LLC (©2024), offering AI resume tailoring, generative AI cover-letter creation, and AI-powered mock interviews. Earlier draft's "DORMANT" assessment was based on "no marketing activity past 2021" but the platform itself is active.
- **2013 NVC expanded with verified other winners** from Samueli engineering source: ValveStrong (Campus Wide 2nd, $7,500, hybrid heart valve prostheses), NoreGen (Campus Wide 3rd, $3,500, cancer detection device), Nobles Medical Technology (Undergraduate Division, $2,500, artificial heart system for surgical practice), MEGAL!NE (TechPortal Calit2 Residency Award), Bloom Diagnostics (UC Irvine Environment Institute Award). LAS team confirmed (Charlene Ong, Tyler Rice, Sean White, Bruce Yang) with coach Dale Sadlik; Sean White from BME/Edwards Lifesciences; Bruce Yang from BME.
- **CarDana 20% flat-fee claim**: not verified on cardana.co (the homepage references KBB integration and a 4-step process but doesn't disclose specific commission rates). Existing OUTCOMES.md entry already softened in previous passes.
- **Apeel Juice (2018) and LAS Charlene Ong** confirmed via search and Samueli source; no fabrication.
- **Outcome distribution counts updated**: OPERATING 28 -> 29 (REMSYS); DORMANT 4 -> 3.

### Fixed (sixth verification pass: ZeroWatt founders, SnapHealth recategorization, Blue Aqua, Esqalate)

- **ZeroWatt Technologies (2009 Grand Prize): Payam Heydari was a co-founder, NOT a "faculty advisor" as previously labeled.** The 2009 Samueli engineering source explicitly identifies him as a full team member and co-founder of the company alongside Fred Tzeng. The coaching figure was actually Goran Matijasevic, PhD MBA. Updated in README's Pre-2017 Editions table and `data/nvc.json` `pre_2017_editions[2009].grand_prize.members` (now lists Payam Heydari as "Associate Professor of EECS & co-founder", Fred Tzeng as "PhD student & co-founder", with student/alumni roles for the other three; coach added).
- **SnapHealth recategorized from DORMANT to PIVOTED.** Verification on 2026-05-11 finds `mysnaphealth.com` operating (©SnapHealth 2024) with a new health-coverage / insurance platform product (a coverage calculator for families plus broker tools), distinct from the 2022 NVC concept of "patient health record data control." Founder Ashraf Hammouri is not named on the current site. Updated in OUTCOMES.md, TEAMS.md, years/2022.md, data/outcomes.json, data/teams.json. Outcome distribution counts updated: DORMANT 5 -> 4, PIVOTED 2 -> 3.
- **Blue Aqua Food Tech** verified operating; `bafoodtech.com` active with insect-protein products line (Insect Protein, Oil, Fertilizer) though current product stock shows "Out of stock"; founder names not on the visible page.
- **Esqalate** Crunchbase profile returned 403; could not re-verify the "$100K nonprofit" claim directly. Existing entry left as-is with the "DORMANT (likely)" assessment supported by the parked-domain observation.
- **LAS team verification**: the 2020 Medtronic acquisition article confirms Sean White (CEO), Tyler Rice (CTO), Bruce Yang (Chief Engineer); Charlene Ong does not appear in that article (the 2013 NVC team may have had a different roster than the 2015-formed company). LAS was "formed" at UCI's Beckman Laser Institute in 2015 per the same article; the 2013 NVC team likely existed as a UCI research project before formal incorporation.

### Fixed (fifth verification pass: 123 Baby Box revenue, DermaVision, Closed Loop, Leprendo)

- **123 Baby Box "7-figure 2025 revenue" claim removed.** Verification of the cited TechCrunch source confirmed the 2023 growth metrics (245% growth, tripled revenue, 5x MRR over 2021) and the company's *target* of $100K MRR / $1M ARR, but did not confirm an actual 2025 revenue figure. The "7-figure 2025 revenue per LinkedIn" claim could not be verified through the cited source and was removed; the verified 2023 figures remain.
- **DermaVision placement clarification.** Sources conflict: BMES official 2024 results page lists DermaVision as **First Place winner** at the 2024 Medtronic / BMES Student Design Competition (represented by Gerald Lee and Elian Lintag); the team's own website lists **third place** in the Mechanical and Electrical track. Both placements now noted in OUTCOMES.md with the discrepancy. Also clarified: the UC Tech Transfer page (NCD/34412) currently says "not available for licensing" rather than the earlier draft's claim of "available"; entry softened to flag this. Additional context added: 2024 NVC roster (Ashley Im, Alejandra Reyes, Mitchell Frazeur, Hao Ngo) is the 2023-24 senior design cohort, distinct from the current 2024-25 cohort on the team website (Siana Jimenez Vences, Matthew Lo, Gerald Lee).
- **Closed Loop Plastics**: LB Business Journal source confirms three core co-founders (Sharon To, Aldrin Lupisan, Will Amos) and Long Beach base; the UCI origin claim is in the original NVC archive but not in the LBBJ piece. Wording softened accordingly.
- **Leprendo $400K first-year sales** confirmed via Sunstone profile. $15,000 NVC prize ($5K RU + $10K CS 1st) matches the Sunstone report. Note added that the Sunstone article erroneously dates Leprendo's NVC win to 2022; UCI primary sources confirm it was the 2023 cycle.
- **TeamMade luminOCity** confirmed: officially "luminOCity" (stylized); team stylized "teamMADE" (Modular Affordable Dwellings for the Environment); 750 sq ft 2-bedroom ADU opened July 9, 2025 in Placentia, donated to HIS-OC, houses at-risk youth ages 18-24.

### Fixed (fourth verification pass: Omni Pet Club, TeamMade LuminOCity confirmation)

- **Omni Pet Club retail distribution claim REMOVED.** Earlier draft claimed retail distribution via Chewy / Walmart / Amazon. Verification on 2026-05-11 found those listings are for a **different brand** called **OmniPet** (made by Leather Brothers in Conway, AR, founded 1976), not the UCI 2023 NVC startup Omni Pet Club. The two similarly-named brands had been conflated. The UCI Omni Pet Club is still operating but sells direct through their own site. Updated in OUTCOMES.md, TEAMS.md, years/2023.md, data/outcomes.json. This is the third documented case of brand-name overlap (after First Step / NeuroQure and Sentinel / Spotter.ai).
- **TeamMade LuminOCity confirmed.** July 2025 donation to Homeless Intervention Services-OC verified via engineering.uci.edu and teammade.eng.uci.edu. The ADU is officially named "luminOCity" (stylized lowercase l + capital OC); 750 sq ft, two-bedroom, opened July 9, 2025 in Placentia. Team stylization is "teamMADE" (MADE = Modular Affordable Dwellings for the Environment). The archive keeps "TeamMade" as the original 2023 NVC team name.
- **Chi Rey / PCOSitive Buddy confirmed.** ANTrepreneur 2026-01 article confirms Ricianne "Chi" Rey was hired as UCI ANTrepreneur Center Program Lead in October 2025 and continues to be described as a PCOSitive Buddy co-founder.
- **CarDana confirmed operating** with UCI NVC + Wayfinder Incubator history. (Specific "20% flat-fee" claim not visible on their About page; left in the OUTCOMES.md entry per first-agent claim but not independently verified.)
- **Quiver confirmed**: 20+ countries, $49/year paid membership, peer-to-peer marketplace.

### Fixed (third verification pass: Sentinel, spelling reversion)

- **Sentinel -> Spotter.ai absorption claim DISCONFIRMED.** The ANTrepreneur 2024-09 source that had been cited does not mention Spotter.ai; the Spotter.ai Sentinel page does not mention UCI. The connection was inferred from product-name overlap and is unverified. Sentinel's category moved from PIVOTED to OPERATING (likely, MVP stage as of September 2024). Updated in OUTCOMES.md (pattern summary + entry), years/2024.md, data/outcomes.json (category + summary), data/teams.json, README.md, BACKLOG.md.
- **Sentinel team-member spellings REVERTED.** Earlier "spelling fixes" in the archive (`O'Carrol` -> `O'Carroll` and `Natan` -> `Natán`) were actually introducing errors. Verification on 2026-05-11 against multiple primary sources (Business Wire May 2024 press release; Merage 2024 announcement; ANTrepreneur 2024 profile) confirms the original spellings used by all primary sources are **Spike O'Carrol** (single L) and **Natan Ampudia** (no diacritic). Reverted in years/2024.md, data/nvc.json, TEAMS.md.
- **Outcome distribution counts updated** in README and data/outcomes.json summary_stats: OPERATING 27 -> 28, PIVOTED 3 -> 2 (reflecting Sentinel's reclassification).

### Fixed (second verification pass: Hyperion, Sayenza, eLysis, BRIUS, iBesties)

Additional verification surfaced more corrections plus genuine new data:

- **Hyperion Therapeutics: "Timothy Luu" -> "Jennings Luu"**. The 2023 archive listed "Timothy Luu" as a founder, but the company's own website (hyperioneye.com), Irvine Standard 2025 coverage, and multiple search results confirm the correct name is **Jennings Luu** (MD/PhD, Founder/CEO, Case Western Reserve). The Krzysztof / Kris Palczewski entry is unchanged. Updated in years/2023.md, data/nvc.json, OUTCOMES.md, and TEAMS.md.
- **Sayenza Biosciences roster expanded**: original archive listed only "Dr. Derek Banyard"; UCI Samueli source confirms co-founders Jered Haun and Alan Widgerow (both UCI professors). Updated in data/nvc.json and years/2022.md.
- **ELF Therapeutics / eLysis Inc. "Not Listed" roster filled**: UCI Beall Applied Innovation source confirms four co-founders: Joon You (CTO / interim CEO), Dr. Brian Wong (facial plastic surgeon), Michael Hill PhD (Occidental College chemistry professor), Dr. Steve Yoelin (ophthalmologist). Note added that "ELF Therapeutics" is the NVC team name while the corporate entity is eLysis Inc. Updated in data/nvc.json and years/2019.md.
- **BRIUS Series B precision**: "$19.45M" -> "$19.5M" (per actual BRIUS press release dated 2025-05-06 led by View Ventures). Total funding $46.2M confirmed via Tracxn / Fundz / MergerLinks (no longer "per PitchBook" alone).
- **Shaka prize amount**: Merage source confirms "$17,500 total" at 2021 NVC. Noted in OUTCOMES.md as a clarification on the "Undisclosed" entries for Shaka's GP + BP 1st (the source reports a combined total, not an itemized breakdown).
- **iBesties Target / Nickelodeon claims softened**: the originally cited dollect.net source returned HTTP 409 (couldn't fetch on 2026-05-11) and themarysue.com is dated 2015 (pre-rebrand). The rebrand to Middle School Moguls remains supported by multiple search results, but the specific Target-retail and Nickelodeon-miniseries claims were flagged at the time as "could not be independently fetched." Subsequently re-verified on 2026-05-12 via Wikipedia and the UCI Merage 2018-12 announcement (Nickelodeon greenlight) and via IMDb (4-episode CG miniseries that aired Sept 2-29, 2019); confidence upgraded to confirmed in OUTCOMES.md.

### Fixed (verification pass against cited sources)

A systematic verification of high-stakes claims against their cited sources surfaced one fabricated connection plus two minor data errors. All corrected:

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

**Snapshot at initial archive build (2026-05-09); see top-of-file "Coverage at a glance (current)" for the post-audit state.**

| Aspect                          | Status (2026-05-09 snapshot)                 |
|---------------------------------|----------------------------------------------|
| Years covered                   | 2009 to 2026 (2010, 2011, 2015 placeholder)  |
| Total teams indexed             | 112                                          |
| Teams with confirmed members    | 67 of 112                                    |
| Teams with `Not Listed` rosters | 43 (mostly 2019 to 2025)                     |
| Outcomes researched             | 35 teams                                     |
| Confirmed exits                 | 2 (LAS to Medtronic 2020; Mechanodontics rebranded to BRIUS, ~$46M raised) |
| Disclosed cash 2017 to 2025     | ~$760,000                                    |
