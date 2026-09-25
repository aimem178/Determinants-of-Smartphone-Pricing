## Determinants of Smartphone Pricing

## Overview

This quantitative business analytics project examines the factors that influence smartphone prices in a highly competitive global market. The study investigates whether retail prices are mainly explained by hardware specifications such as RAM, battery capacity, camera megapixels, and charging power, or whether other factors such as brand value and ecosystem play a larger role.

The analysis was conducted using a secondary dataset containing **558 smartphone observations** from five major brands: Apple, Samsung, Google, Xiaomi, and OnePlus. The main objective was to identify statistically significant relationships between smartphone features, brand, 5G connectivity, and retail price.

## Data Preparation & Management

The project used secondary market data containing information about smartphone prices, hardware specifications, brands, operating systems, and 5G support.

The dataset was first cleaned and prepared for statistical analysis. This included checking the data structure, handling inconsistencies, and standardizing categorical and numerical variables such as brand, operating system, price, RAM, and ROM. The cleaned dataset was then prepared for inferential statistical testing in IBM SPSS.

## Statistical Analysis

IBM SPSS Statistics was used to conduct several statistical tests and develop a pricing model.

### One-Way ANOVA

A One-Way ANOVA was performed to examine whether average smartphone prices differed significantly among the five brands. This helped assess whether certain brands showed a statistically different pricing level within the dataset.

### Independent Samples T-Test

An Independent Samples T-Test was used to compare the prices of **5G and non-5G smartphones**. The purpose was to determine whether 5G connectivity was associated with a statistically significant difference in smartphone prices.

### Multiple Linear Regression

A Multiple Linear Regression model was developed to examine the relationship between smartphone hardware specifications and retail price.

The model used variables such as:

* RAM
* Battery capacity
* Camera megapixels
* Charging wattage

as independent variables, while **retail price** was treated as the dependent variable.

## Key Findings & Business Insights

The statistical analysis provided an interesting view of smartphone pricing. In this dataset, hardware specifications such as RAM, battery capacity, and camera megapixels did not emerge as significant predictors of retail price in the regression analysis.

The ANOVA analysis also did not show a statistically significant difference in average base prices among the five brands.

These findings suggest that smartphone pricing cannot be explained simply by comparing hardware specifications. Factors such as **brand equity, software experience, ecosystem integration, and perceived customer value** may also contribute to how manufacturers position and price their products.

From a business analytics perspective, the project demonstrates how statistical testing can challenge common assumptions and provide evidence-based insights into pricing decisions.

## Key Deliverables

* Cleaned and structured smartphone dataset prepared for statistical analysis.
* IBM SPSS `.sav` dataset containing the processed variables and analysis-ready data.
* Statistical analysis covering ANOVA, Independent Samples T-Test, correlation, and multiple linear regression.
* Regression outputs and diagnostic analysis, including collinearity measures.
* A research report presenting statistical findings and their potential business implications.

## Tools Used

**IBM SPSS Statistics, Python, Pandas, NumPy, Statistical Analysis, Hypothesis Testing, Regression Analysis, Data Cleaning, Data Interpretation**

