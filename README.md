# India CPI Inflation Analysis (2013–2023)

## Project Overview

This project focuses on analyzing India's Consumer Price Index (CPI) and understanding inflation trends using Microsoft Excel.

The analysis explores overall CPI inflation, category-level patterns, food inflation, the impact of the COVID-19 period, and the relationship between Indian Basket crude oil prices and CPI indices.

The project uses data from January 2013 to May 2023 and applies Excel data-cleaning, formulas, PivotTables, charts, and dashboard techniques to identify meaningful trends and insights.

## Objectives

- Analyze year-over-year (YOY) CPI inflation trends
- Examine category-level CPI index patterns
- Understand food inflation trends and category changes
- Compare inflation across different COVID-19 periods
- Explore the relationship between crude oil price changes and CPI movements
- Present key findings through an interactive Excel dashboard

## Tools & Technologies

- Microsoft Excel
- Excel Tables
- Data Cleaning
- Excel Formulas
- PivotTables and Charts
- Data Visualization
- Interactive Dashboard

## Repository Structure

India-CPI-Inflation-Analysis/
│
├── Images/
│    ├── 1.dashboard_part_1.png
│    ├── 2.dashboard_part_2.png
│    ├── cpi_trend.png
│    ├── food_inflation.png
│    └── oil_cpi_correlation.png
│
├── India_CPI_Inflation_Analysis.xlsx
│
└── README.md

## Project Workbook Structure

The Excel workbook contains the following worksheets:

| Worksheet | Description |
|---|---|
| Dashboard | Dashboard presenting key metrics, charts, and findings |
| Raw_Data | Original CPI dataset |
| Cleaned_Data | Cleaned and organized CPI data |
| Category_Mapping | CPI category grouping and mapping |
| Q1_Category_Contribution | Analytical share of summed CPI subcategory index values |
| Q2_YOY_Inflation | Year-over-year CPI inflation analysis |
| Q3_Food_Inflation | Food index and category-level inflation analysis |
| Q4_COVID_Analysis | Comparison of inflation across COVID-19 periods |
| Q5_Oil_CPI_Correlation | Correlation analysis between crude oil prices and CPI indices |


## Key Analysis & Findings

### 1. Analytical Category Share

- Examined the share of summed individual CPI subcategory index values across broader categories.
- Food categories represented approximately 52% of the calculated analytical share.

**Methodological note:** This is an unweighted analytical calculation. It does not represent official CPI expenditure weights or actual contributions to headline inflation.

### 2. YOY CPI Inflation Analysis

- Analyzed monthly year-over-year CPI inflation trends.
- Compared annual average inflation rates from 2017 to 2023.
- Identified the highest monthly YOY inflation within the January 2017–May 2023 analysis period at approximately 7.79% in April 2022.

### 3. Food Inflation Analysis

- Calculated an analytical Food Index using the simple average of 12 individual food category indices.
- Compared monthly changes and individual category movements.
- Observed that spices increased by approximately 17.90%, while oils and fats declined by approximately 16.01% between May 2022 and May 2023.

**Methodological note:** The calculated Food Index is an analytical measure and is not the official Consumer Food Price Index (CFPI).

### 4. COVID-19 Impact Analysis

Compared average YOY inflation across three periods:

- Before COVID: Up to February 2020
- Initial COVID: March–December 2020
- COVID Progression: January 2021–May 2023

The average General CPI inflation rate increased from approximately 3.87% before COVID to 6.04% during the COVID Progression period.

This comparison shows a change in inflation patterns; it does not establish that the pandemic alone caused the increase.

### 5. Crude Oil Price & CPI Correlation

- Compared monthly percentage changes in Indian Basket crude oil prices with CPI index changes.
- Calculated category-wise Pearson correlation coefficients.
- Observed a very weak positive correlation between crude oil price changes and the General CPI Index in the selected period.

**Methodological note:** Correlation does not establish causation. The analysis uses 29 monthly observations from January 2021 to May 2023.

## Dashboard

The final Excel dashboard presents:

- Latest CPI Index
- General YOY Inflation
- Food YOY Inflation
- CPI trend chart
- Analytical category share chart
- COVID-19 impact comparison
- Food category comparison
- Crude oil and CPI correlation chart

## Data Limitations

- The dataset covers January 2013 to May 2023.
- April 2019 observations are missing for all three sectors in the source dataset.
- Missing observations were not replaced with zero or artificially estimated values.
- Some annual averages are based on fewer than 12 available monthly observations.
- The food index and category-share calculations are analytical measures, not official weighted inflation measures.

## Data Sources

- CPI dataset: Add the original dataset source and download link here.
- Indian Basket crude oil prices: [Petroleum Planning & Analysis Cell (PPAC)](https://ppac.gov.in/prices/international-prices-of-crude-oil?article_id=432919950.0)

## Project Status

**Excel analysis and dashboard:** Completed, subject to final workbook review and presentation corrections.

## Author

**Subhadip Gorai**

Aspiring Data Analyst

Skills: Excel | SQL | Python | Power BI

GitHub: [https://github.com/subhadip-gorai/India-CPI-Inflation-Analysis]
