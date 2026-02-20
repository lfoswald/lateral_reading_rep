# Replication Materials for Lateral Reading Germany 

Oswald, L., Kozyreva, A., Nickl, P. L., Herzog, S. M., & Hertwig, R. (2026). Boosting media literacy using lateral reading and online search interventions. 

* Materials are available under a Creative Commons CC0 1.0 Universal license.
* The study was preregistered under the OSF: https://osf.io/tsb68
* The materials contain data, code and study materials. All materials are available under: https://osf.io/wtbr5

## Materials
The materials folder contains supplementary material provided along the manuscript, as well as the full survey scripts with information on randomization.

## Data
The data folder contains two datasets:

1. `exp_data.csv` to replicate any analyses based on survey responses (which include the outcomes of the experiment)
2. `labled_seqs_minimal.csv` provide a minimal dataframe to replicate Fig. 3D displaying relative positions of search following experimental website visits

## Code
The code folder contains the following 6 Quarto files:

### `1-descriptives-sample.qmd`
Creates summary statistics for demographic and attitudinal variables of the sample. 

### `2-descriptives-experiment.qmd`
Creates descriptive statistics of the outcome within the experiment.

### `3-models-main.qmd`
This file contains the primary preregistered models as well as several robustness checks. 

### `4-model-variants.qmd`
This file contains variations of the main models. 

### `5-survey-differences.qmd`
This file contains descriptive statistics regarding the experimental stimuli as well as differences in discernment along survey variables.

### `6-search-behavior.qmd`
Uses (heavily) preprocessed tracking data to allow computational reproduction of search behavior figure.


## Computational Reproduction of the Results presented in the manuscript:

1. Download the replication folder (have R and R Studio installed), click on the .Rproj file.
2. Click the different .qmd files in the order in which they appear, starting with 1. 
3. Render the .qmd files one by one and inspect .html output.