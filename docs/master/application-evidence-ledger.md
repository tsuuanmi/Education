# Application Evidence Ledger

## Purpose

This ledger separates **facts we can safely use now** from facts that still need exact citations or documentary evidence before they appear in a final application CV.

Status labels:

- **public-verified** - independently verifiable from a public source;
- **user-confirmed** - explicitly provided by the applicant, but exact documentary/public citation may still be pending;
- **context-verified** - supported by an applicant-controlled public repository or existing canonical project documentation;
- **pending-exact-evidence** - known to exist, but exact title/date/citation is still needed;
- **do-not-claim-yet** - organization-level evidence exists, but personal attribution is not yet proven.

## Academic background

| Claim | Status | Safe wording now | Evidence still needed |
| --- | --- | --- | --- |
| BEng / Honors Program in Mechatronics Engineering, UET-VNU | user-confirmed | Use in CV | official transcript / degree scan for application |
| Graduated June 2023 | user-confirmed | Use in CV | official graduation evidence if requested |
| GPA 3.47 / 4.0 | user-confirmed | Use in CV | transcript |
| Distinction | user-confirmed | Use in CV | transcript / degree classification |
| Undergraduate thesis: **A STUDY ON EMOTION CLASSIFICATION USING EEG SIGNALS** | user-confirmed | Use exact title | thesis cover / institutional record if available |
| Thesis grade A+ | user-confirmed | Use in CV | transcript |
| Relevant quantitative / control / electronics / programming coursework | user-confirmed / transcript-derived | Use selectively | transcript + syllabus for formal-credit audits |

## Research / awards

| Claim | Status | Safe wording now | Evidence still needed |
| --- | --- | --- | --- |
| Undergraduate scientific research award | user-confirmed | "Undergraduate scientific research award" only | exact award name, year, project title, level/rank |
| Scholarships for two semesters | user-confirmed | "Academic scholarship, two semesters" only | scholarship name, semester/year, selection basis |
| Second Prize, Data For Life 2025 | user-confirmed + organization-public-verified | "Second Prize, Data For Life 2025 - GeneStory / Intron team" | applicant-specific certificate or team roster if available |
| Public genomics research outputs at GeneStory | user-confirmed | Do not list unnamed publications yet | exact paper title, author list, venue, year, DOI/URL, applicant author position |
| Public GeneStory scientific context | public-verified | Use only as organization context | never imply personal authorship without citation |

## Professional experience

### GeneStory

**Known and safe**

- current R&D role in genomics - user-confirmed;
- sustained work with genomic / sequencing-derived biological data - user-confirmed;
- scientific-software / pipeline development - user-confirmed;
- public research outputs exist - user-confirmed;
- GeneStory publicly operates in genomic / precision-health research and maintains a scientific-publication base - public organization evidence.

**Pending**

- exact employment start date;
- exact official job title;
- exact responsibilities safe to disclose;
- exact personally authored public research;
- exact contribution to Data For Life / Intron if used beyond award line;
- exact quantitative scale claims safe to disclose.

### Earable Neuroscience

**Known and safe**

- prior R&D experience in wearable neurotechnology;
- physiological / neural sensing;
- hardware / sensor awareness;
- raw-signal / signal-processing exposure;
- AI / product-oriented R&D.

**Pending**

- exact job title;
- exact start/end dates;
- exact product/project names safe to disclose;
- any patents/publications/public demos attributable to the applicant.

### VinBigData

**Known and safe**

- internship / prior experience in medical imaging;
- exposure to image-based healthcare data and AI.

**Pending**

- exact internship title;
- exact dates;
- exact project / task description safe to disclose;
- public artifact if any.

## Open-source scientific software

### DNA

**Status: context-verified / public repository**

Repository: `github.com/tsuuanmi/DNA`

Safe current description:

> Creator and primary developer of DNA, an open-source deterministic Rust platform for auditable DNA analysis. The current implementation processes Sanger ABIF chromatogram evidence, performs signal-derived base re-calling, quality handling, reference alignment and primary-sequence variant reporting through typed Rust results and versioned JSON contracts.

High-value evidence from the current public README:

- Rust-first scientific-software platform;
- explicit separation of measurement evidence from interpretation;
- ABIF / Sanger signal handling;
- deterministic variant analysis;
- typed failures and versioned schemas;
- scientific-validation / release contracts;
- extensive CI / testing / reproducibility controls;
- architecture designed to extend beyond Sanger / mtDNA.

This is one of the strongest pieces of **direct individual evidence** in the application because authorship / ownership is publicly attributable through the applicant-controlled repository.

## Organization-level public context that must not be over-attributed

### GeneStory / Data For Life

Public GeneStory materials verify:

- the Intron team won **Second Prize, Data For Life 2025**;
- Intron is positioned as an AI platform built around genomic data for preventive / precision health;
- GeneStory publicly maintains genomics research and Vietnamese-population genomic resources.

This evidence corroborates the environment in which the applicant works.

It does **not**, by itself, prove:

- the applicant's exact Intron contribution;
- authorship of any particular GeneStory paper;
- ownership of organization-wide datasets or algorithms.

Use applicant-specific evidence for those claims.

## Evidence collection checklist

Highest priority before producing the final research CV:

1. exact GeneStory official job title + start date;
2. exact Earable job title + start/end dates;
3. exact VinBigData internship title + dates;
4. exact publication list attributable to applicant;
5. undergraduate research award exact title/year/project;
6. scholarship names + semesters/years;
7. Data For Life certificate/team evidence if available;
8. exact public GitHub / publication profile links to put in CV header;
9. any ORCID / Google Scholar link;
10. disclosure-safe quantitative impact metrics.

## Claim-strength rule

Use this ordering in the final CV:

```text
exact personal public evidence
    >
exact user-confirmed documentary fact
    >
carefully scoped role description
    >
organization-level context
```

Never reverse that order for the sake of making the CV look stronger.
