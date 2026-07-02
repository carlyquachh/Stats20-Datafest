# Hazardous Chemicals in CA Cosmetics

**UCLA Stats 20 | Group 33 | Fall 2025**

Brooke Franaszek, Carly Quach, Vivian Meng

## Overview
Cleaned and analyzed a 16,500+ observation dataset from the California Safe 
Cosmetics Program to uncover patterns in hazardous chemical usage across 
cosmetic product categories and brands.

## Dataset
Publicly available from the 
[California Safe Cosmetics Program](https://www.cdph.ca.gov/Programs/CCDPHP/DEODC/OHB/CSCP/Pages/CSCP.aspx).
Download the data and place it in the same folder as the .Rmd file before running.

## Tools Used
- R (ggplot2, dplyr)
- R Markdown

## Key Findings
- Titanium dioxide dominated chemical reports by a significant margin
- Makeup products contained the most reported hazardous chemicals
- Reporting peaked in 2009, then declined and stabilized
- Newer products tend to have slightly more chemicals (r ≈ 0.127, p < 0.001)
- Products without chemicals were more likely to be discontinued 
  (24.6% vs. 11.2% chance, logistic regression)
- Hair coloring and makeup products showed the widest chemical count 
  distributions (ANOVA)

## How to Run
Open `group33_report.rmd` in RStudio and knit to run the full analysis.
Make sure `cscpopendata.csv` is in the same folder as the .Rmd file.
