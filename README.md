# Global Tech and AI Startups Analysis
This project analyzes synthetic data from global technology and AI startups. The main objective is to determine if higher levels of AI adoption are associated with better financial and operational outcomes.

## Table of Contents
- [Project Objectives](#project-objectives)
- [Dataset Information](#dataset-information)
- [Tools](#tools)
- [Overall Methodology](#overall-methodology)
- [Data Analysis Process](#data-analysis-process)
- [Limitations](#limitations)
  
## Project Objectives
- Analyze the relationship between AI adoption and financial outcomes.
- Examine differences in operational metrics.
- Determine whether AI adoption is associated with better startup performance across the selected financial and operational metrics.
- Use statistical tests to determine whether the observed relationships are statistically significant.

## Dataset Information
The dataset is publicly available on Kaggle under the CC0: Public Domain License.

Dataset source: https://www.kaggle.com/datasets/saitejabandaruin/automated-pipeline-dataset-output 

### Dataset Columns

| Variable | Description |
|---|---|
| Company_ID | Unique identifier for the startup. |
| Domain | Specific technology industry sector. |
| Founding_Year | Year the startup was founded. |
| Country | Country where the startup is headquartered. |
| City | City where the startup is headquartered. |
| Funding_Stage | Current venture funding stage of the startup. |
| Total_Funding_USD_Millions | Total venture capital funding raised to date, measured in USD millions. |
| Valuation_USD_Millions | Estimated company valuation, measured in USD millions. |
| Revenue_ARR_Millions | Estimated Annual Recurring Revenue (ARR), measured in USD millions. |
| Monthly_Burn_Rate_Millions | Estimated monthly cash burn rate, measured in USD millions. |
| Runway_Months | Estimated number of months the company can operate without additional funding based on available cash and monthly burn rate. |
| 2024_Peak_Headcount | Estimated total full-time headcount at the company's peak in 2024. |
| Layoffs_2024_2025 | Total number of employees laid off during the 2024–2025 technology market correction. |
| Current_Headcount_2026 | Estimated current full-time headcount in 2026. |
| Investor_Tier | Classification of the startup's investor profile or tier. |
| AI_Adoption_Level | Level of AI adoption within the startup. |
| Acquisition_Status | Current ownership status of the startup. |

## Tools
- **Python**: Programming language used to analyze the data. The libraries of Python used are Pandas, NumPy, Matplotlib, Seaborn and Statsmodels.
- **Jupyter Notebook:** Used to document and run the analysis.

## Overall Methodology
- Data inspection and cleaning
- Missing and duplicate value analysis
- Descriptive Analysis
- Distribution analysis
- Comparison of performance variables across AI adoption levels
- One-Way ANOVA
- Interpretation of p-values using a significance level of α = 0.05

## Data Analysis Process
The analysis was developed in Jupyter Notebooks through Anaconda. The files can be found in the folder `notebooks`. 
- `01_exploratory_descriptive_analysis.ipynb`: Focuses on inspecting and cleaning the dataset, identifying missing and duplicate values. It identifies variable distributions and performs descriptive statistics by comparing selected financial and operational performance variables across AI adoption levels. After all the analysis is done, it recognizes an initial relationship between AI adoption level and the performance variables.
- `02_statistical_hypothesis_testing.ipynb`: Defines the research question and statistical hypotheses, explains why one-way ANOVA is used, and tests the selected performance variables across the AI adoption levels. It evaluates the statistical significance of the results using a significance level of α = 0.05 and interprets the findings.

## Limitations
Missing values in the column *AI_Adoption_Level* were assumed to represent “No AI Adoption”, as there were 2592 missing values, a number of observations that was worth having in the analysis. If the missing values originally represented unknown or unavailable information, the findings of the analysis may therefore be different.
