# [Cardiovascular dataset](https://github.com/ShivaRaghu/Cardio) 
Goal: Design questionnaire to predict mortality by heart failure

Build Classification Tree Model to predict the health outcome

Introduction:Cardiovascular diseases (CVD) which are one of the major cause of death can be prevented by addressing behavioral risk factors such as smoking, and unhealthy diet(high sodium intake). 
Preexisting conditions such as diabetes, hypertension also increases the risk of CVD. 
Our goal is to build machine learning models to help early detection and management of CVD.

```{r setup, include=FALSE}
# load libraries
library(tree)
library(survival)
library(rpart)
library(ggplot2)
library(rpart)
library(rpart.plot)
library(vcd)
library(corrplot)
library(RColorBrewer)
heart_data <- read.csv("~/Desktop/TDA COURSES/TDAI_5620_SU21/R_code_TDAI5620SU21/heart_failure_clinical_records_dataset.csv")
# coerce categorical variables into factors
heart_data$anaemia <- as.factor(heart_data$anaemia)
heart_data$diabetes <- as.factor(heart_data$diabetes)
heart_data$high_blood_pressure <- as.factor(heart_data$high_blood_pressure)
heart_data$sex <- as.factor(heart_data$sex)
heart_data$smoking <- as.factor(heart_data$smoking)
heart_data$DEATH_EVENT <- as.factor(heart_data$DEATH_EVENT)
str(heart_data)
