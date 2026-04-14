# DATA501_FinalProject
This repository contains all files related to our DATA 501 capstone project. <br>

## Data
The original raw data collected from Bloomberg and LSEG Workspace is located in the **"Original Raw Data"** folder. This folder contains multiple Excel files corresponding to different financial and ESG variables extracted from these databases. These datasets were extracted separately and required significant preprocessing before analysis.

Additional details on preprocessing steps are documented in the **"1. Data Cleaning Procedures"** file.

The cleaned dataset used for analysis is available as:
- `FINAL_CLEANED_DATASET_V2.csv`
---
## Analysis Files

There are four R Markdown (`.Rmd`) files in this repository:

- `DATA501_RQ1` — Analysis for Research Question 1  
- `DATA501_RQ2` — Analysis for Research Question 2  
- `DATA501_RQ3` — Analysis for Research Question 3  
- `DATA501_AlternativeAnalysis` — Panel Quantile Regression (PQR) for all research questions  

The alternative analysis file applies panel quantile regression as a complementary method to linear regression, following project feedback.

---

## Software

The code was executed using:

- **RStudio:** 2026.01.0+392 ("Apple Blossom")  
- **Quarto:** 1.8.25  

### Libraries Used

`ggplot2`, `nortest`, `DescTools`, `mosaic`, `dplyr`, `zoo`, `car`, `fixest`, `lmtest`, `performance`, `moments`, `plm`, `sandwich`, `ggeffects`, `rlang`, `quantreg`, `broom`, `gratia`
