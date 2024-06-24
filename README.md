# ABSENTEEISM DATA ANALYSIS

### Project Overview

This project focuses on analyzing absenteeism data to predict future absenteeism using logistic regression. The analysis involves extensive data preprocessing, including data cleaning, manipulation, transformation, and module generation, ensuring the dataset is suitable for accurate predictive modeling.

### Data Preprocessing

#### Data Cleaning

Date Transformation: Utilized datetime functions to extract and transform 'date' information into meaningful features such as months and days.

Dummy Variable Creation: Converted categorical variables, specifically the reasons for absenteeism, into dummy variables to enhance model performance.

#### Data Manipulation

Variable Selection: Identified and selected relevant variables critical to predicting absenteeism.

Feature Engineering: Created new features from existing data to improve model accuracy.

Scaling: Applied scaling techniques to standardize data ranges.

#### Data Transformation

Categorical Encoding: Encoded categorical variables into numerical values using one-hot encoding for better model interpretation.

Date and Time Feature Extraction: Extracted features from date and time data, such as day of the week, month to capture temporal patterns in absenteeism.

### Module Generation

Data Pipeline Creation: Developed a data pipeline to automate data preprocessing steps for efficient and reproducible analysis.

Function Library: Created a library of reusable functions for data cleaning, manipulation, and transformation tasks.

### Model Generation

#### Logistic Regression Model

Model Training: Trained a logistic regression model using the preprocessed dataset to predict absenteeism.

Model Evaluation: Achieved training and testing accuracy of 78% and 74%, respectively.

### Conclusion

This project provides a comprehensive approach to absenteeism data analysis, emphasizing the importance of thorough data preprocessing. The logistic regression model developed through this analysis offers valuable insights and accurate predictions of absenteeism, aiding in better resource planning and management.
