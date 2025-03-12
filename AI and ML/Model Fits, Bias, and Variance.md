# Model Fits
- In case your model has poor performance, you need to look at its fit
- Overfitting
    - Perform well on training data
    - Underperforms on evaluation data
    - **Low Bias and High Variance**
- Underfitting
    - Model performs poorly on training data
    - **High Bias and Low Variance**
- Balanced
    - Neither overfitting or underfitting
    - **Low Bias and Low Variance**

# Bias
- (Predicted value  - Actual Value)
- High Bias
    - Mpdel doesn't closely match the training data
    - Underfitting
- Reducing th Bias
    - Use more complex model
    - Increase the number of features

# Variance
- How much the performance of a model changes if trained on a different dataset which has a similar distribution
- High Variance
    - Model is very sensitive to changes in the training data
    - Overfitting

- Reducing the Variance
    - Feature Selection
    - Split into training and test datasets multiple times