# delivery-time-prediction-linear-logistic-regression
Machine learning project for analyzing and predicting food delivery time using preprocessing, PCA, Linear Regression, and Logistic Regression.
# Food Delivery Time Prediction using Machine Learning

## Project Overview
This project analyzes food delivery data and builds machine learning models to understand and predict delivery time. The notebook includes data preprocessing, feature encoding, normalization, PCA dimensionality reduction, regression modeling, classification, and model evaluation.

## Dataset
The dataset used in this project is `Food_Delivery_Time_Prediction.csv`.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Steps Performed
1. Imported required Python libraries.
2. Loaded and explored the food delivery dataset.
3. Checked missing values and duplicate records.
4. Encoded categorical features such as order priority, traffic conditions, weather, order time, and vehicle type.
5. Dropped unnecessary columns such as order ID and location-related fields.
6. Normalized numerical columns using MinMaxScaler.
7. Performed statistical analysis using mean, median, mode, and variance.
8. Created visualizations such as pair plots, heatmaps, boxplots, scatter plots, confusion matrix, and ROC curve.
9. Applied PCA for dimensionality reduction.
10. Built a Linear Regression model for delivery time prediction.
11. Built a Logistic Regression model to classify delivery status as Fast or Delayed.
12. Evaluated models using MSE, RMSE, MAE, R² score, accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC curve.

## Machine Learning Models Used
- Linear Regression
- Logistic Regression

## Evaluation Metrics
For Linear Regression:
- Mean Squared Error
- Root Mean Squared Error
- Mean Absolute Error
- R² Score

For Logistic Regression:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

## Key Learning
Through this assignment, I learned how to preprocess real-world data, encode categorical variables, normalize numerical features, apply PCA, train machine learning models, and evaluate model performance using different metrics.

## File Structure
```text
food-delivery-time-prediction/
│
├── assign_1.ipynb
├── Food_Delivery_Time_Prediction.csv
└── README.md
