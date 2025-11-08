# ✈️ Flight Price Prediction.

## Project Overview

This project aims to build an accurate and generalizable regression model to predict prices based on input features. Using distance-based and tree-based models and hyperparameter tuning via RandomizedSearchCV, the Random Forest Regressor was identified as the best-performing model.

## Features

- Data preprocessing and exploration (assumed)
- Implementation of multiple tree-based regression models
- Hyperparameter tuning using RandomizedSearchCV with cross-validation
- Model evaluation using metrics: MAE, MSE, RMSE, and R² score
- Final prediction on test data without the target price column
- Recommendation for production deployment of the best model

## Technologies Used

- Python 3.x
- scikit-learn
- pandas
- numpy
- seaborn/matplotlib (optional for visualization)

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed along with the following packages:

- numpy
- pandas
- scikit-learn
- seaborn (optional)

Install the dependencies using pip:


### Running the Project

1. Load and preprocess your training and testing datasets.
2. Define your tree-based models and hyperparameter grids.
3. Run the provided hyperparameter tuning script which performs randomized search with cross-validation.
4. Evaluate model performance on training and test data.
5. Use the recommended Random Forest Regressor model to make final price predictions.
   
## Results

- The Random Forest Regressor with tuned hyperparameters achieved a mean cross-validated R² score of approximately 0.98.
- Metrics like MAE, MSE, and RMSE confirm strong predictive accuracy.
- The model is suitable for deployment in a production environment based on these results.

## Notes

- The test dataset used for prediction did not contain the price column initially.
- It is recommended to evaluate final model performance periodically with fresh data.
- Adjust cross-validation folds and hyperparameter ranges based on specific dataset characteristics.

## Contact

For questions or contributions, please contact Shashwat Singh at theshashwatsingh@gmail.com.

