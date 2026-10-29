# Remaining addable content (not publications)

Compared Fall 2026 lab workbooks in `assets/pubulication/` against the local site. **Publications from those sheets are already on the Publications tab** (23 items). This file lists what is still missing.

Sources: ANL, NLR, PNNL, SNL, and ORNL/Allu workbooks. The blank `ROVI EXTERNAL FALL 2026 .xlsx` template is ignored.

---

## Talks

Already on Talks: IEEE EESAT 2026 (ORNL); DOD Energy and Power 2025 (ANL); LDES Consortium 2025 and SEPA 2024 (SNL); AABC 2024 and IEEE ITEC 2024 (ANL); DOE CTIC 2024 (ORNL); 2023 DOE OE overview and Li-ion requirements; 2021 Industry Roundtable.

**Never use** the May 2026 ORNL DataHub news/briefing (see Do not use).

### Recommended next

| Year | Venue | Title | Lab | Notes |
|---|---|---|---|---|
| 2026 | SciFM, University of Chicago, May 27–29 | Scaling Battery Intelligence: A Universal Foundation Model for Advanced State-of-Health Prognostics | ANL | V. Sampath, S. J. Babinec, N. H. Paulson |
| 2026 | ECS 249, Seattle, May 24–28 | Adaptive Battery State and Life Estimation Using a Hierarchical Kalman Filtering Architecture | ANL / NLR | Same talk in both workbooks; list once. C. Randall, P. Gasper, K. Smith et al. |
| 2026 | ECS 249, Seattle | Near Real-Time Diagnosis and Prognosis of Redox Flow Batteries via a Physics-Informed AI Digital Twin | PNNL | Jie Bao et al. |
| 2026 | ECS 249, Seattle | In-Situ Electrolyte Management for Sustained Operation of Vanadium Redox Flow Batteries | PNNL | Soowhan Kim et al. |
| 2026 | Energy Storage Safety & Reliability Forum, Albuquerque | Near Real Time Diagnosis and Prognosis Framework for Redox Flow Batteries | PNNL | Jie Bao, Vince Sprenkle et al. |
| 2026 | BCI, Nashville, May 3–4 | Rapid and Accurate Life Prediction for Lead Acid using AI | ANL | S. Babinec, N. Paulson, V. Sampath |
| 2026 | IEEE Big Data, Phoenix, Dec 14–17 | QUALIS: Knowledge Guided Operator Learning for Hierarchical Battery Energy Storage Systems | ORNL | Also listed as a publication |
| 2026 | IEEE HiPC, Bengaluru, Dec 16–19 | Scalable Distributed Training of Fourier Neural Operators for Battery Energy Storage System Health Prediction | ORNL | Also listed as a publication |

### Also addable

| Year | Venue | Title | Lab |
|---|---|---|---|
| 2025 | DSI Annual Microgrids for Energy Resilience, Washington, DC, Oct 23 | Accurately predicting battery field performance with AI – lower risk and lower cost | ANL |
| 2025 | Argonne Battery Industry Day, Lemont, Sept 23 | AI/ML Rapid and Accurate Life Prediction | ANL |
| 2024 | Spring MRS, Seattle | AI-driven prognosis of battery performance and health | ANL |
| 2024 | PRiME, Honolulu | AI for Long Duration Redox Flow Batteries: From Materials to Degradation | PNNL |
| 2024 | ACM/IEEE Supercomputing | ROVI presentations and Birds of a Feather sessions | ORNL | Consolidated entry; individual session titles were not listed |

### Optional SNL outreach (repeat title)

Several remaining SNL rows are the same **ROVI: AI for Energy Storage Deployments** talk already on Talks (LDES Consortium, SEPA). Add at most one or two more venues, not all of them:

- IEEE PES General Meeting, Anaheim (Valerio De Angelis)
- NY-BEST Fall Energy Storage Technology & Innovation Conference, Binghamton (De Angelis)
- ESIC Meeting (Yuliya Preger)
- International Electrical Safety Technical Seminar, South Korea (Preger) — also a data-requirements variant
- International Battery Safety Workshop, Germany (Preger)

---

## Software

Already on Software: `battery-data-toolkit`, `auto-soh` (Moirae), `collecting-battery-datasets`, `thevenin` (ROVI-org fork), `rovidh`, plus the other ROVI-org table rows.

| Lab | Name | URL | Why add |
|---|---|---|---|
| NLR | Ampworks | https://github.com/NatLabRockies/ampworks | Battery data processing, visualization, DVA; ~3.5k downloads |
| NLR | BLAST-Lite | https://github.com/NatLabRockies/BLAST-Lite | ASOH trajectory models / synthetic data; ~47.5k downloads |
| PNNL | EZBattery | https://github.com/pnnl/EZBattery | Flow-battery simulator; papers already on Publications |
| PNNL | battery-degradation-prognosis | https://github.com/pnnl/battery-degradation-prognosis | Prognosis forecasting adapted from TSLib |
| SNL | batteryarchive-agent | https://github.com/battery-lcf/batteryarchive-agent | Importers/schema for module-level and flow data |

NLR **Thevenin** upstream is https://github.com/NatLabRockies/thevenin. The site already lists the ROVI-org fork, so a second card is optional.

These live outside `ROVI-org`. If added, keep them in the Software table with the real GitHub org (`NatLabRockies`, `pnnl`, `battery-lcf`) rather than implying they are ROVI-org repos.

---

## Industry

Already on Industry: CMBlu, e-Zinc, Invinity, EPRI, New Energy Risk, Battery Council International.

| Partner | Lab | What the workbook says |
|---|---|---|
| CellCube | ORNL | Primary scoping with Srikanth Allu on vanadium redox-flow data, metadata, DataHub transfer, validation use cases, and governance |

ANL’s BCI **conference talk** is a Talks item, not a new industry partner (BCI is already listed).

SNL industry tab only points at 2024–2025 DOE DC outreach slides; no new named partner.

---

## Press

No addable press. ANL marked press as NONE. The ORNL Impact page for the EESAT paper is a publication landing page, not a press release.

## Do not use

Do not add these anywhere on the site (Talks, Press, DataHub, or elsewhere), now or later:

- **ORNL: ROVI DataHub unifies energy storage data to accelerate long-duration battery innovation** (May 28, 2026). Also listed in the workbooks as a DataHub briefing. Removed from Talks on purpose; not usable for this website.

---

## Copyright, patents, awards

| Item | Lab | Recommendation |
|---|---|---|
| Battery Data Toolkit copyright ANL-SF-21-043 | ANL | Already represented by the software listing |
| `rovidh` MIT release | ORNL | Already on Software |
| IEEE EESAT 2026 Best Paper | ORNL | Already on Talks and Publications |
| QUALIS provisional patent | ORNL | Keep off the public site unless you want a one-line “patent pending” with no filing details |

---

## Suggested first pass (if adding next)

1. Software: Ampworks, BLAST-Lite, EZBattery.
2. Talks: SciFM 2026, ECS 249 Kalman-filter (once), the two PNNL ECS 249 talks, BCI 2026.
3. Industry: CellCube, if the engagement is public.

Skip remaining SNL title repeats, Supercomputing BoF until session titles exist, and unpublished patent details. Never add the ORNL DataHub news/briefing.
