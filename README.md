# Code and data accompanying the paper "Interplay between slow slip events and seismicity in the Hikurangi Subduction Zone revealed by a new high-resolution catalog" 

Authors: Jessica Allen, Ting Wang, Mark Bebbington, Calum J Chamberlain, Jiancang Zhuang

Accepted: Seismological Research Letters 2025

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)

---

## Overview
This repository contains the analysis and code used in the paper above.  
It includes scripts for processing seismicity data, modelling daily Benioff strain, and reproducing the figures in the publication.

---

## Contents
- `data/` — preprocessed datasets  
- `R/` — R scripts for ETAS model fitting and daily rate analysis  
- `figures/` — scripts and outputs for figures  
- `paper/` — manuscript-related materials  

---

## Requirements
- R (≥ 4.3)
- R packages: `Rcpp`, `ggplot2`, `dplyr`, `lubridate`, etc.  
To install dependencies:
```r
install.packages(c("Rcpp", "ggplot2", "dplyr", "lubridate"))
