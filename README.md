# Diabetes Risk Analysis - Reproducible R Code

## Overview

This repository contains the complete R Markdown source file for the paper:

> **"A Reproducible Biostatistical Workflow for Diabetes Risk Prediction Using Logistic Regression: An Analysis of the Pima Indians Dataset"**

The analysis demonstrates a complete biostatistical workflow including data cleaning, missing data imputation, exploratory data analysis, inferential testing, logistic regression modeling, multicollinearity diagnostics, and ROC-based model evaluation.

## Repository Contents

| File/Folder | Description |
|-------------|-------------|
| `diabetes_analysis.Rmd` | Complete R Markdown source file |
| `diabetes_analysis.html` | Knitted HTML output (view in browser) |
| `diabetes.csv` | Original Pima Indians Diabetes Dataset |
| `Diabetes_clean.csv` | Cleaned dataset after imputation |
| `figures/` | All figures in high-resolution TIFF format |
| `README.md` | This file |

## Requirements

- **R version:** 4.3 or higher
- **RStudio:** Recommended for knitting the `.Rmd` file

### Required R Packages

```r
install.packages(c(
  "tidyverse",   # Data manipulation and visualization
  "skimr",       # Data exploration summaries
  "janitor",     # Data cleaning utilities
  "readr",       # CSV data import
  "ggplot2",     # Grammar of Graphics
  "GGally",      # Extended pair plots
  "patchwork",   # Combining multiple plots
  "corrplot",    # Correlation matrix visualization
  "effsize",     # Cohen's d effect size calculation
  "sjPlot",      # Model visualization and tables
  "car",         # Variance Inflation Factor (VIF)
  "pROC"         # ROC curve and AUC analysis
))
