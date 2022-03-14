# ClassicalML_FasionMNIST
Applying Classical Machine Models to compare classification accuracy

Dataset Samples:

![image](https://user-images.githubusercontent.com/12696541/158095025-3f71ed24-6cdd-4e21-8406-a7152d0dd443.png)

Prediction Accuracies (After Hyperparameter Tuning):

KNN: 0.8671 
n_neighbors=5, weights='uniform', p=1

Random Forest: 0.8934
n_estimators=300, max_depth=200, min_samples_split=2, min_samples_leaf=1,  max_features='auto', bootstrap=False, oob_score=False, class_weight=None, n_jobs=-1

SVM: 0.909
C=15, kernel='rbf', gamma='scale'

