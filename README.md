Student Performance Prediction Project


This project analyzes student performance data using machine learning models to predict academic success. The dataset includes features related to students' personal, social, and academic backgrounds. Various steps such as exploratory data analysis (EDA), data preprocessing, feature engineering, and machine learning model development are performed to predict the target variable, Grade_Mean, which is the average of the three grades (G1, G2, G3).

Project Structure:-
1. Data Preprocessing:
- Handled missing values, duplicates, and outliers.
- Performed feature scaling and one-hot encoding for categorical variables.
- Engineered new features like TotalTime, Totalalc, and Grade_Mean.
2. Exploratory Data Analysis (EDA):
- Visualized numerical features using histograms, box plots, and correlation heatmaps.
- Generated pie charts and bar charts for categorical features.
3. Modeling:
- Used RandomForestRegressor for predicting the target variable Grade_Mean.
- Performed hyperparameter tuning with GridSearchCV to optimize the model performance.
- Evaluated the model using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R2 score.
- Applied cross-validation for better evaluation.

Prerequisites and Libraries:-
- pandas
- numpy
- seaborn
- matplotlib
- lightgbm
- sklearn (scikit-learn)
- scipy

Future Improvements:-
- Experiment with other machine learning models such as XGBoost and LightGBM.
- Apply advanced feature engineering and feature selection techniques.
- Test on larger datasets for generalizability.
