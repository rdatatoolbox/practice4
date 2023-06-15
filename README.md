
<!-- README.md is generated from README.Rmd. Please edit that file -->

## :mortar_board: Practice 4 - Renv

<!-- badges: start -->

[![License:
GPL-2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://choosealicense.com/licenses/gpl-2.0/)
<!-- badges: end -->

Structure of the research compendium of the [practice
4](https://rdatatoolbox.github.io/ex-targets.html) of the training
course [**Reproducible Research in Computational
Ecology**](https://rdatatoolbox.github.io/).

### Content

This repository is structured as follow:

- [`data/`](https://github.com/rdatatoolbox/practice4/tree/main/data):
  contains all raw data required to perform analyses

- [`R/`](https://github.com/rdatatoolbox/practice4/tree/main/R):
  contains R functions developed especially for this project

- [`DESCRIPTION`](https://github.com/rdatatoolbox/practice4/tree/main/DESCRIPTION):
  contains project metadata (author, date, dependencies, etc.)

- [`_targets.R`](https://github.com/rdatatoolbox/practice4/tree/main/_targets.R):
  contains the pipeline

- [`index.Rmd`](https://github.com/rdatatoolbox/practice4/tree/main/index.Rmd):
  contains the final report to knit

- [`make.R`](https://github.com/rdatatoolbox/practice4/tree/main/make.R):
  main R script to run the entire project by running
  `targets::tar_make()`

### Usage

Fork and clone the repository, open R/RStudio and run:

``` r
source("make.R")
```

### Notes

- All required packages, listed in the `DESCRIPTION` file, will be
  installed (if necessary)
- All required packages and R functions will be loaded

### How to cite

> Casajus N, Bonnici I, Dray S, Gimenez O, Guéry L, Guilhaumon F,
> Schiettekatte NMD & Siberchicot A (2023) Workshop FRB-CESAB & RT
> EcoStat: Reproducible Research in Computational Ecology. Zenodo.
> <http://doi.org/10.5281/zenodo.4262978>.
