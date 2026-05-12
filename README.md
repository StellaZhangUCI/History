# UCI New Venture Competition: Complete Historical Archive (2009–2026)

A community-maintained archive of finalists, projects, and prizes from the **UCI New Venture Competition (NVC)**, UC Irvine's flagship startup competition, hosted by the Beall Center for Innovation & Entrepreneurship at the Paul Merage School of Business.

This document records each year's award categories, finalist teams, prize amounts, project descriptions, and (where available) team members. The goal is one durable, queryable record of what UCI's student and alumni founders have built. It's the kind of institutional memory that otherwise scatters across press releases, LinkedIn posts, and Wayback captures.

> Spotted an error or have data to add? See [`CONTRIBUTING.md`](CONTRIBUTING.md). PRs welcome.

## Repository layout

- [`README.md`](README.md): this file. Cross-cutting overview, analytics, and the per-year index
- [`years/`](years/): one markdown file per edition with the full awards table for that year
- [`OUTCOMES.md`](OUTCOMES.md): "Where Are They Now?" post-competition outcomes for past finalists
- [`TEAMS.md`](TEAMS.md): alphabetical master index of all 112 teams across 2009 to 2026
- [`SPONSORS-AND-JUDGES.md`](SPONSORS-AND-JUDGES.md): institutional context (naming gift, sponsors, judging panels by year, program staff)
- [`BACKLOG.md`](BACKLOG.md): concrete list of gaps in the archive (missing rosters, prize amounts, years, outcomes)
- [`CHANGELOG.md`](CHANGELOG.md): chronological log of substantive changes to the archive
- [`data/nvc.json`](data/nvc.json): the canonical structured data: competition metadata, per-year awards, members, prizes
- [`data/outcomes.json`](data/outcomes.json): structured mirror of `OUTCOMES.md` with categories, confidence, and source URLs
- [`data/teams.json`](data/teams.json): slim by-team index for quick lookup (name -> years, top award, outcome category)
- [`data/*.schema.json`](data/): JSON Schema (draft-07) definitions for each data file; the three data files validate against their schemas via `npx ajv-cli@5 validate -s data/X.schema.json -d data/X.json`
- [`CONTRIBUTING.md`](CONTRIBUTING.md): how to submit corrections and additions

## Table of Contents

- [About the Competition](#about-the-competition)
- [How to Read This Archive](#how-to-read-this-archive)
- [Cross-Year Analytics](#cross-year-analytics)
- [Year-by-Year Index](#year-by-year-index)
- [Pre-2017 Editions (2009–2016)](#pre-2017-editions-20092016)
- [Where Are They Now?](#where-are-they-now)
- [Sources & Notes](#sources--notes)

## About the Competition

- **Official name:** Stella Zhang New Venture Competition (since 2022)
- **Naming history:** Originally the *Merage Business Plan Competition*; renamed *UCI New Venture Competition* in the 2016–2017 cycle; renamed again to *Stella Zhang New Venture Competition* in 2022 following a naming gift from Stella Zhang (FEMBA '05) and her husband John Shen. All three names refer to the same competition lineage.
- **Naming gift renewal (March 2025):** Stella Zhang added **$750,000** to extend the naming commitment for another five years (through 2031). This is the gift that raised the announced annual prize pool from $100,000 to $150,000+ (visible in the 2025 archive entry). See [`SPONSORS-AND-JUDGES.md`](SPONSORS-AND-JUDGES.md) for full context.
- **Host:** UCI Paul Merage School of Business, Beall Center for Innovation & Entrepreneurship
- **Eligibility:** UCI students, alumni, faculty, and partner-school teams
- **Format:** Multi-round (Concept, Quarter, Semi-final / Board Room Pitch, Grand Finale) with track awards across Business Products & Services, Consumer Products, Consumer Services, Life Sciences, and Social Enterprise (categories vary slightly by year), plus overall Grand Prize, Runner-Up, and specialty awards (MIE, Audience Favorite)
- **Prizes:** Cash plus in-kind professional services (legal, accounting, mentorship, prototyping access). The 2026 cash pool exceeds $100,000.
- **First held:** 2009 (22nd annual edition in 2026). This archive's main per-year tables start at 2017; pre-2017 winners are summarized in the [Pre-2017 Editions](#pre-2017-editions-20092016) section.

## How to Read This Archive

- **"Not Listed"** in *Team Members* → the public source did not publish individual names
- **"Undisclosed"** in *Prize* → the dollar amount was not announced publicly
- **"(See …)"** → row is a cross-reference; the full detail lives in another row of the same year's table (typically the Grand Prize / Runner-Up / Audience Favorite row)
- **Repeating team names** within a single year mean the team won both an overall award and a track award

## Cross-Year Analytics

All numbers below are computed directly from the tables in this archive and cover **disclosed cash prizes only**. Several years included additional in-kind services (legal counsel, accounting, mentorship, lab/prototyping access) that are not counted here, and 2021's track-award amounts were largely undisclosed.

### Disclosed cash prizes by year

| Year      | Disclosed Total | Notes                                                       |
|-----------|-----------------|-------------------------------------------------------------|
| 2025      | ~$103,500       | Announced pool of "$150,000+" includes in-kind services     |
| 2024      | ~$100,000       |                                                             |
| 2023      | ~$100,000       |                                                             |
| 2022      | ~$100,000       |                                                             |
| 2021      | ~$46,000        | Shaka $17,500 total (GP + BP 1st combined) confirmed 2026-05-11; several track-award amounts still undisclosed |
| 2020      | ~$101,000       | Highest Grand Prize on record at $25,000                    |
| 2019      | ~$70,000        | Several rows undisclosed (Tech Surge 1st, CS 2nd tie, CP 2nd) |
| 2018      | ~$92,500        | No overall Grand Prize / Runner-Up awarded that year        |
| 2017      | ~$64,500        | Smaller per-track prizes ($4,000 / $1,500) before 2018 reset |
| **Total** | **~$777,500**   | Excludes still-undisclosed amounts and the value of in-kind services |

### Theme evolution

| Year | Theme as recorded in this archive                          |
|------|------------------------------------------------------------|
| 2017 | Deep Tech and Medical Innovation                           |
| 2018 | Orthodontics and Social Good                               |
| 2019 | Medical Devices and Social Platforms                       |
| 2020 | Pandemic Resilience and First MIE Winner                   |
| 2021 | Remote Work Solutions and Digital Health                   |
| 2022 | Gen Z Technology and Sustainability                        |
| 2023 | Hardware Innovation and Marketplace Platforms              |
| 2024 | Artificial Intelligence (AI) and Industrial Safety         |
| 2025 | Sustainability, Student Life Solutions, and Medical Tech   |

Themes are inferred from the dominant project areas of each year's finalists and aren't always official UCI labels. Three currents recur across nearly every year: **medical / life sciences**, **sustainability**, and **consumer-facing platforms**. They appear under different banners but rarely disappear entirely.

### Repeat finalists across years

People who appeared on a finalist team in more than one year:

| Founder        | First appearance                                                | Later appearance                                  |
|----------------|-----------------------------------------------------------------|---------------------------------------------------|
| Simon Loo      | 2016: FunBand                                                   | 2017: Element: B2B2C (Business Products 1st)      |
| Pravin Surana  | 2016: Negocios & Etc.                                           | 2017: APIC Diagnostics (Tech Surge 2nd)           |
| Daniel Dai     | 2017: Purist (Grand Prize, School of Medicine; Tech Surge 1st)  | 2018: Graduate Data (Consumer Services 2nd)       |
| Dylan Riffle   | 2023: Leprendo (Runner-Up; Consumer Services 1st)               | 2024: Two Cube (Life Sciences 1st)                |

Founders who appeared on two finalist teams in the **same** year:

| Founder                 | Year | Team A                                          | Team B                              |
|-------------------------|------|-------------------------------------------------|-------------------------------------|
| Donald "Don" Magnuson   | 2017 | Purist (Grand Prize, SoM; Tech Surge 1st)       | COMPAS (Business Products 2nd)      |

**Finalist-to-judge transitions:** Gina Heitkamp won the 2014 Grand Prize with iBesties (with sister Jenae). She returned in 2021 as a member of the final-round judging panel: the first documented finalist-to-judge transition in the archive. See [`SPONSORS-AND-JUDGES.md`](SPONSORS-AND-JUDGES.md#2021-17th-annual).

### Outcome distribution (researched teams)

Of the **54 teams researched** as of 2026-05-11 (out of 112 total in the archive):

| Outcome category          | Count | % of researched |
|---------------------------|-------|-----------------|
| OPERATING                 | 29    | 53.7%           |
| NO PUBLIC OUTCOME FOUND   | 15    | 27.8%           |
| DORMANT                   | 3     | 5.6%            |
| PIVOTED                   | 3     | 5.6%            |
| ACQUIRED                  | 2     | 3.7%            |
| SHUT DOWN                 | 1     | 1.9%            |

About half of researched teams are still operating in some form; about a quarter produced no traceable post-competition footprint. The remaining 58 teams have not yet been researched; see [`BACKLOG.md`](BACKLOG.md) Priority 5 for the list. The pattern across two outcomes-research passes: medical / life-sciences teams survive at the highest rate (long FDA timelines keep them alive); consumer apps and social-enterprise winners from 2018 to 2022 disproportionately produced no findable outcome.

### How prizes have shifted over time

- **Grand Prize size:** $15,000 (2017, School-of-Medicine award) → $25,000 (2020, the pandemic-era peak) → $20,000 (2022–2025, current standard)
- **Standard track payouts:** $4,000 / $1,500 in 2017 → $10,000 / $5,000 from 2018 onward, roughly a 6× jump in a single year
- **Number of tracks:** 6 in 2017 (Tech Surge and Poverty Alleviation alongside the four standard tracks) → 5 standard tracks (Business Products, Consumer Products, Consumer Services, Life Sciences, Social Enterprise) plus specialty awards from 2022 forward
- **MIE Award:** introduced in 2020 (Baby Box was the first Master-of-Innovation-and-Entrepreneurship-affiliated Grand Prize winner); now a recurring specialty award
- **Audience Favorite:** appears intermittently (2020, 2021, 2025); typically a $1,000 prize

## Year-by-Year Index

Each year links to its dedicated page with the full awards table and notes. Cross-cutting insights (totals, repeat founders, theme evolution) live in [Cross-Year Analytics](#cross-year-analytics) above.

### [2026 Competition (Upcoming) →](years/2026.md)

**Status:** Grand Finale scheduled for May 21, 2026 (22nd edition); 55 semi-finalists advancing.
**Notable semi-finalists:** AegleBio, Billify, NeuroBoost, plus 2025 Grand Prize winner **Grad2Go** defending.
**Confirmed structure:** $20,000 Grand Prize, $5,000 Runner-Up, 5 standard tracks, $100,000+ cash pool plus AWS credits.

### [2025 Competition →](years/2025.md)

**Theme:** Sustainability, Student Life Solutions, and Medical Tech
**Pool:** Over $150,000 (Cash & In-Kind)
**Grand Prize:** **Grad2Go** ($20,000), sustainable furniture resale and storage for students during move-out cycles.
**Runner-Up:** **GlowGuard** ($5,000), smart UV-C dental retainer case with Bluetooth tracking.

### [2024 Competition →](years/2024.md)

**Theme:** Artificial Intelligence (AI) and Industrial Safety
**Grand Prize:** **Sentinel** ($20,000), AI dashcam detecting trucker drowsiness without violating privacy.
**Runner-Up:** **NeoMold** ($5,000), 3D-printed ear molds for non-surgical correction of newborn ear deformities.

### [2023 Competition →](years/2023.md)

**Theme:** Hardware Innovation and Marketplace Platforms
**Grand Finale Winner:** **VagAligna** ($20,000), medical device for healing vaginal tissue after childbirth or injury.
**Runner-Up:** **Leprendo** ($5,000), specialty food marketplace using short-form video to connect farmers and consumers.

### [2022 Competition →](years/2022.md)

**Theme:** Gen Z Technology and Sustainability
**Grand Prize:** **Noveil** ($20,000), video dating app for Gen Z students.
**Runner-Up:** **Enjovu Paper** ($5,000), sustainable paper from regenerated fibers in elephant feces.
**Note:** First edition under the *Stella Zhang New Venture Competition* name.

### [2021 Competition →](years/2021.md)

**Theme:** Remote Work Solutions and Digital Health
**Grand Prize:** **Shaka** (amount undisclosed), culture-building app for remote teams.
**Audience Favorite:** **MONI** ($1,000), NFC-activated pet tag and community safety app.

### [2020 Competition →](years/2020.md)

**Theme:** Pandemic Resilience and First MIE Winner
**Grand Prize:** **Baby Box** ($25,000, the highest on record), AI-powered subscription for age-tailored baby products. First MIE-affiliated Grand Prize winner.
**Audience Favorite:** **Bottle Built** ($1,000), affordable housing using recycled PETE plastics.

### [2019 Competition →](years/2019.md)

**Theme:** Medical Devices and Social Platforms
**Tech Surge Winner:** **ELF Therapeutics** (Funded), handheld device using electrochemical reaction to destroy fat cells.
**Note:** No overall Grand Prize was awarded; Tech Surge headed the bill.

### [2018 Competition →](years/2018.md)

**Theme:** Orthodontics and Social Good
**Top Tracks:** **Mechanodontics** (Life Sciences 1st, $10,000), behind-the-teeth braces; **Closed Loop Plastics** (Tech Surge 2nd, $7,500), localized plastic recycling infrastructure.
**Note:** No overall Grand Prize was awarded that year.

### [2017 Competition →](years/2017.md)

**Theme:** Deep Tech and Medical Innovation
**Grand Prize (SoM):** **Purist** ($15,000), localized nuclear reactors for cancer-treatment isotopes.
**Notable:** $4,000/$1,500 track payouts (later reset to $10,000/$5,000 from 2018 onward); included a now-defunct Poverty Alleviation track.

## Pre-2017 Editions (2009–2016)

This archive's main per-year tables begin in 2017. For completeness, here are confirmed Grand Prize / overall winners from earlier editions, when the competition was known as the *Merage Business Plan Competition*. Track structures and prize amounts varied considerably during these years, and several years' results aren't preserved in indexed public sources.

| Year | Grand Prize Team               | Project                                                                                  | Prize                                              | Team Members                                                              |
|------|--------------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------|---------------------------------------------------------------------------|
| 2009 | ZeroWatt Technologies          | Low-power data converter ICs to extend battery life in portable electronics              | $15,000 + Best Concept Paper                       | Payam Heydari (Associate Professor & co-founder), Fred Tzeng (PhD student & co-founder), Vipul Jain (PhD student), Howard Ko (MBA), Thomas Pearson (MBA alumnus); coach Goran Matijasevic |
| 2010 | *No public record found*       | -                                                                                        | -                                                  | -                                                                         |
| 2011 | *No public record found*       | -                                                                                        | -                                                  | -                                                                         |
| 2012 | Prescient Imaging              | Compact PET-imaging hardware for medical diagnostics                                     | Not Disclosed                                      | Farhad Daghighian (Co-Founder, CEO; company founded 2008), Ariel Beroukhim (joined via class-project business model) |
| 2013 | Laser Associated Sciences (LAS)| Medical device using laser technology for diagnostic instrumentation (Campus Wide 1st)   | $15,000                                            | Charlene Ong, Tyler Rice, Sean White (BME / Edwards Lifesciences), Bruce Yang (BME); coach Dale Sadlik |
| 2014 | iBesties                       | Books, dolls, and online entertainment to inspire entrepreneurship and tech learning in girls aged 6–10. First all-female team to win, first sister team to make the finals, first toy idea in the contest. | $15,000                                            | Gina Heitkamp (MBA, Merage), Jenae Heitkamp (child therapist)             |
| 2015 | *No public record found*       | -                                                                                        | -                                                  | -                                                                         |
| 2016 | EmbryLux                       | Device screening embryos pre-implantation for IVF                                        | $20,000 (Life Sciences 1st + UCI IP Award)         | Tiffany Chien, Yingkai Su, Thai Nguyen, Shin Fukazawa, Daniel Tran        |

**Other 2013 winners** (confirmed via Samueli Engineering coverage, 2026-05-11 verification):

- 2nd Place (Campus Wide, $7,500): **ValveStrong**, hybrid heart valve prostheses
- 3rd Place (Campus Wide, $3,500): **NoreGen**, cancer detection device
- Undergraduate Division ($2,500): **Nobles Medical Technology**, artificial heart system for surgical practice
- TechPortal Calit2 Residency Award: **MEGAL!NE**
- UC Irvine Environment Institute Award: **Bloom Diagnostics**

**Other 2016 finalist teams** (confirmed but with full track placements not preserved in indexed sources):

| Team                       | Members                                                                                  |
|----------------------------|------------------------------------------------------------------------------------------|
| CeleriBio                  | Sean Freeman, Nikki Koe, Louai Labanieh, Binh Le, Sadaf Mirnia                           |
| Dental Insights            | Michael Bennett, Andy Fields, Vang Kou Khang                                             |
| Jam                        | Emilio Miranda, Miguel Cabral, Jakob Jansson                                             |
| FunBand                    | Rehema Feleke, Simon Loo, Cliff Wang                                                     |
| Curaflow                   | Jeffrey Chum, Josh Drum, Michael Shenk, Matthew Vasquez, Sam Pasin                       |
| Carbo                      | Pooja Raja, Rickesh Patel, Xuemei Zhang, Ahmed Khorshid, Ting-Shuo Chou                  |
| Sher Biomedical            | Rachel Gurlin, Avid Najdahmadi, Bhupinder Shergill, Jonathan Lakey, Elliot Botnivick     |
| Negocios & Etc.            | Caroline Cypriano, Pravin Surana, Fabio Sato                                             |
| Bottle Rocket              | Arthur Avetisov, Brian Leung, Eric Tam, Lisa Tran, Tina Mai                              |
| Maslow Construction Robots | Andy Truong                                                                              |

Two of these 2016 finalists returned to compete in 2017 (Simon Loo joined Element: B2B2C, winning Business Products 1st; Pravin Surana joined APIC Diagnostics, winning Tech Surge 2nd), captured in the [Repeat finalists](#repeat-finalists-across-years) table above.

**2009 Undergraduate division** (separate from the main Grand Prize): *Happy Sleep*, $3,500 + Best Concept Paper. Team: Praveen De Silva and Kevin Hung, both Mechanical & Materials Science Engineering undergraduates. Bluetooth wristband alarm.

## Where Are They Now?

A snapshot of post-competition outcomes for past finalists lives in [`OUTCOMES.md`](OUTCOMES.md). As of 2026-05-11, **54 of 112 teams** in the archive have been researched. Quick highlights:

- **Three documented major outcomes:**
  - Laser Associated Sciences (2013 GP) acquired by **Medtronic**, April 2020 (terms undisclosed).
  - Mechanodontics (2018 LS 1st) rebranded as **BRIUS Technologies** (Carrollton, TX); rebrand confirmed via Crunchbase / CB Insights; commercial Brava launch June 30, 2022. Funding figures (PitchBook) not independently verified here.
  - No Decaf Allowed (2020 CS 1st) acquired by **Moongoat Coffee Roasters**, December 2022 (asset / subscriber transfer, terms undisclosed).
- **One real pivot that became a going concern:** Wing (2018 CS 1st) -> **Wing Assistant**: $2.1M seed in October 2021, still operating as a managed-VA service in 2025/26.
- **Strongest non-medical operating company:** **123 Baby Box** (2020 Grand Prize), $1.2M oversubscribed seed in 2023 (XRC Ventures, Sunstone Fund, Salt Lake City Angels, Crescent Fund). TechCrunch reported 245% growth, tripled revenue, and 5x MRR (2021 baseline), with a target of $100K MRR / $1M ARR.
- **Medical / life-sciences teams have the highest survival rate;** consumer-app and social-enterprise winners from 2018 to 2022 have largely gone dark.
- **Most surprising decline:** Closed Loop Plastics (2018 Tech Surge 2nd), website now a parked domain in 2026.
- **2024 Grand Prize Sentinel** had a working MVP as of September 2024. An earlier draft inferred absorption by Spotter.ai's same-named Fleet Safety Platform; verification on 2026-05-11 could not confirm that connection. Treat the absorption claim as unverified.
- **TeamMade's LuminOCity** (2023 SE 2nd) modular ADU was donated for at-risk-youth housing and opened in July 2025: the most concrete social-impact outcome in the archive.

See [`OUTCOMES.md`](OUTCOMES.md) for the full breakdown, sources, and confidence levels.

## Sources & Notes

Primary sources used to compile this archive:

- UCI Paul Merage School of Business news releases (`merage.uci.edu/news/`)
- UCI Beall Applied Innovation press releases (`beallinnovation.uci.edu`)
- UCI Samueli School of Engineering coverage (`engineering.uci.edu/news/`)
- ANTrepreneur (`antrepreneur.uci.edu`)
- Business Wire press releases for the competition's announcements
- OC Startup Council, OC Register, and OC Business Journal coverage
- Beall / Butterworth Engineering Competition records (`bbcomp.tech.uci.edu`)

### Outstanding source: the official annual reports

The Beall Center publishes a comprehensive end-of-year PDF report for each NVC edition (2021 onward), posted under `merage.uci.edu/_files/documents/beall-center/nvc/` and `merage.uci.edu/_files/images/centers/innovation-entrepreneurship/`. As of this archive's last update, **all of these reports are password-protected**. They are the canonical source for the team rosters that currently read `Not Listed` here. If you can request access through the Beall Center, please open a PR to fill the gaps.

### Methodology notes

- "Confirmed" facts in this archive cite at least one durable public source.
- "Likely" facts (single source, reasonable provenance) are accepted but flagged in PR descriptions when added.
- Prize amounts are reported as announced and aren't inflation-adjusted.
- Spotted an error or have data to add? See [`CONTRIBUTING.md`](CONTRIBUTING.md).
