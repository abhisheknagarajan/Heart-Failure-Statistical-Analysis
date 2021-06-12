# Heart-Failure-Statistical-Analysis

# Problem Statement

Statistical Tools applied to medical records can be useful to predict the survival of a patient, highlighting the features to understand which are risk factors, possibly undetectable by doctors.

In this notebook the analysis will be done starting from an EDA to understand the dataset and applying some Hypothesis to be able to learn properly from it.

Then will follow a number of Statistical models trained on the dataset, aiming to predict the survival of patients that suffered Cardiac Failure.


# About this Dataset:

Age -  Age of the patient in Years [40,..., 95]

Anaemia - Decrease of red blood cells or hemoglobin

High blood pressure - If a patient has hypertension

Creatinine phosphokinase - Level of the CPK enzyme in the blood mcg/L [23,..., 7861] (CPK)

Diabetes - If the patient has diabetes 

Ejection fraction - Percentage of blood leaving Percentage [14,..., 80] the heart at each contraction

Sex - Male and Female

Platelets - Platelets counts in the blood 

Serum creatinine - Level of creatinine in the blood mg/dL [0.50,..., 9.40]

Serum sodium - Level of sodium in the blood mEq/L [114,..., 148]

Smoking - If the patient smokes 

Time - Follow-up period Days [4,...,285]

Death Event - If the patient died during the follow-up period 


# Table of Contents

1.  Dataset Description

2.  Importing Libraries

3.  Dataset

4.  Exploratory Data Analysis (EDA)

5.  Data Cleaning

6.  Numerical Data Analysis

7.  Descriptive Statistics

8.  Measure of Dispersion

9.  Measure of Shape

10. Normality Test

11. Shapiro Test

12. Pearson Test of Correlation

13. Hypothesis Testing - 
    Survival Prediction Classifiers
    
    1. Ejection Fraction vs Chances of Survival
    
    2. Serum Creatinine vs Chance of Survival
    
    3. Sodium Serum vs Chance of Survival
    
14. Test on Risk of Heart Failure
 
    1. Test on Ejection Fraction
    
    2. Test on Serum Creatinine
    
    3. Test on Serum Sodium
    
15. Test of Claim within Normal Level
    
    1. Ejection Fraction within Normal Level
    
    2. Serum Creatinine within Normal Level
    
    3. Serum Sodium within Normal Level
    
16. Survival Prediction Plot
    
    1. Serum Creatinine vs Ejection Fraction
    
    2. Serum Sodium vs Ejection Fraction
    
17. Test of Simulation

18. Conclusion for Statistical Analysis


# Conclusion :

1) Descriptive statistics were calculated to determine the clinical characteristics and outcomes of the registry population.

2) Data were presented as numbers and frequencies for categorical variables and as mean ± standard deviation with interquartile range for continuous variables.

3) For the comparison between groups like Normality, Shapiro, Pearson, Hypothesis Testing (Mann-Whitley U Test, Wilcoxon Signed Rank Test, 2 Way ANOVA) was used for categorical variables.

4) Concordance was expressed as the percentage agreement. Pearson’s correlation was used to calculate the Correlation between the Numerical Columns.

5) In our work, the fact that our Biostatistics analysis selected ejection fraction and serum creatinine as the two most relevant features predicted the Survival of the Patient.

6) Additional information about the physical features of the patients (height, weight, body mass index, etc.) ,Geographical Region had been available and their family history of Heart Disease would have been useful to predict more accurate additional risk factors for cardiovascular health diseases.


<h4>Notebook Link : <a href='https://github.com/abhisheknagarajan/Heart-Failure-Statistical-Analysis/blob/main/Statistics%20Presentation%20(Descriptive%2C%20Inferential%2C%20Simulation).ipynb'>Heart_Failure_Statistical_Analysis.ipynb</a></h4>

<h4>Kaggle Link : <a href='https://www.kaggle.com/andrewmvd/heart-failure-clinical-data'>Heart_failure_clinical_records_dataset.csv</a></h4>

<h4>Dataset Link : <a href='https://github.com/abhisheknagarajan/Heart-Failure-Statistical-Analysis/blob/main/heart_failure_clinical_records_dataset.csv'>Heart_failure_clinical_records_dataset.csv</a></h4>

