# Heart-attack-classification-model
Supervised machine learning algorithms used to predict the probability of patients getting a heart attack.

## 1. Installation:
All libraries that are used in this project are installed with the Anaconda distribution.

## 2. Project Motivation:

Heart attack is a serious medical condition that may be life-threatening. It is happened because of a blockage in the blood vessels that disrupt the flow of the blood to the heart. The cause of the heart attack is that some substances like cholesterol, calcium, fats, proteins, and inflammatory cells are build up in the blood vessels and form plaques. Sudden ruptures of the plaques lead the platelets to cover it up, consequently, a clot is formed in the blood vessel and narrows, or completely blocks the pathway of the blood to the heart. The lack of blood supply leads to a lack of oxygen that's needed for the heart to function, this can damage or destroy part of the myocardium (heart muscles).

Researchers find that there are a lot of risk factors for getting a heart attack, like the increase in age, high blood cholesterol, high blood pressure, etc. Therefore, it is critical to know the probability of getting a heart attack based on these risk factors to prevent it, or at least early detect it to save patients' life.

## 3.File Descriptions:

#### Heart_attack_project.ipynb:
A Jupyter notebook with all the python codes that were used to create the ML model.
### heart_disease_uci.csv: 
The source of the dataset

## 4. Project Details:
The main objective of this project was to to analyze the patients' medical records like their blood pressure, cholesterol level, blood sugar, etc. Furthermore, a ML algorithm was be used to classify the patients based on the probability of having a heart attack.

The first thing that conflicted with the analysis process is the existance of some missing values in the numerical colums. For this, all the null values were replaced with the mean of the patients' records in the same heart attack class in the dataset. 

Secondly, the dataset contains some categorical columns with important data for the ML model .For that, A function was used to create dummy variables for that column. 

The model in this project is able to predict the probability of patients getting a heart attack with accuracy of 82.60% and f1-sccore of 83%.

The results are shared in this link: [click_here](https://gftawfiq.wixsite.com/heart-attack-project/post/heart-attack-classification-model)

## 5. Author:
This project was created by Ghofran Al Tawfiq
## 6. Data Source:
Kaggle.com[Data Source](https://www.kaggle.com/redwankarimsony/heart-disease-data)

