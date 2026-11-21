# The Income Divide in Financial Inclusion
### A Multivariate Analysis of Financial Access and Behaviour in Developing and Emerging Economies

## Project Overview

Financial access and behaviour can differ between lower-income and higher-income adults.

This project examines these differences across developing and emerging economies using data from the World Bank Global Findex Database.

The analysis compares the poorest 40% and richest 60% of adults within each economy to understand how financial access and behaviour differ between the two income groups.

## Research Questions

1. How do financial access and behaviour differ between the poorest 40% and richest 60%, and which financial services show the largest gaps?
2. What are the main dimensions that summarise financial access and behaviour?
3. What underlying factors explain the relationships among financial inclusion indicators?
4. What distinct groups of developing and emerging economies can be identified based on financial inclusion and income-related differences?

## Dataset

- **Source:** World Bank Global Findex Database 2025
- **Survey year:** 2021
- **Economies:** 73 developing and emerging economies
- **Income groups:** Poorest 40% and richest 60%
- **Observations:** 146
- **Financial indicators:** 8

The analysis focuses on low-income, lower-middle-income and upper-middle-income economies.

The selected indicators cover financial institution account ownership, digital payments, utility payments, saving, borrowing and access to emergency funds.

The cleaned dataset contains the eight indicators and three descriptive columns.

The original data can be obtained from the [World Bank Global Findex website](https://www.worldbank.org/en/publication/globalfindex).

## Methods

| Method | Purpose |
|---|---|
| Descriptive Statistics | Examine financial indicators and compare the two income groups |
| Principal Component Analysis (PCA) | Identify the main dimensions of financial access and behaviour |
| Factor Analysis (FA) | Examine underlying factors among the financial indicators |
| Cluster Analysis | Group economies based on financial inclusion patterns and income differences |

## Tools

Python · Jupyter Notebook · pandas · NumPy · Matplotlib · Seaborn · scikit-learn · factor_analyzer · pingouin

## Repository Structure

```text
financial-inclusion-multivariate-analysis/
│
├── income_inequality_analysis.ipynb
├── data/
│   └── processed/
│       └── financial_inclusion_cleaned_2021.csv
├── README.md
└── .gitignore
```

The notebook contains the data preparation, statistical analysis, visualisations and interpretations.

The cleaned CSV contains the data prepared for the analysis. The original Excel dataset is not included in the repository.

To reproduce the data preparation from the beginning, download the original Global Findex workbook, save it as `data/GlobalFindexDatabase2025.xlsx`, and use its `Data` worksheet.

## Project Status

**In progress**

Completed:
- Data preparation and cleaning
- Descriptive statistics
- Outlier investigation
- Income-group comparisons
- Standardisation
- Correlation and partial correlation analysis
- KMO assessment

Next stages:
- Principal Component Analysis
- Factor Analysis
- Cluster Analysis

The results and documentation will be updated as the analysis progresses.

## Data Source

World Bank. *Global Findex Database 2025*. Data for the 2021 survey.