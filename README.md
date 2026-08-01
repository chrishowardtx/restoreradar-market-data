# RestoreRadar restoration market data

This repository is a versioned public mirror of RestoreRadar's aggregate restoration-provider
market-data files. The canonical report, methodology, data dictionary, current downloads, and
correction route are at:

https://restoreradar.com/restoration-market-data/

## Snapshot

- Data updated: **2026-07-30**
- Published provider records: **550**
- Covered metros: **10**
- Covered service categories: **4**

The snapshot contains aggregate counts only. It does not contain provider-level contact records,
private source material, or RestoreRadar's application code.

## Files

- `data/restoration-market-data.csv` — one aggregate row per covered metro.
- `data/restoration-market-data.json` — totals, metro rows, service rows, field definitions, source
  boundaries, limitations, citation text, and reuse terms.
- `data/restoration-provider-signals-by-metro.svg` — reusable chart of selected provider-stated
  signals by metro.
- `CITATION.cff` — machine-readable citation metadata.
- `REUSE_TERMS.md` — the permission and third-party-rights boundary published with the report.

## Read the limitations first

- This is not a census of every restoration company operating in each metro.
- A missing signal means RestoreRadar did not confirm it; it does not establish that a provider
  lacks the attribute.
- Provider-stated 24/7 response and direct insurance billing are statements observed on provider
  websites, not independent performance tests.
- Service rows overlap because one provider may list more than one restoration service.
- Counts do not measure market share, company quality, response time, capacity, project outcomes,
  or insurance-carrier relationships.

The methodology distinguishes provider statements, public Google Business identity/rating data,
IICRC Certified Firm registry matches, and eligible official state mold-credential matches. Source
classes have different scopes and must not be treated as interchangeable.

## Suggested citation

> RestoreRadar, “Restoration Industry Statistics from 550 Provider Records,” updated 2026-07-30,
> https://restoreradar.com/restoration-market-data/

Include the date you accessed the files and preserve the “not a census” limitation with comparisons.

## Updates and corrections

The canonical files are recomputed with each published RestoreRadar data refresh; there is no fixed
calendar schedule. This repository is a dated snapshot, so use the canonical report for the newest
version. Report suspected errors through https://restoreradar.com/contact/ or email
hello@restoreradar.com.

Publisher contact:

- RestoreRadar
- https://restoreradar.com/
- hello@restoreradar.com
- chris.howard@restoreradar.com
- (830) 465-2763
- (837) 330-9858

## Reuse

See [REUSE_TERMS.md](REUSE_TERMS.md). Attribution must link to the canonical report, not merely this
repository.
