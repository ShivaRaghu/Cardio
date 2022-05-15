# [Cardiovascular dataset](https://github.com/ShivaRaghu/Cardio) 
Goal: Design questionnaire to predict mortality by heart failure

Build Classification Tree Model to predict the health outcome

Introduction:Cardiovascular diseases (CVD) which are one of the major cause of death can be prevented by addressing behavioral risk factors such as smoking, and unhealthy diet(high sodium intake). 
Preexisting conditions such as diabetes, hypertension also increases the risk of CVD. 
Our goal is to build machine learning models to help early detection and management of CVD.

Goal: 
- Perform exploratory data analysis on Cardiovascular diseases (CVD) dataset.
- Plot decision tree with significant predictors.
- Also,make predictions on the basis of decision tree.

Introduction:Cardiovascular diseases (CVD) are one of the major cause of death worldwide. They can be prevented by addressing behavioral risk factors such as smoking, and unhealthy diet (high sodium intake). Preexisting conditions such as diabetes, hypertension also increases the risk of CVD. Our goal is to build machine learning models to help early detection and management of CVD.

The data obtained from the following citation comprised of 13 variables/vitals recorded on 299 patients, with 105 women and 194 men:
Study reference: Davide Chicco, Giuseppe Jurman: Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone. BMC Medical Informatics and Decision Making 20, 16 (2020).
DOI: https://doi.org/10.1186/s12911-020-1023-5

Data Cleaning: After understanding CVD dataset, I loaded libraries and coersed following variables into factors. DEATH_EVENT, anaemia, diabetes, high_blood_pressure, sex,and smoking. After coersing, I explored the relationship of each variable with DEATH_EVENT variable to identify the strongly correlated ones. 

For further analysis I changed the level names for diabetes, high_blood_pressure, smoking, and anaemia to No(0), Yes(1) . For clarity purposes, I renamed the sex variable levels to "Woman" (0) and 'Man"(1) and for DEATH_EVENT, I renamed levels to "Survived"(0), 'Dead'(1).  



