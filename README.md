# Hospital Care Quality in the Midwest

## Project Summary
The project analyzes healthcare quality measures for hospitals in the Midwest, focusing on various aspects of patient care such as readmission rates, mortality rates, and patient satisfaction. The main objective is to identify and address inconsistencies in healthcare quality across hospitals, highlight areas for improvement, and support initiatives for enhancing patient care and efficiency.

## Methodology
The project employs quantitative analysis on a hospital care quality dataset obtained from Kaggle. The dataset is cleaned and preprocessed to address issues like missing values and data variability. Key tools include Excel for initial data segmentation, MySQL for efficient data storage and querying, and Python for statistical analysis and data visualization. Exploratory Data Analysis (EDA) was conducted, followed by a linear regression model to predict mortality rates based on hospital performance indicators.

## Technology Stack
- **Data Storage and Querying:** MySQL
- **Data Processing and Analysis:** Python (Pandas, NumPy, Scikit-Learn for machine learning)
- **Data Visualization:** Matplotlib, Seaborn for Python-based visualization; Tableau for interactive dashboards
- **Web Application Development:** Django framework to create a user interface for hospital search and ranking based on quality measures

## Results
The analysis revealed significant variability in quality measures across hospitals. For instance, certain states displayed higher efficiency scores, while others had longer emergency department wait times or higher readmission rates. The predictive model achieved an R-squared value of 0.67, indicating a reasonably good fit for predicting mortality rates. The visualization dashboards provided insights into state-wise hospital performance, enabling stakeholders to make data-driven decisions for improving healthcare quality in targeted areas.
