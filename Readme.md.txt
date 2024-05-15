# Mobile Price Prediction

This project predicts mobile prices using various machine learning models such as Linear Regression, KNN (K-Nearest Neighbors), Decision Tree, and Random Forest. The dataset used for this project is `Mobile Price Prediction.csv`.

## Setup

To run this project on Google Colab, follow these steps:

1. **Upload Dataset**: Upload the `Mobile Price Prediction.csv` dataset to your Google Drive.
2. **Open Notebook**: Open the `Mobile_Price_Prediction.ipynb` notebook in Google Colab.
3. **Run Cells**: Run the notebook cells sequentially to execute the code.

## How to Start

1. **Upload Dataset**: Upload the dataset `Mobile Price Prediction.csv` to your Google Drive.
2. **Open Notebook**: Open the notebook `Mobile_Price_Prediction.ipynb` in Google Colab.
3. **Run Cells**: Run the notebook cells sequentially to train the machine learning models and evaluate their performance.

## What the Code Does

### Linear Regression
- Linear regression is used to predict mobile prices based on features such as RAM, battery capacity, screen size, etc.
- **Optimization**: The model is optimized by minimizing the mean squared error (MSE) during training.
- **Feature Extraction**: No specific feature extraction is performed in this model.
- **Scoring**: The performance of the model is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

### KNN (K-Nearest Neighbors)
- KNN algorithm predicts mobile prices based on the similarity of features with other mobiles in the dataset.
- **Optimization**: The optimal number of neighbors (K) is determined using grid search with cross-validation.
- **Feature Extraction**: No specific feature extraction is performed in this model.
- **Scoring**: The performance of the model is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

### Decision Tree
- Decision Tree algorithm predicts mobile prices by learning simple decision rules inferred from the features.
- **Optimization**: The model is optimized by adjusting hyperparameters such as the maximum depth of the tree, minimum samples split, and minimum samples leaf.
- **Feature Extraction**: Feature importance is plotted to understand which features contribute the most to the model.
- **Scoring**: The performance of the model is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

### Random Forest
- Random Forest algorithm predicts mobile prices by constructing multiple decision trees during training.
- **Optimization**: The model is optimized using grid search with cross-validation to find the best combination of hyperparameters such as the number of trees, maximum depth of the tree, minimum samples split, and minimum samples leaf.
- **Feature Extraction**: Feature importance is plotted to understand which features contribute the most to the model.
- **Scoring**: The performance of the model is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) score.

## Results

### Model and R2 scores

- Linear regression - 26.7%
- KNN - 92.04%
- Decision tree - 93.95%
- Random forest - 95.7%

