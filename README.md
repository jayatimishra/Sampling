# Sampling 

This repository contains solution to sampling assignment for UCS654

### Highlights:
-The given dataset is severely imbalanced (9:763 imbalance ratio)
-Technique used to tackle the imbalance: SMOTE


The following techniques were used to create samples from the given dataset:

- Random Sampling
- Systematic Sampling
- Stratified Sampling
- Cluster Sampling
- Convenience Sampling


The samples so obtained were then trained using the models herewith:

- Logistic Regression (lr)
- Random Forest Classifier (rf)
- Support Vector Machine (svm)
- Decision Tree Classifier (dtree)
- K Nearest Neighbors Classifier (knn)

### Extrapolation and Insights: (After cross-validation)

Accuracy on test set:
|      | Random | Systematic | Stratified |  Cluster   | Convenience |
|------|--------|------------|------------|------------|-------------|
| lr   | 0.901	| 0.774      | 0.934      | 0.920      | 0.983       |
| rf   | 0.902  | 0.967      | 0.985      | 0.992      | 0.983       |
| svm  | 0.804  | 0.838      | 0.985      | 0.966      | 0.983       |
| dtree| 0.803  | 0.838      | 0.967      | 0.984      | 0.950       |
| knn  | 0.551  | 0.645      | 0.953      | 0.947      | 0.983       |


The Random Forest Classifier has clearly outperformed its counterparts!
