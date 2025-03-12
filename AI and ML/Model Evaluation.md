# Model Evaluation

## Confusion Matrix
    - Precision: Best when false postives are costly
    - Recall: Best when false negatives are costly
    - Accuracy: Best wehn you want a balance between precision and recall, especially in imbalanced datasets
    - F1 Score: Best for balanced datasets
- Confusion matrix can be multi-dimensional
- Best way to evaluate the performance of a model that does classification 

## AUC-ROC

-  Area under the curve-reciever operator curve
- Value from 0-1 (perfect model)
- Uses senstivity (true positive rate) and "I-specificity" (false positive rate)

## Regression Metrics
- MAE - Mean Absolute Error
    - Between predicted and actual values
- MAPE - Mean Absolute Percentage Error
- RMSE - Root Mean Squared Error
- R squared
    - Explains variance in your model 
    - R2 close to 1 means predictions are good
