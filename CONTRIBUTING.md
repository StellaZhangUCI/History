# Contributing

This is a community archive of the UCI New Venture Competition. Corrections and additions are welcome. Most rows started with publicly available data and many cells are still incomplete (`Not Listed`, `Undisclosed`).

> **Looking for something concrete to work on?** [`BACKLOG.md`](BACKLOG.md) lists every known gap in the archive (missing rosters, prize amounts, untouched outcomes) organized by priority. That's the menu.

## Validating your data changes

Each JSON file under `data/` has a matching `.schema.json` (JSON Schema draft-07). Before opening a PR that changes a data file, validate it locally:

```bash
npx --yes ajv-cli@5 validate -s data/nvc.schema.json -d data/nvc.json
npx --yes ajv-cli@5 validate -s data/outcomes.schema.json -d data/outcomes.json
npx --yes ajv-cli@5 validate -s data/teams.schema.json -d data/teams.json
```

All three should print `data/<file>.json valid`. If validation fails, the error message will name the offending path inside the JSON.

## Ways to contribute

1. **Open an issue** if you spot incorrect data (wrong prize amount, mis-attributed project, misspelled team member) and have a source to back it up.
2. **Open a pull request** to add or correct rows directly. Keep the existing table format. Cite your source in the PR description.
3. **Fill blanks.** Many `Team Members` cells are `Not Listed` because the original press release didn't publish names. If you can confirm a team's roster from a public source (LinkedIn, the team's own website, news coverage), please contribute.
4. **Add a missing year.** The competition has run since 2009; this archive currently starts at 2017. Pre-2017 editions and the current year are gaps worth filling.
5. **"Where are they now?"** updates: if you know that a past team has raised funding, exited, or shut down, that's valuable context to add (in a dedicated section, not the main awards tables).

## What to include in a correction

- The year and award category you're editing
- The new value
- A link or reference for the new value (durability matters; a UCI press release or news article is more durable than a Twitter post)

## Source quality (in order of preference)

1. UCI Beall Applied Innovation / Paul Merage School official press releases
2. News coverage (OC Register, local press, trade publications)
3. The team's / company's own website or "About" page
4. Founders' LinkedIn profiles
5. First-person knowledge (please note this in the PR description so reviewers can flag for verification)

## Style

- Use `(See [Other Row])` to cross-reference an entry that already appears earlier in the same year's table; don't duplicate full descriptions
- Prize amounts: `$10,000` (no decimals, no spaces inside the number)
- Team members: `First Last, First Last, …`
- Dates and amounts: stick to the year's reported figures; don't inflation-adjust

## Code of conduct

Be respectful. This archive includes the names of real founders, judges, and students; treat their listed achievements with care. If a team member has requested removal of their name from public records, honor that request.
