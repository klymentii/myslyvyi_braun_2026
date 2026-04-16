### Suplementary Materials 
# How Do Ukrainian Learners of German Process Lexical Stress? Evidence from Production and Perception 
doi: 10.1177/00238309261434240
### Klymentii Myslyvyi, Bettina Braun

### April, 2026


## Overview

This repository contains data, analysis scripts, and results for a two-part study investigating (a) prosodic cues to stress and focus in L1 Ukrainian, L2 German, and L1 German speakers, and (b) the influence of F0 on online word recognition in L2 German.

The study consists of two experiments:

* **Experiment 1 (Production study):** Examines production of stress and focus in three varieties: Ukrainian (L1), German (L2), German (L1).
* **Experiment 2 (Eye-tracking study):** Investigates how F0 influences lexical access and fixation behavior during online word recognition.

---

## Repository Structure

```
.
├── exp1/
│   ├── data_exp1_durint_controls.tsv
│   ├── data_exp1_durint.tsv
│   ├── data_exp1_f0.tsv
│   ├── exp1.Rmd
│   ├── exp1.html
│   ├── model1_ml_acf.rds
│   └── plots/
│
├── exp2/
│   ├── exp2.Rmd
│   ├── exp2.html
│   ├── fixdurations.txt
│   ├── metad_learner_types.tsv
│   ├── metad.tsv
│   └── plots/
```

---

## Requirements

The analyses were conducted in R. Key packages include:

* tidyverse
* lme4 / glmmTMB
* mgcv
* broom
* dplyr
* ggplot2

(Exact package versions may affect reproducibility.)

---

## Reproducibility

To reproduce the analyses:

1. Clone this repository
2. Open the `.Rmd` files in `exp1/` or `exp2/`
3. Run all chunks to regenerate analyses and figures

---

## Data Availability

All data and analysis scripts required to reproduce the results are included in this repository.

---

## Notes

* GAMM model (`.rds`) for F0 analysis is included because it requires significant computation time.
* Figures are stored in the `plots/` folders for each experiment.
* Intended outputs of the R scripts are provided in HTML files.
