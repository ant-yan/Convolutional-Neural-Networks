## Housing Value Estimation (ML Model)
This project presents a machine learning approach to estimating home prices using a fully connected neural network. The model is trained on a structured dataset originally from a Kaggle competition involving residential property sales. The objective is to build a predictive system capable of providing close approximations of house prices using both categorical and continuous data inputs.

### Model Description
* Architecture: Multilayer perceptron with dropout layers for improved generalization
* Loss Function: Mean Squared Error (MSE)
* Performance Metrics: Root Mean Squared Error (RMSE), Coefficient of Determination (R²)

### Performance Summary
**Training Data:**
* RMSE: ~908,700
* R²: 0.732

**Testing Data:**
* RMSE: ~1,267,000
* R²: 0.704

### Optimal Training Settings
* Initial Learning Rate: 1e-3
* Total Epochs: 250
* Dropout Probability: 30%

---
The project highlights the importance of data preprocessing, feature handling, and model tuning when addressing regression tasks in real estate price prediction.
