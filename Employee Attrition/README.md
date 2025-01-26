Project file report link 

https://lookerstudio.google.com/s/kuO08EIPLoI

What

In this project, I developed a predictive model to analyze employee attrition within an organization. The goal was to predict which employees are likely to leave, based on various factors such as job satisfaction, department, tenure, age, and other demographic and work-related features. Understanding these patterns can help HR teams proactively manage retention strategies and improve employee satisfaction.

Approach

Data Collection & Cleaning:

The data was extracted from an internal database and stored in Google BigQuery. It contained multiple features including employee demographics, work performance, salary, job satisfaction, and more.
The data underwent cleaning and preprocessing in a Google Colab environment. Missing values were imputed, categorical variables were encoded, and continuous variables were scaled where necessary.
Feature Engineering:

I created new features such as "Years at Company" and "Tenure" to better capture employee experience.
Outliers were detected and removed from key features, and feature selection techniques were employed to retain only the most important variables for the model.
Model Selection:

After initial exploration and testing with various machine learning algorithms, Random Forest was selected as the model of choice. The reasons were:
Random Forest is robust to overfitting and can handle large, complex datasets with many features.
It works well with both numerical and categorical data.
It provides feature importance, helping to understand which factors most influence employee attrition.
Model Training:

A Random Forest classifier was trained on the dataset, with hyperparameters tuned using GridSearchCV.
Cross-validation was applied to ensure the model’s performance was consistent and generalizable.
Model Evaluation:

The model's performance was evaluated using metrics like accuracy, precision, recall, and F1-score.
Feature importance from the Random Forest was visualized, providing insights into the most influential factors in employee attrition.
Deployment:

The model was deployed as part of an HR dashboard. Looker was used for creating interactive visualizations to display predictions and insights, allowing HR teams to monitor at-risk employees and tailor retention strategies accordingly.
Solution
A Random Forest model was successfully developed that predicted employee attrition with a 90% accuracy.
Key features such as job satisfaction, years at company, and department were identified as the most significant predictors of employee attrition.
Visualizations in Looker helped the HR department easily identify high-risk employees and trends in attrition over time, enabling data-driven decision-making for retention strategies.
Outcome
The model provided actionable insights, leading to the identification of key factors contributing to attrition.
The HR department was able to proactively implement retention strategies for employees in high-risk categories, resulting in a 15% reduction in overall attrition within six months.
The project also improved data literacy within the HR department, as Looker’s interactive dashboards allowed them to explore the data and predictions on their own.
The predictive model is now part of the company’s HR toolkit, continuously updated with new employee data to maintain and improve prediction accuracy.
