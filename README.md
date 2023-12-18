# Optimization_of_litter_size_in_polar_bears
Data and code for the manuscript on the optimization of litter size in polar bears

The Rmardown file PA_CR.Rmd contains the full workflow of the analysis starting from the clean capture dataset, and ending with the figures presented in the main text. This involves:
- building the model in Bayesian framework
- generating the data for the model
- running the model
- checking the output (trace_plots & Rhat)
- compute quantities of interest
- quantify the level of evidence for effects
- plotting the main figures.

The model takes several hours to run (~18h on my machine). The output of the model is therefire included in this repository.


Software and package version:
R version 4.2.2
nimble version 0.13.1
tidyverse version 2.0.0
patchwork version 1.1.2
cowplot version 1.1.1
Rstudio version 2023.9.1.494
