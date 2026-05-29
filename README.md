# Climate-Health Vulnerability Targeting in Somaliland: Evidence from SDHS 2020

A reproducible climate-risk analytics project that transforms household survey indicators into actionable climate-health vulnerability insights for risk targeting and resilience planning.

## Overview

This project develops a **Climate-Health Vulnerability Index (CHVI)** using derived indicators from the Somaliland subset of the Somali Health and Demographic Survey (SHDS 2020). The workflow demonstrates how household-level information on WASH, food insecurity, and livelihood shocks can be translated into practical targeting insights for climate-health interventions.

## Project Outputs

* Regional climate-health vulnerability mapping
* CHVI framework and vulnerability pyramid
* Targeting dashboard for priority households
* Regional vulnerability ranking
* Derived summary tables and visualisations
* Reproducible R workflows

## Key Insights

* 26.2% of households were classified as highly vulnerable.
* Vulnerability is unevenly distributed across Somaliland regions.
* High vulnerability frequently overlaps with service exclusion and livelihood shocks.
* Risk targeting can be strengthened through integrated WASH, food security, livelihood, digital inclusion, and financial inclusion approaches.

## Repository Structure

```text
data/derived/      # Non-sensitive derived datasets
scripts/           # Reproducible R workflows
figures/           # Portfolio-ready figures
outputs/           # Generated outputs
docs/              # Project notes and brief
```

## Reproducibility

Run all figures using:

```r
source("scripts/00_run_all.R")
```

## Data Availability

This repository does not contain raw SHDS microdata. Only derived, non-identifiable outputs and reproducible workflows are provided. Access to the original SHDS dataset is subject to the policies of the relevant data custodians.

## Applications

Climate Risk Management • Climate Health • WASH Planning • Food Security • Livelihood Recovery • Digital Inclusion • Financial Inclusion • Climate Resilience

**Author:** Ahmed Hussein Ismail
