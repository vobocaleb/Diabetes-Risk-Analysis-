# Diabetes Risk Analysis - Reproducible R Code

## Overview

This repository contains the complete reproducible analysis for the paper:

> **"A Reproducible Biostatistical Workflow for Diabetes Risk Prediction Using Logistic Regression: An Analysis of the Pima Indians Dataset"**

The analysis demonstrates a complete biostatistical workflow including data cleaning, missing data imputation, exploratory data analysis, inferential testing, logistic regression modeling, multicollinearity diagnostics, and ROC-based model evaluation.

---

## Repository Contents

| File/Folder | Description |
|-------------|-------------|
| `diabetes_analysis.Rmd` | Complete R Markdown source file (the code) |
| **`diabetes_analysis.html`** | **Knitted HTML file (view in any browser)** |
| `Diabetes.csv` | Pima Indians original diabetes dataset  |
| `Diabetes_clean.csv` | Cleaned dataset after median imputation |
| `figures/README.md` | List and description of all figures |
| `README.md` | This file |

---

## How to View the Analysis (No R Required!)

**Option 1: View the HTML file (Recommended)**

1. Click on `diabetes_analysis.html` in this repository
2. Click the **"View raw"** button
3. The file will open in your browser with all code, output, and figures

**OR**

1. Download `diabetes_analysis.html`
2. Open it in any web browser (Chrome, Firefox, Safari, Edge)

---

## How to Reproduce the Analysis (With R)

### Requirements

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
```

## Notes

Due to GitHub file size limits, the high-resolution TIFF figures are not uploaded. 
However, they are generated automatically when you knit the R Markdown file.

