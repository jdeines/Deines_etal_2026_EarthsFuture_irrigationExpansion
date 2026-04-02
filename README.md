[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17478972.svg)](https://doi.org/10.5281/zenodo.17478972)

# Deines et al. 2026, Earth's Future
Derived data and analysis code for Deines et al. 2026

31 March 2026  
Code by: Jillian Deines  
Contact: jillian.deines@gmail.com  

This codebase accompanies the paper:

Deines, JM, S Baur, A Kendall, A Hadjimichael, & R Hetland. 2026. Irrigation expansion in the US Corn Belt: Patterns and yield impacts. Earth's Future [DOI to come]

## Contents

### Data
Small data files (< 100 mb) needed to reproduce the figures in the manuscript can be found in the `data` folder. 

Larger "master" data files of our sampled data needed to run the analyses, model intermediates, and summarized result data to produce results figures can be found in a Zenodo repository at [https://zenodo.org/doi/10.5281/zenodo.19392391](https://zenodo.org/doi/10.5281/zenodo.19392391). Other input data are available at their respective sources as described in the manuscript.

**Data included here**

* `data/tabular`: Various data used in analysis scripts, including USDA NASS data downloads

**Data stored on Zenodo**

* Formatted Input for Figures (csv summaries of causal forest output)
* Cleaned master data sample (as csv and RData files)
* Intermediate and output causal forest objects
* Full 2017 USDA Census Download

### Code
* Code to perform all paper analyses and generate figures in the paper 

Script filenames are numbered in sequential order of use. Processing is done using [R Markdown](https://rmarkdown.rstudio.com/) within an R project structure. Operational scripts have extension .Rmd; notebook style docs (code + outputs) in .md (for easy viewing on Github) and .html (for desktop viewing) are also provided.

To run "analysis" scripts, please download the data at [https://zenodo.org/doi/10.5281/zenodo.19392391](https://zenodo.org/doi/10.5281/zenodo.19392391) and save to your local computer. In the scripts, update the `dataDir` path variable at the top of the analysis script in the "Directories" code chunk.

### Figures_manuscript
Figure output from scripts

### figure
Informal figure output from scripts from R Markdown process
