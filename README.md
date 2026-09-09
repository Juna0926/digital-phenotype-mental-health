# Digital Phenotype-Based Mental Health Prediction and Derived Feature Contribution Analysis

> Longitudinal PHQ-9 / GAD-7 prediction from digital phenotype and EMA data, followed by feature-contribution analysis and a personalized monitoring prototype.

**Period:** May. 2025 - Jun. 2026  
**Progression:** Yongin Severance Hospital Digital Healthcare Hackathon → 23rd Avison Biomedical Symposium 2026  
**Recognition:** **Grand Prize**, Yongin Severance Hospital Digital Healthcare Hackathon  
**Core method:** LSTM  
**Targets:** PHQ-9 · GAD-7

---

## Overview

This project began at the **Yongin Severance Hospital Digital Healthcare Hackathon** and was later developed into a longitudinal mental-health research presentation.

Digital phenotype and repeated EMA records were organized as **participant-level longitudinal sequences** so that changes in mental-health state could be modeled over time rather than as isolated observations.

The final research framework connected three components:

1. **LSTM-based PHQ-9 / GAD-7 prediction**
2. **Derived feature contribution analysis**
3. **Personalized monitoring and reporting prototype**

## Portfolio-aligned main figure

![Digital phenotype mental-health prediction analysis](https://raw.githubusercontent.com/Juna0926/Portfolio/main/assets/media/research-digital-health.webp)

*Representative figure synchronized with the current Portfolio detail page, showing the LSTM-based mental-health prediction and derived-feature analysis framing.*

## Longitudinal data framework

![Data structure](assets/figure-01-data-structure.svg)

The symposium-stage dataset included:

- **1,000 participants**: 700 general adults + 300 college students
- **42 model input features** after feature engineering
- passive behavioral logs such as step count, distance, home-stay time, and sleep duration
- active EMA variables such as mood, appetite, sleep feeling, general condition, and symptoms
- profile variables including age, BMI, social relationships, and socioeconomic characteristics
- target scores: **PHQ-9** and **GAD-7**

Daily records were ordered by date and modeled as longitudinal sequences.

## Prediction model

![Model results](assets/figure-02-model-results.svg)

| Outcome | Test R² |
|---|---:|
| PHQ-9 | **0.6312** |
| GAD-7 | **0.6159** |

The LSTM framework achieved test R² values of **0.6312 for PHQ-9** and **0.6159 for GAD-7**.

These outputs were framed as **supportive monitoring signals**, not standalone clinical diagnoses.

## Derived feature contribution analysis

Beyond prediction, the study examined how engineered behavioral and contextual features contributed to the mental-health outcomes. The goal was to connect model output to interpretable behavioral patterns instead of presenting prediction accuracy alone.

## Personalized monitoring prototype

![Personalized report](assets/figure-03-personalized-report.svg)

Prediction results were connected to a prototype for **continuous mental-health assessment**, including daily input, trend visualization, and personalized reporting.

This step translated the modeling pipeline from a prediction-only result into a user-facing digital-health monitoring workflow.

## Research progression

- **May 2025:** Developed the original digital phenotype / EMA mental-health prediction solution at the Yongin Severance Hospital Digital Healthcare Hackathon and received the **Grand Prize**.
- **Jun. 2026:** Presented the developed research at the **23rd Avison Biomedical Symposium 2026 · Digital Medicine in Mental Health**.

## Why this mattered

This project established the research direction that later led to my current BRIGHTEN study: treating mental health as a **longitudinal monitoring problem** and asking how everyday behavioral data can be transformed into clinically meaningful change signals.

## My contribution

The hackathon team materials identify Junha Won as **team lead**, with responsibilities including:

- Machine-learning modeling
- Data preprocessing
- Overall project coordination
- Healthcare-service planning

The later symposium work extended the project into longitudinal prediction, contribution analysis, and research presentation.

## Public outputs

- [`outputs/hackathon-public-technical-excerpt.pdf`](outputs/hackathon-public-technical-excerpt.pdf) — public-safe excerpt of the hackathon-stage project.
- [`outputs/avison-symposium-public-excerpt.pdf`](outputs/avison-symposium-public-excerpt.pdf) — public-safe excerpt of the symposium-stage research presentation.
- [`outputs/grand-prize-award-verification.pdf`](outputs/grand-prize-award-verification.pdf) — verification note for the Grand Prize recognition.
- [`outputs/PROJECT_OUTPUTS.md`](outputs/PROJECT_OUTPUTS.md) — source provenance and public-release notes.

## Data & privacy

No participant-level mental-health records are redistributed. Public materials are limited to presentation-level aggregates, diagrams, and public-safe prototype reconstructions.

---

**Junha Won** · Ajou University  
[Portfolio detail](https://juna0926.github.io/Portfolio/research/digital-phenotype.html) · [Portfolio](https://juna0926.github.io/Portfolio/) · [GitHub](https://github.com/Juna0926)