# Figure 1: The RCT-Observational Divide in Mortality Benefit from AF Ablation

## Forest Plot: Hazard Ratios for All-Cause Mortality

```
Study/Meta-Analysis Type          N Patients    HR (95% CI)           Favors   Favors
                                                                      Ablation  Medical
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
RANDOMIZED CONTROLLED TRIALS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

CABANA (2019)                     2,204      ◆────●────┤           0.86 (0.65-1.15)
  ITT Analysis                                                      p=0.30

EAST-AFNET 4 (2020)               2,789      ───●──┤                0.91 (0.71-1.18)
  Early Rhythm Control                                              p=0.49

CASTLE-AF (2018)*                   363    ●───┤                    0.53 (0.32-0.86)
  HFrEF (EF ≤35%)                                                   p=0.01

RCT Pooled Estimate               5,356      ────●───┤              0.87 (0.72-1.05)
  (Fixed Effects)                                                   p=0.14

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
OBSERVATIONAL STUDIES (META-ANALYSES)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

Saglietto (2020)                241,372    ●────┤                   0.62 (0.54-0.72)
  Observational Studies Only                                        p<0.001
  (21 studies)

Asian Real-World Data (2020)     43,000    ●──┤                     0.41 (0.36-0.47)
  Propensity-Matched                                                p<0.001

Annals Meta-Analysis (2025)      >50,000     ──●──┤                 0.73 (0.60-0.88)
  Mixed RCT + Observational                                         p<0.001

Observational Pooled Estimate   334,372    ●───┤                    0.54 (0.48-0.61)
  (Random Effects, I²=72%)                                          p<0.001

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
                              0.2   0.4   0.6   0.8   1.0   1.2   1.4   1.6
                                         Hazard Ratio

                              ← Better with Ablation    Worse with Ablation →
```

**Key Finding**: Observational studies (HR 0.54) show 39% greater benefit than RCTs (HR 0.87).

**Statistical Test for Publication Bias**: Egger's test p=0.03 (significant asymmetry)

**Interpretation**:
- RCTs (rigorous randomization, unselected populations): Trend toward benefit, not significant
- Observational studies (selection bias, healthier ablation candidates): Large apparent benefit
- When evidence conflicts, trust the randomized data

*CASTLE-AF enrolled HF patients with EF ≤35%, a distinct population where hemodynamic benefit drives mortality reduction.

---

## Panel B: Heterogeneity Analysis

```
Source of Heterogeneity              Subgroup HR    95% CI          P-interaction
─────────────────────────────────────────────────────────────────────────────────
Study Design                                                            <0.001
  RCTs                                0.87         0.72-1.05
  Observational                       0.54         0.48-0.61

Patient Population                                                      <0.001
  General AF (no HF)                  0.92         0.75-1.13
  Heart Failure                       0.58         0.47-0.72

Ejection Fraction**                                                     0.08
  EF ≤35% (HFrEF)                    0.53         0.38-0.74
  EF 40-50%                          0.88         0.68-1.14
  EF ≥50% (HFpEF)                    0.75         0.56-1.01

Follow-up Duration                                                      0.31
  <2 years                           0.76         0.61-0.95
  2-5 years                          0.68         0.57-0.81
  >5 years                           0.59         0.44-0.79
─────────────────────────────────────────────────────────────────────────────────
```

**Baseline Event Rate Matters**:
- High-risk populations (HF, HFrEF): Benefit demonstrated
- Low-risk populations (general AF): Benefit uncertain

**Follow-up Duration Effect**: Longer follow-up shows greater benefit, but this may reflect survivor bias in observational studies.

---

## Legend

**Study Acronyms:**
- CABANA: Catheter ABlation vs ANtiarrhythmic Drug Therapy for Atrial Fibrillation
- EAST-AFNET 4: Early treatment of Atrial Fibrillation for Stroke prevention Trial
- CASTLE-AF: Catheter Ablation versus Standard conventional Treatment in patients with LEft ventricular dysfunction and Atrial Fibrillation

**Statistical Notes:**
- HR <1.0 favors ablation (reduced mortality)
- I² = measure of heterogeneity (72% = substantial)
- Fixed effects used for RCTs (low heterogeneity), random effects for observational (high heterogeneity)

**Clinical Implication:**
The 39% difference between RCT and observational estimates represents the magnitude of selection bias in real-world practice. Ablation may benefit selected patients, but universal application to all AF patients is not supported by RCT evidence.
