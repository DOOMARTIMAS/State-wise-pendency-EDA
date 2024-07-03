Judgement Pendency Prediction: Analyzing Case Resolution Time in Indian Courts
Overview
This project aims to analyze and predict the pendency of legal cases in Indian courts, focusing on cases from the year 2010. Utilizing a dataset with various features related to case details, judge information, and timelines, we perform extensive exploratory data analysis (EDA) and develop predictive models to estimate the duration of case pendency.

Objectives
Data Cleaning and Preprocessing: Handling missing values and converting date fields into categorical periods.
Exploratory Data Analysis (EDA): Understanding the distribution of pendency across different states, identifying patterns, and visualizing relationships between variables.
Predictive Modeling: Implementing machine learning models to predict case pendency, with a focus on identifying cases that are likely to remain unresolved for six years or more.
Insights and Interpretation: Drawing meaningful insights from the analysis and model predictions to understand factors contributing to prolonged case durations.
Key Features
Data Analysis and Visualization: Generate comprehensive visualizations to illustrate state-wise pendency, gender distribution of defendants and petitioners, and other relevant features.
Machine Learning Models: Develop and evaluate models, including Bagging Tree Classifiers, to predict long-term case pendency.
State-wise Analysis: Provide detailed insights into the performance of different states in terms of case resolution times.
Methodology
Data Preprocessing: Cleaning the dataset by removing irrelevant columns and handling missing values.
EDA:
Calculate the mean pendency period for each state.
Analyze gender distribution among defendants and petitioners.
Visualize the relationship between various features and case pendency.
Model Training:
Split the data into training and test sets.
Train a Bagging Tree Classifier to predict case pendency.
Evaluate model performance using accuracy, classification reports, log loss, and ROC AUC.
Visualization: Use geospatial libraries to create maps showing state-wise pendency and other significant visual insights.
Results
State-wise Analysis: Identify states with the highest and lowest average pendency periods.
Gender Analysis: Compare the distribution of male and female defendants and petitioners.
Predictive Performance: Assess the accuracy and reliability of the predictive models.
Conclusion
The project provides valuable insights into the factors influencing case pendency in Indian courts and demonstrates the application of machine learning techniques to predict case outcomes. These findings can help streamline judicial processes and identify areas requiring policy intervention to reduce case backlog.

Keywords:
Judgement Pendency
Case Resolution Time
Indian Courts
Exploratory Data Analysis (EDA)
Predictive Modeling
Bagging Tree Classifier
Data Visualization
