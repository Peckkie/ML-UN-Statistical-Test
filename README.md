## Overview
 
This codebase implements the identity-level cluster bootstrap analysis used to evaluate the effect of machine unlearning on pairwise embedding distances. Specifically, it reproduces the statistical results reported in the main manuscript and Supplementary Material (S1–S3), including:
 
- Normality assessment via Kolmogorov-Smirnov (KS) tests and Q-Q plots (S1)
- Identity-level cluster bootstrap procedure for confidence interval estimation (S2)
- Extended statistical results for RQ1 and RQ2 (S3)
---
 ## Requirements
 
| Package    | Version (tested) |
|------------|-----------------|
| numpy      | ≥ 1.23          |
| scipy      | ≥ 1.10          |
| matplotlib | ≥ 3.7           |
| seaborn    | ≥ 0.12          |
| pandas     | ≥ 2.0           |
 
---
 
## Reproducibility
 The bootstrap procedure runs `B = 20,000` iterations by default and may take several minutes depending on hardware.
