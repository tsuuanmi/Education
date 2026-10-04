# Expanded Gate 2 - Funding Architecture Pass

## Scope

Expanded Gate 2 starts from all **115 Gate-1 Likely** opportunities.

This pass is **not a programme ranking**. It classifies financial architecture before profile differentiation or PI fit.

The central distinction is:

> **Funding architecture is not the same as net residual cost.**

A programme can guarantee a stipend yet still be financially difficult for an international student after tuition and living expenses.

## Preliminary distribution

| Gate-2 class | Count |
| --- | ---: |
| A - Structural funding | 19 |
| B - Strong competitive full/near-full route | 45 |
| C - Financially resilient / low tuition | 8 |
| D - High cost / scholarship-dependent | 26 |
| Deferred - Australia Awards 2028 | 10 |
| Audit needed | 7 |
| **Total Likely routes** | **115** |

The row-level working data is in `data/master/gate2-expanded-staging.csv`.

## Semantics

### A - Structural funding

Funding is closely connected to admission/research status, or broadly standard for admitted students.

Examples include research studentships, guaranteed department/supervisor packages, and universal graduate fellowships.

A does **not** automatically mean zero residual.

### B - Strong competitive

A credible full or near-full funding route exists, but it requires a separate scholarship competition, nomination, advisor decision, quota, or cycle-specific award.

### C - Financially resilient

Tuition is intrinsically low/no tuition or the public-fee structure limits downside. Living expenses may still be substantially self-funded.

### D - High cost

Sticker price and living costs are material, and no sufficiently robust full-funding route is currently established.

### Deferred - 2028

The route is financially attractive primarily through Australia Awards 2028. It should not be penalised as self-funded before the 2028 country profile is published.

### Audit needed

Current official funding or international-fee evidence is insufficient to classify responsibly.

## Why residual risk is separate

### Toronto BME MASc - strong structural + low residual risk

For 2026/27, eligible international MASc students in the funded cohort receive a guaranteed minimum package of CAD 44,500-46,499 at the base tier. The programme explicitly describes the package as comprising both programme fees and a living allowance.

This is qualitatively different from a nominal stipend that must first absorb a very high international tuition bill.

### Waterloo MASc - structural but residual risk remains

Engineering guarantees MASc funding of CAD 18,000/year, or CAD 36,000 over two years. International Master's Awards of Excellence can add CAD 2,500/term for selected students.

The funding is structural, but tuition is paid from the package, so this cannot yet be treated as near-zero personal cost.

### McGill BBME - structural but international tuition matters

All thesis Master's students, including international students, are guaranteed at least CAD 24,000/year for two years. McGill itself notes that higher stipends are encouraged for international/out-of-province students to offset higher tuition.

This is a funded research degree, but not automatically a financially safe one.

### Dalhousie BME MASc - known post-tuition floor

Dalhousie states that all graduate students in BME receive funding and that MASc students have a minimum guaranteed take-home of about CAD 16,000-17,000/year after tuition and fees in years 1-2. The school also explicitly warns that additional money may still be needed for living in Halifax.

This is a useful example of why the Gate records both funding architecture and residual risk.

## Very strong structural architectures

### KAUST

All admitted Master's students normally receive the KAUST Fellowship:

- full tuition and bench fees;
- housing;
- health insurance;
- relocation support;
- MS living stipend worth about USD 20,000/year.

This is one of the cleanest near-zero-residual structures in the universe.

### Weizmann

Full-time MSc students are entitled to a 24-month fellowship. The current regular MSc rate is NIS 7,000/month.

### Hong Kong MPhil routes

Research MPhil funding remains structurally attractive:

- CUHK Postgraduate Studentship: HKD 229,200/year in 2026/27 for qualified full-time research postgraduates;
- HKUST Postgraduate Studentship: HKD 229,620/year for MPhil/PhD, with up to two years for full-time MPhil in the 2027/28 prospectus;
- HKU PGS: HKD 19,135/month from September 2026 for eligible full-time MPhil/PhD students, subject to funding and annual renewal.

Tuition and realistic housing/living costs still need to be subtracted in the net-cost pass.

### Korea

- KAIST has broad tuition/stipend support and KGPS offers selected Master's students full tuition + KRW 1,000,000/month for four semesters.
- POSTECH's 2026 regular Master's TA/RA package totals KRW 1.85m/month, with KRW 966k/month identified as living allowance; actual amount can vary by lab.
- UNIST BME currently advertises full financial support for all BME students, including tuition waiver, KRW 7.68m/year and stipend.

## Strong but separately competitive

### Singapore research degrees

NUS Research Scholarship currently provides international Master's (Research) students:

- full tuition waiver;
- S$2,900/month;
- typical duration two years;
- no specific service bond;
- Graduate Assistantship duties.

Because scholarship selection is distinct from admission, NUS/NTU research routes are class B in the architecture pass even though the package is financially excellent when awarded.

### SNU

GSFS currently offers full tuition up to four semesters and at least KRW 500,000/month, but only a small number are selected and living-support duration varies by college/school.

### NAIST

The 2027 MEXT International Priority Graduate Program in Information Science has four Master's scholarship slots and offers:

- JPY 144,000/month;
- tuition and entrance-fee exemption;
- airfare;
- two-year Master's scholarship term.

This is a strong route but a limited-quota award, so B rather than A.

## Australia 2028 is deliberately separated

Current Australia Awards Vietnam benefits include:

- full academic fees;
- airfare;
- visa/medical costs;
- establishment allowance;
- ongoing living contribution;
- OSHC;
- supplementary academic support;
- completion travel;
- fieldwork support where eligible.

The user is comfortable with the two-year return-to-Vietnam obligation. Therefore Australia programmes are treated as **Deferred-2028**, not as D-high-cost, when Australia Awards is the intended funding route.

The exact 2028 country profile and eligible-course rules remain TBA.

## Next pass

Deep-audit the 19 A-structural routes first.

For each one, calculate or estimate:

```text
gross guaranteed funding
- mandatory tuition / university fees
- realistic living cost
= annual residual / surplus
```

Then subdivide A into:

- **A1 - near-zero or positive expected residual**
- **A2 - structurally funded but meaningful residual risk**
- **A3 - structural package exists but amount/net cost still unclear**

Only after that should the 45 B routes receive an equivalent scholarship-probability and net-cost audit.
