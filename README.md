# Credit_Risk_Analysis

## Overview
In this activity we leveraged a vareity of tools to train and evaluate outputs from models with the goal of predicting Credit Risk.

## Results

### Naive Oversampling

![Naive Oversampling](https://github.com/madrivers/Credit_Risk_Analysis/blob/main/Resources/Naive%20Over.png)

- Accuracy Score of ~62.4%
- Precision High Score 1%
- Precision Low Score 100%
- Recall High Score 60%
- Recall Low Score 65%


### SMOTE 
![SMOTE](https://github.com/madrivers/Credit_Risk_Analysis/blob/main/Resources/Smote.png)

- Accuracy Score of ~62%
- Precision High Score 1%
- Precision Low Score 100%
- Recall High Score 57%
- Recall Low Score 67%
 
### ClusterCentroids Undersampling
![CC Under Sampling](https://github.com/madrivers/Credit_Risk_Analysis/blob/main/Resources/Under%20S.png)

- Accuracy Score of ~51%
- Precision High Score 1%
- Precision Low Score 100%
- Recall High Score 59%
- Recall Low Score 44%

### SMOTEENN
![SMOTEENN](https://github.com/madrivers/Credit_Risk_Analysis/blob/main/Resources/Smoteen.png)

- Accuracy Score of ~62%
- Precision High Score 1%
- Precision Low Score 100%
- Recall High Score 69%
- Recall Low Score 54%

### Easy Ensemble Classifying
![Easy Ensemble](https://github.com/madrivers/Credit_Risk_Analysis/blob/main/Resources/East%20Ebsemble.png)

- Accuracy Score of ~92.5%
- Precision High Score 7%
- Precision Low Score 100%
- Recall High Score 91%
- Recall Low Score 94%

### Balanced Classifying
![Balanced](https://github.com/madrivers/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Forest.png)

- Accuracy Score of ~67%
- Precision High Score 73%
- Precision Low Score 100%
- Recall High Score 34%
- Recall Low Score 100%

## Summary / Recommendation
The end goal is to identify a model that could be useful in assesing credit risk.

The Ensemble model brings the most benefits to the analysis than any other model.  With an accuracy of 92.5% it predicts best the high risk items.  SMOTEEN and Naive do a decent job of the same.  The low precision of Ensemble points out that we the organization may miss out on potentially good loans, but that is a generally accepted risk with modeling.

I would recommend the Easy Ensemble model as the best approach, with perhaps a secondary review (even on a sample basis) of declined credit applications in an attempt to reduce leaving good business on the table.
