### Methodology

This project followed a structured machine learning workflow to develop a model that predicts the number of calories burned during a workout based on biological and activity-related features.

#### 1. Data Collection and Loading

The dataset was provided in CSV format and included the following features: `User_ID`, `Gender`, `Age`, `Height`, `Weight`, `Duration`, `Heart_Rate`, `Body_Temp`, and the target variable `Calories`. The data was loaded using the `pandas` library for analysis.

#### 2. Data Preprocessing

Unnecessary columns like `User_ID` were removed. The categorical feature `Gender` was encoded numerically (male = 1, female = 0). Z-score standardization was applied to the numerical features to normalize the data. Missing values were checked, and outliers were explored using visualizations.

#### 3. Data Splitting

The dataset was split into training and testing sets using an 80:20 ratio to evaluate model performance on unseen data.

#### 4. Model Selection and Training

Two regression models were implemented: Linear Regression and Random Forest Regressor. These models were trained on the preprocessed training data using the `scikit-learn` library.

#### 5. Model Evaluation

Both models were evaluated using Mean Squared Error (MSE) and R² Score to assess their predictive accuracy. The Random Forest model showed superior performance and was selected as the final model.

#### 6. Model Saving and Inference

The trained Random Forest model was saved using `joblib` for reuse. It was later used to predict calorie values for new or test data points to demonstrate inference.

#### 7. Visualization and Interpretation

Throughout the process, data visualization techniques using `matplotlib` and `seaborn` were employed to understand feature distributions, detect outliers, and interpret results more effectively.
