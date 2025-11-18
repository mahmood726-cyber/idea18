# Figure 2: Sinus Rhythm Mediation and the Procedural Success Problem

## Panel A: Mediation Analysis (Crawford et al. 2024)

### How Much of the Treatment Effect is Explained by Achieving Sinus Rhythm?

```
                        EAST-AFNET 4 Trial
                    (Early Rhythm Control vs Usual Care)

┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   RANDOMIZATION TO RHYTHM CONTROL                                   │
│                    │                                                │
│                    │                                                │
│                    ├─────────────────────────────────────────────┐  │
│                    │                                             │  │
│                    ▼                                             ▼  │
│        ┌───────────────────────┐                    ┌────────────────┐
│        │  SINUS RHYTHM         │ 81% of benefit    │  STILL IN AF   │
│        │  at 12 months         │ mediated          │  at 12 months  │
│        │  (60% of patients)    │ ◄─────────────    │  (40% of pts)  │
│        └───────────────────────┘                    └────────────────┘
│                    │                                             │  │
│                    │                                             │  │
│                    ▼                                             ▼  │
│        ┌───────────────────────┐                    ┌────────────────┐
│        │  MORTALITY REDUCTION  │                    │  NO BENEFIT    │
│        │  HR 0.71              │                    │  HR 0.94       │
│        │  (95% CI 0.55-0.92)   │                    │  (0.65-1.67)   │
│        └───────────────────────┘                    └────────────────┘
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘

KEY FINDING: 81% of treatment effect mediated by sinus rhythm at 12 months
             (95% CI: 68-94%, p<0.001)

IMPLICATION: Rhythm IS prognostic, but only when ACHIEVED and MAINTAINED
```

---

## Panel B: The Success Problem - Why Population Benefit is Diluted

### CABANA Trial: 5-Year AF Recurrence Rates

```
                    ABLATION ARM                    DRUG THERAPY ARM
                    (n=1,108)                       (n=1,096)

    100%   ┌─────────────┐                         ┌─────────────┐
           │             │                         │             │
           │   Success   │                         │             │
     80%   │             │                         │             │
           │   AF-Free   │                         │             │
           │             │                         │ Recurrent AF│
     60%   │             │                         │             │
           │   50.1%     │                         │   30.5%     │
           │             │                         │ AF-Free     │
     40%   │             │                         │             │
           │             │                         │             │
           ├─────────────┤                         ├─────────────┤
     20%   │ Recurrent   │                         │             │
           │    AF       │                         │   69.5%     │
           │   49.9%     │                         │             │
      0%   └─────────────┘                         └─────────────┘

     Absolute Difference in AF Recurrence: 19.6% (95% CI: 15.5-23.7%)
     Relative Risk Reduction: 28% (HR 0.52, p<0.001)

     BUT:
     Absolute Difference in MORTALITY: 0.9% (6.1% vs 5.2%, p=0.38)
     Mortality Hazard Ratio: 0.85 (95% CI: 0.60-1.21, NOT SIGNIFICANT)
```

**The Disconnect**: Large AF reduction (28% RRR) ≠ Mortality reduction

---

## Panel C: Mathematical Model - Why 50% Success Yields 0.86 HR

### Predicted Population-Level Effect

```
Assumptions (from Crawford 2024 mediation analysis):
─────────────────────────────────────────────────────
1. Sinus rhythm reduces mortality by 30% → HR 0.70
2. Ablation achieves sinus rhythm in 50-60% of patients
3. Failed ablation provides no benefit → HR 1.0

Mathematical Expectation:
─────────────────────────────────────────────────────

Population HR = (HR_success × P_success) + (HR_failure × P_failure)

Scenario A: 50% Success Rate
  = (0.70 × 0.50) + (1.0 × 0.50)
  = 0.35 + 0.50
  = 0.85 ◄─── Matches CABANA ITT (HR 0.86)

Scenario B: 60% Success Rate
  = (0.70 × 0.60) + (1.0 × 0.40)
  = 0.42 + 0.40
  = 0.82

Scenario C: 100% Success Rate (Hypothetical Perfect Ablation)
  = (0.70 × 1.0) + (1.0 × 0)
  = 0.70 ◄─── Would be clinically significant!


┌──────────────────────────────────────────────────────────────────┐
│                                                                  │
│  The Problem: Ablation is an IMPERFECT means to VALID end       │
│                                                                  │
│  • Sinus rhythm IS prognostic (Crawford: 81% mediation)         │
│  • Ablation achieves it in only 50-60% (CABANA: 50% at 5y)     │
│  • Result: Population benefit is DILUTED, not ABSENT            │
│                                                                  │
└──────────────────────────────────────────────────────────────────┘
```

---

## Panel D: Number Needed to Treat by Population and Indication

```
Population & Indication                 NNT    Evidence Quality    Recommendation
─────────────────────────────────────────────────────────────────────────────────

SYMPTOMATIC BENEFIT
  Quality of Life Improvement           3-4    High (CABANA QoL)   Class I
  AF Burden Reduction                   5-6    High (Multiple)     Class I

PROGNOSTIC BENEFIT
  HFrEF (EF ≤35%)                       7      High (CASTLE-AF)    Class I
    • Mechanism: Prevent tachy-CMP

  Symptomatic HF (CABANA subset)        14     Moderate (Subgrp)   Class IIa
    • Mortality HR 0.57 (0.33-0.96)

  General AF Population                 ∞      Low (CABANA ITT)    Not Proven
    • Mortality HR 0.86 (0.65-1.15)
    • p=0.30 (NOT significant)

STROKE PREVENTION ALONE                 ∞      Very Low            Contraindicated
    • CABANA stroke HR 0.50 (0.14-1.85)        (Wide CI)          (Continue OAC)
    • Underpowered, non-significant

─────────────────────────────────────────────────────────────────────────────────

Number Needed to HARM (Procedural Complications)
  Major Complications (CABANA)          26     High
    • Includes: Tamponade, stroke, vascular injury
    • Early stroke risk: RR 6.81 (≤30 days)

─────────────────────────────────────────────────────────────────────────────────
```

**Clinical Decision Rule**:

```
Should patient undergo ablation?
└─ YES if:
    ├─ Symptomatic AF despite medical therapy (NNT 3-4 for QoL)
    │   AND
    │   Patient understands:
    │   • Goal is symptom relief, not stroke prevention
    │   • Anticoagulation continues regardless
    │   • 50% chance of AF recurrence at 5 years
    │
    └─ OR: Heart failure (NNT 7-14 for mortality)
        ├─ HFrEF (EF ≤35%): Strong evidence
        └─ Symptomatic HFpEF: Moderate evidence

└─ NO if:
    ├─ Asymptomatic or minimally symptomatic
    ├─ Seeking to stop anticoagulation
    ├─ Unrealistic expectations of "cure"
    └─ High procedural risk (NNH <26)
```

---

## Legend and Interpretations

**Mediation Analysis** (Panel A):
- Tests whether sinus rhythm is the mechanism by which treatment reduces mortality
- 81% mediation means sinus rhythm explains most (but not all) benefit
- Remaining 19% may be due to better medical management in rhythm control arm

**Success Problem** (Panel B-C):
- Ablation reduces AF burden significantly (surrogate success)
- But only 50% maintain sinus rhythm long-term (procedural limitation)
- This incomplete success dilutes population-level mortality benefit
- Mathematical model predicts CABANA result with 50% success rate

**NNT Framework** (Panel D):
- Symptomatic benefit: Small NNT (3-4), well-established
- HF prognostic benefit: Small-moderate NNT (7-14), proven in subgroups
- General population prognosis: Very large NNT (∞), not demonstrated

**The Rhythm Control Paradox Resolved**:
Rhythm control works (when achieved), but ablation is an imperfect means to achieve it. The procedure should be positioned for symptom control and HF-specific mortality benefit, not universal stroke prevention.

---

**Data Sources**:
- Crawford TC, et al. J Cardiovasc Electrophysiol. 2024;35(1):9-15.
- Packer DL, et al. JAMA. 2019;321(13):1261-1274.
- Kirchhof P, et al. N Engl J Med. 2020;383(14):1305-1316.
- Marrouche NF, et al. N Engl J Med. 2018;378(5):417-427.
