# Digital Phenotype-Based Mental Health Prediction and Derived Feature Contribution Analysis

> Longitudinal mental-health prediction from digital phenotype and EMA data, combined with feature-contribution analysis and a personalized monitoring prototype.

**Period:** May. 2025 - Jun. 2026  
**Progression:** Yongin Severance Hospital Digital Healthcare Hackathon → 23rd Avison Biomedical Symposium 2026  
**Recognition:** **Grand Prize**, Yongin Severance Hospital Digital Healthcare Hackathon  
**Core method:** LSTM  
**Targets:** PHQ-9 · GAD-7

---

## Overview

This project began as a digital-healthcare hackathon solution and was later developed into a research presentation on longitudinal mental-health prediction. Digital phenotype and repeated EMA records were organized as participant-level sequences so that changes in mental-health state could be modeled over time rather than as isolated point-in-time observations.

The research combined three components:

1. **LSTM-based PHQ-9 / GAD-7 prediction**
2. **Derived feature contribution analysis**
3. **Personalized monitoring and reporting prototype**

## Data structure

![Data structure](assets/figure-01-data-structure.svg)

The symposium-stage dataset included:

- **1,000 participants**: 700 general adults + 300 college students
- **42 model input features** after feature engineering
- Passive behavioral logs such as step count, distance, home-stay time, and sleep duration
- Active EMA variables such as mood, appetite, sleep feeling, general condition, and symptoms
- Profile variables including age, BMI, social relationships, and socioeconomic characteristics
- Target scores: **PHQ-9** and **GAD-7**

Daily records were ordered by date and modeled as longitudinal sequences.

## LSTM prediction

![Model results](assets/figure-02-model-results.svg)

| Outcome | Test R² |
|---|---:|
| PHQ-9 | **0.6312** |
| GAD-7 | **0.6159** |

The model outputs were framed as supportive monitoring signals rather than standalone clinical diagnoses.

## Derived feature contribution analysis

Beyond prediction, the study examined how engineered behavioral and contextual features contributed to the mental-health outcomes. This analysis was intended to make the longitudinal model more interpretable and to connect prediction results to meaningful behavioral patterns.

## Personalized monitoring prototype

![Personalized report](assets/figure-03-personalized-report.svg)

The prototype connected the prediction pipeline to daily input, trend visualization, and personalized reporting. This allowed the research concept to move from a model-only result toward a continuous digital-health monitoring workflow.

## Research progression

- **May 2025:** Developed the original digital phenotype / EMA mental-health prediction solution at the Yongin Severance Hospital Digital Healthcare Hackathon and received the **Grand Prize**.
- **Jun. 2026:** Presented the developed research at the **23rd Avison Biomedical Symposium 2026 · Digital Medicine in Mental Health**.

## My contribution

The hackathon team materials identify Junha Won as **team lead**, with responsibilities including:

- Machine-learning modeling
- Data preprocessing
- Overall project coordination
- Healthcare-service planning

The later symposium work extended the project into longitudinal prediction, contribution analysis, and research presentation.

## Public outputs

- [`outputs/hackathon-public-technical-excerpt.pdf`](outputs/hackathon-public-technical-excerpt.pdf) - public-safe excerpt of the hackathon-stage project.
- [`outputs/avison-symposium-public-excerpt.pdf`](outputs/avison-symposium-public-excerpt.pdf) - public-safe excerpt of the symposium-stage research presentation.
- [`outputs/grand-prize-award-verification.pdf`](outputs/grand-prize-award-verification.pdf) - verification note for the Grand Prize recognition.
- [`outputs/PROJECT_OUTPUTS.md`](outputs/PROJECT_OUTPUTS.md) - source provenance and public-release notes.

## Data & privacy

No participant-level mental-health records are redistributed. Figures in this repository are limited to presentation-level aggregates, diagrams, and public-safe prototype reconstructions.

---

**Junha Won** · Ajou University  
[Portfolio detail](https://juna0926.github.io/Portfolio/research/digital-phenotype.html) · [Portfolio](https://juna0926.github.io/Portfolio/) · [GitHub](https://github.com/Juna0926)
