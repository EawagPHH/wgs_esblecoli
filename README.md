# ESBL-E. coli WGS Analysis (Switzerland 2021–2023)

This repository contains the R code and related documents used to analyze whole-genome sequencing data of ESBL-producing *E. coli* from wastewater, clinical, cattle, and wildlife sources in Switzerland (2021–2023).

- The `.Rmd` script contains all analysis steps.
- The `.html` file provides a full description of the analysis pipeline and results.
- The folder structure should be kept as-is to ensure the code runs properly.
- The `tables/` and `figures/` folders are intentionally empty; they will be populated with outputs when the analyses are executed.
- The `parsimony/` folder contains previously generated results (e.g. randomizations and transition analyses), allowing the R code to run without re-performing these time-intensive steps.
