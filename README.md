# UCS654-Sampling

This notebook is a comparison of different sampling techniques on the credit card fraud dataset.
The dataset is highly imbalanced and the techniques used are:
1. Simple Random Sampling
2. Stratified Sampling
3. Systematic Sampling
4. Cluster Sampling
5. Multi-Stage Sampling 

The models used are:
1. Logistic Regression
2. Decision Tree Classifier
3. Gaussian Naive Bayes
4. Support Vector Machine
5. KNN

## Table

|                        |Simple Random Sampling | Stratified Random Sampling | Systematic Sampling | Cluster Sampling| Multi-Stage Sampling |
| ---------------------- | --------------------- | -------------------------- | ------------------- | --------------- | -------------------- |
|Logistic Regression     |              0.88764  |                 0.913265   |         0.792208    |       0.895652  |               0.86   |
|Decision Tree           |             0.985019  |                 0.969388   |         0.922078    |       0.982609  |               0.94   |
|Naive Bayes             |             0.749064  |                 0.760204   |         0.779221    |       0.652174  |               0.72   |
|Support Vector Machine  |             0.689139  |                 0.617347   |          0.61039    |       0.669565  |                0.6   |
|KNN                     |             0.981273  |                 0.959184   |         0.922078    |           0.8   |              0.86    |

## Conclusion
By Understanding this we get highest accuracy for Decision Tree Classifier in Simple Random Sampling with 98.5019% accuracy.

## This was created by Rishab Chakrabarti, Roll no:102003688
