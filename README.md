# COVID-19 NPI Effectiveness Analysis
## Overview
This project analyzes the effectiveness of Non-Pharmaceutical Interventions (NPIs) during the second wave of the COVID-19 pandemic in Europe, with a specific focus on the United Kingdom. Using a Bayesian framework, we estimate the impact of various interventions on the transmission dynamics of the virus.

## Methodology
We employ a compartmental epidemiological model (SIR variant) defined by ordinary differential equations (ODEs). The model is implemented using the NumPyro probabilistic programming library to perform Bayesian inference and quantify uncertainties in the effects of different NPIs.
