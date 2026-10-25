# Olaparib versus Chemotherapy: Canadian Cost-Effectiveness Model

This project evaluates the cost-effectiveness of olaparib versus physician’s-choice chemotherapy for patients with germline BRCA-mutated, HER2-negative metastatic breast cancer in Canada.

A three-state partitioned survival model is being developed in R using progression-free and overall survival evidence from the OlympiAD trial.

## Current progress

- Reconstructed approximate patient-level survival data from published Kaplan–Meier curves.
- Fitted and compared four candidate survival distributions using AIC, BIC, and visual assessment.
- Extrapolated survival over a 20-year horizon.
- Selected provisional base-case distributions and calculated monthly health-state proportions.

Survival validation remains ongoing. The next stage involves incorporating Canadian costs and health-state utilities to estimate costs, quality-adjusted life-years (QALYs), and cost-effectiveness.

## Code availability

The model code will be uploaded once development is complete.
