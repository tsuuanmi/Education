# Gate 2 - Funding and Net Personal Cost (Expanded Universe)

## Status

Expanded Gate 2 now starts from the **115 Gate-1 Likely programmes**.

This document replaces the pre-expansion shortlist-centric funding view. There is **no core shortlist at this stage**.

Funding is evaluated by architecture, not by whether a programme advertises a scholarship.

## Funding architecture

| Architecture | Count | Meaning |
| --- | ---: | --- |
| Admission-linked full | 3 | Funding is effectively part of funded admission for the relevant programme population |
| Admission-linked research studentship | 4 | Research studentship is closely tied to research admission, though tuition/living residual remains |
| Guaranteed research package | 4 | A minimum package is guaranteed during normal research candidature |
| Research package with offer | 2 | Admission/supervisor offer includes funding, amount may vary |
| Research-funded conditional | 6 | TA/RA/supervisor support is normal/available but amount or automaticity varies |
| Competitive full internal | 5 | University scholarship can fully fund study but is a separate selection layer |
| Full external competitive | 17 | AAS/EMJM/Vingroup-like external full-funding route |
| Full external limited | 1 | Fully funded external route with a small fixed quota |
| Low-cost self-fund | 4 | Tuition is structurally low/no tuition; living remains self-funded |
| Tuition-scholarship only | 9 | Tuition may be waived/reduced, but living remains exposed |
| High-cost scholarship-dependent | 8 | Financially unattractive unless a major award is won |
| Competitive scholarship route | 37 | Scholarship can materially change economics; exact route needs audit |
| Weak / unknown | 15 | Current evidence is insufficient |

The canonical first-pass table is `data/master/funding-expanded.csv`.

## Critical distinction: admission funding vs scholarship funding

A programme can be "fully funded" in two very different senses.

### Funding is structurally linked to admission

Examples:

- **KAUST**: the fellowship covers tuition/bench fees, housing, insurance, relocation and an MS stipend of about USD 20,000/year for admitted students unless external sponsorship changes the arrangement.
- **Weizmann**: full-time MSc students receive a 24-month fellowship; current regular rate is NIS 7,000/month and tuition is not charged.
- **UNIST BME**: the department advertises full financial support for all BME graduate students.
- **Toronto BME MASc**: a minimum international MASc package is published for years 1-2.
- **Dalhousie BME MASc**: all graduate students are funded and a minimum post-fee take-home range is published.

These should generally be more financially robust than programmes where admission and scholarship decisions are separate.

### Full package exists, but scholarship selection is separate

Examples:

- **NUS Research Scholarship**: full tuition + S$2,900/month for international Master's (Research), but the scholarship is competitive and should not be assumed from admission.
- **NTU Research Scholarship**: similarly strong when awarded, but remains a scholarship layer.
- **Australia Awards**: full fees + living contribution + travel + OSHC when awarded; 2028 is strategically important but the 2028 call is not yet published.
- **Erasmus Mundus**: excellent package if selected, but scholarship competition is very high.

This distinction matters more than nominal scholarship size.

## Canada: funding is strong but not uniform

The new discovery pass materially improves Canada's financial position.

### University of Toronto BME MASc

For 2026/27, the published international MASc minimum stipend total starts around **CAD 44,500-46,499** depending on award tier and rises with larger awards. This is a strong admission-linked research package, but exact net personal exposure still depends on international tuition/fees and Toronto living costs.

### Waterloo BME MASc

Waterloo guarantees **CAD 18,000/year for two years** to full-time MASc students. That money is used toward tuition first; the university explicitly warns that it may not cover living expenses, especially for international students. Therefore Waterloo is **funded**, but not automatically financially safe.

### McMaster BME MASc

Full-time MASc students receive department/supervisor funding for 24 months. The current public page does not state a single package amount, so offer-level economics still need audit.

### Guelph Bioinformatics MSc

A funding package is included with the thesis offer, but the package varies by the supervisor's home department. This makes PI choice part of financial due diligence.

### Dalhousie BME MASc

All graduate students are funded; current guaranteed post-tuition/fee take-home is about **CAD 16,000-17,000/year** in years 1-2. This is useful but should be checked against Halifax living costs.

Canada therefore deserves its own funding sub-model rather than one generic "funded research Master" label.

## Australia 2028 is now a strategic full-funding branch

The current Australia Awards structure covers:

- full academic fees;
- economy travel;
- visa-related costs;
- establishment allowance;
- regular contribution to living expenses;
- OSHC;
- supplementary academic support;
- fieldwork support for eligible research/coursework programmes.

Current Vietnam rules also require at least **two years back in Vietnam after completion**.

For this applicant, that obligation is acceptable in principle because returning to Vietnam can support continued healthcare/genomics R&D, scientific software, publications, and collaboration with an existing Australia-linked company network.

However, **2028 terms are still TBA**. Every Australia programme in the table should be interpreted as:

> financially strong **if AAS 2028 funds that course and the scholarship is won**.

It is not structural programme funding.

## High-value new funding discoveries

### KAUST Bioengineering - Bioinformatics & ML

This is one of the strongest funding structures in the universe: full tuition/bench fees, housing, insurance, relocation, and MS stipend. Funding and profile-amplification are both strong enough that this programme deserves later PI-level audit.

### Weizmann Computational & Systems Biology

No tuition + NIS 7,000/month for 24 months. The financial architecture is excellent. The later question is profile differentiation: whether a Life Sciences degree amplifies or dilutes the engineering identity.

### UNIST BME

The department states full financial support for all BME graduate students, including tuition waiver, KRW 7,680,000/year support and stipend. Exact international MS offer structure still needs confirmation, but this is much stronger than the earlier generic "scholarship possible" label.

### NAIST Computational Biology

The 2027 MEXT International Priority Graduate Program in Information Science has **four Master's scholarships** with tuition/entrance exemption, JPY 144,000/month and airfare. Financial upside is excellent, but quota makes it a limited competitive route rather than structural admission funding.

## Funding decision rule going forward

Gate 2 should eventually assign each Likely programme a conditional residual-cost scenario:

```text
tuition
- admission-linked funding
- competitive scholarship (probability kept separate)
+ living
+ mandatory fees / insurance
= expected personal exposure
```

Do not collapse:

- guaranteed funding;
- common-but-variable research funding;
- competitive scholarship;
- tuition-only waiver;

into one label called "funded".

## Next deep-audit wave

The next funding pass should focus on unresolved programmes with high **Amplification Principle** value:

1. Canada: UBC, UAlberta BME, uOttawa/Carleton BME;
2. Korea/Japan: UNIST exact package, POSTECH 2027 package, Hokkaido/Kyushu/Kyutech funding;
3. Taiwan: NTU/NTHU/NYCU scholarship residual cost;
4. Europe: Bern, TU Graz, Spain Health Data Science, Italy computational/bioengineering routes;
5. Australia: map which 2028 routes are likely AAS-compatible once the 2028 country profile is published.

Profile Differentiation should begin only after this financial architecture pass is sufficiently mature.


## Deep-audit wave 2 - Canada, Korea, Taiwan, and low-cost Europe

### University of Alberta BME MSc

The thesis-based MSc is materially stronger financially than the first-pass table suggested.

The department states that applicants need a supervisor willing to fund them before applying and publishes a **CAD 25,000 minimum annual funding** level for full-time thesis students. The graduate manual also states that thesis students must be funded throughout the programme, with the supervisor responsible for the stipend.

This moves UAlberta BME from weak/unknown to a **guaranteed research package**. The remaining question is whether CAD 25k leaves enough after international tuition and Edmonton living costs.

### POSTECH

The official 2026 regular Master's TA/RA package is now encoded precisely:

- KRW 884,000/month tuition component;
- KRW 966,000/month living component;
- KRW 1.85m/month total.

The university explicitly says actual amounts vary by lab and advisors may provide additional support.

Therefore POSTECH remains **research-funded conditional**, not admission-guaranteed in the same sense as KAUST.

### Taiwan funding is stronger than a generic "scholarship possible" label, but still award-dependent

**NTHU**

Current international-student scholarship:

- Category A: full tuition + credit-fee waiver **plus NT$5,000/month** for Master's;
- Category B: full tuition + credit-fee waiver only.

The award is applied for with admission and can continue for the Master's award period subject to rules.

**NTU Taiwan**

The current Outstanding International Graduate Student Scholarship provides a tuition waiver capped around **NT$65,000** and **NT$8,000/month** for Master's under current university materials. Fees such as insurance/accommodation remain outside the waiver.

**NYCU**

The international scholarship is more flexible and potentially stronger. Current materials show Master's awards of up to **NT$22,000/month and/or tuition waiver**; award plans can instead charge local tuition or provide stipend-only support.

Taiwan should therefore be modelled as several conditional scenarios, not a single funding package.

### TU Graz BME

TU Graz is now confirmed as a genuine low-cost hedge:

- non-EU tuition: **€726.72/semester**;
- student-union fee: €26.20/semester.

The university cites average Austrian student spending of roughly **€1,300/month** in 2025, so living — not tuition — is the main financial exposure.

### URV-led Health Data Science

For non-EU students the current price is **€46.11/ECTS**, plus a first-time €218.15 foreign-degree academic tax and other general fees. Because the degree is online, the relevant financial scenario may allow remaining in Vietnam rather than paying European living costs.

This makes it economically unusual: low tuition and potentially near-zero relocation exposure, but the Profile Differentiation / research-network gate must later decide whether online delivery gives enough value.

### University of Bern BME

From Fall 2026 a typical non-Swiss student without prior Swiss residence pays:

- CHF 850 regular tuition;
- CHF 1,700 additional non-Swiss fee;
- total **CHF 2,550/semester**, plus semester fees.

Tuition is manageable relative to many UK/US programmes, but Swiss living costs remain the dominant risk and no structural Master's stipend has been identified.

## Updated Gate-2 interpretation

The funding architecture is becoming more informative than geography:

```text
Admission-linked / guaranteed research funding
  -> strongest financial robustness

Research package tied to supervisor/offer
  -> strong, but exact net package matters

Competitive full scholarship
  -> excellent if won; probability separate

Low public tuition
  -> useful hedge; living-cost exposure remains

Tuition-only / high-cost scholarship-dependent
  -> weak unless profile fit is exceptional
```

The next unresolved financial questions with highest information value are now:

1. UBC Bioinformatics current MSc package;
2. uOttawa/Carleton BME MASc funding;
3. exact 2027 UNIST stipend composition;
4. Japanese non-MEXT routes (Hokkaido, Kyushu, Kyutech);
5. Italy need/merit routes under the expanded systems-bio scope.
