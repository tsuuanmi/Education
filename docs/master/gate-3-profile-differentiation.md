# Gate 3 - Profile Differentiation / Amplification

## Purpose

This gate asks a different question from eligibility and funding:

> **Does the Master's make the applicant's existing diversity look like a coherent advantage?**

It does **not** ask which university is more prestigious, nor which programme is closest to one current domain.

The profile being amplified is:

```text
Mechatronics / physical systems
+ sensors / control
+ physiological signals at Earable
+ medical imaging at VinBigData
+ genomic data at GeneStory
+ scientific software / pipelines through DNA
```

The intended identity is a **systems-oriented Research Engineer for biological and healthcare data**.

## Current distribution across 103 Gate-1 Likely programmes

| Amplification band | Count |
| --- | ---: |
| Very-high | 19 |
| High | 72 |
| Medium-high | 3 |
| Medium | 9 |
| **Total** | **103** |

The canonical working table is `data/master/profile-differentiation.csv`.

These bands are **not a shortlist or ranking**. They describe programme architecture relative to the applicant's unusual profile.

## What "Very-high amplification" means

A Very-high programme usually does several things at once:

1. accepts Engineering as a normal starting background;
2. treats computation/software/systems as core rather than peripheral;
3. exposes the student to more than one biological/health-data modality;
4. has substantial thesis/research/project work;
5. allows domain expertise to be learned collaboratively instead of demanding a complete biology/CS undergraduate identity before entry.

Typical architectural examples already found include:

- computational bioengineering;
- bioinformatic / biological information engineering;
- broad BME research with informatics/imaging/signals/genomics;
- systems life sciences / information engineering applied to living systems;
- biomedical systems programmes explicitly designed for Mechatronics/engineering entrants.

## Why this gate is separate from research fit

A programme can be fascinating scientifically and still have weak differentiation.

Example:

```text
Pure CS degree
  -> excellent algorithms/software training
  -> but applicant competes against stronger formal CS preparation
  -> biological/hardware experience may be treated as peripheral
```

Conversely:

```text
Computational Bioengineering
  -> engineering is expected
  -> biological data is the application space
  -> software/modelling are central
  -> mixed prior experience becomes evidence of readiness
```

The second route can have greater applicant-specific value even if the first has a stronger generic CS brand.

## Cross-modality criterion

The profile has practical experience in three distinct modalities:

- physiological signals;
- medical imaging;
- genomic/sequencing data.

The goal is **not** to require every programme to cover all three.

Instead, cross-modality breadth is evidence that the degree teaches a reusable systems layer rather than a single data-specific workflow.

A programme can still score High with one biological modality if its methods are portable:

- statistical inference;
- modelling;
- scientific programming;
- workflow/data systems;
- ML with validation;
- HPC;
- reproducibility;
- research methods.

## Degree-label caution

### Bioinformatics / genomics

These can strongly amplify GeneStory and DNA, but later review must ensure the degree is not so narrow that post-Master identity becomes "genomics-only".

### Biomedical Engineering / Bioengineering

These often amplify Mechatronics well, but the selected lab matters enormously. A BME degree can be ideal if the path is data/systems/imaging/informatics and much weaker if it becomes materials/tissue/device-only.

### Health / Medical Informatics

These can map closely to healthcare-data systems, but some programmes lean toward enterprise IT / records management rather than scientific computation.

### Pure CS / Data Science

Keep only when the thesis/research ecosystem or funding is exceptional enough to compensate for weaker admission differentiation.

## Interaction with Gate 2

Profile amplification and funding must remain separate dimensions.

A programme can be:

- Very-high amplification + structurally funded;
- Very-high amplification + financially weak;
- Medium amplification + fully funded;
- High amplification + scholarship-dependent.

Only after both gates mature should the application portfolio be optimized.

## Next deep-audit

The first-pass table is intentionally architecture-driven. The next Profile Differentiation pass should deep-audit the **Very-high and ambiguous High programmes** at curriculum/lab level, especially where:

- a BME degree might be hardware/materials-heavy;
- Bioinformatics might become too gene-specific;
- Informatics might become too clinical-IT-heavy;
- a research programme's value depends almost entirely on one lab.

This will eventually feed the PI/research-environment gate without returning to a BCI-only supervisor search.


## Very-high frontier deep audit

The broad Very-high band has now been split into a strategic frontier that distinguishes **architecture-native** programmes from **methods-specialized** programmes and incorporates funding/timing constraints.

See `docs/master/amplification-frontier.md` and `data/master/amplification-frontier.csv`.

Current P0 cross-domain frontier:

- UNIST BME;
- HKUST MPhil Bioengineering / Biological Information Engineering;
- University of Toronto BME MASc;
- KAIST Bio and Brain Engineering;
- KAUST Bioengineering / Bioinformatics & Machine Learning;
- NAIST Computational Biology;
- UNSW MPhil BME as the deferred 2028 research branch.


## Fit guardrail

Gate 3 must use the canonical fit definition in `docs/master/program-fit-spec.md`.

A programme does not need to contain every prior modality. It can score strongly when it develops portable quantitative/computational methods, substantial research ownership, and preserves engineering identity and career option value.
