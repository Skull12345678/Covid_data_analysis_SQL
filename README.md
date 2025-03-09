# COVID-19 Data Analysis Using SQL Server

## Overview
This project focuses on analyzing COVID-19 data using SQL Server to clean, explore, and extract meaningful insights. The analysis includes data cleaning, statistical computations, correlation analysis, ranking, and predictive modeling to help understand trends and patterns in COVID-19 cases.

## Features
- **Data Cleaning**: Handling missing values in crucial fields like Province, Country, Latitude, Longitude, Date, Confirmed, Deaths, and Recovered. Missing numerical values are replaced with 0 to prevent errors during analysis.
- **Descriptive Statistics**:
  - Total number of rows
  - Time range (start_date to end_date)
  - Number of months covered
  - Min, max, and total values of Confirmed, Deaths, and Recovered cases per month
  - Measures of central tendency: Mean, Median, and Mode
  - Measures of dispersion: Range, Variance, and Standard Deviation
- **Percentiles and Frequency Distributions**:
  - Analysis of case distributions across different time periods
  - Identification of top 10 most affected periods and locations
- **Correlation Analysis**:
  - Strength of relationships between Confirmed cases, Deaths, and Recoveries
  - Strong positive correlation between Confirmed cases and Deaths (0.7917)
  - Moderate correlation between Confirmed and Recovered cases (0.68807)
  - Moderate correlation between Deaths and Recovered cases (0.60565)
- **Ranking and Row Numbering**:
  - Sorting records based on Confirmed cases
  - Identifying the most affected regions and months
- **Predictive Modeling (Linear Regression)**:
  - Estimating Deaths based on Confirmed cases using the equation: **y = 0.0136x + 9.99**
  - Predicts that every increase of 100 Confirmed cases results in approximately 1.36 additional Deaths

## Insights & Impact
- Highlights seasonal variations in COVID-19 case numbers.
- Demonstrates strong correlations between Confirmed cases and Deaths.
- Provides a predictive model for estimating Death tolls based on rising infection numbers.
- Assists policymakers, healthcare professionals, and researchers in making data-driven decisions for resource allocation and pandemic management.

## How to Use
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/covid19-sql-analysis.git
   ```
2. Open SQL Server and import the dataset.
3. Run the provided SQL scripts to perform analysis and generate insights.

## Requirements
- Microsoft SQL Server
- COVID-19 dataset (to be imported into SQL Server)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
[Your Name](https://github.com/your-username)

## Acknowledgments
- Data sourced from reliable COVID-19 repositories.
- Inspiration from data science methodologies and SQL analytics best practices.
