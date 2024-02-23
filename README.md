# Income-Prediction

This project develops a machine learning model to predict income levels based on individuals' demographic and socio-economic characteristics.

## Dataset

The dataset is loaded from a CSV file named "income.csv". This dataset includes various demographic features (age, education, work class, marital status, race, etc.) and the individual's annual income.

## Data Preprocessing

- The dataset is loaded, and unnecessary columns (e.g., education level and weight) are dropped.
- Categorical variables are one-hot encoded, and some binary variables are converted to numerical values.
- Relationships between features are visualized with heatmaps.
- Feature correlations are examined for feature selection, and features with low correlations are dropped.

## Model Development

- The dataset is split into training and test sets.
- A Random Forest classifier is created and initially trained with default parameters.
- Hyperparameter optimization is performed using GridSearchCV to find the best parameters.
- A new model is created with the best parameters, and the model's performance is evaluated.

## Requirements

- Python 3.x
- pandas
- scikit-learn
- seaborn
- matplotlib