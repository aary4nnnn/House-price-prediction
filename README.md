# California Housing Price Prediction

This project builds an end-to-end machine learning pipeline to predict median house prices in California using historical housing data.

## Problem Statement
House prices depend on multiple factors such as location, population, income, and housing characteristics.  
The goal of this project is to predict the median house value using these features.

## Dataset
- California Housing Dataset
- Target variable: `median_house_value`
- Features include location, housing age, rooms, population, income, and ocean proximity

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Approach
- Data loading and preprocessing
- Train-test split
- Log transformation to reduce skewness
- One-hot encoding for categorical features
- Feature engineering (bedroom ratio, rooms per household)
- Model training using:
  - Linear Regression
  - Random Forest Regressor
- Hyperparameter tuning using GridSearchCV
- Model evaluation using R² score and RMSE

## Results
- Random Forest performed better than Linear Regression
  <img width="1102" height="730" alt="image" src="https://github.com/user-attachments/assets/fff68ff0-a1a6-405e-aee5-eb7228c2dba7" />

- Feature engineering and hyperparameter tuning improved model performance
  <img width="1311" height="706" alt="image" src="https://github.com/user-attachments/assets/3d099bf7-73b8-4329-8a58-8ac2100eb707" />

- The final model generalized well on unseen test data
  <img width="213" height="55" alt="image" src="https://github.com/user-attachments/assets/b30e1736-45b8-429d-a2fd-24ab4a989126" />

## Screenshots
Below are some visualizations and outputs generated during the project:

- Correlation heatmap of numerical features  
- Geographic scatter plot showing housing prices by location  
- Model evaluation results and performance comparison  


