# Code and data accompanying the paper "Interplay between slow slip events and seismicity in the Hikurangi Subduction Zone revealed by a new high-resolution catalog" 

Authors: Jessica Allen, Ting Wang, Mark Bebbington, Calum J Chamberlain, Jiancang Zhuang

Published: Seismological Research Letters 2026

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.xxxxxxx.svg)](https://doi.org/10.5281/zenodo.xxxxxxx)

---

## Overview
This repository contains code for implementing the MCST (magnitude of spatio-temporal completeness) clustering algorithm, performing metric‐based classification of sequences, and calculating the mutual information with confidence limits. Our catalog of classified seismic sequences compiled from the Hikurangi matched filter catalog (10.5281/zenodo.15361215) is also provided.  

---

## Contents
- `Sequence catalog/` — catalog of clustered sequences (2009-2022) identified in the Hikurangi subduction zone, with their respective classifications as mainshock-aftershock or seismic swarm.  
- `MCST algorithm/` — R scripts for calculating the spatio-temporally smoothed magnitude of completeness, comparing choices of threshold parameters, using the MCST algorithm to identify clustered sequences, and assessing the remaining background activity for different thresholds.
- `Sequence classification/` — R scripts for calculating classification metrics for sequences, performing k-means classification, and carrying out principal components analysis to aid in interpretation of the k-means classes.
- `Mutual information/` — R scripts for calculating the mutual information between two 0-1 time series, along with the corresponding parametric and non-parametric confidence intervals. 
 
---

## Requirements
- R (≥ 4.5)
- R packages: `spatstat`, etc.  
To install dependencies:
```r
install.packages(c("spatstat"))
