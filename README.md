# Statistical-Analysis-on-Cardiac-Failure

### Problem Statement: 
To predict the survival of patients that have suffered a Cardiac Failure

### Introduction:
Cardiac Failure occurs when the heart is not able to pump enough blood to the body.

Cardiac Failure are only a subgroup of all the cardiovascular diseases that comprehend also coronary heart diseases (heart attacks), cerebrovascular diseases (strokes) and other pathologies that altogether kill every year approximately 17 million people around the world.

Statistical Tools applied to medical records can be useful to predict the survival of a patient, highlighting the features to understand which are risk factors, possibly undetectable by doctors.

In this notebook the analysis will be done starting from an EDA to understand the dataset and applying some Hypothesis to be able to learn properly from it.

Then will follow a number of Statistical models trained on the dataset, aiming to predict the survival of patients that suffered Cardiac Failure.

The results are presented at the end of the notebook.

### Table of Contents

1.  Features Description

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

13. Hypothesis Testing - Survival Prediction Classifiers
    
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



### Feature Description

1. Age: Age of the patient in Years [40,..., 95]

2. Anaemia: Decrease of red blood cells or hemoglobin

3. High blood pressure: If a patient has hypertension

4. Creatinine phosphokinase: Level of the CPK enzyme in the blood mcg/L [23,..., 7861] (CPK)

5. Diabetes: If the patient has diabetes 

6. Ejection fraction: Percentage of blood leaving Percentage [14,..., 80] the heart at each contraction

7. Sex: Male and Female

8. Platelets: Platelets counts in the blood 

9. Serum creatinine: Level of creatinine in the blood mg/dL [0.50,..., 9.40]

10. Serum sodium: Level of sodium in the blood mEq/L [114,..., 148]

11. Smoking: If the patient smokes 

12. Time: Follow-up period Days [4,...,285]

13. Death Event: If the patient died during the follow-up period (TARGET VARIABLE)

### Conclusion
- Descriptive statistics were calculated to determine the clinical characteristics and outcomes of the registry population

- Data was presented as numbers and frequencies for categorical variables and as mean ± standard deviation with interquartile range for continuous variables

- For the comparison between groups like Normality, Shapiro, Pearson, Hypothesis Testing (Mann-Whitley U Test, Wilcoxon Signed Rank Test, 2 Way ANOVA) was used for categorical variables

- Concordance was expressed as the percentage agreement. Pearson’s correlation was used to calculate the Correlation between the Numerical Columns

- In our work, the fact that our Biostatistics analysis selected ejection fraction and serum creatinine as the two most relevant features predicted the Survival of the Patient

- Additional information about the physical features of the patients (height, weight, body mass index, etc.), Geographical Region had been available and their family history of Heart Disease would have been useful to predict more accurate additional risk factors for cardiovascular health diseases. 
