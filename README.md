# Global Tech and AI Startups Analysis
This project analyzes synthetic data from global technology and AI startups. The main objective is to determine if higher levels of AI adoption are associated with better financial and operational outcomes, such as revenue, company valuation, funding, layoffs, headcount, runway, and acquisition status.

## Table of Contents
- [Project Objectives](#project-objectives)
- [Dataset Information](#dataset-information)
- [Tools](#tools)
  
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
