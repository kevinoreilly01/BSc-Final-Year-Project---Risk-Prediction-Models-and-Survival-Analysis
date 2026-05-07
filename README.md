# Risk Prediction Models: Temporal Recalibration 
# and Non-Linear Effects
### BSc Data Science and Analytics — Final Year Project
### University College Cork

## Overview
This project investigates temporal recalibration of 
survival risk prediction models using the Rotterdam 
breast cancer study dataset (2,982 patients, 1978-1993).

The core objective was to develop a risk prediction 
model that accurately reflects improving survival 
outcomes over time, without sacrificing the statistical 
reliability that comes from larger sample sizes.

## Key Topics
- Cox Proportional Hazards Modelling
- Kaplan-Meier Survival Analysis
- Temporal Recalibration
- Non-linear Age Effects (Cubic Splines & Fractional 
  Polynomials)
- Schoenfeld Residuals & Proportional Hazards Testing
- Time-dependent Covariate Effects

## Key Findings
- Survival outcomes improved significantly between 
  1978-1987 and 1988-1993 (p < 0.0001)
- Age was shown to have a non-linear effect on hazard — 
  decreasing through middle age before accelerating 
  after 70
- Temporal recalibration successfully updated the full 
  cohort model to reflect more recent survival 
  improvements, closely matching the period analysis 
  model while retaining more reliable risk factor 
  estimates
- Non-linear modelling of age explained apparent 
  time-dependent effects, satisfying the proportional 
  hazards assumption required for temporal recalibration

## Methods
- Language: R
- Key techniques: Cox PH model, Kaplan-Meier curves, 
  cubic splines, fractional polynomials, Schoenfeld 
  residuals, temporal recalibration
- Dataset: Rotterdam breast cancer study 
  (Royston & Altman, 2013)

## Note
To the best of the author's knowledge, this represents 
the first temporal recalibration performed on the 
Rotterdam breast cancer dataset.
