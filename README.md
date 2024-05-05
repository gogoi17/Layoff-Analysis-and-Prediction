# Layoff-Analysis-and-Prediction

## Description
This project aims to analyze a dataset containing information about layoffs in companies across various industries and locations. The dataset includes details such as company names, locations, industries, total number of employees laid off, percentage of employees laid off, dates of layoffs, company stages, countries, and funds raised. The analysis encompasses data cleaning, exploratory data analysis (EDA), and feature engineering to gain insights into the patterns and trends related to layoffs.

## Key Findings
1. **Data Cleaning and Preprocessing:** Missing values in the dataset were handled by imputing with median values, ensuring data integrity for subsequent analysis.

2. **Exploratory Data Analysis (EDA):**
   - **Geographical Analysis:** The San Francisco Bay Area, New York City, Boston, and Bengaluru experienced the highest number of layoffs among all locations.
   - **Industry Comparison:** The retail, consumer, and transportation sectors were heavily affected by layoffs, while industries like real estate and media also faced notable challenges.
   - **Temporal Analysis:** The highest number of layoffs occurred in January 2023, while the lowest number was observed in May 2021.

3. **Feature Engineering:** Additional features like year, month, and day were extracted from the date column to facilitate temporal analysis.

4. **Predictive Modeling:** A Random Forest Regression model was trained and optimized using GridSearchCV to predict the month of layoffs based on various features. The optimized model achieved high accuracy scores, with an R-squared value of 1.0, indicating a perfect fit on the training data.

## Conclusion
This project provides a comprehensive analysis of a layoff dataset, revealing valuable insights into the industries, locations, and periods most affected by layoffs. The EDA uncovered significant patterns and trends, while the predictive modeling approach demonstrated the potential for forecasting layoffs based on the available features. However, it's important to note that the model achieved a perfect fit on the training data, which may indicate overfitting and limited generalization capability. Further validation on unseen data and additional feature engineering may be necessary to improve the model's robustness and practical applicability.

Overall, this project showcases proficiency in data analysis, visualization, and machine learning techniques, while contributing to a better understanding of the layoff landscape across industries and regions.
