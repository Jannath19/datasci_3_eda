# datasci_3_eda
# Exploratory Data Analysis (EDA) Assignment

## Objective
This project was completed as part of an assignment for an Exploratory Data Analysis. The objective was to engage in EDA using Python tools to understand a dataset's characteristics and relationships between variables.

## Dataset Description
This dataset contains the estimated percentage of Californians with asthma (asthma prevalence). Two types of asthma prevalence are included:

1. **Lifetime Asthma Prevalence:** Describes the percentage of people who have ever been diagnosed with asthma by a health care provider.

2. **Current Asthma Prevalence:** Describes the percentage of people who have ever been diagnosed with asthma by a health care provider AND report they still have asthma and/or had an asthma episode or attack within the past 12 months.

The tables "Lifetime Asthma Prevalence by County" and "Current Asthma Prevalence by County" are derived from the California Health Interview Survey (CHIS) and include data stratified by county and age group (all ages, 0-17, 18+, 0-4, 5-17, 18-64, 65+) reported for 2-year periods. The table "Asthma Prevalence, Adults (18 and older)" is derived from the California Behavioral Risk Factor Surveillance System (BRFSS) and includes statewide data on adults reported by year.

## Analysis Steps

### 1. Data Loading
- I loaded the dataset into my Jupyter Notebook (.ipynb) using the pandas library.

### 2. Univariate Analysis
- Performed univariate analysis on each variable, calculating mean, median, mode, range, variance, standard deviation, and IQR.
- Created histograms to visualize the distribution of numerical variables.

### 3. Bivariate Analysis
- Analyzed relationships between pairs of variables.
- Utilized scatter plots to explore potential relationships between numerical variables.
- Employed boxplots for categorical and numerical variable pairs.
- Calculated correlation coefficients for numerical variables and documented strong correlations.

### 4. Handling Outliers
- Identified outliers using the IQR method and visualization tools.
- Dataset did not have any outliers. 

### 5. Automated Analysis
- Utilized pandas-profiling for automated EDA.
- Saved the output as an HTML file within the "automaticEDA" folder.

## Repository Structure

- **datasets:** Contains the dataset used for the EDA.
- **automaticEDA:** Contains the automated EDA output in HTML format.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- pandas-profiling
