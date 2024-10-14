# Exploratory Data Analysis (EDA) on House Sale Prices

## Introduction
This project involves exploratory data analysis (EDA) on a housing dataset to understand the factors affecting house sale prices. The analysis provides insights into the relationships between various features and the target variable, SalePrice.

## EDA Steps Followed
1. **Data Loading and Initial Exploration**
   - Loaded the dataset and performed initial data checks.

2. **Data Cleaning**
   - **Handling Duplicate Records:** Identified and removed duplicate entries.
   - **Addressing Missing Values:**
     - Analyzed the impact of missing values on each column.
     - Dropped columns with more than 80% missing values.
     - Imputed remaining missing values with appropriate statistical measures.
   - **Converting Data Types:**
     - Converted date columns from integer to datetime format.

3. **Univariate Analysis**
   - Analyzed individual features to understand their distribution and characteristics.

4. **Bivariate Analysis**
   - Examined the relationships between each feature and the target variable, SalePrice, to identify trends and patterns.

## Results
The analysis provided key insights into the housing market, revealing significant relationships between features and SalePrice, which can guide predictive modeling efforts.

## Requirements
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`

## Usage
Run the Jupyter Notebook to perform the EDA and visualize the findings.

