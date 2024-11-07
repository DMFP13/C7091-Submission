# DPeters C7091 Mini Project

**Author**: Dan Peters  
**Module**: C7091  
**Date**: October 23, 2024  

This repository contains solutions to R programming tasks focused on data manipulation, statistical analysis, and visualization. Key tasks involve calculations, data filtering, plotting, and statistical tests using popular R libraries.

## Contents

1. **Scatter Plot of `mpg` Data**: Visualizes engine displacement vs. highway miles per gallon by year.
2. **Cylinder Volume Calculation**: Computes cylinder volume with a given radius and height.
3. **Sample Size Estimation**: Calculates sample size for a t-test using `pwr.t.test`.
4. **Matrix NA Handling**: Fills missing values in a matrix and computes means.
5. **Post-hoc Analysis**: Performs ANOVA and pairwise species comparisons in the `iris` dataset.
6. **Sum of Squares and F-Statistic**: Calculates within- and between-group variations.
7. **Total Variation (SST)**: Measures variation in `Sepal.Length` across all samples in `iris`.
8. **Nested List Access**: Demonstrates indexing to access specific elements in a nested list.

## Setup

Install required packages:

```r
options(repos = c(CRAN = "https://cran.rstudio.com/"))

install.packages(c('emmeans', 'ggplot2', 'pwr', 'dplyr'))
