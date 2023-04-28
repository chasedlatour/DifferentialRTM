# DifferentialRTM

The repository contains the code used for the simulation by Latour et al. published in Clinical Epidemiology.

In this study, we aim to simulate a non-interventional comparative effectiveness study of two treatments for immune thrombocytopenia, a medical disorder characterized by low platelet counts. The primary objective of this simulation is to understand if propensity scores (and associated weighting) can be used to mitigate bias in treatment effect estimate that is due to regression-to-the-mean that is differential by treatment arm.

The R Markdown files are posted in this repository and were used for this simulation. Substantial commenting and explanation is provided throughout this code. Various sections are commented out to batch submit this code in a step-wise manner. In particular, this code takes a long time to run and a user should be cautious before running the code as-is without commenting out sections in which they're not interested or decreasing the number of simulations they're testing. Though, the code should generally run as-is.

Files should be run according to the numbers at the end of the file names (i.e., 1, 2, 3). Further, I have uploaded a file that shows how the publication's figures were generated.
