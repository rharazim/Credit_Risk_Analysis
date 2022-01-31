# Credit_Risk_Analysis
## Module 17 Challenge

## Overview
We have been learning and testing different machine-learning algorithms in Python to find out which can best identify high or low credit risk with our given dataset. 

## Results
### Naive Random Oversampling
![Naive Random Oversampling](https://github.com/rharazim/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Naive%20Random%20Oversampling.png)
- Balanced Accuracy Score: 59%
- Precision: 1%
- Recall: 51%

### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/rharazim/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/SMOTE%20Oversampling.png)
- Balanced Accuracy Score: 57%
- Precision: 1%
- Recall: 48%

### Undersampling
![Undersampling](https://github.com/rharazim/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Undersampling.png)
- Balanced Accuracy Score: 57%
- Precision: 1%
- Recall: 58%

### Combination (Over and Under) Sampling
![Combination Sampling](https://github.com/rharazim/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Combination%20Sampling.png)
- Balanced Accuracy Score: 52%
- Precision: 1%
- Recall: 70%

### Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://github.com/rharazim/Credit_Risk_Analysis/blob/main/Module-17-Challenge-Resources/Balanced%20Random%20Forest%20Classifier.png)
- Balanced Accuracy Score: 70%
- Precision: 3%
- Recall: 51%

## Summary
Through testing different machine-learning algorithms, we only achieved a balanced accuracy score of 70% which is not high enough to be useful for accurately predicting credit risk. 70% accuracy is simply not high enough for the risk involved to be viable as a prediction method. Therefore, we would not recommend any of these algoithms be used. We would need to keep testing different algorithms or improve upon the most accurate ones used here. 
