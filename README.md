# Layoff Landscape: Analyzing Patterns and Trends in Workforce Reductions

## Description
This project aims to analyze a dataset containing information about layoffs in companies across various industries and locations. The dataset includes details such as company names, locations, industries, total number of employees laid off, percentage of employees laid off, dates of layoffs, company stages, countries, and funds raised. The analysis encompasses data cleaning, exploratory data analysis (EDA), and feature engineering to gain insights into the patterns and trends related to layoffs.

## Key Findings
1. **Data Cleaning and Preprocessing:** Missing values in the dataset were handled by imputing with median values, ensuring data integrity for subsequent analysis.

2. **Exploratory Data Analysis (EDA):**
   - **Geographical Analysis:** The San Francisco Bay Area, New York City, Boston, and Bengaluru experienced the highest number of layoffs among all locations.
   - **Industry Comparison:** The retail, consumer, and transportation sectors were heavily affected by layoffs, while industries like real estate and media also faced notable challenges.
   - **Temporal Analysis:** The highest number of layoffs occurred in January 2023, while the lowest number was observed in May 2021.

3. **Feature Engineering:** Additional features like year, month, and day were extracted from the date column to facilitate temporal analysis.

4. **Predictive Modeling:** A Random Forest Regression model was trained and optimized using GridSearchCV to predict the month of layoffs based on various features.

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
