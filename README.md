# Soldier_race
Implementing many algorithms commonly used for Multi-Class Classification problems such as Logistic Regression, Support Vector Machine, XGBoost and Random Forest algorithms, also enhancing the scores with SMOTE, using SHAP to explain how the best model.

**Welcome!**

In this project, you will apply Exploratory Data Analysis (EDA) processes to develop predictive models. You'll face challenges such as handling outliers, utilizing domain knowledge, and performing feature engineering.

## Project Overview

This project aims to enhance your ability to implement algorithms for Multi-Class Classification. You'll have the opportunity to implement several algorithms commonly used for Multi-Class Classification problems.

## Data Source

The dataset used in this project is the 2012 US Army Anthropometric Survey (ANSUR II), conducted by the Natick Soldier Research, Development and Engineering Center (NSRDEC) from October 2010 to April 2012. It comprises data from personnel representing the entire US Army force, including Active Duty, Reserves, and National Guard members. In addition to anthropometric and demographic data, the ANSUR II database also includes 3D body scans of participants.

- Total Anthropometric Measurements: 93 (Directly Measured)
- Demographic/Administrative Variables: 15

The ANSUR II Male working database contains 4,082 subjects, while the ANSUR II Female working database contains 1,986 subjects.

**Data Dictionary**: [ANSUR II Data Dictionary](https://data.world/datamil/ansur-ii-data-dictionary/workspace/file?filename=ANSUR+II+Databases+Overview.pdf)

To achieve high prediction success, you must thoroughly understand the dataset and develop various approaches that can influence the dependent variable. Start by exploring the dataset column by column using the pandas module and conducting domain-specific research online to gain insights quickly.

You will implement the following algorithms:
- Logistic Regression
- Support Vector Machine
- XGBoost
- Random Forest

Evaluate the success of your models using appropriate performance metrics. Choose the most successful model and try to enhance the scores using SMOTE. Additionally, use SHAP to explain how the best model works.

## Project Tasks

### 1. Exploratory Data Analysis (EDA)

- Import Libraries
- Ingest Data
- Explore Data
- Outlier Detection
- Drop Unnecessary Features

### 2. Data Preprocessing

- Scale the data if needed
- Separate the data frame for evaluation purposes

### 3. Multi-class Classification

- Import libraries
- Implement SVM Classifier
- Implement Decision Tree Classifier
- Implement Random Forest Classifier
- Implement XGBoost Classifier
- Compare The Models

**Note:** During the EDA, consider dropping unnecessary columns and the "DODRace" class if the value count is below 500, as it may affect the model's ability to learn effectively.

---

Feel free to tailor this template to your specific project, adding more details or sections as needed. Good luck with your project!

