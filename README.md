# Optimization_of_litter_size_in_polar_bears
Data and code for the manuscript on the optimization of litter size in polar bears

The Rmardown file PA_CR.Rmd contains the full workflow of the analysis starting from the (cleaned) capture data, and ending with the figures presented in the main text. Specifically, the workflow involves:
- building the model in a Bayesian framework
- generating the input data and initial values for the model
- fitting the model with MCMC using nimble
- checking the output (trace plots & Rhat)
- computing quantities of interest (predictions, observations corrected for the effect of a given set of variables, etc.)
- quantifying the level of evidence for effects
- plotting the main figures.

The model takes several hours to run (~18h on my machine). The output of the model is therefore included in this repository.


Software and package version:
R version 4.3.0
nimble version 1.1.0
tidyverse version 2.0.0
patchwork version 1.2.0
Rstudio version 2024.9.1.394
