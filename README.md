# Data-Science-Project

## Project Title: Predicting Stress Levels Using Behavioral and Physiological Data

### General Information:
- Project Authors:  Anna Čivčiša, Līva Mazure, Polina Khrystynchenko
- Motivation: Get meaningfull insight about correlation of daily data with stress levels to be able to better control and understand potential stress factors
- Goal: predict Perceived Stress Scale (PSS) score using daily behavioral, psychological, and physiological data from Stress Detection Dataset taken from Kaggle
- Link to the dataset: https://www.kaggle.com/datasets/swadeshi/stress-detection-dataset

### Guide to the Contents of the Repository
The repository contains all the main file with code that was used to perform the data analysis in the project. All the files are aploaded into tthe main branch. The files named direcly refer to the content. Some codes that are uploaded are not required to perform the steps of the project, but are just supplementary data analysis that helped us to make inttermediate conclusions and proceed further.

#### Content explanation:

MAIN FILES TO PERFORM THE PROJECT:
1) stress_detection.csv: the dataset that was used (sourse: Kaggle)
2) Data_cleaning(done).ipynb: code to analyse the data integrity and clean it => output: "cleaned dataset is created" (future work will be done with cleaned dataset)
4) cleaned_data.csv: stress_detection data sett after cleaning proceedure
5) Correlation_analysis.ipynb: explores correlation between attributes and the lable for each individual separately and all together (whole dataset)
6) Model_training.ipynb: performs training using different models => best model is identified
7) SVR_improvement.ipynb: code that attempts to improve the best model identified in the previous step (SVR for this dataset) 

SUPPLEMENTARY FILES:
1) C7_report.pdf: contains in-depth description of set goals, methods and dataset content
2) feature_importance_exploring.ipynb: explores which variable are most important in the random forest model
