# Customer Churn Prediction

## Overview
This project focuses on predicting customer churn using various machine learning classifiers. The dataset is preprocessed, features are standardized, and three models are trained and evaluated to determine the best performer.

## Dataset
- The dataset used is `sid.csv`.
- Preprocessing includes:
  - Dropping irrelevant columns (`customerID`, `TotalCharges`).
  - Encoding categorical variables.
  - Handling missing values.
  - Standardizing features.

## Models Used
- **Logistic Regression**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**

## Implementation Steps
1. **Data Preprocessing**
   - Drop unnecessary columns.
   - Encode categorical variables.
   - Handle missing values.
   - Standardize features.
2. **Splitting the Dataset**
   - Data is split into training (80%) and testing (20%) sets.
3. **Training Models**
   - The three classifiers are trained using `X_train` and `y_train`.
4. **Making Predictions**
   - Predictions are generated for `X_test`.
5. **Evaluating Models**
   - Metrics used: Accuracy, Precision, Recall, F1-score.
   - The models' performance is compared using bar charts.

## Evaluation Metrics
Each model is evaluated using the following metrics:
- **Accuracy**: Measures overall correctness.
- **Precision**: Measures how many of the positive predictions were correct.
- **Recall**: Measures how many actual positives were correctly identified.
- **F1-score**: Harmonic mean of Precision and Recall.

## Results Visualization
- Bar charts are used to compare models based on Accuracy, Precision, Recall, and F1-score.
- The visualizations help in understanding which model performs best.

## Dependencies
- Python
- Pandas
- Scikit-learn
- Matplotlib

## Running the Project
1. Install the necessary dependencies:
   ```sh
   pip install pandas scikit-learn matplotlib
   ```
2. Run the Python script to train and evaluate the models.

## Conclusion
This project demonstrates a machine learning pipeline for predicting customer churn. The evaluation metrics help determine the best-performing model for future deployment in customer retention strategies.

