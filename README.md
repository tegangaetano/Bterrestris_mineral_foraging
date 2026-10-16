# Bumblebee mineral foraging

**R code supporting the study:** *Behavioural responses to a range of mineral salt concentrations in the buff-tailed bumblebee (Bombus terrestris audax)*

## Overview

This repository contains R code used to process, analyse, and visualise experimental data investigating the behavioural responses of buff-tailed bumblebees (*Bombus terrestris audax*) to different concentrations of four essential mineral nutrients: calcium (Ca), potassium (K), magnesium (Mg), and sodium (Na).

The study used a multi-choice foraging assay in which cohorts of bumblebee workers were presented with five concentrations of an individual mineral salt dissolved in artificial nectar (45% w/w sucrose), alongside a sucrose-only control.

The experiment aimed to characterise concentration-dependent consumption responses, identify evidence of acceptance or aversion, and assess whether these responses were consistent with the non-linear relationship predicted by Bertrand's Rule.

## Data analysis

All statistical analyses were conducted in R using linear mixed-effects models (LMMs).

The analyses included:

- **Data processing:** Calculation of consumption volumes, correction for evaporation, and normalisation of consumption values.
- **Categorical concentration analysis:** Comparison of consumption across individual mineral concentrations using LMMs and post hoc pairwise contrasts.
- **Continuous concentration analysis:** Comparison of linear and quadratic models to investigate concentration-dependent consumption responses.
- **Environmental covariates:** Assessment of the effects of temperature, relative humidity, and their interaction on consumption.
- **Visualisation:** Generation of figures illustrating consumption responses, model predictions, and confidence intervals.

## Data availability

The experimental datasets supporting this study are provided in the electronic supplementary material accompanying the associated publication.

## Citation

If you use or adapt the code in this repository, please cite the associated publication:

Gaetano T, Yourstone J, Lancaster LT, Manfredini F. *Behavioural responses to a range of mineral salt concentrations in the buff-tailed bumblebee (Bombus terrestris audax).* Royal Society Open Science. [Publication details to be added upon publication.]

The code repository is available at:

https://github.com/tegangaetano/Bterrestris_mineral_foraging

## Funding

This research was supported by a UK Research and Innovation–Natural Environment Research Council (UKRI–NERC) studentship through the QUADRAT Doctoral Training Partnership (grant NE/S007377/1).

## Licence

This repository is distributed under the terms of the GNU General Public License version 3.0 (GPL-3.0). See the `LICENSE` file for details.
