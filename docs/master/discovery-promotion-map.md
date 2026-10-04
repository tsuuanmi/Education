# Discovery Promotion Map

This file assigns stable canonical IDs to Discovery Phase 2.0 records **without yet mutating the old 78-record canonical universe**.

Why this intermediate step exists:

- the old Gate-1 snapshot remains internally consistent;
- merge/reframe records keep their existing IDs;
- genuinely new routes receive deterministic IDs now;
- the expanded Gate-1 pass can work against stable identifiers;
- canonical `opportunities.csv` and `eligibility.csv` can be replaced atomically after the expanded gate closes.

## ID policy

Existing conventions are preserved where they exist:

- `EU-<country>` for Europe;
- `AS-<country>` for Asia;
- `AU` for Australia.

New geography prefixes introduced for Discovery 2.0:

- `NA-CA`, `NA-US` - North America;
- `ME-SA`, `ME-AE`, `ME-IL` - Middle East;
- `OC-NZ` - New Zealand / Oceania;
- `AF-ZA` - South Africa;
- `LA-BR` - Brazil / Latin America.

IDs are identifiers, not rankings.

## Promotion rule

- `merge_exact` / `merge_reframe`: use the existing canonical ID.
- `new_opportunity`: use the proposed new ID.
- `new_replace_placeholder`: use a new ID and later mark the old placeholder superseded.

No shortlist semantics are encoded in the IDs.

## Next operation

Use `data/master/discovery-promotion-map.csv` together with the staging CSV to run the **expanded Gate 1**. Do not merge all new rows into the old canonical snapshot until formal-eligibility statuses have been assigned.
