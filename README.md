# Global Life Expectancy Analysis (2000–2021)

## Project Overview
This project is a submission for **Stage 0 of the HNG Data Analytics Internship (Cohort 14)**. The objective was to analyze World Health Organization (WHO) and United Nations data to identify global disparities in life expectancy, investigate gender-based differences, and track trends over a 10-year period (2012–2021).

## Dataset Description
The dataset tracks "Life Expectancy at Birth," representing the average number of years a newborn is expected to live. It covers multiple countries and geographic regions from 2000 to 2021.
### Columns
IND_ID → Indicator ID (unique code for life expectancy)<br>
IND_NAME → Name of the indicator (e.g., life expectancy at birth)<br>
GEO_ID → Code for the country/region<br>
GEO_NAME_SHORT → Short name of the country/region<br>
DIM_TIME → Year the data was recorded<br>
DIM_GEO_CODE_M49  → Numeric country/region code based on the United Nations M49 standard.<br>
DIM_GEO_CODE_TYPE → Type of geographic coding system<br>
GEO_NAME_SHORT → Short name of the country/region<br>
DIM_SEX → Gender category (Male, Female, Both)<br>
AMOUNT_N → Main value (life expectancy in years)<br>
AMOUNT_NL → Lower estimate (minimum possible value)<br>
AMOUNT_NU → Upper estimate (maximum possible value)<br>
UNIT_MEASURE → Unit of measurement (years)<br>
OBS_STATUS → Data status (e.g., estimated, actual, etc.)<br>
DATA_SOURCE → Source of the data<br>
COMMENT → Extra notes or explanations<br>



## Data Cleaning & Transformation
The raw dataset was refined to ensure clarity and professional reporting:
* **Feature Selection:** Removed redundant technical ID columns and stagnant data points that did not vary across rows.
* **Renaming:** Standardized column headers (e.g., changed `GEO_NAME_SHORT` to `COUNTRY_REGION`).
* **Normalization:** Rounded life expectancy estimates to two decimal places for easier comparison.

## Key Insights
* **The Global Divide:** A massive 35 year gap exists between the highest and lowest performing nations. 
* **Top Performers:** Japan leads the world (83+ years), followed by Switzerland and Australia.
* **Bottom Performers:** Countries like Lesotho and Eswatini show averages below 50 years.
* **Gender Gap:** In every country analyzed, women consistently live longer than men.
* **Recent Trends:** Analysis shows a noticeable stagnation or dip in life expectancy during 2020 and 2021, likely due to global health challenges.

## Limitations
* The analysis is limited to the timeframe of 2000 to 2021.
* The data focuses on expectancy at birth and does not detail specific causes of mortality or quality of life factors.

## Tools Used
* **Excel:** Data cleaning, pivot tables, and trend visualization.
* **PowerPoint:** Stakeholder reporting and storytelling.

---
**Author:** Aisha Abdulkarim
**Role:** Data Analyst Intern (HNG Cohort 14)
