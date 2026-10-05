
# Supervised Learning — Final Report

## Best model: Logistic Regression
- Accuracy: 0.8156
- F1: 0.7442
- ROC-AUC: 0.8422

## All models (sorted by ROC-AUC):
               Model  Accuracy     F1  ROC-AUC
 Logistic Regression    0.8156 0.7442   0.8422
  LightGBM (default)    0.7877 0.7206   0.8376
       Random Forest    0.7933 0.7218   0.8331
    LightGBM (tuned)    0.7709 0.6822   0.8263
   XGBoost (default)    0.7877 0.7121   0.8250
     XGBoost (tuned)    0.8045 0.7107   0.8221
KNN (k=11, distance)    0.7151 0.6107   0.7428
      SVM (rbf, C=1)    0.6257 0.3232   0.6974
