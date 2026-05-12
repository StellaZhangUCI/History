# Changelog

[← Back to main archive](README.md)

This file captures substantive changes to the archive. For per-commit detail, run `git log`.

## Coverage at a glance (current, 2026-05-11)

| Aspect                          | Status                                                                                          |
|---------------------------------|-------------------------------------------------------------------------------------------------|
| Years covered                   | 2009 to 2026 (2010, 2011, 2015 confirmed structural gaps in indexed sources)                    |
| Total teams indexed             | 112                                                                                             |
| Outcomes researched             | 54 teams                                                                                        |
| Outcome distribution            | 29 OPERATING / 15 NO_PUBLIC_OUTCOME_FOUND / 3 DORMANT / 3 PIVOTED / 2 ACQUIRED / 1 SHUT DOWN    |
| Confirmed acquisitions          | 2 (LAS to Medtronic Apr 2020; No Decaf Allowed to Moongoat Coffee Roasters Dec 2022)            |
| Notable rebrand                 | Mechanodontics to BRIUS Technologies; $46.2M total per Tracxn / Fundz / MergerLinks             |
| Notable pivot to going concern  | Wing to Wing Assistant ($2.1M seed Oct 2021)                                                    |
| Disclosed cash 2017 to 2025     | ~$777,500 (updated from $760K after Shaka $17,500 confirmation in 5th verification pass)        |
| Verification audit              | 14 passes against cited sources completed; 13 factual errors / hallucinations corrected + 5 stale derived figures or prose references caught and fixed |

## 2026-05-11

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
- **OUTCOMES.md header annotated** with "eleven verification passes against cited sources completed; thirteen factual errors / hallucinations corrected and one stale derived figure caught."

### Fixed (eleventh verification pass: consistency audit of derived totals)

After 13 corrections across the prior passes, the derived Cross-Year Analytics totals were re-audited for staleness. Found one stale figure:

- **2021 disclosed cash total updated $28,500 -> $46,000** to incorporate Shaka's previously-confirmed $17,500 (GP + BP 1st combined per Merage source). The Shaka prize was confirmed in the fifth pass (2026-05-11) but the Cross-Year Analytics table wasn't recalculated then. Now fixed.
- **Cumulative 2017-2025 disclosed total $760,000 -> $777,500** (same delta).
- **BACKLOG.md Priority 3**: Shaka GP and Shaka BP 1st rows struck-through with resolved note (other 2021 undisclosed amounts remain: Health Libero, MONI, Hydroflow, HydroVasc).
- **data/nvc.json `cross_year_notes.disclosed_cash_totals_by_year_usd`** updated with 2021_note documenting the change.
- **years/2021.md notes** updated to reflect the new total and the remaining undisclosed list.

### Confirmed (tenth verification pass: 2010/2011/2015 gap confirmed structural; Conshus Mahbub via PDF metadata)

- **2010, 2011, 2015 missing years: GENUINELY UNFINDABLE.** Confirmed conclusive after three research-agent passes plus four direct WebSearch / WebFetch attempts on 2026-05-11. Wayback Machine returns ECONNREFUSED for archived merage.uci.edu pages. The competition was held each of those years (a 2010 3rd-place reference exists; 2015 was the kick-off for the 2016 cycle), but 1st-place winner announcements are not preserved in any indexed source. BACKLOG.md updated to reflect that this is a structural public-record gap, not a research effort failure.
- **Conshus Clothing (2020) founder Arneeb Mahbub** partially confirmed via PDF metadata of the concept paper hosted at merage.uci.edu (the PDF is titled "Conshus Exec Summary" created by Arneeb Mahbub). Co-founder "Parth" still not directly verifiable; left as-is per the original NVC archive entry.

### Added / Confirmed (ninth verification pass: more pre-2017 enrichment + Hyperion pipeline confirmed)

- **2009 Happy Sleep undergraduate winner**: $3,500 prize + Best Concept Paper for undergraduate division (NEW data; previously the archive had no prize amount). Both team members confirmed as Mechanical & Materials Science Engineering undergraduates. Updated in README + data/nvc.json `pre_2017_editions[2009].undergraduate_winner`.
- **2014 iBesties Heitkamp sisters enriched**: confirmed they were the first all-female team to win, the first sister team to make the finals, and the first toy idea in the (then) 11-year-old contest. Gina = MBA Merage + previous social-networking startup experience; Jenae = child therapist with 15 years of experience. Source: UCI News + universityofcalifornia.edu. Updated in README + data/nvc.json. (The specific Target / Nickelodeon claims about the post-2016 rebrand to Middle School Moguls remain unverifiable from primary sources.)
- **Hyperion Therapeutics pipeline confirmed**: SP3, SP4, SP5 are real named formulations in preclinical validation; 2023 PNAS publication referenced on hyperioneye.com/investors. No funding amounts disclosed publicly. Validates the agent's earlier claim about the SRED pipeline.
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

- **123 Baby Box "7-figure 2025 revenue" claim removed.** Verification of the cited TechCrunch source confirmed the 2023 growth metrics (245% growth, tripled revenue, 5x MRR over 2021) and the company's *target* of $100K MRR / $1M ARR, but did not confirm an actual 2025 revenue figure. The "7-figure 2025 revenue per LinkedIn" claim from the agent could not be verified through the cited source and was removed; the verified 2023 figures remain.
- **DermaVision placement clarification.** Sources conflict: BMES official 2024 results page lists DermaVision as **First Place winner** at the 2024 Medtronic / BMES Student Design Competition (represented by Gerald Lee and Elian Lintag); the team's own website lists **third place** in the Mechanical and Electrical track. Both placements now noted in OUTCOMES.md with the discrepancy. Also clarified: the UC Tech Transfer page (NCD/34412) currently says "not available for licensing" rather than the agent's claim of "available"; entry softened to flag this. Additional context added: 2024 NVC roster (Ashley Im, Alejandra Reyes, Mitchell Frazeur, Hao Ngo) is the 2023-24 senior design cohort, distinct from the current 2024-25 cohort on the team website (Siana Jimenez Vences, Matthew Lo, Gerald Lee).
- **Closed Loop Plastics**: LB Business Journal source confirms three core co-founders (Sharon To, Aldrin Lupisan, Will Amos) and Long Beach base; the UCI origin claim is in the original NVC archive but not in the LBBJ piece. Wording softened accordingly.
- **Leprendo $400K first-year sales** confirmed via Sunstone profile. $15,000 NVC prize ($5K RU + $10K CS 1st) matches the Sunstone report. Note added that the Sunstone article erroneously dates Leprendo's NVC win to 2022; UCI primary sources confirm it was the 2023 cycle.
- **TeamMade luminOCity** confirmed: officially "luminOCity" (stylized); team stylized "teamMADE" (Modular Affordable Dwellings for the Environment); 750 sq ft 2-bedroom ADU opened July 9, 2025 in Placentia, donated to HIS-OC, houses at-risk youth ages 18-24.

### Fixed (fourth verification pass: Omni Pet Club, TeamMade LuminOCity confirmation)

- **Omni Pet Club retail distribution claim REMOVED.** Earlier draft claimed retail distribution via Chewy / Walmart / Amazon. Verification on 2026-05-11 found those listings are for a **different brand** called **OmniPet** (made by Leather Brothers in Conway, AR, founded 1976), not the UCI 2023 NVC startup Omni Pet Club. The agent confused two similarly-named brands. The UCI Omni Pet Club is still operating but sells direct through their own site. Updated in OUTCOMES.md, TEAMS.md, years/2023.md, data/outcomes.json. This is the third documented case of agent confusion via name overlap (after First Step / NeuroQure and Sentinel / Spotter.ai).
- **TeamMade LuminOCity confirmed.** July 2025 donation to Homeless Intervention Services-OC verified via engineering.uci.edu and teammade.eng.uci.edu. The ADU is officially named "luminOCity" (stylized lowercase l + capital OC); 750 sq ft, two-bedroom, opened July 9, 2025 in Placentia. Team stylization is "teamMADE" (MADE = Modular Affordable Dwellings for the Environment). Our archive keeps "TeamMade" as the original 2023 NVC team name.
- **Chi Rey / PCOSitive Buddy confirmed.** ANTrepreneur 2026-01 article confirms Ricianne "Chi" Rey was hired as UCI ANTrepreneur Center Program Lead in October 2025 and continues to be described as a PCOSitive Buddy co-founder.
- **CarDana confirmed operating** with UCI NVC + Wayfinder Incubator history. (Specific "20% flat-fee" claim not visible on their About page; left in the OUTCOMES.md entry per first-agent claim but not independently verified.)
- **Quiver confirmed**: 20+ countries, $49/year paid membership, peer-to-peer marketplace.

### Fixed (third verification pass: Sentinel, spelling reversion)

- **Sentinel -> Spotter.ai absorption claim DISCONFIRMED.** The ANTrepreneur 2024-09 source (which the agent cited) does not mention Spotter.ai; the Spotter.ai Sentinel page does not mention UCI. The connection was inferred from product-name overlap and is unverified. Sentinel's category moved from PIVOTED to OPERATING (likely, MVP stage as of September 2024). Updated in OUTCOMES.md (pattern summary + entry), years/2024.md, data/outcomes.json (category + summary), data/teams.json, README.md, BACKLOG.md.
- **Sentinel team-member spellings REVERTED.** Earlier "spelling fixes" in the archive (`O'Carrol` -> `O'Carroll` and `Natan` -> `Natán`) were actually introducing errors per the first research agent. Verification on 2026-05-11 against multiple primary sources (Business Wire May 2024 press release; Merage 2024 announcement; ANTrepreneur 2024 profile) confirms the original spellings used by all primary sources are **Spike O'Carrol** (single L) and **Natan Ampudia** (no diacritic). Reverted in years/2024.md, data/nvc.json, TEAMS.md.
- **Outcome distribution counts updated** in README and data/outcomes.json summary_stats: OPERATING 27 -> 28, PIVOTED 3 -> 2 (reflecting Sentinel's reclassification).

### Fixed (second verification pass: Hyperion, Sayenza, eLysis, BRIUS, iBesties)

Additional verification surfaced more corrections plus genuine new data:

- **Hyperion Therapeutics: "Timothy Luu" -> "Jennings Luu"**. The 2023 archive listed "Timothy Luu" as a founder, but the company's own website (hyperioneye.com), Irvine Standard 2025 coverage, and multiple search results confirm the correct name is **Jennings Luu** (MD/PhD, Founder/CEO, Case Western Reserve). The Krzysztof / Kris Palczewski entry is unchanged. Updated in years/2023.md, data/nvc.json, OUTCOMES.md, and TEAMS.md.
- **Sayenza Biosciences roster expanded**: original archive listed only "Dr. Derek Banyard"; UCI Samueli source confirms co-founders Jered Haun and Alan Widgerow (both UCI professors). Updated in data/nvc.json and years/2022.md.
- **ELF Therapeutics / eLysis Inc. "Not Listed" roster filled**: UCI Beall Applied Innovation source confirms four co-founders: Joon You (CTO / interim CEO), Dr. Brian Wong (facial plastic surgeon), Michael Hill PhD (Occidental College chemistry professor), Dr. Steve Yoelin (ophthalmologist). Note added that "ELF Therapeutics" is the NVC team name while the corporate entity is eLysis Inc. Updated in data/nvc.json and years/2019.md.
- **BRIUS Series B precision**: "$19.45M" -> "$19.5M" (per actual BRIUS press release dated 2025-05-06 led by View Ventures). Total funding $46.2M confirmed via Tracxn / Fundz / MergerLinks (no longer "per PitchBook" alone).
- **Shaka prize amount**: Merage source confirms "$17,500 total" at 2021 NVC. Noted in OUTCOMES.md as a clarification on the "Undisclosed" entries for Shaka's GP + BP 1st (the source reports a combined total, not an itemized breakdown).
- **iBesties Target / Nickelodeon claims softened**: the originally cited dollect.net source returned HTTP 409 (couldn't fetch on 2026-05-11) and themarysue.com is dated 2015 (pre-rebrand). The rebrand to Middle School Moguls remains supported by multiple search results, but the specific Target-retail and Nickelodeon-miniseries claims are now flagged as "per research-agent claims, could not be independently fetched."

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
