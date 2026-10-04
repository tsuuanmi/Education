# Discovery Merge Audit

This audit prevents Discovery Phase 2.0 from inflating the canonical opportunity universe with duplicate degree records.

## Merge actions

- **merge_exact** - the same programme already exists in `opportunities.csv`; Discovery 2.0 adds richer framing/data only.
- **merge_reframe** - the staging record is a concentration, research focus, or methods framing inside an existing degree; merge the new evidence into that degree.
- **new_replace_placeholder** - a concrete actionable route has been found where the old universe only had a generic/non-actionable placeholder. Preserve provenance: add the concrete opportunity and later mark the placeholder superseded rather than silently rewriting history.
- **new_opportunity** - no equivalent canonical degree has been identified.

## Current counts

| Action | Count |
| --- | ---: |
| merge_exact | 5 |
| merge_reframe | 3 |
| new_replace_placeholder | 1 |
| new_opportunity | 83 |
| **Total staging records** | **92** |

Therefore the 92 staging records do **not** imply 92 new canonical opportunities.

At the current audit state:

- 5 are exact duplicates;
- 3 are existing degrees viewed through the new systems/biological-data lens;
- 1 is a concrete replacement for an old generic placeholder;
- the remaining 83 are candidate new opportunities.

## Verified merge examples

### HKUST Bioengineering

The 2027/28 official catalogue lists **Biological Information Engineering** as a research focus/concentration within the MPhil/PhD Bioengineering programme. It covers medical imaging and data-driven areas including health analytics, bioinformatics, protein structure, drug design and systems biology.

Action: merge into `AS-HK-002`.

### EPFL Life Sciences Engineering

Biological Data Science is a specialisation of the Life Sciences Engineering Master's, alongside Biomedical Engineering and other specialisations.

Action: merge into `EU-CH-002`; do not create a second EPFL degree row.

### UNSW MPhil Biomedical Engineering

Digital Medicine & Digital Biology is a research-area/lab framing for the existing MPhil Engineering - Biomedical Engineering opportunity.

Action: merge the broader computational/genomics interpretation into `AU-001`.

### University of Osaka

The old `AS-JP-003` was a generic, non-actionable English-Master placeholder. Discovery 2.0 found a concrete Bioinformatic Engineering / Information Science route. The Graduate School of Information Science and Technology is being reorganised in April 2027: the former Bioinformatic Engineering department is folded into the new Department of Information Science and Technology, while the graduate school continues 2027 Master's admissions and an English Information Technology Special Course.

Action: preserve a new concrete Osaka opportunity during canonical promotion and mark the old placeholder superseded. Do not treat the generic row as the same precise programme.

## Important rule

Same university does **not** mean duplicate.

Examples that must remain separate unless later evidence proves otherwise:

- NUS ECE Research vs NUS Biomedical Informatics vs NUS Precision Health;
- NTU Singapore EEE Research vs Biomedical Data Science;
- HKU ECE MPhil vs Computing & Data Science MPhil;
- UTokyo Bioengineering vs Computational Biology and Medical Sciences;
- SNU Bioengineering vs Bioinformatics;
- NTU Taiwan Smart Medicine vs Biomedical Electronics & Bioinformatics vs Biomedical Engineering.

The canonical universe should represent **application-distinct degrees/routes**, not universities.
