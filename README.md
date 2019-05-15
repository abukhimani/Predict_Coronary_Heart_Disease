# Predict_Coronary_Heart_Disease
Capstone Project for the Flatiron School Data Science Bootcamp Immersive Program

### Motivation:
The motivation for this project was to indentify certain health, lifestyle, and nutrition related questions that could be asked in a non-clinical setting (examples: website, mobile apps) to identify if someone could be at risk for coronary heart disease (CHD). The application could be for pharmaceutical/healthcare companies to identify target audience to include in a disease awareness program - CRM emails or targeted digital advertising.

### Data Source:
- National Health and Nutrition Examination Survey (NHANES) data from 2015-2016.
- Identified 36 features from the Demographics, Examination, and Questionnaire datasets
- **Target: if a survey participant was ever told by a healthcare professional that they had coronary heart disease (CHD) - this is one of the questions on the NHANES medical conditions questionnaire**
- Segmented data to only include adults between the age group of 18-65



### Identified 36 Feature Questions from NHANES datasets:

![Features](https://github.com/abukhimani/Predict_Coronary_Heart_Disease/blob/master/imgs/36-features.png)


### Class Imbalance
Cleaned data included:
 - 80 positive cases (participant was told they had CHD)
 - 4343 negative cases (no CHD)
 
### Best Model: Logistic Regression w/ Parameter Tuning

![Best Model](https://github.com/abukhimani/Predict_Coronary_Heart_Disease/blob/master/imgs/Best_Model.png)


**Recall score of 0.73**





