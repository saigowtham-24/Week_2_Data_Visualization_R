# Week 2: Data Visualization and Insight Communication using R

**Author:** SONTYANA SAI GOWTHAM  
**Dataset:** Titanic passenger dataset  
**Task:** Week 2 — Data Visualization and Insight Communication using R

## Overview
This project explores the Titanic passenger dataset using R and `ggplot2`. It demonstrates how different chart types can communicate category comparisons, distributions, relationships, and correlations to a non-technical audience.

## Objectives
- Explore key variables in the Titanic dataset.
- Check and prepare missing values for visualization.
- Create multiple chart types in R.
- Compare survival outcomes by passenger class and sex.
- Explain the purpose and interpretation of each visualization.
- Save plots and supporting summaries for reproducibility.

## Tools and libraries
- R and RStudio
- `titanic`
- `ggplot2`
- `dplyr`
- `tidyr`
- `scales`

## Visualizations
The R script is designed to create these charts:
1. `survival_counts.png` — bar chart of survival counts
2. `age_distribution.png` — histogram of passenger age
3. `fare_distribution.png` — histogram of ticket fare
4. `age_vs_fare_scatter.png` — scatter plot of age versus fare
5. `survival_by_class.png` — survival outcomes by passenger class
6. `survival_by_sex.png` — survival outcomes by sex
7. `fare_boxplot.png` — fare distribution by passenger class
8. `survival_by_age_group.png` — survival outcomes by age group
9. `correlation_heatmap.png` — correlation heatmap for numeric variables

## Repository structure
```text
Week_2_Data_Visualization_R/
├── README.md
├── data_visualization_week2.R
├── Week_2_Data_Visualization_R_Report.docx
├── plots/
│   └── [R-generated PNG charts]
└── outputs/
    └── [CSV summaries and session_info.txt]
```

## How to run
1. Install R and RStudio.
2. Open `data_visualization_week2.R` in RStudio.
3. Set the working directory to the repository folder.
4. Run the script and check the Console for errors.
5. Confirm that the `plots/` and `outputs/` folders have been generated.
6. Review the report and use the actual R-generated charts and summary files to complete the findings.

## Interpretation note
The report explains why each chart type is appropriate and what to examine. Final numerical claims and key findings should be checked against the actual R-generated plots and CSV outputs. Do not present unverified values as measured results.

## Deliverables
- R analysis script
- Nine R-generated visualizations
- CSV summaries and R session information
- Word report with chart descriptions and interpretations

## Repository link
https://github.com/saigowtham-24/Week_2_Data_Visualization_R
