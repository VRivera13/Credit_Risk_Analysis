# Credit_Risk_Analysis

## Overview
Creidt worthiness is always hard to predict.  The risks are high depending on the economic situation.    Using the loan_stats.csv data provided, the factors within the file will be used to assist with predicting whether an applicant is a low or high credit risk.    Using imbalanced-learn and scikit-learn libraries to build models will be useful in the decision making process.

## Results of Six Machine Learning Models

- Naive Random Oversampling
    - Balanced Accuracy Score:  64.8%
    - Overall Precision:  1% 
    - Overall Recall: 60%
 
![insert screenshot](https://github.com/VRivera13/Credit_Risk_Analysis/blob/main/images/Naive%20Random.png)

- SMOTE Oversampling
    - Balanced Accuracy Score:  66.3%
    - Overall Precision:  1%  
    - Overall Recall: 69%
 
![insert screenshot](https://github.com/VRivera13/Credit_Risk_Analysis/blob/main/images/SMOTE.png)

- Undersampling
    - Balanced Accuracy Score:  66.3%
    - Overall Precision:  1%  
    - Overall Recall: 40%
 
![insert screenshot](https://github.com/VRivera13/Credit_Risk_Analysis/blob/main/images/Undersampling.png)

- Combination Sampling
    - Balanced Accuracy Score:  54.5%
    - Overall Precision:  1%  
    - Overall Recall: 58%

![insert screenshot](https://github.com/VRivera13/Credit_Risk_Analysis/blob/main/images/Combination.png)

- Balanced Random Forest Classifier
    - Balanced Accuracy Score:  77.2%
    - Overall Precision:  1%  
    - Overall Recall: 87%

![insert screenshot](https://github.com/VRivera13/Credit_Risk_Analysis/blob/main/images/Balanced%20Random%20Forest.png)

- Easy Ensemble AdaBoost Classifier
    - Balanced Accuracy Score:  91.8%
    - Overall Precision:  1%  
    - Overall Recall: 94%

![insert screenshot](https://github.com/VRivera13/Credit_Risk_Analysis/blob/main/images/AdaBoost.png)

## Summary
Differences noticed were in the accuracy scores and the overall recall percentages.   The first four models were fairly low compared to the last two models.    Based on the data, it appears using the classifiers provides a much better outcome, escpecially the Easty Ensemble AdaBoost Classifier.    This model provided a much higher balanced accruacey score along with balance between the overall precision and recall.    
