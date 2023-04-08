# BME580 Project: Exploring the Relationship Between Heart Rate Variability and COVID-19 Infection using Wearables Data. 

#### Objectives:
The COVID-19 pandemic has led to a surge in research to better understand the virus and its impact on the human body. HRV has been shown to be a useful indicator of early COVID-19 symptoms. We aim to predict whether and when a subject is infected by COVID-19 using HRV-related features.

#### Data Source:
The data we will be using comes from Welltory COVID-19 and Wearables Open Data Research, which is avaliable at https://github.com/Welltory/hrv-covid19. After data cleaning, our final dataset contains 3245 rows and 25 columns, and we will use the onset date of COVID-19 as the response variable.

#### Tentative Predictive Model Building Approach:
We will try two approaches to handle the large number of features of the data set: removing highly correlated variables and performing PCA. We will then explore different models, including logistic regression, random forest, and support vector machine. To make use of the time-series structure of the data, we will use sliding windows of the data, and may also use the rr_data variable if necessary.

#### Project Updates:
All modeling progress will be tracked and updated via frequent updates to the Github file.
Current Progress: Building models & Performance measurement

Model list: logistic regression, LDA, decision tree, random forest, svm
