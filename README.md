# youtube-video-performance-analytics
End-to-end data analysis and machine learning project using multiple regression models to identify key drivers of YouTube video performance, 
including engagement, retention, and revenue metrics.


## Overview
This project analyzes YouTube video performance using 364 videos and 70 features to understand engagement, retention, and revenue drivers.

Multiple regression and machine learning models were used to predict:
- Average View Percentage
- Watch Time
- Revenue per 1000 Views


## Objective
Identify key factors that influence:
- Viewer retention
- Engagement behavior
- Monetization performance


## Methods
- Multiple Linear Regression
- Ridge Regression (with GridSearchCV)
- Random Forest Regressor
- OLS Regression
- Feature selection using VIF & correlation analysis
- Cross-validation for model validation


## Key Results
- Average View % model: R² = 0.78
- Watch Time model: R² = 0.97
- Revenue per 1000 views model: R² = 0.79



## 🔍 Key Insights
- Video duration strongly affects retention negatively
- Average view duration is the strongest predictor of engagement
- Views and impressions are major drivers of watch time
- Monetization depends more on ad-quality metrics than engagement alone



## Full Report
See detailed analysis with visuals and findings:
[Download Full Report](docs/YouTube_Analytics_Project_Report.pdf)
